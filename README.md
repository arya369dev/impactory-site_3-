# IMPACTORY 2.0 — Arya Patole

GitHub-ready static portfolio website with an interactive perspective-based Infinite Gallery, animated triangular HUD, cinematic hero and glowing gaming cursor.

## Upload to GitHub

1. Download and unzip `IMPACTORY_2_0_GitHub_Ready.zip`.
2. Create a new GitHub repository (e.g. `impactory-2`).
3. Choose **Add file → Upload files** and upload the **contents** of the `IMPACTORY_2_0` folder. The `index.html` file must be at the repository root.
4. Commit the files.
5. For Vercel: **Add New → Project → Import Git Repository → Deploy**. Framework preset: **Other**; build command: **none**; output directory: **.** (repository root).
6. For GitHub Pages: **Settings → Pages → Deploy from a branch → main / root → Save**.

## Edit content

- `index.html` — text, navigation, contact email, page structure.
- `style.css` — colors, spacing, motion and responsiveness.
- `projects.js` — seven projects, descriptions, destinations and logo file paths.
- `script.js` — gallery interaction, cursor effects, modals and navigation.
- `assets/impactory-wordmark.png` — existing IMPACTORY branding.
- `assets/images/cinematic-entrance.png` — cinematic visual supplied for this project.
- `assets/images/arya-portrait.jpg` — supplied portrait asset.

## IMPORTANT: original project logos

The seven official project logo files are **not available as individually identified files in this package**. The gallery uses clearly generic symbols as temporary placeholders rather than pretending to recreate your official logos.

To add each original logo: copy its PNG/SVG/WebP into `assets/logos/`, then edit the corresponding `logo` property in `projects.js`, for example `logo:'assets/logos/nagarik.png'`. The website will show the supplied image as-is.

## IMPORTANT: cinematic intro

The hero uses the supplied cinematic entrance image with a slow camera-like zoom. A fully animated, photorealistic 3D character reveal is **not included**: that requires a verified final character model or finished video. The small `.glb` from an earlier portfolio ZIP was not used as a verified likeness.

## Contact

Replace `hello@example.com` in `index.html` with your actual email. The placeholder is deliberately not represented as a working address.

## Technical notes

No npm install, build pipeline or API keys needed. Works as a static site. The gallery is CSS 3D perspective with interactive depth and navigation, **not** a fully modeled WebGL walk-through. Fonts use Google Fonts when available, with local fallback. The site supports touch swipes, keyboard arrow keys, and reduced-motion preferences.
