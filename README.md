nginx
===

This role will install NGINX package, and run it as a service.

Requirements
------------

So far it was tested under Ubuntu 14 and Ubuntu 16. 

Role Variables
--------------

 You can change NGINX options with "nginx__daemon_options" variable. DO NOT change it in the defaults/main.yml, use vars/main.yml instead. 

Dependencies
------------

 No.

Example Playbook
----------------

Here is an example of how to use this role (for instance, with variables passed in as parameters):

    - hosts: servers
      roles:
         - { role: nginx, nginx__daemon_options="-g" }

License
-------

Apache v2.0

Author Information
------------------

Dmitrii Ageev <dmitrii.ageev@reannz.co.nz>


TODO
----


HISTORY
-------

+ Add CentOS 6.x and Ubuntu 12 support

