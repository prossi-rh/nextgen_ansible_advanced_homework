Role Name
=========

Create RHOSP Instances for QA environment

Requirements
------------

N/A

Role Variables
--------------

./osp-servers/vars/main.yml

Dependencies
------------

N/A

Example Playbook
----------------

     - hosts: workstation
       become: no
       roles:
         - osp-servers

License
-------

BSD

Author Information
------------------

Pierluigi Rossi for Ansible Advanced Homework
