# ansible-precheck
Ansible playbook to perform prechecks on different nodes before CM deployment

Setup an Ansible Control Machine

Prerequisites to be perfomed on Ansible Control Machine
1. Install dnspython package on the Control Machine to perform DNS lookup 
2. Create host inventory in : /etc/ansible/hosts

Running Playbook:
ansible-playbook ansible-precheck/precheck.yml
ansible-playbook ansible-prehceck/start-install.yml
