# HEAPHEART: FIRST INTENTION

A phone-first offline roguelike about restoring the First Intentions trapped inside a privatized miracle engine.

## Play

After GitHub Pages is enabled, open:

https://killthelightsandputonashow.github.io/roguelarpz/

On iPhone, open that address in Safari, tap **Share**, choose **Add to Home Screen**, and launch it once while online. The service worker will cache the game for offline play.

## Repository layout

- `index.html` — launcher that reassembles and opens the game
- `game/0.txt` through `game/6.txt` — compressed complete game archive
- `manifest.webmanifest` — home-screen installation metadata
- `sw.js` — offline cache
- `icon.svg` — home-screen icon
- `browser-test.html` — JavaScript, storage, and unpacking test

The archive is split only to accommodate the connected GitHub uploader. The player never has to handle the pieces.

## Publishing

This repository is currently private. For free GitHub Pages hosting, change its visibility to **Public**, then go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
