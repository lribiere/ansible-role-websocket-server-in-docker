websocket-server-in-docker
=========

This is an ansible role to deploy a custom Java websocket server in docker.

Requirements
------------

The following packages have to be installed and well configured on the host :
- [Docker-ce](https://docs.docker.com/engine/installation/)

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

Tests
------------

ansible-playbook tests/test.yml --ask-become-pass -e websocket_server_root_location="$(PWD)/.workdir/"

License
-------

MIT
