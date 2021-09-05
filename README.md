andrewrothstein.qemu
=========

![Build Status](https://github.com/andrewrothstein/ansible-qemu/actions/workflows/build.yml/badge.svg)

Installs [qemu](https://www.qemu.org).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.qemu
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
