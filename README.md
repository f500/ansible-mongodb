MongoDB
=============

Install and configure MongoDB.

Requirements
------------

None.

Role Variables
--------------

Select the prefered state of the package (`present` or `latest`):

    mongodb_state: present

These configuration variables are used to create `/etc/mongod.conf`:


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: f500.mongodb, mongdb_bind_ip: "127.0.0.1" }

License
-------

LGPLv3

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
