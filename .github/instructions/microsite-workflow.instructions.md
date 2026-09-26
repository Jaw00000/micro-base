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

## Portfolio business plan and stage gates

The goal is a sustainable portfolio of useful, focused websites—not a high count of near-duplicate domains. The business model, target customer, offer, and preferred markets are not yet finalized. Do not assume them; compare options with the user before committing to a pilot.

### Stage 0: choose the business model

For each proposed venture, document:

- Who pays, who receives the service, and who actually performs it.
- The offer and value to the customer.
- How the site earns revenue: a service business, contracted marketing/site service, disclosed referral/affiliate arrangement, or another explicit model.
- Who owns the brand, domain, site, leads, customer relationship, and data.
- How leads are qualified, routed, consented to where required, followed up, and handled when the provider cannot serve them.
- Startup and recurring costs, expected revenue assumptions, operating work, and the evidence behind each assumption.
- What must be verified with the user, provider, accountant, attorney, or regulator before launch.

Do not describe a lead-generation site as the local service provider when it is only an intermediary. Make the operator/referral relationship understandable to visitors, and verify applicable advertising, privacy, consumer-protection, and sector rules before collecting or selling leads.

Substantiate objective advertising claims before publication. Keep reviews and testimonials genuine; disclose material referral, sponsorship, or affiliate relationships clearly near the relevant recommendation. Before a lead form is submitted, explain who operates it, why information is collected, and who may receive it where applicable. Do not imply that a quote or service comes from one provider if the inquiry will be routed to multiple providers.

### Stage 1: discover and prioritize opportunities

1. Gather candidate niches and places from the user's strategy, observed customer problems, credible market sources, and provider conversations.
2. For each candidate, assess demand, customer urgency, service value, seasonality, competition and SERP composition, map-pack eligibility/difficulty, realistic provider availability, and geographic coverage.
3. Identify actual prospective providers/partners and validate that they can answer, qualify, and fulfill inquiries in the proposed territory. Do not infer partner demand from search volume alone.
4. Use source types appropriate to the question: Search Console/keyword tools and live SERPs for search signals; Census and BLS data for demographic/economic context; state/local licensing boards and permit offices for service eligibility; provider interviews and records for actual capacity and economics. None of these is a substitute for another, and no single source proves market profitability.
5. Record citations, observation date, geography, assumptions, confidence, and unresolved questions. Separate measured facts, third-party claims, estimates, and hypotheses.
6. Use the sub-niche risk score as a prioritization aid, not a forecast. Explain what evidence would change the score. A candidate cannot pass merely because an exact-match domain is available or the SERP appears weak.
7. Create a build/hold/avoid recommendation. No domain purchase, service commitment, paid campaign, or public claim without the user's approval.

### Stage 2: validate economics and fulfillment before building

Make the pilot's economics explicit before incurring costs:

- One-time costs: domain, design/development, content/review, setup, and any required professional advice.
- Recurring costs: hosting, domain renewal, software, analytics, maintenance, support, and acquisition/fulfillment costs.
- Revenue model: contract/site fee, agreed qualified-lead price, referral commission, or actual service revenue; write down assumptions and payment timing.
- Lead funnel: visits → inquiries → valid/qualified leads → provider-accepted leads → booked work or sales → collected revenue.
- Unit economics: revenue actually collected minus variable and attributable costs; report fixed costs separately and calculate a break-even point only from disclosed assumptions.
- Risks: weak search demand, no eligible/available provider, low lead acceptance, unresponsive follow-up, legal restrictions, seasonality, domain/platform dependency, and inaccurate claims.

Where practical, validate through direct conversations and written provider terms before launch. Agree what counts as a valid lead, service area, response expectations, attribution, refunds/disputes, data handling, ownership, termination, and whether exclusivity applies. Do not claim forecast revenue, ranking, or lead volume as fact.

### Stage 3: build one pilot to a reusable standard

