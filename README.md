Role Name [![Build Status](https://travis-ci.org/Copser/elm-ansible-role.svg?branch=develop)](https://travis-ci.org/Copser/elm-ansible-role)
=========

Ansible role for [Elm](https://elm-lang.org/) 

Requirements
------------

None

Role Variables
--------------

You can check available variables in `vars/main.yml`. For now we are compiling elm from source so the only
variable for now are:

- wget
- curl

Dependencies
------------

None

Example Playbook (using default package)
----------------

    - hosts: servers
      roles:
         - copser.elm

License
-------

BSD

Author Information
------------------

This role was created in 2018 by [Petar Pilipovic](https://twitter.com/Coopsess).

