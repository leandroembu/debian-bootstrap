Debian Bootstrap
=========

Ansible role to deploy new Debian Servers

Requirements
------------

A fresh Debian server with SSH access

Role Variables
--------------

vars/main.yml:
    - debian_version

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: leandroramos.debian_bootstrap, become: yes }

License
-------

GNU GPLv3
