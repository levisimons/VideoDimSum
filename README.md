# Video Dim Sum · Random Player

A zero-dependency, single-file GitHub Pages site that randomly picks one of 61
curated YouTube videos (from the Video Dim Sum spreadsheet tab `gid=726294062`)
and plays it in an embedded player.

**No API key. No build step. No dependencies.**  
All 61 video IDs are baked directly into the HTML.

---

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `vds-random-player`)
2. Upload `index.html` to the root of the `main` branch
3. Go to **Settings → Pages → Source**, set branch to `main`, folder to `/ (root)`, click **Save**
4. Your site is live at `https://YOUR_USERNAME.github.io/vds-random-player/`

---

## How it works

- On load, a splash screen is shown
- Clicking **⚡ Random Video** (or the splash) picks a random URL from the 61-item list
- The video is embedded via the standard YouTube IFrame embed — no API needed
- A session history of played videos is shown as clickable pills to replay
- The player tracks which videos have been seen and avoids repeats until all 61 have played

---

## Source

Videos sourced from:  
<https://docs.google.com/spreadsheets/d/1vu8cF-PIEEWoEuko2-VwfC554dudyF1gsTC7BjEPPjE/edit?gid=726294062>

All video content © original creators / Video Dim Sum.
