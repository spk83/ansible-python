spk83.python3
===========================
[![Build Status](https://travis-ci.org/spk83/ansible-python.svg?branch=master)](https://travis-ci.org/spk83/ansible-python)

A role for installing a [Python 3](https://www.python.org/) development environment from operating system packages including [pip](https://pypi.python.org/pypi/pip) and [virtualenv](https://pypi.python.org/pypi/virtualenv).

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
    - spk83.python3
```

License
-------

MIT

Author Information
------------------

Vishal Shah <vishal.shah@nyu.edu>
