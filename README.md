# README

This deployment required on CentOS 7, I try on local by Ansible, not on AWS because I have no privacy AWS account

Ansible command:

ansible-playbook -i inventories/production -u username playbooks/wordpress.yml --extra-vars "host=wordpress project_name=wordpress" -vv


Dont forget change ansible.cfg to your working local dir