docker-swarm-ubuntu
=========

This role will setup a docker swarm cluster as outlined in the docker docs for production example. It is intended for use with vagrant but can easily be adjusted to use against any inventory.

Requirements
------------

None.

Role Variables
--------------
All variables are set in defaults, out of the box there should be no adjustments required for use with vagrant.

- docker_apt_repo
- docker_opts
- consul_ip_addr
- docker_swarm_addr
- docker_swarm_port

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```- name: Provision Docker Swarm cluster
  hosts: all
  become: true

  roles:
    - { role: docker-swarm-ubuntu }
```

License
-------

BSD

Author Information
------------------

Luke Tislow
