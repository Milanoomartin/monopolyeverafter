# Monopoly Ever After site bundle (local-file friendly)

## Included
- `index.html`
- `assets/MonopolyEverAfter-favicon.png`

## What changed
This bundle is fully self-contained for easy use with browser local storage.

- No CSV loading
- No hosted-only set color override logic
- Works cleanly when opened directly as a local `file://` page
- Account data, sticker progress, and related tracker state still save in browser local storage

## Editing set names or set colors later
If you want to change the built-in set names or set colors later, edit the set data directly inside `index.html`.

Look for the main set data array in the script section:
- `window.SET_DATA = [...]`

That is now the single source of truth for local and hosted use.

## GitHub Pages
You can still upload this folder to GitHub Pages as-is.
