ansible-role-home-assistant
======================

This role configures home assistant for my homelab.

Requirements
------------

N/A

Role Variables
--------------
* duplicati\_success\_endpoint

Role Defaults
-------------
* duplicati\_conf\_dir
* duplicati\_user
* duplicati\_group

N/A

Dependencies
------------

N/A

Example Playbook
----------------

```
- hosts: servers
  roles:
    - ansible-role-home-assistant
```

License
-------

MIT

Author Information
------------------

I can be reached at [djm@murrayfoundry.com](mailto:djm@murrayfoundry.com).
