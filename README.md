<div align="center">

# Selfhosted Picks

**A curated shortlist of self-hosted apps worth running — chosen for real usefulness, not list size.**

Instead of another catalogue with thousands of projects, this repo focuses on software that solves a clear problem, is actively useful at home, and is realistic to maintain.

**[Browse the picks →](PICKS.md)**

</div>

---

## Why this list exists

The self-hosted ecosystem is huge. The hard part is no longer finding software — it is deciding what is actually worth deploying and maintaining.

This list favors projects that:

- replace a paid/cloud dependency or solve a recurring problem;
- are useful after the novelty wears off;
- have a healthy open-source project or community;
- can be deployed without an enterprise-sized homelab;
- have a clear reason to self-host.

Recent self-hosting discussions repeatedly highlight the same pattern: apps that become daily infrastructure — password managers, media, photos, documents, monitoring, backups and networking — tend to stay, while novelty installs often get abandoned.

## Quick shortlist

| Need | Pick | Why it stands out | Difficulty |
|---|---|---|---|
| Passwords | **Vaultwarden** | Lightweight Bitwarden-compatible server | Medium |
| Photos | **Immich** | Excellent self-hosted photo/video library | Medium |
| Media | **Jellyfin** | Mature, subscription-free personal media server | Easy–Medium |
| Documents | **Paperless-ngx** | OCR + searchable document archive | Medium |
| File sync | **Syncthing** | Direct device-to-device sync | Easy |
| DNS filtering | **AdGuard Home / Pi-hole** | Network-wide blocking and DNS control | Easy |
| Uptime | **Gatus / Uptime Kuma** | Config-driven or GUI-driven monitoring | Easy |
| Bookmarks | **Karakeep / Linkwarden** | Archive and organize useful links | Medium |
| RSS | **Miniflux** | Fast, focused feed reader | Easy |
| Music | **Navidrome** | Lightweight personal music streaming | Easy |
| Requests | **Seerr** | Media request/discovery workflow | Medium |
| Remote access | **Tailscale / WireGuard** | Private access without exposing every service | Easy–Medium |

## Beyond the usual names

If you already know Jellyfin, Immich, Vaultwarden and Home Assistant, start with:

- **Gatus** — uptime monitoring configured as code;
- **Blocky** — YAML-driven DNS proxy/filtering;
- **Yamtrack** — track movies, TV, anime, games and books;
- **Ampcast** — one music interface across sources such as Navidrome/Jellyfin;
- **Karakeep** — save links, notes and web content for later;
- **Memos** — lightweight self-hosted notes/micro-journal;
- **PairDrop** — local-network file sharing in the browser;
- **changedetection.io** — monitor pages for meaningful changes;
- **Gatus** — especially good when you prefer GitOps/config files to dashboards.

## Rating fields

Each recommendation in [PICKS.md](PICKS.md) uses the same practical questions:

- **What does it replace?**
- **Why self-host it?**
- **Setup difficulty** — Easy / Medium / Advanced
- **Resource class** — Light / Moderate / Heavy
- **Container friendly?**
- **Best for** — who benefits most
- **Caveats** — what could make it a bad fit

## Start small

A good first server does **not** need 30 containers. A sensible beginner path is:

1. one service you will actually use;
2. backups for that service;
3. private remote access;
4. monitoring;
5. only then add more apps.

If you are building the infrastructure itself for the first time, see **[homelab-from-zero](https://github.com/ish4ra/homelab-from-zero)**.

For a larger directory of open-source alternatives, see **[open-source-alternatives](https://github.com/ish4ra/open-source-alternatives)**.

## Contributing

Suggestions are welcome, but this repo intentionally rejects "list everything" growth. Read [CRITERIA.md](CRITERIA.md) before proposing a project.

---

If this shortlist helps you avoid a weekend of installing things you never use, a ⭐ helps other people find it.