andrewrothstein.gitlab-ci-multi-runner
======================================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-gitlab-ci-multi-runner.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-gitlab-ci-multi-runner)

Installs and configures a [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-ci-multi-runner).

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
    - andrewrothstein.gitlab-ci-multi-runner
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>

Contributors
------------

Vishal Shah <vishal.shah@nyu.edu>
