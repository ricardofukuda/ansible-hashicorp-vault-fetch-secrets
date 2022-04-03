## About
Ansible role to test hashicorp vault colletion to fetch secrets.

## Installation
```
ansible-galaxy collection install community.hashi_vault
```

## Run
```
ansible-playbook -i inventory --vault-password-file=ansible-vault.secret playbooks/hello-world/main.yml
```