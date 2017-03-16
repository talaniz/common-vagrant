Common Vagrant
==============

A simple role to complete common vagrant setup tasks.

Requirements
------------

Ansible version 16+ as the ufw module is used.

Variables
---------

There are currently no variables, but some will need to be added to customize the role (see to do list).

Example Playbook
----------------

    - hosts: servers
      roles:
         - talaniz.common-vagrant

License
-------

BSD

Author Information
------------------
E-mail: antonio.alaniz@gmail.com
Website: www.antonioalaniz.com

To Do
------

* Add {{user}} variable so users can select the non-root user.
