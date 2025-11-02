# Ansible Role: Users

[![Ansible Molecule](https://github.com/leberkaslabs/ansible-role-fail2ban/actions/workflows/molecule.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-fail2ban/actions/workflows/molecule.yml)

Setup fail2ban on linux systems.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: dudecalledbro.fail2ban
```

## License

Copyright © 2025 Niclas Spreng

Licensed under the [MIT license](LICENSE).
