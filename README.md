# Ansible-Installation On Ubuntu
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu

Installing Ansible on Ubuntu
Ubuntu builds are available in a PPA here.

To configure the PPA on your machine and install Ansible run these commands:

$ sudo apt update

$ sudo apt install software-properties-common

$ sudo apt-add-repository --yes --update ppa:ansible/ansible

$ sudo apt install ansible



Note: On older Ubuntu distributions, “software-properties-common” is called “python-software-properties”. You may want to use apt-get instead of apt in older versions. Also, be aware that only newer distributions (in other words, 18.04, 18.10, and so on) have a -u or --update flag, so adjust your script accordingly.
