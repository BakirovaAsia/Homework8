# Homework8
Devops-school. Ansible playbook.



primery
# nano /etc/ansible/hosts

add

[build_host]
178.154.213.234

[prod_host]
178.154.208.51

~ sudo apt-add-repository ppa:ansible/ansible
~ sudo apt update
~ sudo apt install ansible

# ansible-playbook CaucusCalculator.yml --ask-vault-pass
