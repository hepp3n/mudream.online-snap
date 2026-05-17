# MuDream.online

Unofficial Snap Packaging for MuDream.online.

# Downloading the game archive

Go to [Mudream.online/download](https://mudream.online/download)

Select one of the source for downloading the game.

Copy the `rar` archive with the game files inside `snap/local/src/`.

# Requirements

Distribution needs `snapd` and `snapcraft` installed. Probably `lxd` too.

# Building

Inside root directory of this repo run:

  - `snapcraft pack`

It will produce output as following: `mudream-online_7.0_amd64.snap`

# Installation

`sudo snap install --dangerous mudream-online_7.0_amd64.snap`
