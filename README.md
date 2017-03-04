Ansible Django Install
======================

A simple Ansible role used to install Django framework.

Role Variables
--------------

```yaml
django_db_drivers: [ ] 
django_version: "1.10"
django_py_major_ver: "2"
django_state: "present"
```


Example Playbook
----------------

```yaml
    - hosts: all
      become: true

      roles:
         - { role: meddam.django-install, django_version: "1.10" }
```

License
-------

BSD

Author Information
------------------

Mauro Medda aka deftunix < medda.mauro at gmail dot com >
