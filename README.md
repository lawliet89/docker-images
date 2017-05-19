# docker-images

Ansible role to load images onto a remote Docker host where access to a registry is not possible.

## Requirements

On Ansible control machine and host that executes module:

- `python` >= 2.6
- `docker-py` >= 1.7.0
- `Docker API` >= 1.20

## Role Variables


## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
