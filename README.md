# Hearth — Fireplace Screensaver

A full-screen animated fireplace designed for a display, screensaver-style ambience, or a browser source in OBS.

## Features
- Animated 1920 × 1080 fireplace with layered flames, glowing logs, ember cracks, sparks, and warm light.
- Fullscreen mode with the F key.
- Press D to record and download a 25-second video with synthesized crackling ambience.
- Video exports as WebM at 30 FPS. YouTube accepts WebM uploads.
- Audio starts after a user interaction because browsers restrict autoplay audio.
- Press H to toggle the controls.

## Run locally
Open index.html in a recent version of Chrome or Edge. Click Enable fire audio once to activate sound.

## OBS
Add the existing deployed Worker URL as a Browser Source and set its dimensions to 1920 × 1080. The Cloudflare Worker is named `fireplace`.

## Worker
- Worker name: fireplace
- Health check: /health

The crackling audio is synthesized in-browser; it is not a field recording.
