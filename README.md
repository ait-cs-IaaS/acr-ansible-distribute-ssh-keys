# Ansible-Role: acr-ansible-distribute-ssh-keys

AIT-CyberRange: Distributes previously generated ssh key pairs. 


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
# List with defined keys
key_list: []

```

## Example Playbook

```yaml
- hosts: all
  roles:
    - acr-ansible-distribute-ssh-keys
      vars:
        key_list: []
```

## License

GPL-3.0

## Author

- Lenhard Reuter