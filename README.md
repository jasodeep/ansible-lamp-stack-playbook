# Ansible LAMP Stack Playbook
This is a Ansible Playbook to deploy a LAMP Stack infrastructure on ubuntu/debian hosts. 

### Stack -
* apache2
* mysql 
* php7.0-fpm 

### Pre-requisites
You must have Ansible 2.3 installed.

### Setup
* Add host in /etc/ansible/hosts file. See the given hosts file to add hosts.  
* Run command `sudo ansible-playbook lamp-playbook.yml`


### Database Configuration
* USERNAME: root
* PASSWORD: [update the variable "mysql_root_password" in lamp-playbook.yml]




