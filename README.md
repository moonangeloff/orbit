# Orbit

Windows messenger with personal AI companions. Development builds; clean Windows acceptance is still in progress.

## Download

[Orbit 0.1.10 for Windows x64](https://github.com/moonangeloff/orbit/releases/download/v0.1.10/Orbit_0.1.10_x64-setup.exe)

Clients 0.1.3 or later receive 0.1.10 inside Orbit. Install the current package once when upgrading from an older client. The release package is verified by the native updater before installation. Updates are installed when the user chooses to restart.

This repository hosts release packages and update metadata. GitHub commits are not application updates: a new signed release package is required.

## Third-party media components

The installer includes an unchanged GPLv3 Gyan FFmpeg 9.0.1 binary. The release includes an exact FFmpeg core source mirror and upstream notices/configuration/library versions. It does **not** include all statically linked external-library sources; that source/notice audit remains open. See the release's THIRD_PARTY_MEDIA.md and FFmpeg-source-and-notices archive for the precise scope. Updater checks do not establish legal completeness or clean Windows acceptance.

## Music services

Orbit 0.1.10 stores public music links and embeds the official Spotify, SoundCloud and Yandex Music players. Service controls, branding, account and regional restrictions remain in place. Service embeds do not download their audio. The separate experimental SoundCloud importer is described below. An official embed is not a general content license; a future paid or advertising business model requires a separate provider-terms review.

## Local audio downloads

Orbit 0.1.10 can save a directly downloadable public HTTPS MP3/WAV/OGG/FLAC file (up to 64 MiB) into the user's local library on their PC. Download only content you are permitted to save. Playlist URLs are not audio files; Orbit does not export encrypted subscription music from Yandex or Spotify. Local audio uses Orbit volume/seeking controls and is not automatically uploaded to the server.

## Free music catalogue

Orbit 0.1.10 searches Wikimedia Commons audio with explicit CC BY, CC BY-SA or CC0 licences. Play opens the original recording in Orbit, with volume and seeking controls. Author credits, licence and source are available for every recording. Classical, instrumental and independent recordings are included; a mainstream commercial catalogue is not promised.

Permitted recordings are downloaded once to the shared server library and temporarily stored on the user's PC (256 MiB, seven days). Repeated playback reuses existing copies. Imported personal audio files remain separate. See the release's MUSIC_CATALOG.md for storage limits, licence handling and tested acceptance.
## Experimental SoundCloud import

Orbit 0.1.10 adds public-track search and single-song SoundCloud URL import for a self-hosted prototype. Full unprotected progressive MP3 files play locally with Orbit volume controls; server and temporary owner PC caches avoid repeated audio downloads. This uses the maintained yt-dlp web extractor, not the official SoundCloud API SDK. Availability can change; playlists, gated/DRM, preview and HLS-only records are unsupported. Spotify audio is not extracted.

The feature defaults to disabled and was enabled on the owner's server for their requested evaluation. Source agreements/content permissions remain pending; this is not a licensed public music service. See the release's MUSIC_IMPORT.md for scope, configuration, limitations and actual acceptance evidence.
