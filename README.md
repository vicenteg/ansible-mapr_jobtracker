mapr-jobtracker
========

Installs mapr-jobtracker.

Requirements
------------

None

Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: https://1.2.3.4:3128
```

Dependencies
------------

Node

Example Playbook
-------------------------

```
- hosts: jobtracker
  max_fail_percentage: 0
  roles:
    - jobtracker
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com