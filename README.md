# yt-dlp-mac-helper

One-command setup for yt-dlp on macOS, with defaults that:
- save to `~/Downloads`
- output MP4 (auto-convert if needed)

## Quick start
./scripts/install.sh
./scripts/setup-config.sh
# download anything:
./scripts/dl.sh "https://www.youtube.com/watch?v=VIDEO_ID"

## What it does
- Installs Homebrew, yt-dlp, and ffmpeg if missing
- Writes yt-dlp config to `~/.config/yt-dlp/config`
- dl.sh wraps yt-dlp so you always get an MP4 in Downloads
mkdir -p ~/yt-dlp-mac-helper
cd ~/yt-dlp-mac-helper#mkdir -p ~/yt-dlp-mac-helper
cd ~/yt-dlp-mac-helper

 mkdir -p ~/yt-dlp-mac-helper
cd ~/yt-dlp-mac-helper
yt-dlp-mac-helper

One-command setup for yt-dlp on macOS, with defaults that:
- save to `~/Downloads`
- output MP4 (auto-convert if needed)

## Quick start
```bash
./scripts/install.sh
./scripts/setup-config.sh
# download anything:
./scripts/dl.sh "https://www.youtube.com/watch?v=VIDEO_ID"

