# Agent Note: Bootstrap Leon Cheung's personal site

Status: implemented locally; initial publication authorized on 2026-09-15

## Outcome

The al-folio starter is configured as a simple personal site for Leon Cheung.
The public navigation contains About, Blog, and Projects. The homepage uses
Leon's photograph and the supplied Reze image, while the template identity,
sample posts, sample projects, and unrelated demo pages have been removed.

The site is configured for `https://leoncheung033.github.io` with an empty
`baseurl`. It builds and renders locally, including responsive image variants.
Embedded EXIF metadata has been removed from both site-ready images.

The public copy is Chinese-first while keeping established technical terms in
English. The homepage identifies Leon as an HKUST(GZ) AI MPhil, ByteDancer, and
LLM algorithm engineer.

## Verification

- `npm run lint:prettier` passes.
- `npm run lint:style-contract` passes.
- The Jekyll Docker build passes.
- `bundle exec al-folio upgrade audit --no-fail` reports zero blocking and zero
  non-blocking findings.
- Local checks confirm the home, Blog, and Projects pages render without the
  default al-folio identity or sample content.

## Publication boundary

This checkout remains under AgentEval's ignored `references/` directory. Leon
authorized creation of the public repository, upload of the site images, and
initial GitHub Pages deployment on 2026-09-15. Every later push or publication
change requires fresh explicit authorization.

The Reze image is user-supplied. Its source, public-use rights, and any required
attribution remain the site owner's responsibility.
