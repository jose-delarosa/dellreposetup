dellreposetup
=============

This role subscribes a RHEL-compatible or Debian-compatible system to the official Dell yum repositories for OpenManage and DSU (RHEL only).

Requirements
------------

A Dell PowerEdge server with RHEL 6 or 7 or Ubuntu 14.04 (more coming soon). CentOS not tested yet but should work the same.

Make sure you have OS repositories already defined in your system so you can pull in package dependencies as needed.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

- hosts: dell
  roles:
     - role: jose-delarosa.dellreposetup

License
-------

Apache

Author Information
------------------

jose.delarosa@dell.com
Please note this playbook is not officially supported by Dell and is published here as a convenience to Dell customers.
