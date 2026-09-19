# Repository guidance

## Purpose

This repository contains Leo Jiang's public personal website. Maintain it as a clear, age-appropriate record of his piano performances, speed-skating progress, artwork, awards, and selected updates.

## Safety and privacy

Leo is a minor. Before publishing, remove or generalize:

- home or school addresses, daily schedules, travel plans, and real-time locations;
- birth date, student identifiers, registration numbers, private contact details, and medical information;
- certificates or photographs that expose sensitive information in the image or embedded metadata.

Use broad locations only when they add legitimate context to a past public event. Do not invent biographical facts, achievements, dates, results, quotations, or media rights. Ask Yu Jiang when a fact is unclear.

## Change workflow

- Work on a dedicated branch and submit a pull request; do not push content changes directly to `main`.
- Keep each pull request focused and describe the public-facing effect.
- Preserve the existing Jekyll structure unless a redesign is explicitly requested.
- Run `bundle exec jekyll build --trace` before requesting review.
- Treat the pull-request preview and diff as required review steps before publishing.
- Do not alter GitHub Pages configuration, domains, analytics, or external integrations without explicit approval.

## Content map

- `_posts/`: dated news, performances, competitions, and milestones.
- `about.md`: biography. Avoid school-grade wording that becomes stale; prefer durable phrasing.
- `awards.md`, `arts.md`, and `updates.md`: section entry points backed by custom layouts.
- `images/piano/`, `images/art/`, and `images/certificates/`: public media.
- `_layouts/`, `_includes/`, `_sass/`, and `assets/`: presentation and theme customizations.
- `_config.yml`: navigation, metadata, plugins, and social links.

## Writing and media

- Use concise, factual language and Leo's existing tone.
- Use ISO dates in post filenames: `YYYY-MM-DD-short-title.md`.
- Include descriptive alt text for meaningful images.
- Prefer optimized JPEG, PNG, or WebP assets below 1 MB when practical.
- Strip location metadata from photographs before publishing.
- Confirm ownership or permission before publishing recordings, artwork, certificates, or third-party photographs.
- Avoid unsupported superlatives and promotional claims.

## Verification

For content-only changes, verify:

1. Front matter is valid YAML.
2. Internal links and image paths exist.
3. Dates and event names match the supplied source.
4. The site builds with `bundle exec jekyll build --trace`.
5. The rendered change does not reveal sensitive information.

For layout or style changes, also review desktop and mobile rendering and confirm that existing pages remain usable.
