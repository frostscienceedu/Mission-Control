# Mission Control 1.1

This update fixes:
- Functional English / Español toggle on all three screens.
- Mission names, material profiles, controls, and mission reports translate without losing the selected mission/materials.
- Mars uses a local NASA Perseverance rover image, so it no longer depends on the broken Mars image link.

## GitHub update
In your `frostscienceedu/Mission-Control` repository, replace the existing files with the contents of this folder.
Make sure `images/mars-rover.webp` is uploaded inside the `images` folder.
Then commit the changes. GitHub Pages should update automatically.

If the old version appears after the update, hard-refresh once (Ctrl+Shift+R) because the PWA/service worker may still have the earlier version cached.
