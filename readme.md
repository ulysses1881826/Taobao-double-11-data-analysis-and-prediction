# Project name: Taobao double 11 data analysis and predict

## Main Frames
Linux configuration:
google cloud compute machine
ubuntu 18.04
One master and three slaves for this project






## Steps:
1. Set up cloud machine
	1.Connect machine via GCP web ssh window,
	2.After connectting, switch to the "ubuntu" account, "sudo su ubuntu"
	3.Enable the SSH connect from outside
		1.edit the "/etc/ssh/sshd_config" file, set "PasswordAuthentication" to be "yes"
		2.change dir to "/etc/init.d", and "sudo ./ssh restart"
	4.Set the "ubuntu" account password, "sudo passwd ubuntu", and enter your new password.
	5.You can ssd to your machine from putty or MobaXterm now!
Notes: since the google machine not updates at first, you may try "sudo apt-get update" at first, and then you can install the softwares as you like.

2.Installing Java


