# ansible-container_wordpress

[![Galaxy Role](https://img.shields.io/badge/galaxy-container_wordpress-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/container_wordpress)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-container_wordpress.svg)](https://github.com/lotusnoir/ansible-container_wordpress/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-container_wordpress?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/container_wordpress)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/container_wordpress)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/container_wordpress)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install and launch a wordpress container
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: container_wordpress
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-container_wordpress


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
