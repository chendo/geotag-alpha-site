---
layout: page
title: Changelog
include_in_header: true
---

# Changelog

## v0.3 (18/19)

* Fixed occasional crash on remaining photo count change
* Improve reliability after reconnecting in background
  * Fixed a race condition where locations don't get pushed after reconnecting in background under certain conditions
  * Attempt to work around Bluetooth stack oddities
* Improve discovery reliability 
* Add option to disable Fast Reconnections within Camera detail view, for devices where "Control when Powered OFF" needs to be enabled

## v0.3 (16)

* Track reconnections and time connected in background
* Improved UI

## v0.2

* Added map view
* Added adjustable settings for distance between updates and update interval
* Added experimental location accuracy feature (mostly for testing)

## v0.1

* Initial release
