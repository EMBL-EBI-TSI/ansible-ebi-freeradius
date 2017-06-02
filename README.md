FreeRADIUS
==========
Install FreeRADIUS from source.

Only versions 2.x are supported.

Aditonally compiles and installs LinOTP's freeradius module if
requested in `freeradius_linotp`. The version of LinOTP to clone can
be specified with `freeradius_linotp_branch`.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
See `defaults/main.yml`.

Dependencies
------------
None.

Example Playbook
----------------
Example:
```
- hosts: servers
  roles:
    - freeradius
```

TODO
----
- Select modules to compile.

Licence
-------
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Author Information
------------------
Luis Gracia while at [EMBL-EBI](http://www.ebi.ac.uk/):
- luis.gracia [at] ebi.ac.uk
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)
