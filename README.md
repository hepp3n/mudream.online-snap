# MuDream.online

Unofficial Snap Packaging for MuDream.online.

# Requirements

You need to put `rar` archive called `Mudream.online` inside `snap/local/src/`.

Distribution needs `snapd` and `snapcraft` installed

# Building

Inside root directory of this repo run:

  - `snapcraft pack`

It will produce output as following: `mudream-online_7.0_amd64.snap`

# Installation

`sudo snap install --dangerous mudream-online_7.0_amd64.snap`
