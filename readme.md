# Project name: Taobao double 11 data analysis and predict

## Main Frames
Linux configuration:
google cloud compute machine
ubuntu 18.04
One master node and three slaves nodes for this project

Version control:
Hadoop:2.7.7(https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.7/hadoop-2.7.7.tar.gz)
spark:2.4.1(https://www.apache.org/dyn/closer.lua/spark/spark-2.4.1/spark-2.4.1-bin-hadoop2.7.tgz)
mysql-server: up-to-the-date "sudo apt-get install mysql-server"
Hive:2.3.4(http://apache.01link.hk/hive/hive-2.3.4/)





## Steps:
###1. Set up cloud machine
	1.Connect machine via GCP web ssh window,
	2.After connectting, switch to the "ubuntu" account, "sudo su ubuntu"
	3.Enable the SSH connect from outside
		1.edit the "/etc/ssh/sshd_config" file, set "PasswordAuthentication" to be "yes"
		2.change dir to "/etc/init.d", and "sudo ./ssh restart"
	4.Set the "ubuntu" account password, "sudo passwd ubuntu", and enter your new password.
	5.You can ssd to your machine from putty or MobaXterm now!
Notes: since the google machine not updates at first, you may try "sudo apt-get update" at first, and then you can install the softwares as you like.

###2.Installing Java


