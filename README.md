Ansible Runit Role
========

Install runit and add runit module. runit module can manage runit services.

Requirements
------------

Tested on Ubuntu only. Patches welcome for other platforms.

Role Variables
--------------

None at this time.

Dependencies
------------

None at this time.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: bakins.runit }
      tasks:
         - runit: name=myservice state=started

runit supports hree states: "started", "stopped", "restarted"


License
-------

Apache2

Author Information
------------------

brian@akins.org
