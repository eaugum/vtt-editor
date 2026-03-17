# VTT Editor

A lightweight, browser-based editor for WebVTT subtitle files. Edit cues in sync with video and a timeline.

## Features

- **Load and edit WebVTT** – Open a VTT file and edit cue text, start and end times
- **Video preview** – Open a video file; playback stays in sync with the subtitle list
- **Timeline** – Waveform, cue blocks, zoom (1×–100×), horizontal scroll; resizable timeline height
- **Cue list** – Click a cue to seek; click start/end time to set via prompt; duplicate or delete cues
- **Save** – Save button with state (Save / Saved / Saving…); **⌘S** (Ctrl+S) also saves
- **Subtitle zoom** – Adjust preview font size (1–100%)
- **Welcome modal** – Brief intro on first load (shortcuts and usage)

**Coming:** Light mode (with optional toggle).

## Getting started

Open `index.html` in your browser. No build step or server required.

1. Open a **video** file and a **VTT** file (order doesn’t matter).
2. Click a cue in the side panel to jump to that time; edit text and times as needed.
3. Use the timeline to scroll and zoom, or drag cue block edges to adjust times.
4. Save when done (**Lagre** or **⌘S**).

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| **Space** / **S** | Play / Pause |
| **A** / **←** | Previous frame |
| **D** / **→** | Next frame |
| **⌘S** / **Ctrl+S** | Save |
| **Escape** | Close welcome modal (when open) |

## Development

Single static HTML file: HTML, CSS, and JavaScript in `index.html`. No dependencies.
