# libvirt-galaxy

Create new VM:
```bash
ansible-playbook create-vm.yml
```

### Ansible Setup

Install Ansible - Ubuntu 20.04 LTS:
```bash
sudo apt remove ansible
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
```

Install Ansible - macOS:
```bash
brew install ansible
```
