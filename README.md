# Ansible Mikrotik config playbook

## About
I want to make a simple solution to configure vlans on mikrotik switches.

## Basic configuration:
* set ip address
* set default gw
* add user with password

## Run the tasks playbook:
* Create `group_vars/all/secrets.yaml` based on secret-vars.template
* run: `ansible-playbook playbook-tasks.yaml --ask-pass [--tags bridge|basic|basic-once] [-v]`
