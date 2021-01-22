Ansible-Role-Hostname
=========
This is a simple role which updates hostnames
Requirements
------------
None
Role Variables
--------------
hostname="localhost.localdomain"
Dependencies
------------
None
Example Playbook
----------------
  roles:
    - role: ansible-role-hostname
      vars:
        hostname: "customhostname"
License
-------
MIT
Author Information
------------------
Olga Guseva