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

Cloudflare Pages is currently verified at its default hostname. Netlify is the verified backup deployment. The custom domain `extend-lines.com` is not attached to the Pages project and its DNS has been observed pointing to a Namecheap parking destination; do not change its records without confirming the intended domain use.

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

## Approved sub-niche intelligence workflow

Before building a microsite, evaluate the proposed service and market using this workflow:

1. Understand the niche, service, customer intent, and real-world context.
2. Analyze demand, including search volume, frequency, stability, and lead potential.
3. Evaluate competition, including large brands and the opportunity for smaller businesses.
4. Assess Google Map Pack difficulty, including ads, major brands, and local competition.
5. Check organic slot availability beneath AI Overview and determine whether organic results remain viable.
6. Estimate ticket price and lead value. Give priority to niches where a qualified lead has meaningful commercial value.
7. Evaluate seasonality and distinguish stable year-round demand from short seasonal spikes.
8. Assess leasing potential and whether local business owners may pay monthly for qualified leads.
9. Generate exact-match domain (EMD) ideas based on the niche and target city. Treat EMDs as validation and branding inputs, not a guarantee of ranking.
10. Evaluate nearby cities for lower competition and stronger opportunity.
11. Run competitor reconnaissance to identify what ranking sites do well, what they omit, and what useful gaps can be served.
12. Score the niche from 1–10 based on demand, competition, map difficulty, organic opportunity, ticket value, seasonality, and leasing potential.
13. Make a plain build/avoid decision with explicit reasoning and red flags.
14. Recommend the strongest domain from the generated list.
15. Recommend the best city based on opportunity and commercial potential.
16. Recommend the microsite angle, such as emergency messaging, pricing clarity, insurance guidance, or another truthful positioning strategy.
17. Deliver a concise final summary containing:
   - risk score
   - build/avoid decision
   - red flags
   - opportunities
   - recommended domain
   - recommended city
   - recommended microsite angle

Research conclusions must be evidence-based and current. Do not invent search volumes, rankings, reviews, businesses, map results, demand, or customer outcomes. Clearly label estimates, assumptions, and information that still needs verification.

## Pilot SERP validation and launch playbook

Use this transcript-derived method as a set of hypotheses to test, not as proof that any tactic guarantees rankings or revenue:

1. **Inspect the actual search results before committing.** Record the target query, location, date, device/context, and visible result features: ads, AI Overviews, local/map results, directories, major brands, and independent local sites. Estimate whether meaningful organic visibility is available and label the assessment as a snapshot.
2. **Compare more than one query or nearby market when uncertain.** Prefer a small pilot where demand is credible and the results show a realistic opening. Treat relative difficulty as an estimate, not a promise that a “light” result set will rank quickly.
3. **Plan the complete useful site before launch.** Publish only when the core pages, navigation, contact route, metadata, mobile layout, working assets, and factual review are ready. A sitemap and Search Console can support discovery and measurement, but neither guarantees indexing or rankings.
4. **Align page titles, headings, URLs, and copy with the service and place naturally.** Use terms where they accurately describe the page and help visitors. Do not repeat exact-match phrases unnaturally, create near-duplicate city pages, or build pages solely to funnel ranking signals to a homepage.
5. **Make every location or service page materially useful and truthful.** Include genuinely specific coverage, service details, limitations, pricing or estimate information when known, and a clear contact path. Do not imply a local office, staff, license, availability, or completed work that does not exist.
6. **Use profiles only for a real eligible business or organization.** Keep name, address/service area, phone, and website details accurate and consistent where those profiles are permitted. Do not create fake businesses or listings, fabricate identities, or mass-create profiles to simulate authority.
7. **Pursue relevant, editorially legitimate mentions and links.** Examples include real trade associations, local organizations, community publications, or genuine partner references. Avoid link schemes, purchased spam links, irrelevant high-authority placements, and self-created directories intended to manipulate rankings.
8. **Measure consistently over a meaningful period.** Track query, location, date, rank/source, indexing, qualified visits, calls/forms, and lead quality. Use Search Console and analytics where available; rank checks are variable by location, device, and personalization. Early movement—including a six-day contest result—is not durable evidence of ranking or business viability.
9. **Decide whether to continue based on evidence.** Compare the pilot’s actual qualified leads, conversion, operating costs, and competition against the original assumptions before expanding to additional cities or niches.

Transcript claims such as “rank any website,” rapid ranking, domain-name ranking advantages, or borrowed authority must be treated as speaker claims unless independently substantiated. Exact-match domains may be considered for clarity and branding, but are not a ranking guarantee. Preserve useful strategic ideas while prioritizing search-engine guidelines, truthful representation, and visitor value.

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
