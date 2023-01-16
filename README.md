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
## Run ansible Jenkins playbook
```
$ ansible-playbook -i host.txt jenkins-ub.yaml
```
