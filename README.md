Qafoo Base
==========

Base Ubuntu Server requirements for a web/php application server(s).
This role must be used on any server that is later modified using other qafoo- ansible roles.

Requirements
------------

Ubuntu Server

Role Variables
--------------

The Qafoo-Base role is almost unconfigurable, it contains all the required base
packages and repositories that a web/application server needs.

    # Java Version to install, defaults to Java8
    base_java_version: 8

Example Playbook
----------------

The Qafoo-Base role is not configurable, it contains all the required base
packages and repositories that a web/application server needs.

    - hosts: servers
      roles:
         - role: "qafoo.base"
           base_java_version: 8

License
-------

BSD

Author Information
------------------

Benjamin Eberlei <benjamin@qafoo.com>
https://github.com/QafooGalaxy
