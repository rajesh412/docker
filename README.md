# Docker Installation - Ansible Role
Install [Docker](http://docker.com) on CentOS and Red Hat hosts. Used to make sure that docker is installed
and running to enable the use of [Ansible's docker module](http://docs.ansible.com/docker_module.html)

## Test

### Usage

```yaml
- hosts: localhost
- roles:
    - docker
```
