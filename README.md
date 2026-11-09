# Luma Music

A modern Android music player built with Kotlin and Jetpack Compose.

Luma Music brings online music discovery, playback, synced lyrics, library management, playlists, audio effects, and Android Auto into one app.

## Features

- YouTube Music search and discovery
- Online playback, queue management, shuffle and repeat
- Song artwork, metadata, duration and synced lyrics
- Local music library and playlist management
- Background playback and Android media controls
- Android Auto support
- Equalizer, audio effects and playback customisation
- Optional integrations and source modules

## Build

### Requirements

- Android Studio
- JDK 21
- Android SDK 36
- NDK `27.0.12077973`

Clone the repository and open it in Android Studio:

```bash
git clone https://github.com/PauzeDevs/Crane-Music.git
cd Crane-Music
./gradlew assembleUniversalFossDebug
```

The APK is generated under `app/build/outputs/apk/`.

## Project identity

- Product name: **Luma Music**
- Android application ID: `com.pauzedevs.lumamusic`
- Kotlin namespace retained from the upstream codebase to avoid breaking internal source references and database migrations.

## Upstream credits and licensing

Luma Music is a rebrand and derivative work based on [Mochy Music](https://github.com/realidkroo/Mochy-Music), which is licensed under the **GNU General Public License v3.0**.

This repository retains the upstream `LICENSE` and relevant notices. The upstream project builds on work from ViviMusic, Metrolist, SimpMusic, ArchiveTune, InnerTune and other projects; their respective notices and licences remain applicable. See the source tree and provider/module directories for component-level credits.

Luma Music is distributed under GPL-3.0. If you redistribute modified binaries, you must comply with the GPL, including providing the corresponding source code and preserving required copyright and licence notices.

## Disclaimer

Luma Music is an independent, unofficial project. It is not affiliated with or endorsed by YouTube, YouTube Music, Google, Spotify, Apple, or any other third-party service. All trademarks belong to their respective owners.

Availability of third-party services and content can change. Use the app in accordance with applicable laws and the terms of the services you access.

---

**Luma Music** · Built by PauzeDevs

<!-- Build verification trigger -->
