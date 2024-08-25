Role Name
=========

Restart WAS/Solr App, Apache Webserver


Role Variables
--------------
./defaults/defaults.yml

Example Playbook
----------------
- name: Restart Web Servers
  hosts: web_server
  become: yes
  roles:
    - role: edu-was-restart
      tags:
        - stop_web_server
        - start_web_server

License
-------
BSD

Author Information
------------------
as511-devops