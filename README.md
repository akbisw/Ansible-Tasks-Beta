# Ansible-Tasks-Beta
Using my own private cloud as a playground for these ansible playbooks. Basic user module, docker swarm setup and more to come.

### vars/main.yml
reboot: false
users:
  abiswas:
    name: Amit Biswas
    password: 'hashedpassword'
    groups: "sudo"
  .......
