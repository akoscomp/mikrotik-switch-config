# Ansible Mikrotik config playbook

## Basic configuration:
* set ip address
* set default gw
* add user with password

## Run the tasks playbook:
* Create `group_vars/all/secrets.yaml` based on secret-vars.template
* run: `ansible-playbook playbook-tasks.yaml --ask-pass [--tags bridge|basic|basic-once] [-v]`
