Debian-Python
=============

Python Programming Language

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-python }

Tasks
-----

  - Install [Python](http://www.python.org/)
  - Install [python-mysqldb](http://mysql-python.sourceforge.net/) MySQL driver


License
-------

BSD
