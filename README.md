ansible-role-ssh-port
=====================

An ansible role that configures the port of SSH daemon and related SELinux and firewalld settings.

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

* [`bit_kitchen.open_port`](https://github.com/bit-kitchen/ansible-role-open-port) for firewall configuration.


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
