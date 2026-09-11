# Mika's blog

A small personal/dev blog built with Astro and styled as a sibling to the Mochi website.

## Local development

```bash
npm install
npm run dev
```

The dev server prints the local URL in the terminal.

## Add a post

Create a Markdown file in `src/content/blog/`:

```md
---
title: "Post title"
description: "One-sentence summary."
date: 2026-09-11
tags: ["linux", "python"]
featured: false
draft: false
---

Write here.
```

Set `draft: true` to keep a post out of the generated site.

## Build

```bash
npm run build
```

## GitHub Pages

The repository is configured for `https://miflow13.github.io/my-blog/`.

After the repository exists on GitHub:

1. Open **Settings → Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push or merge to `main`.
4. The `Deploy to GitHub Pages` workflow will build and publish the site.

The repository path is configured in `astro.config.mjs` as `/my-blog`.
