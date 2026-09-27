# Omar Atef — Personal Website

Static site served by GitHub Pages at [omar-atef.com](https://omar-atef.com).
No build step — edit the files and commit.

Positioning: Product Management first, then Product Owner and Business Analysis.
Official employment titles are kept exactly as on the CV. Education shows the
university and degree only (no graduation year or major).

## Files
| File | Purpose |
| --- | --- |
| `index.html` | All page content (hero, about, services, work, experience, skills, contact) |
| `styles.css` | Design — light theme by default, dark theme via OS setting or the header toggle |
| `script.js` | Mobile menu, theme toggle, scroll animations, active nav link |
| `cv.pdf` | CV linked from the "Download CV" button |
| `profile.webp` / `profile.jpg` | Optimized portrait (800 px wide) used on the page |
| `profile.png` | Original full-size portrait (source file) |
| `og-image.jpg` | 1200×630 preview shown when the link is shared on LinkedIn, WhatsApp, etc. |
| `favicon.svg`, `apple-touch-icon.png` | Browser / home-screen icons |
| `404.html`, `robots.txt`, `sitemap.xml`, `CNAME` | Pages / SEO / domain config |

## Changing your photo
Use a vertical portrait (ideally 2:3 or 4:5, at least 800 px wide) and save it
as both `profile.jpg` and `profile.webp` (any free converter such as
squoosh.app works; aim for under ~150 KB). If the image is missing, the site
falls back to `profile-placeholder.svg`.

## Updating the CV
Replace `cv.pdf` with the new file (same name).
