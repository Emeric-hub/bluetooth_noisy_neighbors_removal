# bluetooth_noisy_neighbors_removal
an experiment to remove noisy neighbors

Based on https://threadreaderapp.com/thread/1661998416652640257.html ideas

Recon : 

sudo apt install bluez

hcitool scan

First solution :

l2ping -i hci0 -s -f

Second Solution : 

With websploit (old code in python 2 with issues that need installation and dirty things):

https://github.com/The404Hacking/websploit

git clone git@github.com:The404Hacking/websploit.git

cd Setup
sudo sh install.sh

#Divers :

sudo apt install python-is-python3

Idea is the same ... L2ping ....
