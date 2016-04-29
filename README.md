# Ansible-Tasks-Beta
Using my own private cloud as a playground for these ansible playbooks. Basic user module, docker swarm setup and more to come.

### vars/main.yml
<pre><code>
  reboot: false
  update_packages: 1
  users:
    abiswas:
      name: Amit Biswas
      password: 'hashedpassword'
      groups: "sudo"
</pre></code>
  .......
