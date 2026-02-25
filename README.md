# nginx selinux pre config

Helm Chart NGINX hardened, rootless, compativel com SELinux enforcing.

## Features

- Rootless
- Read-only filesystem
- Compativel com SELinux enforcing
- Logs JSON
- Health e metrics endpoints
- Pod Security Standards: restricted

## Instalação

```bash
helm repo add nginx-custom https://luiscorreiaOps.github.io/nginx-custom-helm
helm install nginx-custom nginx-custom/nginx-custom-selinux
