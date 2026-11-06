# Learning Module

A simple, single-file web app for organizing YouTube videos into a personal learning library.

## Features

- Add YouTube videos by URL or 11-character video ID
- Organize by title, category, and description
- Search and filter modules
- Embedded YouTube player for each module
- Export / import your library as JSON
- Data persists in browser localStorage (no server needed)
- Responsive, dark theme

## Usage

Open `index.html` in any modern browser. That's it.

To host it, drop `index.html` on any static host (GitHub Pages, Netlify, Vercel, etc.).

### Adding a video

Paste any of these into the URL field:
- `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
- `https://youtu.be/dQw4w9WgXcQ`
- `https://www.youtube.com/shorts/dQw4w9WgXcQ`
- `dQw4w9WgXcQ` (raw video ID)

## Note on "upload"

This app embeds YouTube videos you already have on YouTube — it does not upload videos *to* YouTube. Uploading to YouTube requires the YouTube Data API with OAuth, which needs a backend and Google Cloud credentials.
