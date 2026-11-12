# Caddy
Caddy is used to create custom TLS certificates for custom domains on the network. It also functions as a reverse proxy so the Jellyfin, Navidrome and Nextcloud services can all be hosted on one docker instance and still have custom domain names.


# Caddyfile
[`Caddyfile`](caddy/Caddyfile) is what tells Caddyfile which IP/Port combo belongs to each domain.
