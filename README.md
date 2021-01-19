# mdadm

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/mdadm/status.svg)](https://drone.osshelp.ru/ansible/mdadm)

Installs mdadm userspace components and manage configuration.

## Example

``` yaml
- role: mdadm
  email_to: "{{ pd_email }}"
  email_from: "{{ inventory_hostname }}"
```

## TODO

- We should create mdadm conf with sane defaults? (i.e. our emails, etc)
- Add testing on VMs instead of LXC
