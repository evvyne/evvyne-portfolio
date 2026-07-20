# Evvyne Tan — Video & Content Producer Portfolio

Single-file HTML portfolio site. No build step, no dependencies — just `index.html`.

## Live site

Deployed on Netlify via this repo's `main` branch. Any push to `main` auto-deploys.

## Updating the site

1. Edit `index.html` directly on GitHub (pencil icon on the file) or clone locally and edit.
2. Commit the change.
3. Netlify picks up the push automatically and redeploys — usually live within a minute.

## Structure

Everything (HTML, CSS, JS, and the profile photo as base64) lives in `index.html`.
Video data (YouTube/Instagram/TikTok links, titles, dates, roles) is in the
`projects` array near the top of the `<script>` section.
