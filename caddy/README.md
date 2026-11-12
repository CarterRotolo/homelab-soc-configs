# Caddy
Caddy is used to create custom TLS certificates for custom domains on the network. It also functions as a reverse proxy so the Jellyfin, Navidrome and Nextcloud services can all be hosted on one docker instance and still have custom domain names.


# Nextcloud redirection
'redir /.well-known/caldav /remote.php/dav 301' redirects the standard discovery URLs to Nextcloud’s DAV endpoint, otherwise IOS/MacOS devices require the full file path when trying to use the custom domain name.
