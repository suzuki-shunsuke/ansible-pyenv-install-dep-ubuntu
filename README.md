pyenv-install-dep-ubuntu
==========================

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-pyenv-install-dep-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-pyenv-install-dep-ubuntu)

Install pyenv install dependencies on Ubuntu.

> # This role is deprecated
>
> From the version 3.0.0, [suzuki-shunsuke.pyenv](https://galaxy.ansible.com/suzuki-shunsuke/pyenv/) supports to install build dependencies.

Requirements
------------

Nothing.

Role Variables
--------------

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.pyenv-install-dep-ubuntu
```

License
-------

MIT
