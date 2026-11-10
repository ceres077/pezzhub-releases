# pezzhub

**Movies, TV shows, anime, manga, music and live TV in one free app, in sync on every device.**

[Website](https://pezzhub.netlify.app/) · [Discord](https://discord.gg/75z6vwfQkK) · [Report a problem](https://github.com/ceres077/pezzhub-releases/issues)

<p align="center">
  <a href="https://github.com/ceres077/pezzhub-releases/raw/main/media/pezzhub-presentation.mp4">
    <img src="media/pezzhub-preview.gif" alt="pezzhub in 50 seconds" width="820">
  </a>
</p>

## Download

| Device | Download |
|---|---|
| **Windows** 10 / 11 | [`pezzhub-setup-X.Y.Z.exe`](https://github.com/ceres077/pezzhub-releases/releases/latest) |
| **macOS** 11+ · Apple Silicon | [`pezzhub-mac-arm64-X.Y.Z.dmg`](https://github.com/ceres077/pezzhub-releases/releases/latest) |
| **macOS** 11+ · Intel | [`pezzhub-mac-x64-X.Y.Z.dmg`](https://github.com/ceres077/pezzhub-releases/releases/latest) |
| **Linux** · Arch, CachyOS and derivatives | [`pezzhub-linux.pacman`](https://github.com/ceres077/pezzhub-releases/releases/download/linux-channel/pezzhub-linux.pacman) · [`pezzhub-linux.AppImage`](https://github.com/ceres077/pezzhub-releases/releases/download/linux-channel/pezzhub-linux.AppImage) |
| **Android** phone & tablet · Android 8+ | [`pezzhub-android.apk`](https://github.com/ceres077/pezzhub-releases/releases/download/android-app-channel/pezzhub-android.apk) |
| **Android TV** · Android TV 8+ (alpha) | [`pezzhub-tv.apk`](https://github.com/ceres077/pezzhub-releases/releases/download/android-channel/pezzhub-tv.apk) |
| **Samsung TV** · Tizen, 2020+ | Installer for [Windows](https://github.com/ceres077/pezzhub-releases/releases/download/tizen-channel/pezzhub-tv-samsung-setup.exe) · [macOS Apple Silicon](https://github.com/ceres077/pezzhub-releases/releases/download/tizen-channel/pezzhub-tv-samsung-mac-arm64.zip) · [macOS Intel](https://github.com/ceres077/pezzhub-releases/releases/download/tizen-channel/pezzhub-tv-samsung-mac-x64.zip) · [Linux](https://github.com/ceres077/pezzhub-releases/releases/download/tizen-channel/pezzhub-tv-samsung-linux.AppImage) ([how to](#samsung-tv)) |

Every link gives you the latest version, and pezzhub updates itself from then on. LG TV (webOS) is coming soon.

## Features

- **cinehub**: movies, TV shows and anime, with Stremio add-ons, trailers, calendar, diary and Watch together.
- **mangahub**: manga, manhwa and manhua with a reader that remembers your page.
- **soundhub**: songs, albums and playlists with synced lyrics and Spotify import.
- **tvhub**: live TV and TV guide from your own Xtream (IPTV) subscription.
- **Sync**: up to six profiles, and an optional account that syncs library and progress in real time. AniList and
  Simkl tracking are built in.

Free, no ads. Available in English, Italian, French, Spanish and German.

![pezzhub home](screenshots/home.jpg)

## Installing

- **Windows**: run the setup.
- **macOS**: open the dmg and drag pezzhub to Applications. On first launch, confirm it in *System Settings › Privacy
  & Security › Open Anyway*.
- **Linux**: `sudo pacman -U pezzhub-linux.pacman`, or make the AppImage executable and run it (needs `mpv` and `fuse2`).
- **Android**: open the APK and allow installs from that source if asked.
- **Android TV**: copy the APK to the TV (for example with a USB stick) and open it with a file manager.

### Samsung TV

You need a computer on the same network as the TV.

1. On the TV, open *Apps*, type **1 2 3 4 5** with the remote, turn *Developer mode* on, enter your computer's IP
   address (the installer shows it) and restart the TV.
2. Open **pezzhub for Samsung TV** on the computer and choose your TV, found automatically or by IP address.
3. Click *Install pezzhub*. The first time, sign in with your free Samsung account (email and password).

To update pezzhub on the TV, run the installer again. [▶ Watch the video guide](https://github.com/ceres077/pezzhub-releases/raw/main/media/pezzhub-samsung-tv.mp4)

## Community

Questions, feedback and ideas: join the [Discord](https://discord.gg/75z6vwfQkK). Bugs: open an
[issue](https://github.com/ceres077/pezzhub-releases/issues) with your version, device and steps to reproduce, and no
passwords or tokens.

## Disclaimer

pezzhub does not provide or host any content. It only uses the sources, add-ons and subscriptions you set up yourself,
which you must have the right to access. This repository holds installers and release notes only. Download pezzhub
only from here.
