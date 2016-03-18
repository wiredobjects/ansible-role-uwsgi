Ansible Role uwsgi
==================

Managing the uwsgi service.
uWSGI is a fast (pure C), self-healing, developer/sysadmin-friendly application container server for Python WSGI apps.

Requirements
------------

No requirements.

Role Variables
--------------



Dependencies
------------

This role depends on wiredobjects.epel.

Example Playbook
----------------

    - hosts: wsgiservers
      roles:
         - { role: wiredobjects.uwsgi }

License
-------

Apache

Author Information
------------------

Initial created 2016 by refnode and CONTRIBUTORS.

