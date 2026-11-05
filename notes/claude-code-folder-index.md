# "Claude Code" Folder — Organized Index

A map of everything in the **Claude Code** folder on Payton's Mac, grouped by topic.
Built from the file list on 2026-11-05. Descriptions are based on file and folder
names only. Contents have not been reviewed yet (see "Next steps").

ABE = Another Broken Egg Cafe.

---

## 1. ABE Website Redesign: `abe-handoff/`
Design handoff package for the ABE website (19 pages).

| What | Where |
|---|---|
| Start page / overview | `abe-handoff/index.html`, `README.md`, `manifest.json` |
| Page builds (HTML + images + NOTES.md for each) | `abe-handoff/pages/01-home` … `19-legal-accessibility` |
| Full-page PNG exports | `abe-handoff/exports/png/` (01–19) |
| Desktop + mobile preview images | `abe-handoff/previews/` (one pair per page) |
| Figma import files (desktop 1360px, mobile 390px) | `abe-handoff/figma-import/` |
| Standalone pages | `abe-locations-standalone.html`, `abe-menu-standalone.html` |
| Desktop page PNGs, zipped | `abe-desktop-pages-png.zip`, `abe-menu-desktop.png` |
| Helper scripts (double-click on Mac) | `serve.command` (local preview), `refresh-previews.command` |

**The 19 site pages:**
1. Home
2. Menu
3. Locations
4. Cafe
5. Order
6. Waitlist
7. Catering
8. Co-op
9. Gift Cards
10. Contact
11. FAQs
12. Press
13. Press Article
14. Careers
15. Privacy
16. Terms
17. Cookies
18. California Privacy
19. Accessibility

## 2. Website & Email Reporting
| What | File |
|---|---|
| Year-to-date email performance report | `ytd-email-performance.html` |
| Campaign signal report | `campaign-signal.html` |
| Weekly report generator (script) | `weekly_report.py` |
| Mailchimp data pull (script) | `mailchimp_pull.py` |
| Gmail event log, Jul 19 – Aug 19, 2026 | `gmail-events-2026-07-19-to-2026-08-19.md` |

## 3. Email Design System: `email/`
| What | Where |
|---|---|
| Brand guidelines for email | `email/brand.md` |
| Color schemes | `email/colorways.json`, `email/ds-cards/email-colorways.html` |
| Reusable email modules | `email/modules.html`, `modules.preview.html` |
| Design-system cards (components, contrast, layouts) | `email/ds-cards/` |
| Email canvas templates (Main, Feature, Roundup, Components) | `email/canvas/` |
| Master brand template | `email/canvas/abe-email-brand-template.html` |
| Campaigns folder | `email/campaigns/` |
| Tools | `email/preview.py`, `email/recolor.py` |

## 4. Loyalty Program
| What | Where |
|---|---|
| Loyalty planning day | `loyalty-planning-day.html` |
| "Loyalty That Works" deck (8 slides) | `slides/loyalty-that-works.pptx` + `slides/loyalty-that-works-previews/` |
| "Why Loyalty" deck | `slides/Why-Loyalty.pptx`, `Why-Loyalty-GoogleSlides.pptx`, `why-loyalty.html` |
| "Program Design" deck | `slides/Program-Design.pptx`, `Program-Design-GoogleSlides.pptx`, `program-design.html` |
| "Good vs. Bad Loyalty" slide | `slides/good-vs-bad-loyalty.pptx` / `.png` |
| Deck build scripts | `slides/build.py`, `build_case.py`, `*.js`, `slides/README.md` |

"Loyalty That Works" slides:
1. Title
2. Name the behavior
3. Four structures
4. Economics
5. First three visits
6. Capture rate
7. Measurement
8. Build order

## 5. Brand
| What | File |
|---|---|
| Brand home page | `brand/home.html` |
| Email brand rules | `email/brand.md` (see section 3) |

## 6. Project Management & Daily Briefs
| What | Where |
|---|---|
| Asana board drift report | `asana-board-drift.html` |
| Asana snapshot (Aug 19, 2026) | `asana-snapshot-2026-08-19.json` |
| Daily Outlook brief + tracker | `outlook-brief/brief.html`, `outlook-brief/tracker.html` |
| Past briefs | `outlook-brief/archive/` (Sep 2, Sep 10, Oct 14) |

## 7. Events & Presentations
- `ABE Summit Presentation_Tuesday General Session_All.pdf`

## 8. Learning / Claude Code
- `claude-code-bootcamp-notes.md` and `Claude Code Bootcamp Notes.docx` (the same notes in two formats)
- `CLAUDE.md`: Claude's existing memory file for the Claude Code folder

---

## Next steps
- Share key files (especially `CLAUDE.md`, the reporting files in section 2, `email/brand.md`,
  and `abe-handoff/README.md`) so their contents can go into the knowledge base.
