Role Name
=========

Ansible role to install and start Tomcat.

This role is for demonstration or development use only.

References
* [systemd](https://devops.profitbricks.com/tutorials/how-to-install-and-configure-tomcat-8-on-ubuntu-1604/#create-a-systemd-service-file)

Requirements
------------

The target system requirements are specified in [meta/main.yml](meta/main.yml).

Role Variables
--------------

Variables are defined in [vars/main.yml](vars/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: agilityroots.tomcat }

License
-------

MIT

Author Information
------------------

http://www.agilityroots.com, http://github.com/agilityroots
