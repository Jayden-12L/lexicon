# Lexicon

A personal learning library that turns English-learning videos into organized, searchable notes.

## V1 interface prototype

The current prototype is a responsive, browser-based interface with:
- Home dashboard and recent lessons
- Searchable video library
- Consolidated vocabulary dictionary
- Simple flashcard-style review
- Editable video notes and vocabulary
- JSON export

## Run locally

Open `index.html` in a browser, or enable GitHub Pages from **Settings → Pages** and deploy from the `main` branch, root folder.

## Current limitations

This is the interface prototype. Notes are currently saved in the browser's local storage and sample content is included. Automatic YouTube detection, transcript processing, AI extraction, accounts, and cross-device synchronization are not connected yet. Those require a secure backend and a browser extension; API secrets must never be placed in the public frontend.

## Planned architecture

- Responsive web application
- Supabase authentication and database
- Browser extension for opted-in YouTube playback detection on supported desktop browsers
- Server-side transcript and AI processing
- Cross-device synchronization
