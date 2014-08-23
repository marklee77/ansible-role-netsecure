marklee77.netsecure
===================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-netsecure.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-netsecure)

Installs packages and makes configuration changes to improve Ubuntu network
security. In particular, this installs fail2ban and various openssh and openssl
blacklists.

Example Playbook
----------------

    - hosts: all
      sudo: True
      roles:
        - marklee77.netsecure

License
-------

GPLv2

Author Information
------------------

http://stillwell.me
