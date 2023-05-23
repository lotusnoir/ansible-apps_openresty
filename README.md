# ansible-apps_openresty

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_openresty-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_openresty.svg)](https://github.com/lotusnoir/ansible-apps_openresty/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_openresty?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
[![downloads](https://img.shields.io/ansible/role/d/56105)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56105)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Deploy [openresty](https://openresty.org/en/) a web platform based on nginx which can run Lua scripts using its LuaJIT engine.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_openresty
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_openresty


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
