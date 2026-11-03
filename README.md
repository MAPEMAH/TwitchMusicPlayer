# 🎵 Twitch Music Player

**Twitch Music Player** is a desktop music player designed for Twitch streamers. It combines YouTube playback, Twitch Channel Points song requests, Donatik paid music requests, Spotify integration, and customizable OBS overlays in one application.

## ✨ Features

### 🎧 Music Player
- Play music from YouTube.
- Play local audio files.
- Unified playback queue.
- Automatic playback of the next track.
- Volume control, playback progress, pause, resume, skip and track management.
- YouTube audio extraction powered by yt-dlp.

### 🟣 Twitch Channel Points Integration
- Connect your Twitch account.
- Automatically receive song requests through Channel Points rewards.
- Configurable maximum song duration.
- Duplicate song protection.
- Automatic rejection of duplicate requests with Channel Points refunds.
- Customizable song blacklist based on YouTube URLs, video IDs, song titles and artists.

### 🟡 Donatik Integration
- Import paid music requests from Donatik.
- Paid requests receive priority in the playback queue.
- Automatic synchronization with the Donatik music widget.
- Automatic removal of imported requests from the active Donatik queue.

### 🎵 Spotify Integration
- Integration with the installed Spotify application.
- Spotify playback pauses when the player starts playing queued music.
- Spotify resumes when the music queue becomes empty.
- Spotify playback is coordinated with track transitions.

### 📺 OBS Studio Overlay
- Browser Source integration.
- Customizable now-playing music card.
- Album artwork, track title and artist.
- Playback progress bar and timestamps.
- Automatic overlay visibility.
- Smooth appearance and disappearance animations.
- Customizable overlay appearance.

### 💬 Twitch Chat Integration
- `!skip` command for the broadcaster and moderators.
- Twitch EventSub integration.
- Chat-based playback control.

### ⚙️ Additional Features
- Desktop graphical interface.
- Persistent application settings.
- Session logging and diagnostic information.
- Automatic updates through GitHub Releases.
- Windows installer with desktop shortcuts.

## 🚀 Installation

Download the latest installer from the [Releases](../../releases) page.

1. Download `TwitchMusicPlayer_Setup.exe`.
2. Run the installer.
3. Follow the installation instructions.
4. Launch Twitch Music Player.
5. Connect your Twitch account and configure your integrations.

## 🔄 Automatic Updates

Twitch Music Player supports automatic update checks through GitHub Releases.

The application can:
- Check for updates automatically on startup.
- Check for updates manually.
- Display release notes.
- Download and install new versions.

## 🛠️ Technologies

- Python
- PySide6 / Qt
- Twitch API
- Twitch EventSub
- Donatik integration
- yt-dlp
- Windows Media Session (Spotify)
- OBS Browser Source
- PyInstaller
- Inno Setup

## 💻 Platform

Currently designed for Windows.

## 📦 Releases

Official builds and updates are published on the GitHub Releases page.

## ⚠️ Disclaimer

This is an independent community project and is not affiliated with, endorsed by, or officially connected to Twitch, Spotify, Donatik or OBS Studio.

All trademarks and product names belong to their respective owners.

## 📜 License

License information will be added separately.
