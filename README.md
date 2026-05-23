# 🎵 Numper Music

A clean, ad-free music player with a Spotify-style interface. Stream millions of songs — pop, hip-hop, R&B, rock, Latin, electronic, and more.

> Part of the [Numper Hub](https://github.com/Bril584-lgtm/Numper-Hub) ecosystem.

---

## Features

- 🔥 **Trending rows** — curated genre sections that load on launch
- 🔍 **Search** — find any song or artist instantly
- ⌨️ **Keyboard shortcuts** — Space to play/pause, ← → to seek 10s
- 🔀 **Shuffle & Repeat** — toggle on the player bar
- 📋 **Queue** — add songs to queue with the + Queue button
- 🎨 **Dark theme** — easy on the eyes, always

## Setup

```bash
pip install -r requirements.txt
```

Double-click **run.bat** or:

```bash
python server.py
```

Then open **http://localhost:7779**

## Stack

- **Backend**: FastAPI + uvicorn (Python)
- **Music source**: JioSaavn via [saavn.dev](https://saavn.dev) — free, no API key needed
- **Frontend**: Vanilla JS, HTML5 Audio API
- **Port**: 7779
