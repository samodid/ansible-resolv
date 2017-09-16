Role Name
=========

My way to populate resolv.conf data

Requirements
------------

None

Role Variables
--------------

resolv_domain - string. Local domain name.

resolv_search - list of strings. Search list for host-name lookup.

resolv_options - list of strings. Options allows certain internal resolver variables to be modified.

resolv_servers - list of name server IP adresses.

Dependencies
------------

None

Example Playbook
----------------


    - hosts: servers
      roles:
         - role: resolv
           resolv_domain: mylocal.net

License
-------

BSD

Author Information
------------------

samodid@gmail.com
