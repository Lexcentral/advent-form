# advent-form

Public GitHub Pages host for the **LexCentral Advent Devotions** signup form.

- `index.html` — the signup form (no build; Alpine.js via CDN). It POSTs to the
  Apps Script web app `/exec` URL configured in `GAS_URL` inside the file.

**Source of truth** is the `site/` folder of the private `advent-signups` repo;
this repo is the published copy. Update there, then copy `index.html` here.

Served at: https://lexcentral.github.io/advent-form/
