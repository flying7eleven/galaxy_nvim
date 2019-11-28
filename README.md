galaxy_nvim
==========

This role can be used to install and set up `neovim` on your linux computer. **WARNING**: Be aware, that on Debian/Ubuntu computers,
this playbook will only install the configuration files, not neovim itself.

Requirements
------------

There are **no** additional requirements which have to be fulfilled before using this role.

Role Variables
--------------

There are **no** variables to set for this role.

Dependencies
------------

This roles is **not** depending on any other role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      connection: local
      roles:
         - galaxy_nvim

License
-------

GPLv3

Author Information
------------------

This role is developed and maintained by [Tim Hütz](https://github.com/thuetz).
