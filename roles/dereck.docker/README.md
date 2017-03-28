ansible-role-docker
=========

An Ansible role to install Docker in Debian or Ubuntu.

Requirements
------------

64bit Debian / Ubuntu

installation
------------

    ansible-galaxy install dereck.docker

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dereck.docker }


