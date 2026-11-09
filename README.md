# Vox

A lightweight browser-based text-to-speech app built with plain HTML, CSS, and JavaScript.

## Features

- Type any text and read it aloud
- Choose from available browser voices
- Adjust playback speed
- Stop playback at any time

## Run locally

Open `index.html` directly in a web browser.

You can also serve the folder with a simple local web server if needed:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Files

- `index.html` — app structure, styling, and speech logic
- `README.md` — project overview and usage notes

## Notes

This project uses the browser's built-in Speech Synthesis API, so voice availability depends on the operating system and browser.
