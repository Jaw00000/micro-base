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
- Do not create a Google Business Profile for a lead-generation agent or company; profiles are for eligible real-world businesses. A real service provider may authorize a representative to manage its profile under Google's rules.
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

1. **Qualify the opportunity before writing.** Inspect current search results for the target query and location. Record date, location/device context, ads, AI features, map results, directories, large brands, local providers, and the kinds of pages ranking. Compare nearby markets or related queries when the opportunity is uncertain. SERP composition is a snapshot, not a stable score or ranking guarantee.
2. **Reject doorway-network strategies.** Do not build multiple near-identical sites or city pages to capture query variations and funnel visitors to the same business or endpoint. Build a microsite only when it has a distinct, legitimate audience/offer and can provide standalone utility. A city/service page must contain genuinely useful details for that area, not just swapped place names.
3. **Design around customer tasks, then map pages.** Define the audience, offer, service limits, coverage, proof, conversion path, and unanswered customer questions. Create only the pages needed to serve those tasks. Use a crawlable hierarchy with ordinary `<a href>` links; make every page reachable from navigation or contextual links. Keep URLs simple and descriptive.
4. **Create original, credible content.** Use verified facts, real operating knowledge, and clear sourcing; identify who operates the site and who provides the service. Add information that helps a visitor decide or act, such as process, realistic coverage, limitations, estimate factors, safety/permit pointers where verified, and a working contact route. AI may accelerate drafts and structure, but a knowledgeable human must verify claims and add real value. Do not mass-produce lightly varied pages.
5. **Optimize accurately, not mechanically.** Give each page a concise descriptive title, clear main heading, and natural copy. Mention service and location where relevant, but avoid keyword stuffing or boilerplate titles. Exact-match domains can aid naming clarity; they should not be bought or selected on the assumption they confer a ranking advantage.
6. **Make the launch technically complete.** Before publishing, check HTTPS, mobile rendering, semantic HTML, titles/descriptions, status codes, canonical/robots settings, working navigation/contact/asset paths, and no accidental `noindex` or blocked crawling. Use a sitemap when useful—especially for a new site with few inbound links or a larger/complex set of pages—but a small well-linked site may not need one. Configure Search Console if available to inspect indexing and performance; submission/requesting a crawl is a discovery aid, not a ranking boost or guarantee.
7. **Use only legitimate business identities and profiles.** Google Business Profiles require an eligible real-world business with in-person customer contact; lead-generation agents or companies are ineligible. For a client's profile, act only with express authorization, keep the business owner in control, and use the owner's authoritative website and phone. Never invent a business, address, staff, reviews, service coverage, licenses, or profile to borrow trust.
8. **Earn relevance rather than manufacture authority.** Seek genuine mentions and links from relevant organizations, suppliers, community sources, and editorial publications. Avoid paid/manipulative link schemes, link exchanges intended to manipulate rankings, self-created directory networks, fake profiles, and third-party-host “parasite SEO” placements chosen mainly to exploit another site's ranking signals.
9. **Measure and iterate patiently.** Record query, locale, device, date, result type, index status, impressions/clicks, qualified visits, calls/forms, lead quality, and costs. Use Search Console and analytics where appropriate; rankings vary by context. Google says crawling may take days to weeks, and SEO changes can take from hours to several months to have an effect; repeated URL inspection requests do not make crawling faster. Evaluate a pilot over a meaningful period and expand only when observed demand, qualified leads, economics, and quality justify it.

Transcript claims such as “rank any website,” rapid ranking, domain-name ranking advantages, or borrowed authority must be treated as speaker claims unless independently substantiated. Exact-match domains may be considered for clarity and branding, but are not a ranking guarantee. Preserve useful strategic ideas while prioritizing search-engine guidelines, truthful representation, and visitor value.

### Independent review of the supplied transcript

Reviewed against first-party Google guidance on 2026-09-26. This assesses whether the proposed tactics are suitable for our strategy; it does not reproduce or independently verify the speaker's contest data.

- **Keep as sound process, not ranking guarantees:** inspect the live SERP and competition before choosing a query; test one pilot; launch a complete, working site; use clear page titles/headings and crawlable internal links; measure search visibility and qualified leads; seek genuinely relevant mentions.
- **Qualify:** a well-completed site and sitemap can help discovery and user experience, but do not guarantee indexing, rankings, or a fast result. A sitemap is optional for many small, well-linked sites. Google reports crawling may take days to weeks and changes can take hours to several months to affect search; a six-day contest snapshot is not evidence of durable ranking or revenue.
- **Do not use as a default tactic:** exact-match domains as a ranking shortcut; bulk “profile stacking” for borrowed authority; mass-published city/service permutations; or third-party host pages chosen mainly to exploit another site's ranking signals.
- **Policy-sensitive business model:** organic lead-generation sites are not automatically prohibited, but Google's Business Profile rules explicitly exclude lead-generation agents/companies from profile eligibility. Only represent an eligible real service provider, with its authorization and accurate owner-verifiable information.

### Evidence base

The workflow above is grounded primarily in current first-party Google documentation. The sources describe eligibility and policies; they do not promise a particular ranking outcome:

- [Google Search Essentials](https://developers.google.com/search/docs/essentials)
- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Google Search spam policies](https://developers.google.com/search/docs/essentials/spam-policies) — includes doorway abuse, scaled content abuse, link spam, and site reputation abuse
- [Google ranking systems guide: exact-match domain system](https://developers.google.com/search/docs/appearance/ranking-systems-guide#exact-match-domain-system)
- [Sitemap overview](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)
- [Ask Google to recrawl URLs](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl)
- [Get started with Search Console](https://developers.google.com/search/docs/monitor-debug/search-console-start)
- [SEO Starter Guide: how long changes take](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Crawlable link best practices](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [Title link best practices](https://developers.google.com/search/docs/appearance/title-link)
- [Google Search technical requirements](https://developers.google.com/search/docs/essentials/technical)
- [Google Business Profile eligibility and ownership](https://support.google.com/business/answer/13763036)
- [Google Business Profile representation guidelines](https://support.google.com/business/answer/3038177)
- [How to improve local ranking on Google](https://support.google.com/business/answer/7091)

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
