aws-iam-authenticator
=========

A simple Ansible role that installs [aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator) on the system.

Requirements
------------

See [meta/main.yml](meta/main.yml).

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml) and [vars/main.yml](vars/main.yml).

Dependencies
------------

See [meta/main.yml](meta/main.yml).

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: samcre.aws-iam-authenticator, aws_iam_authenticator_privilege_escalation: True }

License
-------

GNU GENERAL PUBLIC LICENSE Version 3

Author Information
------------------

Samuel Crespo (samuelcc87@gmail.com)
