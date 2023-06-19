# Ansible Mikrotik config playbook

## About
I want to make a simple solution to configure vlans on mikrotik switches.

## Basic configuration:
* configure inventory
* add user with password

## Run the tasks playbook:
* Create `group_vars/all/secrets.yaml` based on secret-vars.template
* run: `ansible-playbook playbook-tasks.yaml [--ask-pass] [--tags debug] [-v]`
