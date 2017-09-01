# Ansible DripStat Infra Role

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
