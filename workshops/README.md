# Workshops folder

How to add or update a workshop on the Resources page:

1. Create a folder here named `YYYY-MM-DD-venue-slug` (e.g. `2026-08-15-beijing-american-center`).
2. Drag your files into that folder — no need to rename them, just avoid special characters like `#` or `%`.
3. Optionally add a `blurb.txt` in the same folder with a short reflection on the workshop — it's shown on the page above the file list and is never listed as a download.
4. Ask Claude to "sync the resources page" — it scans this folder, updates `manifest.json`, and the dropdown on resources.html picks it up automatically.

`manifest.json` is generated from the folder contents — don't hand-edit it unless you want to override a display title.
