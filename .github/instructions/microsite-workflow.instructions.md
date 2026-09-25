---
description: Project context and workflow for building, deploying, and scaling the Micro Base microsite system.
applyTo: '**'
---

# Micro Base project instructions

## Purpose

This repository is the base for a repeatable microsite system. The long-term goal is to create focused sites for specific U.S. markets and later expand to international markets without losing a consistent structure, quality standard, or deployment process.

The user will provide the approved site format, business methods, target markets, and audience strategy over time. Preserve those decisions here when they are provided.

## Current project

- Repository: `Jaw00000/micro-base`
- Branch: `main`
- Local folder: `microsite-empire` (the folder name is historical and does not change the public project identity)
- Site type: plain static HTML, CSS, and JavaScript
- Current files:
  - `index.html` - page structure and content
  - `style.css` - presentation
  - `script.js` - browser behavior

## Deployment references

- GitHub: `https://github.com/Jaw00000/micro-base`
- Netlify production site: `https://harmonious-lokum-a6459a.netlify.app/`
- Netlify project: `harmonious-lokum-a6459a`
- Cloudflare Pages project: `micro-base`
- Cloudflare default hostname: `https://micro-base.pages.dev/`
- Custom domain available in Cloudflare: `extend-lines.com`

Netlify is the currently verified backup deployment. Cloudflare Pages previously returned 522 errors and should be diagnosed before being treated as the primary production host.

## Required workflow

1. Inspect the current files, Git status, and deployment configuration before changing anything.
2. Make focused changes that match the approved site format and target audience.
3. Keep `index.html`, `style.css`, and `script.js` correctly linked and test their paths.
4. Validate HTML/CSS/JavaScript changes and check for broken links, missing assets, encoding problems, and responsive behavior.
5. Never commit passwords, API keys, private documents, tracking secrets, or other credentials.
6. Commit related changes with a clear message and push to `main` only when the user has approved the change or asked for implementation.
7. Verify the deployment URL after publishing. Do not assume a successful Git push means hosting succeeded.
8. Record meaningful architecture, market, branding, SEO, and deployment decisions in this file or in a directly related repository document.

## Microsite scaling rules

- Prefer reusable components, templates, content fields, and configuration over copying ad-hoc pages.
- Every location-specific site must use truthful location and service claims.
- Do not create fake reviews, misleading business identities, doorway pages, spam, or deceptive local signals.
- Keep market-specific content, SEO metadata, calls to action, contact details, and legal requirements explicit.
- Test one pilot market before multiplying the same approach across many locations.
- Keep a clear distinction between the base template and site-specific content so future sites can be generated consistently.

## Pending decisions to capture

When the user supplies the business method or site format, document:

- Target customer and offer
- Geographic selection method
- Site sections and required fields
- Branding and design rules
- Lead or contact workflow
- SEO and analytics standards
- Domain naming and deployment conventions
- Internationalization and localization rules
- Compliance, privacy, and advertising requirements