1. Select one niche, one initial market, one real offer, one fulfillment arrangement, and one primary conversion action.
2. Use the smallest site that fully serves customer needs. A small site may have a focused home/service page, provider/about and coverage information, useful answers, and a clear contact path; add pages only where they serve distinct needs.
3. Use the current static HTML/CSS/JavaScript base for the pilot unless evidence justifies another platform. Keep content, market facts, contact details, metadata, and brand configuration separate from reusable layout where the implementation supports it.
4. Before scaling, extract a template/configuration approach only after learning what must vary. Do not generate city pages by swapping names or publish separate domains to capture similar queries and funnel users to one destination.
5. Verify all content with the actual operator/provider. Include honest disclosures, service limitations, proof, contact ownership, privacy information, and required consent choices based on the actual data flow and applicable law.
6. Minimize collected lead data. Inventory form fields, analytics/ad tags, vendors, access, and retention; never send names, emails, phone numbers, or sensitive form answers into analytics events or URLs. Document the form/consent text shown and the user's action where appropriate, and define deletion, opt-out, and incident-response procedures.
7. Treat channels separately: commercial email must be reviewed against CAN-SPAM; marketing calls/texts require a separate review of current federal/state rules, consent, technology, recipient, and message. Do not rely on a generic contact checkbox as universal permission for marketing.
8. Complete the launch checklist in the pilot SERP playbook, including accessibility basics (keyboard use, labels, contrast, image text alternatives), mobile usability, secure forms, working links, indexability, and deploy verification. Use WCAG 2.2 AA as a practical engineering target, not a claim that this alone satisfies every legal duty.
9. Before a brand/domain purchase, check domain availability, similar trademarks and marketplace usage, renewal costs, and likely confusion; domain availability alone is not trademark clearance. Before each new state or country, re-check licenses, advertising/privacy/consent rules, taxes, language/cultural fit, and local fulfillment.

### Stage 4: launch, observe, and improve

Record a dated baseline before launch: target queries and geography, observed SERP features, competitor types, existing domain/site status, provider response capacity, costs, and assumptions. After launch, use Search Console and analytics where appropriate and track:

- Technical: deployment availability, HTTPS, status codes, crawl/index state, broken links/assets, and form delivery.
- Search: impressions, clicks, queries, landing pages, and contextual rank observations; rankings vary and are not the business outcome.
- Conversion: calls/forms, valid and qualified leads, provider acceptance, response time, bookings/sales, and collected revenue.
- Economics: spend, recurring cost, cost per qualified/accepted lead, contribution after variable costs, and outstanding receivables.
- Quality/compliance: complaints, opt-outs, inaccurate claims, consent records where applicable, security/privacy events, and provider/customer feedback.

Review at agreed operational intervals (for example, monthly); do not treat a fixed interval as an SEO-results guarantee. Diagnose the funnel: low impressions calls for checking demand/indexing/content and competition; traffic without inquiries suggests intent/offer/UX mismatch; inquiries without provider acceptance suggests qualification, routing, coverage, or partner fit. Change one major hypothesis at a time where feasible and log the change/date.

### Stage 5: scale only after a documented go decision

Before cloning or opening another market, require evidence that:

- The offer is legitimate, fulfillable, and useful to the target audience.
- The pilot has working operations and a measured conversion/lead process.
- Actual costs, accepted leads, and collected revenue support the user's chosen economics.
- Search/content performance is based on enough relevant observations to inform a decision, not a short ranking spike.
- The new location is genuinely served and each page/site will add distinct, accurate value.
- The user approves the next investment and any new domain, provider, market, or data collection.

If these conditions are not met, improve, pause, or stop the pilot rather than multiplying it. Record the decision and learning so later sites reuse proven components without copying thin content.

### Portfolio operations and source of truth

