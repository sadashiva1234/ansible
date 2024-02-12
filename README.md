# ansible

#Commands to install and run ansible<br>
sudo apt-get update<br>
sudo apt-get install awscli<br>
aws configure<br>
sudo apt-get install software-properties-common<br>
sudo apt-add-repository ppa:ansible/ansible<br>
sudo apt-get update<br>
sudo apt-get install ansible<br>
sudo apt-get install pip<br>
pip install boto<br>
ansible-playbook -v ec2.yaml<br>

#In case of Older OS use this commans (export LC_ALL=C)

#In case pid does not work<br>
sudo apt-get remove --purge python-pip<br>
sudo apt-get autoremove<br>
sudo rm -f /usr/local/bin/pip<br>
sudo easy_install pip==20.3.4<br>
pip --version<br>
