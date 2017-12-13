# ansible-precheck
Ansible playbook to perform prechecks on different nodes before CM deployment

Prerequisites to be perfomed on Ansible Control Machine
1. Install dnspython package to perform DNS lookup 
2. Create host inventory in : /etc/ansible/hosts

Running Playbook:
ansible-playbook ansible-precheck/main.yml
