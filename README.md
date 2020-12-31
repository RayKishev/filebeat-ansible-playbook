# filebeat-ansible-playbook

Ansible-Filebeat
Ansible role for Filebeat deployment
Ansible Playbook
This playbook is for installing and configuring filebeat to production server.
Notes and requirements
The playbook was built and tested on RedHat Enterprise_linux:7.3.
You will need Ansible installed and running.
Edit your Ansible hosts file ('/etc/ansible/hosts') and add an 'filebeatservers' entry for the server you wish to install Filebeat on.
In the terminal on the machine hosting Ansible, clone this repo.
Cd into the directory, and run: ansible-playbook playbooks/install-filebeat.yml
The plays in the playbook will run on the target server, installing filebeat.
