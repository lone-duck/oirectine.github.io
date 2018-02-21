---
layout: post
title: "Serial Interface for UBC LAIR"
comments: true
description: "..."
keywords: "markdown"
---

In first year university I volunteered as an undergraduate research assistant at the Laboratory for Atomic Imaging Research (LAIR). My main task was the development of a serial interfacing script in Python to pull and log data from pressure gauges in scanning tunneling microscopes. This data was recorded in .csv files as well as being tweeted to make it accessible remotely to LAIR staff. This project required me to build custom cables as the distance between the pressure gauges and the computer the script would run on was longer than commercially available RS-232 cables allow. The script, as well as documentation on how the cables were built and how to build a general serial interface can be found [here](https://github.com/oirectine/LAIR-interface).
