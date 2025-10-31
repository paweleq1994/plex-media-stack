# Plex Media Stack (Docker)

Kompletny domowy serwer multimediów zbudowany na Dockerze:
- **qBittorrent** – klient torrent
- **Radarr** – filmy
- **Sonarr** – seriale
- **Bazarr** – napisy
- **Prowlarr** – indexery dla *-arr
- **Overseerr** – prośby od użytkowników
- **ByParr** – obejście Cloudflare (proxy FlareSolverr-compatible)
- **Portainer** – panel do zarządzania Dockerem (HTTP)
- **Watchtower** – automatyczne aktualizacje kontenerów

> Repo zawiera `docker-compose.yml`. Ścieżki hosta domyślnie wskazują na `/media/plex/...`.
