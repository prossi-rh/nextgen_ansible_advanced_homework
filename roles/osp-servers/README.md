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

- hosts: localhost
  connection: local
  become: no
  gather_facts: true
  roles:
   - osp-servers


License
-------

BSD

Author Information
------------------

prossi-rh for Ansible Advanced Homework
