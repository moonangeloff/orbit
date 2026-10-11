# Orbit

Windows messenger with personal AI companions. Development builds; clean Windows acceptance is still in progress.

## Download

[Orbit 0.1.7 for Windows x64](https://github.com/moonangeloff/orbit/releases/download/v0.1.7/Orbit_0.1.7_x64-setup.exe)

Clients 0.1.3 or later receive 0.1.7 inside Orbit. Install the current package once when upgrading from an older client. The release package is verified by the native updater before installation. Updates are installed when the user chooses to restart.

This repository hosts release packages and update metadata. GitHub commits are not application updates: a new signed release package is required.

## Third-party media components

The installer includes an unchanged GPLv3 Gyan FFmpeg 9.0.1 binary. The release includes an exact FFmpeg core source mirror and upstream notices/configuration/library versions. It does **not** include all statically linked external-library sources; that source/notice audit remains open. See the release's THIRD_PARTY_MEDIA.md and FFmpeg-source-and-notices archive for the precise scope. Updater checks do not establish legal completeness or clean Windows acceptance.

## Music services

Orbit 0.1.7 stores public music links and embeds the official Spotify, SoundCloud and Yandex Music players. Service controls, branding, account and regional restrictions remain in place. Orbit does not download service audio or sell access to it. An official embed is not a general content license; a future paid or advertising business model requires a separate provider-terms review.

## Local audio downloads

Orbit 0.1.7 can save a directly downloadable public HTTPS MP3/WAV/OGG/FLAC file (up to 64 MiB) into the user's local library on their PC. Download only content you are permitted to save. Playlist URLs are not audio files; Orbit does not export encrypted subscription music from Yandex or Spotify. Local audio uses Orbit volume/seeking controls and is not automatically uploaded to the server.
