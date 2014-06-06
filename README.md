php
========

This role installs and configures PHP.

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/php/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/php)

Requirements
------------

No requirements.

Role Variables
--------------

See [defaults/main.yml](https://github.com/rack-roles/php/blob/master/defaults/main.yml) for a list of variables to override.

Dependencies
------------

There are no external dependencies.

Example Playbook
-------------------------

Here is a simple example playbook:

    ---
    - hosts: all
      roles:
        - { role: Rackspace_Automation.php, x: 42 }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
