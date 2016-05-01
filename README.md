Ansible common role
=====================

This is a meta role to perform basic configuration.

It ties together the roles below:

```yaml
dependencies:
  - accounts
  - packages
  - openssh-server
  - ntpd
  - resolv
```

Requirements
------------

None.

Role Variables
--------------

See variables of each of those roles.

Dependencies
------------

None.

Example Playbook
-------------------------

```yaml
- hosts: servers
  roles:
    - { role: archf.common }
```

License
-------

MIT

Author Information
------------------

Felix Archambault
