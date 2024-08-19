# Spotify <> Apple Music Playlist Converter

A simple web application that converts playlists between Spotify and Apple Music.

## Goals / Features

- Convert playlists from Spotify to Apple Music and vice versa.
- User-friendly interface for easy conversions.
- Supports authentication with Spotify and Apple Music.
- Real-time progress updates during the conversion process.

### TODOs
#### Step 1: basics

- [ ] spotify: login
- [ ] spotify: access playlists
- [ ] spotify: show songs in playlist
- [ ] spotify: search for song

- [ ] apple music: login
- [ ] apple music: access playlists
- [ ] apple music: show songs in playlist
- [ ] apple music: search for song

#### Step 2: visualization
- [ ] webui: basic main page
- [ ] webui: login process for both platforms

#### Step 3: conversion basic
- [ ] spotify: create new playlist 
- [ ] spotify: add songs to playlist

- [ ] apple music: create new playlist 
- [ ] apple music: add songs to playlist

- [ ] webui: choose playlist / show songs in playlist
- [ ] webui: selecting a song shows results in the other platform
- [ ] webui: manual conversion done

## Getting Started

### Prerequisites

- Zig programming language installed. [Installation Guide](https://ziglang.org/download/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/playlist-converter.git
    cd playlist-converter
    ```

2. Build the application:
    ```
    zig build
    ```

3. Run the application:
    ```
    zig build run
    ```

Access the application at http://localhost:8080.
