Role Name
=========

infra-apache: Simple web server config for studying purposes

Requirements
------------

None

Role Variables
--------------

[defaults]

# Location for web content
apache_content_dst: /var/www/html

# apache group
apache_group: apache


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - infra-apache

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
---


