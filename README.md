# Personal Website — Dinuk Jayarathna

This is a Jekyll site, built to run on GitHub Pages for free.

## How to publish it

1. Create a GitHub repository named exactly: `YOURUSERNAME.github.io`
2. Upload every file in this folder into that repository (keep the same folder structure)
3. Go to the repo's Settings → Pages, and confirm it's set to build from the `main` branch
4. Wait 1-2 minutes — your site will be live at `https://YOURUSERNAME.github.io`

## Before you publish, update these placeholders

- `_config.yml` — replace `your.email@example.com` with your real email
- `_layouts/default.html` — replace `YOUR-LINKEDIN`, `YOUR-ORCID-ID`, and `your.email@example.com`
- `index.html` — replace `YOUR-LINKEDIN` and `YOUR-ORCID-ID` (appears in the hero links)

## How to add a new blog post

1. Create a new file inside `_posts/` named like: `2026-07-10-my-post-title.md`
   (the date at the front of the filename must match the real date)
2. Start the file with this front matter, then write your post in Markdown below it:

```
---
title: "Your Post Title Here"
category: Lab Notes
excerpt: "One or two sentences that will show up as the preview text."
---

Your post content goes here, written in normal Markdown.
```

3. Commit the file to your repo (via GitHub's "Add file" button, or `git push` if using Git locally)
4. It will automatically appear on your homepage under "Field Notes" — no other steps needed
