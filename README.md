# Spotify/YouTube Playlist Downloader

This is a Python-based script that downloads audio tracks from Spotify and YouTube playlists using the `yt-dlp` library. It fetches playlist details and automatically downloads the tracks, providing a simple solution for saving music locally.

## Features

- **Spotify Integration**: Fetches playlist details from Spotify and downloads equivalent tracks from YouTube.
- **YouTube Downloader**: Downloads YouTube videos as audio files using `yt-dlp`.
- **Customizable Formats**: Supports downloading audio in various formats (mp3, wav, etc.).
- **Automatic Track Matching**: Attempts to match tracks from Spotify playlists to YouTube videos.

## Requirements

- See requirements.txt, might need to --upgrade some packages
- Python 3.8+
- `yt-dlp`: A powerful downloader for video and audio from YouTube and other platforms.
- `spotipy`: A lightweight Python library for the Spotify Web API.

- Must install package locally
  ```bash
  pip install -e .
  ```
