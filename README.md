ECGALAXY docker-compose
=======================

This role installs docker-compose.

Requirements
------------

None.

Role Variables
--------------

- `docker_compose_version`: "1.26.0"
- `docker_compose_path`: /usr/local/bin/docker-compose

Dependencies
------------

None.

Example Playbook
----------------

- hosts: all
  roles:
    - ecgalaxy.docker_compose

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
