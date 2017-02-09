# Ansible_Cloud
Using my own private cloud as a playground for these ansible playbooks. Basic packages, user module, docker swarm setup and more to come.

Compatibility: DEBIAN and RHEL

### vars/main.yml
<pre><code>
  reboot: false
  update_packages: 1
  install_essentials: 1
  users:
    abiswas:
      name: Amit Biswas
      ssh_pub_key: "id_rsa.pub"
</pre></code>
  .......
