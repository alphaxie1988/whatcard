# WhatCard (magic)

## What
Progressive Web App (PWA) for a card prediction / magic trick.
- Stack: Vanilla JS, HTML, CSS, Service Worker (offline support)
- Single entry point: `index.html`
- PWA: `manifest.json`, `sw.js`, maskable icons (192×192, 512×512)

## Why
Installable magic card-trick app with offline capability. Published as alphaxie1988/whatcard on GitHub.

## How
Open `index.html` in a browser — no build step required.
Service worker caches assets on first load.
To update the PWA cache, bump the cache version constant in `sw.js`.
