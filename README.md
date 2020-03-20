andrewrothstein.docker_engine
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-docker_engine.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-docker_engine)

Installs the Docker Container Engine from OS packages.

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
    - role: andrewrothstein.docker_engine
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
