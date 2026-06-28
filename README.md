# Moonbloom

A soft studio for neurospicy brains — free tools built slowly, without burning out.  
Built by [Nex](https://rainbowcatteck.notion.site/Link-Directory-130127c6a16980d7bf78f03a1cef88cf).

## Repo layout

```
index.html      ← landing page   (moonbloom.quest)
netlify.toml    ← Netlify config
sitemap.xml
robots.txt
favicon.svg
og-image.png
```

## Branches

| Branch | Purpose |
|---|---|
| `feature/*` | bigger features start here, branched off `dev` — merges into `dev` only once fully stable and done |
| `dev` | active development — small fixes go here directly, features merge in from `feature/*` |
| `main` | production — merging here triggers a Netlify deploy |

## Netlify setup

| Site | Base directory | Publish directory | Deploy branch |
|---|---|---|---|
| moonbloom.quest | `/` | `.` | `main` |

## Tech

Pure HTML/CSS/JS — no build step, no bundler, no dependencies.
