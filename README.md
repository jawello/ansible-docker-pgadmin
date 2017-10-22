ansible-docker-pgadmin
======================

Provisions and runs pgadmin4 in a docker container

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

tjcim.ansible-vagrant-box
tjcim.ansible-docker

Example Playbook
----------------

    ---
    - hosts: pgadmin
      roles:
        - {role: 'tjcim.ansible-docker-pgadmin', tags: 'pgadmin'}


License
-------

BSD

Author Information
------------------

Present
