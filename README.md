[![Build Status](https://travis-ci.org/wtanaka/ansible-role-php56-fpm.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-php56-fpm)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-php56-fpm.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-php56-fpm)

wtanaka.php56-fpm
=================

Ansible role to install php56-fpm

Example Playbook
----------------

    - hosts: all
      roles:
         - role: wtanaka.php56-fpm
           php56_fpm_listen: 127.0.0.1:9000

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
