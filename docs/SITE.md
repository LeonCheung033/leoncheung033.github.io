# leoncheung033.github.io

This repository is the working copy of Leon Cheung's personal website, built
from the al-folio v1 starter.

## Current public surface

- Home/About: Chinese-first identity and introduction, personal photograph, and Reze visual.
- Blog: initially empty and ready for primarily Chinese Markdown posts.
- Projects: initially empty and ready for primarily Chinese project entries.
- Social links: GitHub only until Leon supplies additional public contacts.

## Asset policy

- `assets/img/leon-profile.jpg` is Leon's personal photograph.
- `assets/img/reze-banner.jpg` is a locally supplied Reze image.
- Leon authorized their initial public upload on 2026-09-15.
- Embedded EXIF metadata has been removed from both site-ready image files.
- Before publication, confirm Leon's authorization to upload his photograph and
  confirm the Reze image's source, license, and any required attribution.

## Publishing boundary

The checkout lives under AgentEval's ignored `references/` directory. Leon
authorized the initial public repository creation and deployment on 2026-09-15.
Every later push or publication change requires fresh explicit authorization at
the time it is performed.

## Local verification

Follow the commands in `AGENTS.md`. The minimum handoff checks are:

```bash
npm ci
npm run lint:prettier
bundle exec al-folio upgrade audit --no-fail
bundle exec jekyll build
```
