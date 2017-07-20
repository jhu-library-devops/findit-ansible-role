FindIt Ansible Role
===================

An ansible role to deploy FindIt (umlaut_jh) a customized ulmaut, which is a rail application.
FindIt is a our open-url link resolver, and integrates with sfx, catalyst, hati-trust, google schoar.

Requirements
------------

The following must be available for findit to function 
- MySQL database
- SFX service
- Catalyst service

Role Variables
--------------

TBD

Dependencies
------------

* Ruby

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: findit }

License
-------

CC0

Author Information
------------------

Farooq Sadiq
Drew Heles
