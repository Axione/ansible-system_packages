# ansible-system_packages

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_packages-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_packages)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_packages.svg)](https://github.com/lotusnoir/ansible-system_packages/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_packages?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_packages)
[![downloads](https://img.shields.io/ansible/role/d/56916)](https://galaxy.ansible.com/lotusnoir/system_packages)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56916)](https://galaxy.ansible.com/lotusnoir/system_packages)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install base packages
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

With default variables, this role dont change anything on the system. You need to set the config variables like in the exemple in order to start configuration.

## Examples

        ---
        - hosts: system_packages
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_packages
          vars:
            packages_install_epel_repo: true
            package_repo_yum_cleanup: true
            packages_common:
              - bash-completion
            packages_family_debian:
              - locate
            packages_family_redhat:
              - yum-utils
            packages_distrib_debian:
              - rcconf
            packages_distrib_centos_7:
              - redhat-lsb-core
            packages_distrib_oraclelinux_7:
              - redhat-lsb-core
            packages_rm_common:
              - bash-completion
            packages_rm_family_debian:
              - locate
            packages_rm_family_redhat:
              - yum-utils
            packages_rm_distrib_debian:
              - rcconf
            packages_rm_distrib_centos_7:
              - redhat-lsb-core
            packages_rm_distrib_oraclelinux_7:
              - redhat-lsb-core



## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
