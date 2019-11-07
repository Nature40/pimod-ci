pimod-ci
===

[![Test Build Status](https://github.com/Nature40/pimod-ci/workflows/Test%20Build/badge.svg)](https://github.com/Nature40/pimod-ci/actions?query=workflow%3A%22Test%20Build%22)
[![Release Status](https://github.com/Nature40/pimod-ci/workflows/Release/badge.svg)](https://github.com/Nature40/pimod-ci/actions?query=workflow%3A%22Release%22)
[![Build Status](https://travis-ci.org/Nature40/pimod-ci.svg?branch=master)](https://travis-ci.org/Nature40/pimod-ci)

Build single-board computer operating systems images with continuous integration using [pimod](https://github.com/Nature40/pimod).

This repo is intended as a stub repo to be forked and filled with your Pifiles

## CI Support

We showcase the integration into [Travis CI](https://travis-ci.org/Nature40/pimod-ci) and into [GitHub Actions](https://github.com/Nature40/pimod-ci/actions). 

## Example

To evaluate the feasibility of the approach an image of the router distribution [OpenWRT]() for the Raspberry PI is loaded and a command is issued in our example Pifile:

```bash
FROM openwrt-18.06.4-brcm2708-bcm2710-rpi-3-ext4-factory.img

RUN cat /etc/os-release
```



