# Ansible Playbook Icinga2

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Preriquisite

* Install Ansible

### Usage

Run playbook
```sh
ansible-playbook config.yml
```

Run Rollback playbook
```sh
ansible-playbook uninstall.yml -e full_uninstall=true
```

