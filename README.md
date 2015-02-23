# Docker Installation - Ansible Role
Install [Docker](http://docker.com) on CentOS and Red Hat hosts. Used to make sure that docker is installed
and running to enable the use of [Ansible's docker module](http://docs.ansible.com/docker_module.html)

### Installation
Add this repository as a submodule of your git with:

```
git submodule add git@github.com:Vinelab/ansible-docker roles/docker
```

Or simply clone this repository directly into your *roles* directory:

```
git clone git@github.com:Vinelab/ansible-docker roles/docker
```

### Usage

```yaml
- hosts: all
- roles:
    - docker
```

#### Tags
All tasks have the tag `docker`
