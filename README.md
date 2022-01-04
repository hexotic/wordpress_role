Ansible Role: wordpress_role
-------

Supported distributions:
* ubuntu
* centos

This role installs the ansible module for lauching Wordpress with containers.

Example playbook
-----

```yaml
- hosts: prod
  become: true
  roles:
    - wordpress_role
```
