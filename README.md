# ansible
Ansible repo for setting up machines.


# Using ssh agent forwarding for github downloads
ssh-agent bash
. env/bin/activate
ssh-add ~/.ssh/id_rsa 
ansible-playbook playbooks/laptop/main.yml -i inventories/laptop
=======
One Ansible repository To Rule Them All.

This is for setting up and configuring freshly installed linux computers (virtual machines, rpi's or laptops).
