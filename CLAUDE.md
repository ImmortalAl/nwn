# CLAUDE.md - New World News (NWN)

**Domain**: nwn.box
**Last Updated**: 2025-12-10
**Repo**: https://github.com/ImmortalAl/nwn.git

---

## Project Overview

New World News is a news aggregation and presentation site. Currently a minimal static site with potential for expansion.

---

## Architecture

### Current Stack
- **Hosting**: TBD (likely Cloudflare Pages or similar)
- **Type**: Static HTML
- **Framework**: Tailwind CSS (via CDN)
- **Fonts**: Libre Baskerville (headlines), Roboto (body)

---

## Current Files

```
NewWorldNews/
├── index.html          # Main news page
├── dlive.html          # DLive integration page
└── newworldnews.png    # Logo/branding asset
```

---

## Git Workflow

**After making ANY changes:**

1. `git add .`
2. `git commit -m "type: description"`
3. `git push origin main`

**Commit types**: feat, fix, update, style, refactor, docs

---

## Design Notes

- Newspaper-style layout
- Serif headlines (Libre Baskerville)
- Clean, readable body text (Roboto)
- Hover effects on news items
- Death toll / breaking news styling with red accents

---

## Related Content

This site may relate to the "New World News" Saturday DLive show documented in:
`/home/opc/MommyDearest/income-project/new-world-news/`

That folder contains show planning, episode templates, and OBS overlays for the livestream. This repo (nwn.box) is the standalone website.

---

## TODO

- [ ] Determine hosting setup
- [ ] Expand beyond static pages if needed
- [ ] Consider integration with DLive show content

---

## Communication Preferences

- Challenge ideas and propose alternatives
- Debate before implementing
- Ask if anything is unclear
- Never be a "yes man"
