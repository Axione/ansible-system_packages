# ansible-system_packages

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_packages-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_packages)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_packages.svg)](https://github.com/lotusnoir/ansible-system_packages/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_packages?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56916)](https://galaxy.ansible.com/lotusnoir/system_packages)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56916)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install base packages

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_packages
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_packages


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

