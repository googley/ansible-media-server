# Ansible media server

Personal media server configuration

## Requirements
* Ansible > 2.3

## Prepare
```shell
ansible-galaxy install -r requirements.yml
```

## Use
```shell
ansible-playbook -i hosts ansible-media-server.yml -e admin_password=xxxx -e reverse_proxy_addr=127.0.0.1
```
