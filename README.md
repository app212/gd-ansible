# GD Ansible task


Apply configuration
``` 
ansible-playbook playbooks/load_balancer.yml playbooks/web_server.yml  -i inventories/dev/hosts.ini --ask-vault-pass
```

Validation
```
ansible-playbook playbooks/validation.yml -i inventories/dev/hosts.ini --ask-vault-pass
```
