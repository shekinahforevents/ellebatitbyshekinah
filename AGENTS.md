# AGENTS.md

## Architecture
- Static site, no build step, no framework. `netlify.toml` publishes `public/`.
- `public/index.html` is the entire site: inline `<style>`, one inline base64 JPEG, two small inline `<script>` blocks (countdown to 31 Oct 2026 in `#compte`, smooth anchor scrolling).

## Conventions
- Content is in French; keep the brand palette defined in `:root` CSS variables (crème, brun, terre, or, feuille) and fonts Playfair Display / Great Vibes / Montserrat.
- Sections are anchored by id: `#accueil`, `#pourquoi`, `#episodes`, `#rencontre`, `#suivre`.
- The page was supplied by the owner (exported from a Wix design); edit in place rather than restructuring.

## Notes
- Social buttons in `#suivre` are placeholders (`<span>`) until the accounts launch.
