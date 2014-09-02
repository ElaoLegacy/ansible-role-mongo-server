Ansible Role - MongoDB Server
=============================

A MongoDB server role to install MongoDB server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    mongo server restart  # Restart MongoDB server


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.mongo-server }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
