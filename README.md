# ansible-skeleton

Ansible role skeleton for Ansible Galaxy init function

[![Ansible Version](https://img.shields.io/badge/Ansible-v2.9+-green.svg)](https://github.com/eagleusb/ansible-skeleton)

## Requirements

None

## Quickstart

```sh
ansible-galaxy install eagleusb.skeleton
```

## Variables

| Name         | Required | Default Value | Description                                          |
|--------------|----------|---------------|------------------------------------------------------|
| skeleton_foo | no       | *5.0*         | flush input data to foobar every seconds.nanoseconds |

## Playbook Example

```yml
- hosts: all
  roles:
    - role: ansible-skeleton
      vars:
        skeleton_foo: "1.0"
```

## License

GPL3
