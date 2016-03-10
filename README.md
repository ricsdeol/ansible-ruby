Ansible-ruby
=========

Ruby installer

Requirements
------------

Build essentials

Role Variables
--------------

ruby:
  default: ruby2.2
  versions:
    - ruby2.2

Dependencies
------------

No.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: speedy-looper.ansible-ruby }

License
-------

MIT

Author Information
------------------

Hi, This is speed-of-light
