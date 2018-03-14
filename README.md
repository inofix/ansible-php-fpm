PHP FPM
=======

Install the FastCGI Process Manager and configure one or more pools.

State
-----

Unstable.

Installation
------------

    # ansible-galaxy install inofix.php-fpm

Requirements
------------

* Ansible >2.0
* Python2/3 on target host
* Generic UNIX with FHS
* Sudo

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - inofix.php-fpm

License
-------

GPLv3

Author Information
------------------

* Michael Lustenberger at [inofix.ch](http://www.inofix.ch)

