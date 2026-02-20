# docker-images

Custom Docker images for homelab use, built weekly via GitHub Actions and published to GHCR.

## Images

### caddy-desec

Standard [Caddy](https://caddyserver.com/) web server with the [caddy-dns/desec](https://github.com/caddy-dns/desec) module baked in, enabling DNS-01 ACME challenges via [deSEC](https://desec.io/) for automatic TLS certificate provisioning on hosts that aren't publicly reachable.

`ghcr.io/tinnet/caddy-desec:latest`

### caddy-bunny

Standard [Caddy](https://caddyserver.com/) web server with the [caddy-dns/bunny](https://github.com/caddy-dns/bunny) module baked in, enabling DNS-01 ACME challenges via [Bunny.net](https://bunny.net/) for automatic TLS certificate provisioning on hosts that aren't publicly reachable.

`ghcr.io/tinnet/caddy-bunny:latest`
