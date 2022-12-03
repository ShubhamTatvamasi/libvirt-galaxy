# libvirt-galaxy

Create new VM:
```bash
ansible-playbook create-vm.yml
```
> add `-K` flag for providing sudo password.

### Ansible Setup

Install Ansible:
```bash
sudo apt remove ansible
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
```
