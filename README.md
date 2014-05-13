tower
========

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/tower/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/tower)

This role will install and configure various features of Ansible Tower.

Requirements
------------

Shares the same requirements as the official Tower installer.

Role Variables
--------------

* `tower_version` Used to set the version of Tower to be installed.
* `tower_checksum` sha256 checksum of the Tower installer that is downloaded.
* `tower_force_setup` Force the role to run the setup command. (Default: False).
* `tower_dependencies` Any dependent packages for the install process.

Dependencies
------------

No external dependencies.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: Rackspace_Automation.tower, x: 42 }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
