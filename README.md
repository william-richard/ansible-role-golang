# README.md
# Ansible Role: mats116.golang

An Ansible role that installs golang on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yml
go_version: ""
go_path: /usr/local/go
```

## Dependencies

none

## Example Playbook

```yml
- hosts: web-server
  roles:
    - role: mats116.golang
```

## License

MIT
