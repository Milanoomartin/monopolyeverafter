# Monopoly Ever After site bundle

## Included
- `index.html`
- `assets/MonopolyEverAfter-favicon.png`
- `assets/set_colors_reference.csv`

## What the CSV does now
When the site is hosted over HTTP/HTTPS (for example GitHub Pages), the page will try to load `assets/set_colors_reference.csv` on startup.

You can edit these columns to change the live album styling/data:
- `Set` or `Set #`
- `Set Name`
- `Estimated Hex Code` or `Set Color Hex Code`

That means the CSV is no longer just reference-only — it can override the set names and set rim/banner colors.

## Important note for local file opening
If you double-click `index.html` and open it as a local `file://` page, some browsers block CSV loading for security reasons. In that case the built-in defaults will still work, but CSV edits may not auto-apply until you:
- run a small local web server, or
- upload to GitHub Pages / another host

## GitHub Pages
Upload the full folder contents and publish the repo/folder as a Pages site.
