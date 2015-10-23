# Ansible Role: ServerSpeeder

Install ServerSpeeder via Ansible.

## Features

- Ability to install and update ServerSpeeder
- Detect network interface

## Requirements

This role requires Ansible 1.6 or higher and platform requirements are listed in the metadata file.

## Dependencies

None

## Example Playbooks

In `serverspeeder.yml`:

```yaml
- name: install serverspeeder
  hosts: shadowsocks-servers
  roles:
    - role: sparanoid.serverspeeder
      serverspeeder_user:
        email: my@example.com
        passwd: myPassw0rd!
```

## License

GPLv3

## Author Information

**Tunghsiao Liu**

- Twitter: @[tunghsiao](http://twitter.com/tunghsiao)
- GitHub: @[sparanoid](http://github.com/sparanoid)
