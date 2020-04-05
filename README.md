ansible-role-ssh-port
=====================

An ansible role that configures the port of SSH daemon.

Requirements
------------

None.

Role Variables
--------------

variable | default
-------- | -------
ssh_port | 22

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: servers
  roles:
  - role: bit_kitchen.ssh_port
    ssh_port: 10022
```

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
