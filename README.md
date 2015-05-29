mariadb
=======

Installs and configures MariaDB

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name                   | Default | Description                          |
|------------------------|---------|--------------------------------------|
| mariadb_server_version | 10.0    | Version of MariaDB server to install |
| mariadb_server         | true    | Install MariaDB server               |
| mariadb_client_version | 10.0    | Version of MariaDB client to install |
| mariadb_client         | true    | Install MariaDB client               |

Dependencies
------------

None

Example Playbook
----------------

Install MariaDB
```
- hosts: all
  roles:
    - { role: kbrebanov.mariadb }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
