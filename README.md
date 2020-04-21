# standalone-mongodb-ansible
Standalone MongoDB  using ansible. Installing MongoDB in localhost using ansible

## Status of the project 
It's a POC ! 

## How to use this project

### prerequisite
1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide)
2. Playbook works in Ubuntu Xenial

### Ansible settings 
1. Copy the contents of `hosts` and `ansible.cfg` to `/etc/ansible/hosts` and `/etc/ansible/ansible.cfg` where the default configs are located. 

### Command 
1. Run  `ansible-playbook --ask-become-pass  mongodb.yml` from the directory which has `mongo.yml`
