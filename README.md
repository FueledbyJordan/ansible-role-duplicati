ansible-role-duplicati
======================

This role configures duplicati for my homelab.

Requirements
------------

N/A

Role Variables
--------------
* duplicati\_success\_home\_assistant\_endpoint

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
    - ansible-role-duplicati
```

License
-------

MIT

Author Information
------------------

I can be reached at [djm@murrayfoundry.com](mailto:djm@murrayfoundry.com).
