# Claude Setup for ABE SEO & Website Reporting

Last updated: 2026-11-05

## Status
| Item | Status | Who |
|---|---|---|
| Knowledge base repo (`website-reporting` on GitHub) | Done | Claude |
| Folder index + SEO tool notes saved | Done | Claude |
| Marketing plugin (Anthropic) | Installed | Payton |
| SEO GSC Wizard plugin | Installed. Still needs sign-in to Search Console (see below) | Payton |
| SEO Audit plugin | Installed | Payton |
| Claude in Chrome extension | To do | Payton |
| Repo downloaded on the Mac (`Claude Code/website reporting`) | Check, then run `git pull` | Payton |
| Scheduled tasks (below) | To do: create from the Mac-connected session | Payton + Claude |

## Steps only Payton can do
1. **Claude in Chrome:** Chrome Web Store → "Claude in Chrome" → Add to Chrome →
   sign in with paytonyoung1219@gmail.com.
2. **SEO GSC Wizard:** in the Claude desktop app, open a chat and ask
   "connect GSC Wizard". Sign in with the Google account that has access
   to ABE's Search Console and GA4.
3. **Update the Mac copy:** in Terminal, inside `Claude Code/website reporting`, run `git pull`.

## Which session to use
- **Desktop app session connected to the MacBook Pro:** anything needing the browser
  (GA4, Search Console, Business Profile, Bing, Apple Business Connect, ChatGPT/Gemini checks).
- **Cloud sessions (claude.ai/code):** writing, analysis of uploaded exports, and updating this repo.

## Plugin skills to use
| Task | Skill |
|---|---|
| Quarterly / monthly website report | `marketing:performance-report` |
| Weekly SEO digest | `seo-gsc-wizard:weekly-report` |
| Full SEO health check | `seo-gsc-wizard:site-audit` or `seo-audit:seo-audit` |
| Quick wins | `seo-gsc-wizard:quick-wins` |
| Indexing problems (check after the relaunch!) | `seo-gsc-wizard:indexing-health` |
| Read Screaming Frog / GSC exports | `seo-audit:search-console-data-review` |
| Turn findings into tickets for contractors | `seo-audit:seo-fix-plan` |
| Review the new site's code before launch | `seo-audit:technical-seo-code-audit` |

## Scheduled tasks to create (paste each into the Mac-connected session)
1. **Monthly website report (1st business day):**
   "Every month on the first weekday at 9:40am, open GA4 for the ABE consumer site and Search
   Console, pull last month vs. the prior month and the same month last year, and build the
   website report as an artifact. Save it to website-reporting/reports/ and push."
2. **Weekly SEO check (Mondays):**
   "Every Monday at 8:50am, run seo-gsc-wizard:weekly-report for the ABE site and flag new
   indexing errors. Save a short summary to website-reporting/reports/weekly/."
3. **Monthly AI visibility check:**
   "Every month on the 15th, ask ChatGPT and Gemini these questions and log whether Another Broken
   Egg appears: best brunch in Orlando / Tampa / Atlanta / Dallas / Nashville / New Orleans,
   breakfast near me, brunch catering near me. Append results to
   website-reporting/data/ai-visibility.csv."

## First task once Chrome is set up
"Open GA4 for the ABE consumer site and build the Q3 2026 (Jul 1–Sep 30) website report as an
artifact. Compare it to Q2 and to Q3 2025. Save it to website-reporting/reports/."
