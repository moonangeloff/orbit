# Orbit

Windows messenger with personal AI companions. Development builds; clean Windows acceptance is still in progress.

## Download

[Orbit 0.1.4 for Windows x64](https://github.com/moonangeloff/orbit/releases/download/v0.1.4/Orbit_0.1.4_x64-setup.exe)

Clients 0.1.3 or later receive 0.1.4 inside Orbit. Install the current package once when upgrading from an older client. The release package is verified by the native updater before installation. Updates are installed when the user chooses to restart.

This repository hosts release packages and update metadata. GitHub commits are not application updates: a new signed release package is required.

## Third-party media components

The installer includes an unchanged GPLv3 Gyan FFmpeg 9.0.1 binary. The release includes an exact FFmpeg core source mirror and upstream notices/configuration/library versions. It does **not** include all statically linked external-library sources; that source/notice audit remains open. See the release's THIRD_PARTY_MEDIA.md and FFmpeg-source-and-notices archive for the precise scope. Updater checks do not establish legal completeness or clean Windows acceptance.
