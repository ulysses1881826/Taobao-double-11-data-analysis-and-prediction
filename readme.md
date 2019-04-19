# Project name: Taobao double 11 data analysis and predict
<br><br>
## Main Frames
Linux configuration:<br>
google cloud compute machine<br>
ubuntu 18.04<br>
One master node and three slaves nodes for this project<br>

Version control:
Hadoop:2.7.7(https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.7/hadoop-2.7.7.tar.gz)<br>
spark:2.4.1(https://www.apache.org/dyn/closer.lua/spark/spark-2.4.1/spark-2.4.1-bin-hadoop2.7.tgz)<br>
mysql-server: up-to-the-date "sudo apt-get install mysql-server"<br>
Hive:2.3.4(http://apache.01link.hk/hive/hive-2.3.4/)<br>





## Steps:
### 1. Set up cloud machine <br>
	1.Connect machine via GCP web ssh window <br>
	2.After connectting, switch to the "ubuntu" account, "sudo su ubuntu" <br>
	3.Enable the SSH connect from outside <br>
		1.edit the "/etc/ssh/sshd_config" file, set "PasswordAuthentication" to be "yes" <br>
		2.change dir to "/etc/init.d", and "sudo ./ssh restart" <br>
	4.Set the "ubuntu" account password, "sudo passwd ubuntu", and enter your new password. <br>
	5.You can ssd to your machine from putty or MobaXterm now! <br>
Notes: since the google machine not updates at first, you may try "sudo apt-get update" at first, and then you can install the softwares as you like. <br>

### 2.Installing Java


