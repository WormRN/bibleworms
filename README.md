# BibleWorms

Teaching site for the GOAL and EDGE Bible study methods.
Companion to the EDGE Study App.

## Structure

- `index.html` — homepage
- `styles.css` — shared stylesheet (all future pages link to this)
- Coming: `goal.html`, `edge.html`, Bible Basics articles

No build tools. Every page is plain HTML, editable in GitHub.dev.

## One-time setup

1. **Create the repo:** on GitHub, create `WormRN/bibleworms` (public).
   Upload these files to the repo root.
2. **Cloudflare Pages:** dash.cloudflare.com → Workers & Pages →
   Create → Pages → Connect to Git → select `bibleworms`.
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
3. **Deploy:** Cloudflare builds automatically on every push,
   same as Vercel. First deploy gives you `bibleworms.pages.dev`.
4. **Domain (later):** Pages project → Custom domains →
   add `bibleworms.org` and follow the DNS prompt.

## Updating the site

Edit in GitHub.dev → commit → Cloudflare redeploys in ~60 seconds.
