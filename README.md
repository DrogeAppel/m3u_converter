# 🇹🇷 Open IPTV Playlist

This project generates an up-to-date `.m3u` playlist of publicly available Turkish IPTV channels, enriched with logos and metadata from [iptv-org](https://github.com/iptv-org/iptv).

### ✅ Features

- Combines data from:
  - [TVGarden Channel List](https://github.com/TVGarden/tv-garden-channel-list)
  - [iptv-org channel metadata](https://iptv-org.github.io/api/channels.json)
- Filters Turkish channels only
- Merges multiple working stream URLs per channel
- Automatically adds channel logos (`tvg-logo`)
- Updates automatically every 20 hours via GitHub Actions

---

## 📺 Playlist URL

You can use this link directly in IPTV apps (like VLC, Tivimate, IPTV Smarters, etc.):

