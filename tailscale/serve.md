## Unraid

# Plex
tailscale serve --service=svc:plex --https=443 localhost:32400

# Radarr
tailscale serve --service=svc:radarr --https=443 localhost:7878

# Sonarr
tailscale serve --service=svc:sonarr --https=443 localhost:8989

# Lidarr
tailscale serve --service=svc:lidarr --https=443 localhost:8686

# Jellyseerr
tailscale serve --service=svc:jellyseerr --https=443 localhost:5055

# Bazarr
tailscale serve --service=svc:bazarr --https=443 localhost:6767

# Wizarr
tailscale serve --service=svc:wizarr --https=443 localhost:5690

# Jellyfin
tailscale serve --service=svc:jellyfin --https=443 localhost:8096

# Prowlarr
tailscale serve --service=svc:prowlarr --https=443 localhost:9696

# MeTube
tailscale serve --service=svc:metube --https=443 localhost:8333

## Homebridge RPi

# Service
tailscale serve --service=svc:hb --https=443 localhost:8581