## Synopsis
This is an ansible role used to reset the default password on an AWX installation deployed using [geerlingguy/ansible-role-awx](https://github.com/geerlingguy/ansible-role-awx)

## Playbook example

This is used to continue an AWX deployment and perform further configuration.  For example in the [ansible_azure_ansible_demo](
://github.com/tonyskidmore/cloud-msp/tree/master/examples/ansible_azure_ansible_demo)

```
---
- name: set tower admin password
  hosts: localhost
  connection: local

  roles:

  - ansible-role-awx-default-password
```


