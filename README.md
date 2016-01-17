Ansible role panxatony.x2go
=========

Ansibile role used to install X2go server as well as Windowmanager (Default: Xfce)

Requirements
------------

none

Role Variables
--------------

Windowmanager installation is based on groupinstall feature with following variables:

    x2go_windowmanager: Xfce

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: panxatony.x2go, x2go_windowmanager: Xfce }

License
-------

BSD

Author Information
------------------

Created by Lars Hunold (hunold@hpe.com)
