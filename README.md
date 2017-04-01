# Ansible_Cloud
Using my own private cloud as a playground for these ansible playbooks. Basic packages, user module, docker swarm setup and more to come.

## Task: User
### vars/main.yml
<pre><code>
reboot: false
update_packages: 1
users:
  amitbiswas:
    name: Amit Biswas
    key: "{{ lookup('file', '/path/.ssh/id_rsa.pub') }}"
    pass: encrypted_password
    sudo: true
</pre></code>
  .......
