Role Name
=========

A role to Deploy MYSQL and wordpress using Docker containers.

Requirements
------------

Using the module docker_container.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - name:  "deploy wordpress"
    hosts: worker01
    become: true
    roles:
      - wordpress

