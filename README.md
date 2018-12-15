Role Name
=========

haproxy_setup

Requirements
------------

You will need to set/define the variables in the defaults variable file in 'defaults/main.yml'. Use the pre-compiled on as a guide line. You can customize it as you like.

Role Variables
--------------

If you need/want to add additional variables you can.

Dependencies
------------

The target host needs to have already been installed with base OS Centos7.

Example Playbook
----------------

  - name: Init
    hosts: LB
    become: true

    roles:
      - haproxy_setup

License
-------

BSD

Author Information
------------------

Name: Micka Kadima Luboya
Blog: cybersecmickey.blogspot.com
