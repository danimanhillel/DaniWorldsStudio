# DaniWorldsStudio

Browser-based video editor for Dani Worlds.

## Features
- Dark mode modern UI
- Import videos and images
- Multi-track timeline (3 tracks, higher track overrides)
- Tools: Select (move), Trim (edges), Split (cut)
- Live preview with playhead and scrubber
- Export with FPS (24/30/50/60) and resolution (720p/1080p/2K/4K)

## How to use
1. Open `index.html` in a modern browser (Chrome/Firefox/Edge).
2. Click Import to add media.
3. Drag media to timeline tracks.
4. Use tools to edit.
5. Play to preview.
6. Export to download WebM (browser-supported).

## Notes
- Fully client-side, no server required.
- Export uses MediaRecorder (WebM). For MP4, future FFmpeg.wasm integration possible.
- Performance depends on media size and browser.

## Development
This is the initial version. Contributions welcome for advanced features like effects, audio, transitions, and better export.

Created for DANI WORLDS.
