# ssh
How to access Kali or Remote machine with cmd prompt

first 
check ip of that machine 
in kali using ifconfig & in window ipconfig

if cmd display error like: ssh: connect to host port 22 : connection refused 

then u have to install ssh in device

Change Your User go to Root User:- 
$sudo -i

Install SSH :-
sudo apt-get update
sudo apt-get install ssh
systemctl restart ssh.service
systemctl enable ssh.service
systemctl status ssh.service

cmd for access kali :

ssh username@ip addr
