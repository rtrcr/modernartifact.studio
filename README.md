# modernartifact.studio

Website for Modern Artifact (exported from Claude Design, "Production 1A").

- **Hosting:** Netlify. Every push to `main` deploys automatically to https://modernartifact.studio
- **Structure:** `index.html` (page), `support.js` (design runtime; loads React from unpkg), `assets/` (fonts, logos, videos), `netlify.toml` (publish root + long cache on `/assets/*`).
- **Note:** assets are cached for a year, so when replacing a video or logo, give the new file a new name.
