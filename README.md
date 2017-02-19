Role Name
=========

Role install docker 1.13.0

Requirements
------------

Only works on Centos 7 or RedHat 7

Role Variables
--------------

**docker_vagrant** (optional): Default true. Permit to add group docker to user vagrant

**docker_storagedriver** (optional): Default devicemapper

**docker_remote_access** (optional): Default false. Permit remote accesss docker API

**docker_remote_access_port** (optional, use if docker_remote_access is true ): Default 2375. Listen port docker API.


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
