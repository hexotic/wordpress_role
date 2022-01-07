Ansible Role: wordpress_role
-------

To get the roles:
`ansible-galaxy install -r roles/requirements.yml`

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
