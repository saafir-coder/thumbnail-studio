# Thumbnail Studio

AI-powered YouTube thumbnail generator with a 3-step pipeline.

## How It Works

1. **Reference Selection** — Search YouTube or paste a URL to grab any thumbnail as reference
2. **Character Generation** — Generate your character via Higgsfield Soul 2.0 with pose/mood controls
3. **Scene Merging** — Combine reference + character using Gemini Nano Banana 2 for the final thumbnail

## Features

- Full YouTube search (Piped/Invidious API — no backend needed)
- HEIC/HEIF support (iPhone photos converted client-side)
- A/B testing with variant B and C panels
- 7 pose presets with auto-mood detection from video titles
- Dark theme, responsive design

## Tech Stack

- HTML / CSS / JavaScript (zero build tools)
- Gemini 3.1 Flash (Nano Banana 2) for image merging
- Higgsfield Soul 2.0 for character generation
- Piped + Invidious API for YouTube search
- GitHub Pages for deployment

## Live

**[Try it →](https://saafir-coder.github.io/thumbnail-studio/)**

## Local Development

```bash
python3 server.py  # Starts on localhost:8090 with full yt-dlp search
```

## License

MIT
