# Ansible Role for OpenJDK

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-openjdk/master)](https://gitlab.com/alvistack/ansible-role-openjdk/-/pipelines)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-openjdk.svg)](https://github.com/alvistack/ansible-role-openjdk/releases)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-openjdk.svg)](https://github.com/alvistack/ansible-role-openjdk/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.openjdk-blue.svg)](https://galaxy.ansible.com/alvistack/openjdk)

Ansible Role for OpenJDK Installation.

## Requirements

This role require Ansible 4.0 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 20.10, 21.04
  - CentOS 7, 8 Stream
  - openSUSE Leap 15.2, Tumbleweed
  - Debian 10
  - Fedora 33, 34
  - RHEL 7, 8

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
