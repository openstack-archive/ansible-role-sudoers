====================
ansible-role-sudoers
====================

Ansible role to manage Sudoers

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-sudoers.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-sudoers
* Bugs: https://bugs.launchpad.net/ansible-role-sudoers

Description
-----------

The sudoers policy plugin determines a user's sudo privileges.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install sudoers
      hosts: www
      roles:
        - ansible-role-sudoers
