# Ansible Role: PHPStorm

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-x2goserver.svg)](https://travis-ci.org/tschifftner/ansible-role-x2goserver)

Installs x2goserver on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    x2go_packages:
      - 'x2goserver'
    x2go_aptkey: 'E1F958385BFE2B6E'
    x2go_apt_repositories:
      - 'deb http://packages.x2go.org/debian jessie main'
      - 'deb-src http://packages.x2go.org/debian jessie main'

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.x2goserver }

## License

MIT / BSD

## Author Information

 - Tobias Schifftner, @tschifftner