## Meta
| Field | Value |
| Project | Splash and Scrub: logo-hero option (repo name is historical) |
| Last Active | 2026-10-08 |
| Status | shipping |
| Location | /home/wner/splash-and-scrub-boat-hero |
| Repo | jimmyardis/splash-and-scrub-boat-hero (public) |
| Live URL | https://jimmyardis.github.io/splash-and-scrub-boat-hero/ |

## Current State
Despite the repo name, this now hosts the **logo-hero option** for the client to
compare with production. It is production's `index.html` (painted design, live
Google Maps embed, bays photo in gallery slot 3) with the original painted
logo banner restored as the hero on desktop and mobile. Production at
splashandscrubsc.com has the boat photo hero instead. One self-contained file,
~7.8 MB.

## Next Action
The client picks logo hero (this page) or boat hero (production). If they choose
this one, copy this `index.html` over production and retire this repo.

## Blockers
None.

## Open Questions
- Which hero does the client want: logo (here) or boat photo (production)?

## Session Log
### 2026-10-08
- The owner disliked this repo's light single-layout redesign, so production
  got its boat photo instead, and this repo was overwritten with a comparison
  build: production's current file with the original painted logo hero restored
  (the #services panel and mobile `.hero-art` taken from production commit
  c726216), keeping the map embed and the re-cropped bays photo.
- The old light redesign is only in this repo's git history now (commit before
  this one).
- Verified live on GitHub Pages.
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
