ssh-port
========

An ansible role that changes the port of SSH daemon.


Role Variables
--------------

variable | default
-------- | -------
ssh_port | 22

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bit_kitchen.ssh_port, ssh_port: 10022 }
