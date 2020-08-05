Role Name
=========

Delete RHOSP Instances for QA environment

Requirements
------------

N/A

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

     - hosts: workstation
       become: yes
       roles:
         - osp-instance-delete

License
-------

BSD

Author Information
------------------

Pierluigi Rossi for Ansible Advanced Homework
