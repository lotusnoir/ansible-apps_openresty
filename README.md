# Ansible Role: ansible-apps_openresty

## Description

[![Build Status](https://travis-ci.com/lotusnoir/ansible-apps_openresty.svg?branch=master?style=flat)](https://travis-ci.com/lotusnoir/ansible-apps_openresty)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![Ansible Role](https://img.shields.io/badge/galaxy-apps_openresty-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_openresty?color=orange&style=flat)
![Ansible Quality Score](https://img.shields.io/ansible/quality/52300)
[![downloads](https://img.shields.io/ansible/role/d/52300)](https://galaxy.ansible.com/lotusnoir/apps_openresty)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_openresty.svg)](https://github.com/lotusnoir/ansible-apps_openresty/releases/)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=lotusnoir_ansible-apps_openresty&metric=alert_status)](https://sonarcloud.io/dashboard?id=lotusnoir_ansible-apps_openresty) 
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=lotusnoir_ansible-apps_openresty&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=lotusnoir_ansible-apps_openresty)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=lotusnoir_ansible-apps_openresty&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=lotusnoir_ansible-apps_openresty)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=lotusnoir_ansible-apps_openresty&metric=security_rating)](https://sonarcloud.io/dashboard?id=lotusnoir_ansible-apps_openresty)

Deploy [openresty](https://openresty.org/en/) a web platform based on nginx which can run Lua scripts using its LuaJIT engine.

## Role variables

| Name                    | Default Value     | Description                        |
| ----------------------- | ----------------- | -----------------------------------|

## Examples

	---
	- hosts: apps_openresty
	  become: yes
	  become_method: sudo
	  gather_facts: yes
	  roles:
	    - role: ansible-apps_openresty
	  environment: 
	    http_proxy: "{{ http_proxy }}"
	    https_proxy: "{{ https_proxy }}"
	    no_proxy: "{{ no_proxy }}

## Monitoring



## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.
