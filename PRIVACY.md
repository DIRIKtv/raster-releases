# Raster privacy policy

*Last updated: 19 October 2026*

Raster is an IPTV player for Fire TV and Android TV made by DIRIKtv. This page explains what
Raster stores, what it sends and to whom. In short, Raster has no accounts, ads, analytics or
tracking. What you set up stays on your TV.

## What stays on your TV

Raster keeps these in its own private storage on the TV, and doesn't send them to us:

- the providers you add, including their server addresses, usernames and passwords
- channel lists, the TV guide, and movie and series catalogues downloaded from your providers
- favourites, reminders, channel edits, watch history and settings
- recordings, and the short live-TV buffer used for pause and rewind
- crash reports (see below)

Android's own backup and device-to-device transfer are turned off for Raster, so none of this
goes to Google or Amazon backups. To move your setup, use **Settings › Backup & Restore**. A
backup file contains your provider logins, so keep it private.

## What Raster connects to

- **Your providers.** Raster connects to the servers you add, and to the guide, logo and stream
  addresses they give it. Those providers see your TV's IP address and the login you entered.
  Their own privacy policies apply.
- **GitHub, for updates.** When it checks for updates, Raster asks GitHub
  (api.github.com and github.com) for the latest release and downloads it from there. GitHub sees
  your IP address. You can turn the check off in **Settings › Updates**.

## The phone page

Some screens show a QR code so you can type details on your phone. While that screen is open,
Raster runs a small web page on your home network. The address includes a random code, and the page
is only reachable from devices on the same network. It closes when you leave the screen. The page
uses plain HTTP on your local network, so only use it on a network you trust.

## Crash reports

If Raster crashes, it saves a short report on the TV: the app version, the device model, the
Android version and the technical details of the error. Provider usernames, passwords and tokens
are removed before it is saved. Reports are never sent automatically. You can download them with
the phone page and choose to send them to us, and you can delete them in **Settings › Backup &
Restore**.

## Children

Raster doesn't collect personal information from anyone, including children. Parental controls
(**Settings › Parental Controls**) let you lock channels, groups and settings with a PIN.

## Deleting your data

Uninstalling Raster deletes everything it stored on the TV.

## Changes and contact

If this policy changes, the new version will be published at
https://github.com/DIRIKtv/raster-releases/blob/main/PRIVACY.md with a new date. Questions:
https://github.com/DIRIKtv/raster-releases/issues
