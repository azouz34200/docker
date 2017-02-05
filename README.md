Role Name
=========

Role install docker 1.13.0

Requirements
------------

Only works on Centos 7 or RedHat 7

Role Variables
--------------

**docker_vagrant** (optional): Default true

**docker_storagedriver** (optional): Default devicemapper

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: docker }

License
-------

Apache

Author Information
------------------

AZEMA Mickael
