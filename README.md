# Runtipi appstore
This is my own [Runtipi](https://runtipi.io/) appstore. Some are custom apps (not in the [official Runtipi appstore](https://github.com/runtipi/runtipi-appstore)), some are custom setups of apps from the [official Runtipi appstore](https://github.com/runtipi/runtipi-appstore).

> [!WARNING]
> This is my personal repository for my own Tipi instance(s).
> * I am not an expert in any area of self-hosting.
> * I cannot guarantee that any of these apps work (for me or for you).
> * I take no responsibility for any software or hardware issues you may encounter as a result of your usage of any apps in this repository. This includes any potential data loss as a result of updates to the repository/app. Do your own due diligence!
> **USE AT YOUR OWN RISK!!!**


## Apps available (16)

|  Type  |  Name  |  Docker image version  |  Description  |  Port  |  Has dynamic file  |  Notes  |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| Custom app  | [Pangolin Newt client](https://github.com/fosrl/newt)  |  1.6.0 | Connect your site (machine) to your Pangolin network.  | none required  | yes  |  |
| Modified existing app | [Cup](https://cup.sergi0g.dev/) |  v3.4.3 | Check for Docker container updates. |  8465 | yes  | Updated Docker image version from `v3.2.3` to `v3.4.0`.  |
| Modified existing app | [Docmost](https://docmost.com/) |  0.20.4 | An open-source collaborative wiki and documentation software.  |  9713 | yes  | Updated Docker image version for PostgreSQL from `16-alpine` to `16.9-alpine` |
| Modified existing app | [Dokuwiki](https://www.dokuwiki.org/dokuwiki) |  2025-05-14-ls268 | A simple to use and highly versatile open source wiki software.  |  8149 | yes  | Updated Docker image version from `2024-02-06b-ls250` to `2025-05-14-ls268`.  |
| Modified existing app | [Forgejo](https://codeberg.org/forgejo/forgejo) |  13.0.2 | Self-hosted lightweight Git server  |  8195 | yes  | Removed dependence on PostgreSQL. Updated Docker image version from `11.0.1` to `11.0.2`.   |
| Modified existing app | [Homebox](https://github.com/hay-kot/homebox) |  0.19.0-rootless | Inventory and organization system.  |  7745 | yes  |  |
| Modified existing app | [IT-Tools](https://it-tools.tech/) |  2024.10.22-7ca5933 | Collection of handy online tools for developers.  |  8171 | yes  |  |
| Modified existing app | [Mealie](https://mealie.io/) |  v3.4.0 | A self-hosted recipe manager and meal planner.  |  8220 | yes  |  |
| Modified existing app | [Outline](https://github.com/outline/outline) |  1.0.1 | Team knowledge and wiki base.  |  8404 | yes  | Updated Docker image version for PostgreSQL from `16-alpine` to `16.9-alpine` and Redis from `7-alpine` to `8.0.2-alpine`.  |
| Modified existing app | [PrivateBin](https://privatebin.info/) |  1.7.6 | A minimalist, open source online pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256 bits AES.  |  8122 | yes  |  |
| Modified existing app | [SiYuan](https://github.com/siyuan-note/siyuan) |  v3.1.30 | A privacy-first personal knowledge management system.  |  6806 | yes  | Added workspace name as variable in config file.  |
| Modified existing app | [Stirling PDF](https://stirlingpdf.io/?lang=en_GB) |  1.5.0 | Powerful locally hosted web based PDF manipulation tool.  |  8234 | yes  |  |
| Modified existing app | [SyncThing](https://github.com/syncthing/syncthing/) |  1.29 | Peer-to-peer file synchronization between your devices.  |  8090 | yes  |  Removed ROOT_FOLDER_HOST mapping, as planning to use symlinks in data directory for folders to sync. Changed description for SYNCTHING_HOSTNAME variable, as this is not a HOSTNAME, but the DEVICE NAME that SyncThing will use.  |
| Modified existing app | [Tandoor](https://tandoor.dev/) |  2.3.3 | Recipe collection manager.  |  8341 | yes  | Updated Docker image version from "ghcr.io/tandoorrecipes/recipes:1.5.34" to "ghcr.io/tandoorrecipes/recipes:1.5.35".  |
| Modified existing app | [VaultWarden](https://github.com/dani-garcia/vaultwarden) |  1.34.1 | Open-source password management solution that serves as a lightweight alternative to Bitwarden.  |  8107 | yes  |  |
| Modified existing app | [Wallos](https://github.com/ellite/wallos) |  4.5.0 | Open-source personal subscription tracker.  |  8222 | yes  | Updated Docker image version from "bellamy/wallos:3.1.1" to "bellamy/wallos:3.3.0".  |
