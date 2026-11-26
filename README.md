# Jesus-Centric KJV for Kids ✝

Kid-friendly searchable viewer for the Jesus-centric modernization of the public-domain King James Version.

## Features
- Emojis next to key words to help children understand (e.g. ✝ for JESUS / cross, ❤️ for love, 🌟 for LORD, 🕊️ for peace, 🙏 for faith / pray)
- LORD / GOD in all caps, name Jesus forced to JESUS, with [JESUS] markers on titles
- Red-letter highlighting for JESUS, LORD, and GOD
- Searchable by book, chapter, or verse text
- Light, playful theme sized for kids (with light/dark toggle)
- Suggest-a-change button that opens a pre-filled GitHub Issue

## Source text
The processed Bible text (`docs/jesus_centric_kjv_all66.txt`) is kept in sync with the latest version from the main repository:

https://github.com/evalrjcom/jesus-centric-kjv/blob/main/docs/jesus_centric_kjv_all66.txt

A scheduled GitHub Action (`.github/workflows/sync-bible.yml`) runs daily and also on manual trigger. It downloads the latest file from the main repo and commits an update only if the content has changed.

## Viewer (GitHub Pages)
The site is served from the `/docs` folder.

**To enable GitHub Pages:**
1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / folder: `/docs`
4. Save

The kids site will be available at `https://evalrjcom.github.io/JESUS-centric-kjv-kids/`.

Source text: public-domain KJV (processed in the main [jesus-centric-kjv](https://github.com/evalrjcom/jesus-centric-kjv) repo).
