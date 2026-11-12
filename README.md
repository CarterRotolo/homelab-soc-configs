# Homelab/SOC configuration files

A collection of various configuration files that are used in my homelab's services. Files range from Docker Compose files to JSON configuration files.

All services with files (that I can safely share without compromising system security) are stored in a folder with that service's name. Some files have been altered to prevent things like IP addressing schemes from being leaked, but are otherwise unchanged.

---

##  List of current services

| Service | Description | Config file |
| :-- | :-- | :-- |
| **Caddy** | Reverse proxy server that works with Pi-hole | [`Caddyfile`](caddy/Caddyfile) |
| **Jellyfin** | Media server library primarily for eBooks and home videos | [`docker-compose.yml`](jellyfin/docker-compose.yml) |
| **Navidrome** | Music streaming server | [`docker-compose.yml`](navidrome/docker-compose.yml) |
| **Nextcloud** | Network file sharing service used to upload new things to Jellyfin and Navidrome from the web | [`docker-compose.yml`](nextcloud/docker-compose.yml) |
> [!NOTE]
> IP addresses, domains, passwords, and other secrets have been removed or replaced with placeholders. Update them for your own environment before using any of these files.

---

## What's coming next?

- Security Onion + Elastic rule configuration
- Windows Active Directory + GPOs
- A game server hosting service
- ...and much more!
