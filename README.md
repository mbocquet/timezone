# timezone

Ansible role to configure timezone.

## Requirements

None.

## Role Variables

See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://github.com/mbocquet/timezone.git roles/timezone`

## Example Playbook

    - hosts: servers
      roles:
         - { role: timezone, timezone: 'Europe/Paris' }

## License

GPLv3

## Author Information

http://www.sekoya.org
