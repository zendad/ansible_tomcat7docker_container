ansible-role-tomat
=========

An Ansible role to install tomcat7 Docker  container.

Requirements
------------

docker installation

installation
------------

    ansible-galaxy install dereck.tomcat7

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dereck.tomcat7 }