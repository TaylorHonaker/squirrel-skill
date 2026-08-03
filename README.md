# Squirrel Skill 🐿️

**Live:** <https://www.squirrelskill.com>

Landing page for **Squirrel Skill** — an AI skill that catches an idea mid-sentence and hands your momentum straight back. Say *"squirrel that"* and the idea is bottled in a structured 13-field record in about five seconds, with zero questions asked. Once a month the Chase ranks what you caught, until one idea earns the year.

It is a folder of plain markdown — an [Agent Skill](https://www.anthropic.com/news/agent-skills), born on Claude, runnable anywhere the open standard runs. No app, no account, no server.

**Free tier:** capture, forever · **Full system:** $147 once · all sales final

---

## This repo is a deploy target, not the source

It holds only what GitHub Pages serves. **Edits belong upstream** in the private product repo, which owns the page source, the skill sources and the funnel copy.

Editing `index.html` here will be silently overwritten by the next deploy — and because the upstream repo has no record of this one, the change leaves no trace anywhere.

```
index.html      the landing page (self-contained: markup, CSS, JS)
llms.txt        machine-readable product facts
terms.html      Terms of Sale & Use
privacy.html    Privacy
changelog.html  shipped changes
og.png          1200×630 share card
squirrel-free.zip   the free tier — public by design
CNAME           custom domain for Pages
.nojekyll       serve files as-is, no Jekyll processing
```

> The paid ZIP is deliberately **absent**. It is delivered by email and must never have a public URL here.

## Serving

GitHub Pages from `main`, custom domain via `CNAME`, HTTPS enforced. Apex, `www`, and the old `taylorhonaker.github.io` address all resolve to the canonical `https://www.squirrelskill.com/`.

Builds take about 30 seconds. Verify against the live URL rather than the Pages build API, which has been observed reporting a stale commit.

---

Sold by **AI Company USA dba SUMMIT Business Automation** · Helena, Montana · <taylor@aicompanyusa.com>
