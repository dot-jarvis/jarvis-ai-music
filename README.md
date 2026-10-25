# JARVIS AI Music

Static, editable website source for JARVIS AI Music.

Official website: https://music.autosystems.tech

This branch expands the initial v3 website with release listening guides, a documented production notebook, AI/editorial transparency, contact and reuse guidance, and a privacy notice. These changes are prepared for review; this branch does not itself deploy the website.

## Files

- `dist/index.html`: page markup and music links
- `dist/style.css`: responsive layout and CSS artwork
- `dist/app.js`: English, Japanese, Spanish, Simplified Chinese and Traditional Chinese translations, language persistence and video dialog
- `dist/editorial-content.js`: complete editorial copy in the same five languages

No dependencies or build step are required. Serve `dist/` with a static web server (for example `python -m http.server 8000 --directory dist`).

YouTube players load only after selecting a track. The site does not provide live streaming or an automated Discord bot.

English content is present in the HTML without JavaScript. Language selection replaces that content locally and saves only the language preference. No remote translation service, font request, analytics tracker, advertising code, cookie banner or account system is added. Production measurements describe the identified source master; they are not an independent listening review or a rights-clearance guarantee. Translations have not received professional native-language review.

The Discord invitation is time-limited (30 days from 2026-10-23); verify or replace it before expiry.

No license is granted by this repository. No credentials, deployment identity, Git history or private configuration are included.
