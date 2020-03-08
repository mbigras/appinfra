# appinfra

> Learning about infrastructure

## Features

* Vagrant development environment
* Ansible configuration management
* Demonstrates application delivery concepts: test, package, provision, deploy, monitor
* Demonstrates using three tools as program supervisors: systemd, supervisor, docker
* Rundeck self-service operations

## Setup development environment

```
git clone https://github.com/mbigras/appinfra
cd appinfra/ansible
vagrant up
ansible-playbook -i vagrant.yml playbooks/site.yml
```
