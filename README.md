nginx
=====

This role handles the installation and configuration of an NGINX instance.

Requirements
------------

So far it was tested with Ubuntu 16. 

Role Variables
--------------

 You can change NGINX options with "nginx__options" variable. DO NOT change it in the defaults/main.yml, use group_vars/host_vars instead. 

Example Playbook
----------------

Here is an example of how to use this role (for instance, with variables passed in as parameters):

    - hosts: servers
      roles:
         - { role: nginx, nginx__options="-g" }

License
-------

GPLv2

Author Information
------------------

Dmitrii Ageev <d.ageev@gmail.com>

