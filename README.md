# They Call Me Giulio — local clone

This folder recreates the portfolio with its served UI bundle, 3D scenes, textures, project artwork, audio, and fonts. The analytics tag is omitted. Guestbook entries stay in local browser storage and are not sent to the original site's database. Project reels stream from the original site.

## GitHub Pages

After the first deployment completes, the site is available at:

<https://dev-sudeep018.github.io/1to1copy/>

## Run locally

Use a browser with WebGPU support. From this folder, run:

```powershell
py -3 -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.