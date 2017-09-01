# Ansible DripStat Infra Role

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-Dripstat.dripstat--infra-blue.svg)](https://galaxy.ansible.com/Dripstat/dripstat-infra/)

Install and configure DripStat Infra agent.

Supports most Ubuntu, Debian and RHEL based Linux distros.

## Installation

```
ansible-galaxy install Dripstat.dripstat-infra
```

## Role Variables

- `ds_lic` - DripStat License Key


## Example Playbook

```
---
- hosts: all
  roles:
  - {role: dripstat-infra, become: yes, ds_lic: "DripStat_License_Key" }
```
