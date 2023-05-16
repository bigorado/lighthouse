Lighthouse-role
=========

Install Lighthouse with nginx web server

Requirements
------------

CentOS

Role Variables
--------------
|Variable|Value|
|--------|-----|
|lighthouse_location_dir|directory for Lighthouse|
|lighthouse_vcs|Lighthouse repo URL| 

Example Playbook
----------------

    - hosts: servers
      roles:
         - lighthouse-role

License
-------

MIT

Author Information
------------------

Vladislav Brattsev