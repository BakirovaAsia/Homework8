# Homework8
Devops-school. Ansible playbook.



primary
 nano /etc/ansible/hosts

add

[build_host]
IP
[prod_host]
IP

~ sudo apt-add-repository ppa:ansible/ansible
~ sudo apt update
~ sudo apt install ansible

 ansible-playbook CaucusCalculator.yml --ask-vault-pass
