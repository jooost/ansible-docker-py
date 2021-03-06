andrewrothstein.docker-py
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-docker-py.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-docker-py)

Installs the [Docker bindings for Python](https://docker-py.readthedocs.io/en/stable/). Necessary for controlling Docker with Ansible.

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
    - andrewrothstein.docker-py
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
