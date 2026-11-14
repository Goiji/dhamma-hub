# dhamma-hub

- Static single-page site (`index.html`, fonts embedded). No build step.
- Netlify (dhamma-hub.netlify.app) is linked to this repo and auto-deploys every push to `main`.
- Owner preference: after a change, commit and push straight to `main` — no PR, no need to ask first.
- Link-preview image: `og-image-v2.jpg` (1200×630, title on the lotus/wheel art), referenced as https://dhamma-hub.netlify.app/og-image-v2.jpg. Source: `design/og-image.svg` (art) + `design/og-image-title.html` (title overlay, render at 1200×630). Use a new filename when changing the image so Discord refetches it.
- Home-screen icon: `apple-touch-icon.png` (180, opaque cream bg) and `icon-512.png`, rendered from `design/icon.svg`.
- Discord caches previews per URL; to check a new preview, share the link with a fresh `?v=N`.
