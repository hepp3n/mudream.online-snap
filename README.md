# MuDream.online

Unofficial Snap Packaging for MuDream.online.

Require: Wayland! For best performance and smooth expierence.

# Install from snap store

You can find MuDream.online directly in snap-store or on the website: https://snapcraft.io/mudream-online

## Installation from cli

`sudo snap install mudream-online`

### Building

# Requirements for Building

Distribution needs `snapd` and `snapcraft` installed. Probably `lxd` too.

# Building

Inside root directory of this repo run:

  - `snapcraft pack`

It will produce output as following: `mudream-online_7.0_amd64.snap`

# Installation

`sudo snap install --dangerous mudream-online_7.0_amd64.snap`

# First run

  - First run might take a while since it's creating wineprefix and copy game files inside your Snap directory. Please wait a minute or two.

  - When you have been prompted for installing wine-mono. Say YES to it!
