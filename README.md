# Docker Installation [ansible]

[![Build Status](https://travis-ci.org/ruiznato/ansible-docker.svg?branch=master)](https://travis-ci.org/ruiznato/ansible-docker) [![Ansible Galaxy](http://img.shields.io/badge/galaxy-ruiznato.docker-blue.svg?style=flat)](https://galaxy.ansible.com/ruiznato/docker/)

Install Docker in Ubuntu

### Requirements
None

### Variables
- ```docker_users: []```

List of users to be added to docker group

### Dependencies
None

### Usage
```yaml
hosts: all
roles:
  - { name: ruiznato.docker }
```

```yaml
hosts: all
roles:
  - { name: ruiznato.docker, docker_user: [vagrant] }
```
