Role Name
=========

Install fp

Dependencies
------------
edu-was-stop
edu-was-start

Example Playbook
----------------
- hosts: all
  strategy: free
  # any_errors_fatal: true 
  become: yes
  roles:
    - edu-was-install-fp

TODO
--------
For prd add serial

License
-------
BSD

Author Information
------------------
as511-devops