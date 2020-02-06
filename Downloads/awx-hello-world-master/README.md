# Awx-Hello-World

A simple hello world role to be used as a base for our new roles.

The role is meant to show case a few features of ansible that we will want to
make use of. It is also used to show a very basic but common type of role, where
we install a package, render a configuration file and start the service.

# Requirements

There are no requirements for this role.

# Role Variables

| Variable | Default | Required | Comment |
| ---   | --- | ---  | ---  |
|hello_world_network|||The docker network to create with `docker network create`|

# Dependencies

This role does not have any dependencies.

# Example Playbook

```yaml
- hosts: all
  roles:
  - role: awx-hello-world
    hello_world_network: "my-network"
```
