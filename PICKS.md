# Self-hosted picks

This page is intentionally selective. The goal is to help you decide what is worth running, not to duplicate `awesome-selfhosted`.

## Core infrastructure

| Project | Replaces / solves | Difficulty | Resources | Why it earns a spot |
|---|---|---:|---:|---|
| **Tailscale / WireGuard** | Private remote access | Easy–Medium | Light | Lets you reach services without exposing each one publicly. |
| **Caddy** | Reverse proxy + HTTPS | Medium | Light | Simple automatic TLS and readable configuration. |
| **AdGuard Home / Pi-hole** | DNS filtering | Easy | Light | High daily value with little maintenance. |
| **Gatus** | Uptime monitoring | Easy | Light | Excellent if you prefer config-as-code and GitOps. |
| **Uptime Kuma** | Uptime monitoring | Easy | Light | Friendly GUI and fast setup. |
| **Beszel** | Lightweight server monitoring | Easy | Light | Useful visibility without a huge observability stack. |

## Data you actually care about

| Project | Replaces / solves | Difficulty | Resources | Best for |
|---|---|---:|---:|---|
| **Vaultwarden** | Password manager backend | Medium | Light | Families / personal Bitwarden-compatible hosting |
| **Immich** | Google Photos-style library | Medium | Moderate–Heavy | Photos and videos |
| **Paperless-ngx** | Paper/document archive | Medium | Moderate | Bills, scans, PDFs, OCR search |
| **Nextcloud** | General cloud suite | Medium–Advanced | Moderate | Files + calendar + contacts + collaboration |
| **Syncthing** | Device file synchronization | Easy | Light | Direct sync without a central cloud |
| **Kopia / Restic** | Backups | Medium | Light–Moderate | Real backup workflows, snapshots and retention |

## Media

| Project | Purpose | Difficulty | Why use it |
|---|---|---:|---|
| **Jellyfin** | Movies/TV/live TV media server | Easy–Medium | Mature FOSS media server with broad client support. |
| **Navidrome** | Personal music server | Easy | Lightweight and purpose-built for music. |
| **Audiobookshelf** | Audiobooks and podcasts | Easy–Medium | One of the best category-specific self-hosted apps. |
| **Yamtrack** | Track entertainment across categories | Medium | Useful companion when you track more than just movies. |
| **Ampcast** | Multi-source music interface | Easy–Medium | Interesting companion for Navidrome/Jellyfin music libraries. |
| **Seerr** | Media request/discovery | Medium | Good for shared Jellyfin/Emby-style servers. |

See the dedicated **[Jellyfin guide](https://github.com/ish4ra/jellyfin-media-server-guide)** for server setup.

## Knowledge, bookmarks and reading

| Project | Purpose | Difficulty | Why it stands out |
|---|---|---:|---|
| **Karakeep** | Save links, notes and web content | Medium | Strong "read/save later" workflow with self-hosting. |
| **Linkwarden** | Bookmark management + archiving | Medium | Preserves pages and organizes links. |
| **Memos** | Lightweight notes / micro-journal | Easy | Very low friction compared with a full knowledge base. |
| **Miniflux** | RSS reader | Easy | Focused, fast and dependable. |
| **FreshRSS** | RSS reader | Easy | Feature-rich and widely supported. |
| **Readeck** | Read-later/archive workflow | Easy–Medium | A focused alternative to cloud read-later services. |

## Useful small services

- **PairDrop** — browser-based local file transfer.
- **changedetection.io** — monitor pages and notify on changes.
- **Stirling PDF** — practical web-based PDF toolkit.
- **Mealie** — recipe manager and meal planning.
- **Actual Budget** — local-first personal budgeting.
- **IT-Tools** — collection of small developer/admin utilities.
- **Gotify** — simple self-hosted push notifications.

## Home automation

- **Home Assistant** — the obvious pick if you actually own smart-home devices.
- **Node-RED** — visual automation/data-flow tool that pairs well with home automation and APIs.

## What I would install first

For a first server, a strong sequence is:

```text
1. Tailscale or WireGuard
2. One app you genuinely need
3. Restic or Kopia backups
4. Uptime Kuma or Gatus
5. AdGuard Home / Pi-hole
6. More services only when a real use case appears
```

The best self-hosted app is the one you still use six months later.