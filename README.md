# BPM Detector

A simple single-page web app that estimates the tempo (beats per minute) of an uploaded MP3 file directly in the browser using the Web Audio API.

## Usage
1. Open `index.html` in a modern browser (Chrome/Edge/Firefox/Safari).
2. Click **Choose an MP3 file** and select a track from your computer.
3. Wait a moment for the file to be decoded and analyzed; the estimated BPM will appear in the status box.

All processing happens locally—your audio never leaves the browser.

## GitHub Pages deployment
A GitHub Actions workflow (`.github/workflows/pages.yml`) publishes the site to GitHub Pages whenever changes are pushed to `main` or the workflow is manually dispatched. Make sure GitHub Pages is set to "GitHub Actions" in the repository settings, then visit the environment URL from the workflow run to load `index.html`.
