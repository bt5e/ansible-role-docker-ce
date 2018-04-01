Ansible Role - Docker CE - CentOS
=================================

[![Build Status](https://travis-ci.org/bt5e/ansible-role-docker-ce.svg?branch=master)](https://travis-ci.org/bt5e/ansible-role-docker-ce)

Docker CE non-production install based on: https://docs.docker.com/engine/installation/linux/centos/

Requirements
------------

Assumes no existing Docker installation.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - bt5e.docker-ce

License
-------

MIT

Author Information
------------------

Ben Tse
