# Runtipi appstore
This is my own [Runtipi](https://runtipi.io/) appstore. Some are custom apps (not in the [official Runtipi appstore](https://github.com/runtipi/runtipi-appstore)), some are custom setups of apps from the [official Runtipi appstore](https://github.com/runtipi/runtipi-appstore).

> [!WARNING]
> This is my personal repository for my own Tipi instance(s).
> * I am not an expert in any area of self-hosting.
> * I cannot guarantee that any of these apps work (for me or for you).
> * I take no responsibility for any software or hardware issues you may encounter as a result of your usage of any apps in this repository. This includes any potential data loss as a result of updates to the repository/app. Do your own due diligence!
> **USE AT YOUR OWN RISK!!!**


## Apps available (4)

|  Type  |  Name  |  Docker image version  |  Description  |  Port  |  Has dynamic file  |  Notes  |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| Custom app  | [Pangolin Newt client](https://github.com/fosrl/newt)  |  1.11.0 | Connect your site (machine) to your Pangolin network.  | none required  | yes  |  |
| Modified existing app | [Forgejo](https://codeberg.org/forgejo/forgejo) |  15.0.0 | Self-hosted lightweight Git server  |  8195 | yes  | Removed dependence on PostgreSQL.  |
| Modified existing app | [Gotify](https://gotify.net/) |  2.9.1 | A simple server for sending and receiving messages.  |  8129 | yes  | Removed username and password variable on installation, as it didn't work.  |
| Modified existing app | [Outline](https://github.com/outline/outline) |  1.7.0 | Team knowledge and wiki base.  |  8404 | yes  | Updated Docker image version for PostgreSQL from `16-alpine` to `16.9-alpine` and Redis from `7-alpine` to `8.4.0-alpine`. Changed settings to allow large attachments.  |