Maintain a portfolio register for each site with: internal site ID; business model; niche/market; audience/offer; operating provider and authorization; owner of site/domain/leads; domain registrar and renewal date; DNS host; repository/branch; production and backup URL; launch/version dates; Search Console/analytics ownership; costs and revenue assumptions/results; privacy/consent data flow; risks; and current status/next decision.

Keep credentials, tokens, customer lead data, transcripts containing personal data, contracts, and private business plans out of this public repository. Use a private repository or access-controlled storage for confidential operational records. The public base repository may hold generic templates and non-sensitive process instructions. Back up important records and use least-privilege access.

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
- [U.S. FTC advertising and marketing guidance](https://www.ftc.gov/business-guidance/advertising-marketing)
- [FTC endorsement guides: what people are asking](https://www.ftc.gov/business-guidance/resources/ftcs-endorsement-guides-what-people-are-asking)
- [FTC advertising FAQs for small businesses](https://www.ftc.gov/business-guidance/resources/advertising-faqs-guide-small-business)
- [FTC Consumer Reviews and Testimonials Rule Q&A](https://www.ftc.gov/business-guidance/resources/consumer-reviews-testimonials-rule-questions-answers)
- [FTC CAN-SPAM compliance guide](https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business)
- [FTC guide to protecting personal information](https://www.ftc.gov/business-guidance/resources/protecting-personal-information-guide-business)
- [FCC guide to unwanted robocalls and texts](https://www.fcc.gov/consumers/guides/stop-unwanted-robocalls-and-texts)
- [Federal rules for telemarketing calls and texts, 47 C.F.R. § 64.1200](https://www.ecfr.gov/current/title-47/section-64.1200)
- [California Privacy Protection Agency FAQ](https://cppa.ca.gov/faq.html)
- [Google Analytics privacy and data collection](https://support.google.com/analytics/answer/6004245)
- [Google Analytics regional controls](https://support.google.com/analytics/answer/12017362)
- [U.S. DOJ ADA web accessibility guidance](https://www.ada.gov/resources/web-guidance/)
- [W3C WCAG standards](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [USPTO trademark search](https://www.uspto.gov/trademarks/search)
- [ICANN domain lookup](https://lookup.icann.org/en)
- [U.S. Census Bureau QuickFacts](https://www.census.gov/quickfacts/)
- [BLS Occupational Employment and Wage Statistics](https://www.bls.gov/oes/)
- [U.S. Small Business Administration: licenses and permits](https://www.sba.gov/business-guide/launch-your-business/apply-licenses-permits)
- [EU General Data Protection Regulation, Article 3](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- [European Commission: data-protection obligations for businesses](https://commission.europa.eu/law/law-topic/data-protection/information-business-and-organisations_en)

These sources are a starting point, not legal advice or a substitute for jurisdiction- and industry-specific review. Before an international launch, research the destination's language and cultural context, local search ecosystem, consumer/advertising rules, privacy and consent requirements, taxes, domain rules, and service-provider licensing. Use qualified local advice for legal or tax decisions.

The strategy's specific objectives, including which service to offer, which business model to use, target markets, spending limits, and minimum acceptable unit economics, require the user's decisions. No search tactic, market score, or automation can substitute for those choices or guarantee rankings, leads, or revenue.

## Pending decisions to capture

The operating process is documented, but these owner decisions remain open. Ask one decision at a time when execution depends on them; use evidence-based options and label recommendations:

- Business model and who fulfills each offer
- Target customer, initial service niche, and pilot U.S. market
- Available startup/operating budget and acceptable risk
- How leads will be fulfilled, transferred, attributed, and compensated
- Approved brand/site format, required sections, and content voice
- Domain and brand naming criteria
- Analytics, lead quality, and go/no-go thresholds
- Preferred rollout process and who approves publishing, spending, and outreach
- Target countries/languages and localization priorities before international expansion
- Industry- and jurisdiction-specific legal, licensing, privacy, advertising, and tax review
