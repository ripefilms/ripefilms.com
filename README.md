# RIPE Films — GitHub Pages landing page

This is the RIPE Films static website.

## Structure

- `index.html` — home page
- `imprint.html` — imprint page
- `style.css` — typography, layout and responsive design
- `images/ripe-films.svg` — logo

## Current design

- Background: `#ffff7a`
- Text: black
- Font: Geist Sans, weights 400 / 600 / 700
- Responsive desktop/mobile layouts
- Logo has a dedicated bottom row so it cannot overlap the page text
- The headline, intro and email form an adaptive vertically centered group with responsive breathing room
- Intro wrapping uses responsive width plus CSS `text-wrap: pretty` to avoid awkward short lines
- Site name remains visible in the mobile header and links back to the landing page
- Email: `look@ripefilms.com` with a clickable `mailto:` link

## GitHub Pages

Keep the custom domain disconnected until the design is finished.

When ready:
1. GitHub → repository → Settings → Pages
2. Add `ripefilms.com` under Custom domain
3. Then configure the website DNS records in Squarespace
4. Leave Google Workspace MX records untouched
