Cassandra on Centos;

Requirements

You will need N Centos Boxes

Deploy
The simpliest way to deploy this project is to use Ansible :
git clone https://github.com/NathanPoncelet/Ansible.git
editor hosts
ansible-playbook -i hosts cass.yml
