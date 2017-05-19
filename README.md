# docker-images

Ansible role to load images onto a remote Docker host where access to a registry is not possible.


## Requirements

- Ansible >= 2.3

On Ansible control machine and host that executes module:

- `python` >= 2.6
- `docker-py` >= 1.7.0
- `Docker API` >= 1.20

## Role Variables

- `images`: List of image names and tags to pull from registries
- `force_pull_images`: Set to `True` to force a pull from registries even if images already exist on the control
machine. Defaults to `False`.
