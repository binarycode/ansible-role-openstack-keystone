Ansible Role: OpenStack Keystone
================================

This role installs and configures OpenStack Keystone on EL7 system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

    host: controller

Host that runs identity services.

    admin_token: foobar

Keystone administration token.

    region: RegionOne

Keystone region.

    admin_password: admin

Password for `admin` keystone user.

    demo_password: demo

Password for `demo` keystone user.

    mysql_host: controller
    mysql_password:

MySQL credentials.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - binarycode.openstack-keystone

License
-------

BSD

Author Information
------------------

[Igor Sidorov](https://github.com/binarycode)
