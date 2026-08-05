# Tax Pro Mode — clickable prototype

A static, pixel-for-pixel clickable prototype mirroring the [Tax Pro Mode Figma design](https://www.figma.com/design/W7yeXHYC6bKE2et95fnsaT/Tax-pro-mode).

Built as plain HTML/CSS/JS (no build step) so the markup stays a faithful copy of the design and deploys to Vercel with zero configuration.

## Screens

| File | Screen |
| --- | --- |
| `index.html` | Wages (W-2) |

Add each new Figma frame as its own `.html` file and link screens together to make the flow clickable.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Pushed to [antonea-april/taxpromode](https://github.com/antonea-april/taxpromode) and deployed on Vercel as a static site.
