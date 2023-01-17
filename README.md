# Ansible Playbooks
## Ansible pre-requisites
- Configure password less ssh 
## Ansible Installation on Fedora
```
$ sudo dnf list available ansible
$ sudo dnf install ansible
$ sudo "rpm -qa | grep ansible"
$ sudo dnf list ansible
```
## Ansible Installation on Ubuntu
```
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo dnf install ansible
$ sudo apt update && sudo apt install ansible
```
## Run ansible Jenkins playbook
```
$ ansible-playbook -i host.txt jenkins-ub.yaml
```
