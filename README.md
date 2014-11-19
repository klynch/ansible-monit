Monit
=========

Installs [monit](http://mmonit.com/monit/).

Requirements
------------

None.

Role Variables
--------------

Monit can be configured to check services every `monit_daemon_timeout_seconds` seconds. By default, this is set to 60 seconds.

Dependencies
------------

None.

Example Playbook
----------------

This is run like any basic role:

    - hosts: servers
      roles:
         - monit

License
-------

BSD
