# Ansible Role for Podman in RHEL
A role for install and configuring Podman for RHEL-based systems

## Tasks
- Install podman
- Create a caddy user, service and container

## Variables
Variables for configuration are provided in vars/main.yml
```
unprivileged_port_start: 23
```

## Caddy
Rename `files/caddy/Caddyfile.example` to `files/caddy/Caddyfile` and change the contents. By default it shows "Hello!" to all visitors.
