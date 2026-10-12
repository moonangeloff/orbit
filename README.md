# Orbit

Windows messenger with personal AI companions. Development builds; clean Windows acceptance is still in progress.

## Download

[Orbit 0.1.12 for Windows x64](https://github.com/moonangeloff/orbit/releases/download/v0.1.12/Orbit_0.1.12_x64-setup.exe)

Clients 0.1.3 or later receive 0.1.12 inside Orbit. Install the current package once when upgrading from an older client. The release package is verified by the native updater before installation. Updates are installed when the user chooses to restart.

This repository hosts release packages and update metadata. GitHub commits are not application updates: a new signed release package is required.

## Third-party media components

The installer includes an unchanged GPLv3 Gyan FFmpeg 9.0.1 binary. The release includes an exact FFmpeg core source mirror and upstream notices/configuration/library versions. It does **not** include all statically linked external-library sources; that source/notice audit remains open. See the release's THIRD_PARTY_MEDIA.md and FFmpeg-source-and-notices archive for the precise scope. Updater checks do not establish legal completeness or clean Windows acceptance.

## Servers and everyday controls

Orbit 0.1.12 adds servers with text/voice channels, invitation codes and assignable roles. Server permissions are checked by the API. All channels currently share membership; private channels, member removal/leave and role hierarchy remain future work. See COMMUNITIES.md in the release.

Resize the chat sidebar by dragging its edge. Settings have searchable sections, a centred audio-device dialog, and separate desktop companion scale/always-on-top controls. Message entrances preserve their positions in the virtual list. Embedded Spotify, SoundCloud and Yandex players have been removed; the local player and catalogue remain.

The client checks the newest release directly and rechecks before installation, replacing a ready package if a later release is available. Missed versions do not need to be installed one by one.

## Local audio downloads

Orbit 0.1.12 can save a directly downloadable public HTTPS MP3/WAV/OGG/FLAC file (up to 64 MiB) into the user's local library on their PC. Download only content you are permitted to save. Playlist URLs are not audio files; Orbit does not export encrypted subscription music from Yandex or Spotify. Local audio uses Orbit volume/seeking controls and is not automatically uploaded to the server.

## Free music catalogue

Orbit 0.1.12 searches Wikimedia Commons audio with explicit CC BY, CC BY-SA or CC0 licences. Play opens the original recording in Orbit, with volume and seeking controls. Author credits, licence and source are available for every recording. Classical, instrumental and independent recordings are included; a mainstream commercial catalogue is not promised.

Permitted recordings are downloaded once to the shared server library and temporarily stored on the user's PC (256 MiB, seven days). Repeated playback reuses existing copies. Imported personal audio files remain separate. See the release's MUSIC_CATALOG.md for storage limits, licence handling and tested acceptance.
## Experimental SoundCloud import

Orbit 0.1.12 adds public-track search and single-song SoundCloud URL import for a self-hosted prototype. Full unprotected progressive MP3 files play locally with Orbit volume controls; server and temporary owner PC caches avoid repeated audio downloads. This uses the maintained yt-dlp web extractor, not the official SoundCloud API SDK. Availability can change; playlists, gated/DRM, preview and HLS-only records are unsupported. Spotify audio is not extracted.

The feature defaults to disabled and was enabled on the owner's server for their requested evaluation. Source agreements/content permissions remain pending; this is not a licensed public music service. See the release's MUSIC_IMPORT.md for scope, configuration, limitations and actual acceptance evidence.
