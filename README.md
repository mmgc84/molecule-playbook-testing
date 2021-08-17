[![CI](https://github.com/mmgc84/molecule-playbook-testing/actions/workflows/ci.yml/badge.svg)](https://github.com/mmgc84/molecule-playbook-testing/actions/workflows/ci.yml)

This playbook install a simple web site using the Apache web server

Usage
=====
$ ansible-playbook -i INVENTOR main.yml

Requirements
============
Supports only CentOS8 or Ubuntu20.04

Testing
=======
Testing is provided via Molecule. Run `molecule test` to verify this playbook.