Ansible Role: Memcached
=======================

Installs minimal Memcached 1.4.21 (from source) on CentOS 6.5

Requirements
------------

None.

Role Variables
--------------

Default values:

* memcached_port: 11211
* memcached_user: memcached
* memcached_maxconn: 1024
* memcached_cachesize: 64

You can override these values on your playbook.

Dependencies
------------

* tcosta84.yum

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tcosta84.memcached }

License
-------

BSD

Author Information
------------------

This role was created by [Thiago Costa](http://thiagocostapy.com)
