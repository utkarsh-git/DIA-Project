# DIA-Project

Run Docker File in an Ubuntu 20.04 virtual machine

Pyspark and Hadoop will be installed with latest version and all config files will be updated.

source ~/.bashrc

pip install -r requirements.txt

./hadoop/sbin/start-dfs.sh

./hadoop/sbin/start-yarn.sh

cd /home/hduser/DIA-Project

spark-submit Dataset1.py

spark-submit Dataset2.py
