## Meta
| Field | Value |
| Project | Splash and Scrub: boat-hero version |
| Last Active | 2026-10-01 |
| Status | shipping |
| Location | /home/wner/splash-and-scrub-boat-hero |
| Repo | jimmyardis/splash-and-scrub-boat-hero (public) |
| Live URL | https://jimmyardis.github.io/splash-and-scrub-boat-hero/ |

## Current State
An alternate version of the Splash and Scrub site (Irmo, SC car and boat wash),
published in its own repo so it sits beside the production site at
splashandscrubsc.com without replacing it. One self-contained `index.html`
(~2.8 MB) with a photo hero, a light page background, and a single responsive
layout instead of the production site's separate desktop and mobile trees. Live
on GitHub Pages and verified byte-for-byte against the delivered file.

## Next Action
Decide whether this version replaces the production site at splashandscrubsc.com
or stays a side-by-side preview.

## Blockers
None.

## Open Questions
- Is this a preview for the owner to compare, or the intended replacement for
  the live site?
- If it replaces production, does this repo get retired afterwards?

## Session Log
### 2026-10-01
- Copied `splash-and-scrub-boat-hero.html` from Windows Downloads as
  `index.html`, added `.nojekyll`, and created the public repo
  `jimmyardis/splash-and-scrub-boat-hero`.
- Enabled GitHub Pages on `main` at root; the build reported `built` and the
  live page matched the local file byte-for-byte (2,773,254 bytes).
- Checked the file before publishing: same title, phone number (803-834-0367),
  address, and Google Maps link as production; no external assets, no forms.
- Kept it in a separate repo on request, so the production repo
  (`jimmyardis/splash-and-scrub`) and its custom domain were not touched.
