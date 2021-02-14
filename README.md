# ansible
Ansible repo for setting up machines.


# Using ssh agent forwarding for github downloads
ssh-agent bash
. env/bin/activate
ssh-add ~/.ssh/id_rsa 
ansible-playbook playbooks/laptop/main.yml -i inventories/laptop
