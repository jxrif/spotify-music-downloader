# Spotify Music Downloader 🎵

A powerful and easy-to-use tool to download music from Spotify. This tool allows you to download tracks, playlists, and artist top tracks directly to your local machine. It also embeds metadata (like track name, artist, album, and cover art) into the downloaded MP3 files.

---

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dependencies](#dependencies)
5. [Configuration](#configuration)
6. [License](#license)
7. [Support](#support)

---

## Features ✨
- **Download Spotify Tracks**: Download individual tracks from Spotify.
- **Download Playlists**: Download entire playlists with metadata.
- **Download Artist Top Tracks**: Download the top tracks of any artist.
- **Metadata Embedding**: Automatically embeds track name, artist, album, and cover art into the downloaded MP3 files.
- **Progress Bar**: Real-time progress bar for downloads.
- **Error Handling**: Handles rate limits, invalid links, and other errors gracefully.

---

## Installation 🛠️

### Prerequisites
- Node.js (v14 or higher)
- npm (Node Package Manager)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spotify-music-downloader.git
   ```
2. Navigate to the project directory:
   ```bash
   cd spotify-music-downloader
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```
4. Create a `config.json` file in the root directory and add your Spotify API credentials:
   ```json
   {
     "spotifyid": "your-spotify-client-id",
     "spotifyclient": "your-spotify-client-secret"
   }
   ```
   - To get your Spotify API credentials, visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).

---

## Usage 🚀

1. Run the application:
   ```bash
   npm start
   ```
2. Enter a valid Spotify link when prompted:
   - **Track Link**: `https://open.spotify.com/track/...`
   - **Playlist Link**: `https://open.spotify.com/playlist/...`
   - **Artist Link**: `https://open.spotify.com/artist/...`

3. The tool will:
   - Download the audio in MP3 format.
   - Embed metadata (track name, artist, album, and cover art).
   - Save the files in the `music` directory.

---

## Dependencies 📦

This project uses the following packages:
- **`axios`**: For making HTTP requests (e.g., downloading cover art).
- **`node-id3`**: For embedding metadata into MP3 files.
- **`progress`**: For displaying a progress bar during downloads.
- **`prompt-sync`**: For taking user input in the terminal.
- **`spotify-web-api-node`**: For interacting with the Spotify API.
- **`ansi-colors`**: For adding colors to console output.

To install all dependencies, run:
```bash
npm install
```

---

## Configuration ⚙️

### `config.json`
- **`spotifyid`**: Your Spotify Client ID.
- **`spotifyclient`**: Your Spotify Client Secret.

### Folder Structure
- **`music/`**: Contains downloaded tracks, playlists, and artist top tracks.
  - Each playlist/artist gets its own subfolder.
  - Single tracks are saved in the `Single Tracks` folder.

---

## License 📄

This project is licensed under the **Proprietary License**. All rights reserved.

---

## Support 💬

If you encounter any issues or have questions, feel free to reach out:

- **Follow me on [Instagram](https://www.instagram.com/jxrif)**.
- **Subscribe to my [YouTube Channel](https://www.youtube.com/channel/UClv-kdP1ORF5tHc9msY1Ggg)**.
- **Join my [Discord Server](https://discord.gg/4n8AB4WvqU)** for support.
- **Watch the [YouTube Video Tutorial](https://youtu.be/l3W5byt1r8E?si=bjs_fX6I9onnA_3G)** for a step-by-step guide.

For any inquiries, please contact me at **jxrifmd@gmail.com**.

---

## Disclaimer ⚠️

This tool is for educational purposes only. Downloading copyrighted material without proper authorization may violate Spotify's terms of service and local laws. Use it responsibly.

---

Enjoy downloading your favorite music! 🎧