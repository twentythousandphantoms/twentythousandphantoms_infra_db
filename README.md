Ansible Role twentythousandphantoms_infra_db
=========

[![Build Status](https://travis-ci.org/twentythousandphantoms/twentythousandphantoms_infra_db.svg?branch=master)](https://travis-ci.org/twentythousandphantoms/twentythousandphantoms_infra_db)
Dump role installing Mongo for discover how to test roles using Molecule and GCP

Installation
--------------

`ansible-galaxy install https://github.com/twentythousandphantoms/twentythousandphantoms_infra_db`

Example Playbook
----------------

---
- name: Install MongoDB
  become: true
  hosts: all
  vars:
    mongo_bind_ip: 0.0.0.0
  roles:
    - role: twentythousandphantoms_infra_db

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
