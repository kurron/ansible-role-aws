Role Name
=========

Installation of tools than any self-respecting Python developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* python_pycharm_install: true
* python_pycharm_version: 2016.2.3
* python_pycharm_edu_install: true
* python_pycharm_edu_version: 3.0.1

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.python-developer, python_pycharm_version: 2016.2.3 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
