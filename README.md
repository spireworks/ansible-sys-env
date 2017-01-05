# ansible-sys-env

Simple Ansible role to write system variables in a machine

## Usage

```yml
---
- name: Example playbook
  hosts: example_host
  roles:
    - role: sys-env
      sys_env_vars:
        RAILS_ENV: production
        MEMCACHED_SERVERS: foo.bar.server
```
