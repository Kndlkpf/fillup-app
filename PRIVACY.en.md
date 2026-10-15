---
title: Privacy policy for Fillup
permalink: /privacy-en.html
lang: en
---

# Privacy policy for Fillup

Last updated: 15 October 2026

Fillup is a log book for refuelling, workshop visits, costs and trips. This policy describes which data the app
processes and where it goes.

## Controller

Michael Bernegger

Email: kndlkpf@gmail.com

## In short

- Fillup has no account, no ads and no analytics or tracking services.
- Your vehicle data, photos and trips stay on your device.
- Only requests needed for a feature go to the internet (see below). We do not sell any data.

## Data on your device

Fillup stores vehicles with their photos, refuelling, workshop visits, costs, reminders, receipt photos, templates and recorded trips
in its own app storage. Only if you switch on "Back up to Google account" in Fillup's settings (off by default),
Android backs up this data to your Google account under Google's rules. There is no direct transfer to a new phone. Backups and CSV files you create yourself are stored where you save them. A backup also contains your settings, including your Tankerkönig key.

Fillup keeps the charging station list it loaded last (data of the charging register and the middle of the search circle) for up to 24 hours in a file in the app's cache, so it is there right away after a restart. Android can delete it at any time; it is not part of a backup and never leaves the device.

For troubleshooting, Fillup keeps a small log on the device (at most 512 KB): what the search for stations and charging points, the price lookup and the trip
log did, for example "car connected" or "trip saved", with the time. For requests to services it only holds the kind, radius, duration and number of results. Locations, addresses and Bluetooth addresses are
not in it. The log only leaves the device if you choose "Create error report" in the settings. You then decide in the
share menu who gets it; the report also contains the app version, Android version, device model and the state of
the permissions.

## Location

- **Station search, fuel prices and charging stations:** when you search, Fillup sends your approximate position to the services
  listed below to find stations nearby. For an electric car, the Charge tab and the search in the form show the charging stations of the
  Bundesnetzagentur register; the position goes to its map service only on request, when you open or refresh the tab
  or tap "Search nearby", never in the background. For a refuelling, Fillup stores the place of the refuelling
  on your device.
- **When you open the app:** if you have granted the location permission, Fillup determines your location once
  when you open it, so the station search is faster. It stays on your device and only goes to the services when
  you search.
- **Automatic trip log (optional):** once set up, Fillup collects your location even when the app is closed, but
  only while your phone is connected to the chosen car via Bluetooth or you continue a paused trip yourself in the
  notification (then until you stop it). Distance and route stay on your device. You can
  turn it off at any time in the vehicle settings.

## Services Fillup connects to

Each service technically receives your IP address with every request.

| Service | Purpose | Data |
|---|---|---|
| Tankerkönig (creativecommons.tankerkoenig.de) | Fuel prices in Germany | position, search radius |
| Bundesnetzagentur, charging station register (via ArcGIS Online by Esri, services-eu1.arcgis.com) | Charging stations nearby (electric cars, tab and form) | position, search radius |
| Overpass API (overpass-api.de), OpenStreetMap | Fuel stations nearby | position, search radius |
| OpenFreeMap (tiles.openfreemap.org) | Maps in the app | map area shown |
| Google Play | Notice of new versions | as for any app from Google Play |

## Permissions

- **Location:** station search, fuel prices, charging stations and the automatic trip log.
- **Location in the background:** only for the automatic trip log.
- **Nearby devices (Bluetooth):** to notice when your phone connects to the car.
- **Notifications:** reminders and running or saved trips.
- **Camera and photos:** only when you take or pick a receipt or vehicle photo; Fillup uses the Android picker and only sees
  the chosen pictures.

## Your rights

You can view, change and delete all data in the app. When you uninstall Fillup, Android deletes all app data. As we
do not store personal data on our own servers, there is nothing else to delete on our side. For questions and your
rights under the GDPR (access, correction, deletion, complaint to a supervisory authority), contact us at the
address above.

## Children

Fillup is not directed at children under 16.

## Changes

If this policy changes, the new version is published here.
