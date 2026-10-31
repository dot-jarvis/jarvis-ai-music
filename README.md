# JARVIS AI Music

Static, editable website source for JARVIS AI Music.

Official website: https://music.autosystems.tech

This branch expands the initial v3 website with release listening guides, a documented production notebook, AI/editorial transparency, contact and reuse guidance, and a privacy notice. These changes are prepared for review; this branch does not itself deploy the website.

## Operations

See [the AI Music operations guide](docs/operations.md) for daily releases, live start/stop, Discord announcements, ownership, verification and failure handling. The guide documents operations performed by existing dedicated systems; this website repository does not implement those systems. Runtime records and credentials remain private.

## Files

- `dist/index.html`: page markup and music links
- `dist/style.css`: responsive layout and CSS artwork
- `dist/app.js`: English, Japanese, Spanish, Simplified Chinese and Traditional Chinese translations, language persistence and video dialog
- `dist/editorial-content.js`: complete editorial copy in the same five languages

No dependencies or build step are required. Serve `dist/` with a static web server (for example `python -m http.server 8000 --directory dist`).

YouTube players load only after selecting a track. The site does not provide live streaming or an automated Discord bot.

English content is present in the HTML without JavaScript. Language selection replaces that content locally and saves only the language preference. No remote translation service, font request, analytics tracker, advertising code, cookie banner or account system is added. Production measurements describe the identified source master; they are not an independent listening review or a rights-clearance guarantee. Translations have not received professional native-language review.

The website's existing Discord invitation was documented as time-limited (30 days from 2026-10-23); verify it before expiry. The current operations invitation is specified in the operations guide; its validity must be checked independently.

No license is granted by this repository. No credentials, deployment identity, Git history or private configuration are included.
