Role Name
=========

This role comprises of the basic tasks used to deploy a lug.org.uk server.

Requirements
------------

None

Role Variables
--------------

sshd_port: Defaults to 22

Dependencies
------------

Currently, none.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lugorguk.common sshd_port: 2222 }

License
-------

BSD

Author Information
------------------

This is the code which drives lug.org.uk. It was created by Jon "The Nice Guy" Spriggs (jon@sprig.gs | https://jon.sprig.gs | https://twitter.com/jontheniceguy)
