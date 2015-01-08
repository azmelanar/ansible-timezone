Timezone
========

[![Build Status](https://api.travis-ci.org/azmelanar/ansible-timezone.png)](https://travis-ci.org/azmelanar/ansible-timezone) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-timezone-blue.svg)](https://galaxy.ansible.com/list#/roles/2527)

Role for installation packages of timezone and configuration system timezone.

Requirements
------------

Tested with Ansible 1.8.2

Role Variables
--------------

Default value can be found in defaults/main.yml

    timezone: UTC

Also you can set your timezone like string in *unix directory path format, which be valid from `/usr/share/zoneinfo/`.

Dependencies
------------

None

Example Playbook
----------------

Example of usage:

    - hosts: servers
      roles:
         - { role: azmelanar.timezone, timezone: UTC }

License
-------

MIT

Feedback, improvements, bugs
----------------------------

Please use [issues](https://github.com/azmelanar/ansible-timezone/issues).
