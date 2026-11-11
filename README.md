# Krish & Milo — Rebuild the Doghouse

A SKAI group mission for 3–4 players on one screen.

## How to launch

* **On a website:** upload the entire contents of this folder to any static
  host and open `index.html`. No build step or server-side code is needed.
* **On one computer:** double-click `index.html`. It plays in the browser
  straight from the folder.

## Offline

Everything the game needs is in this folder — art, audio, fonts and the
animation library. It makes no internet requests and works with no
connection.

## Browsers

Current Chrome, Edge, Firefox or Safari (desktop or tablet), in landscape.

Hosting notes: keep both audio sets (`.ogg` and `.mp3`) and both clip files
(`.webm` and `.mov`) — each browser picks the one it supports. A few older
Apache servers need `.ogg` (audio/ogg), `.webm` (video/webm), `.webp`
(image/webp) and `.mov` (video/quicktime) added as MIME types.
