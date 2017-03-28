ansible-role-tomcat7-docker-container
=========

An Ansible role to install Docker & tomcat7 docker container in Debian or Ubuntu.

Requirements
------------

64bit Debian / Ubuntu

installation
------------

    ansible-playbook playbook/site.yml 



Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dereck.docker }
		 - { role: dereck.tomcat7}



Example War Deploy
------------------

deploy https://tomcat.apache.org/tomcat-6.0-doc/appdev/sample/sample.war to /opt/tomcat/webapps/
test on browser:
http://localhost:8080/sample

