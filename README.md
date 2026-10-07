# Little Black Book

A single-file, private tracker. Runs entirely in the browser. No server, no accounts.

## Use it
- **Locally:** double-click `index.html`.
- **On GitHub Pages:** push these files, then Settings > Pages > deploy from the `main` branch, root folder.

## Where data lives
In your browser's local storage, per device and per address. A copy opened from a file, from GitHub Pages, and from another browser each have separate data. Move data between them with Back up / Import backup.

## Never commit your backups
Backup files contain real names and notes. Keep them out of the repo:
add `*.json` to a `.gitignore` file.
