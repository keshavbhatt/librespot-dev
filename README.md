# Librespot snap 

## What is [Librespot](https://github.com/librespot-org/librespot) ?
_librespot_  is an open source client library for Spotify. It enables applications to use Spotify's service to control and play music via various backends, and to act as a Spotify Connect receiver. It is an alternative to the official and  [now deprecated](https://pyspotify.mopidy.com/en/latest/#libspotify-s-deprecation)  closed-source  `libspotify`. Additionally, it will provide extra features which are not available in the official library.

_Note: librespot only works with Spotify Premium. This will remain the case for the foreseeable future, as we are unlikely to work on implementing the features such as limited skips and adverts that would be required to make librespot compliant with free accounts._
 

## About this repository:
This repo contains snap build recipe for librespot rust app. The snap is built from `dev` branch of the official repository of _librespot_. The snap from this build is published by name `librespot-dev` install instructions are written below.

# Install and project status

﻿Nightly Build on any [snapd](https://docs.snapcraft.io/installing-snapd) enabled Linux Distribution can be installed using:

﻿[![librespot](https://snapcraft.io//librespot-dev/badge.svg)](https://snapcraft.io/pixelfx) [![librespot](https://snapcraft.io//librespot-dev/trending.svg?name=0)](https://snapcraft.io/librespot-dev)

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/librespot-dev)

    snap install librespot-dev

## Usage of librespot
Read the official Readme of project [here](https://github.com/librespot-org/librespot).
