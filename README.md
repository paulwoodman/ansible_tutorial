# ansible_tutorial

A simple ansible playbook to install Apache on Ubuntu

This will:
- update the system
- install apache and enable for boot
- add an index.html file from the data file within templates

How to run:
- edit the ansible host file '/etc/ansible/hosts' and enter server(s) to be run on
- Don't forget to add your ssh keys from the deploy host to the server!
- execute the playbook: ansible-playbook -s apache.yml

Nothing special, just used to learn ansible. SIMPLES
