# ML Systems — SEO Brief & Working Context

> **Purpose.** This file is a self-contained SEO context for ML Systems LLC. If you're an AI
> assistant helping Sal with search visibility, listings, content, or local SEO, read this plus
> `company-profile.json` (structured facts) and use `localbusiness-schema.jsonld` (drop-in
> structured data). Everything here is public marketing information — no proprietary financials,
> ontology, or gated data.

## Who / what

- **Business:** ML Systems LLC — a Rhode Island construction proptech company (NAICS 236115).
- **Founder:** Sal Parvez.
- **Tagline:** *Tougher Problems Inspire Creative Solutions.*
- **One-liner:** A closed-loop construction company that finances, deconstructs, designs, and
  builds — so every dollar compounds into equity, not interest, with near-zero waste.
- **Base:** Warwick, RI. **Serves:** all of Rhode Island (23 towns — see `company-profile.json`).

## The offer (value chain)

1. **Loan Origination** — a marketplace where lenders compete to fund the homeowner's build.
2. **Deconstruction** — recover up to 80–90% of a home's materials (target); reuse › resale › recycle.
3. **Construction** — rebuild larger on the same lot, reusing recovered materials.
4. **Equity loop** — completed construction creates equity to reinvest into the next cycle.

## Digital footprint

| Property | URL | Role |
|---|---|---|
| Marketing site | https://mlsystemsri.com | Primary SEO target |
| Live web app | https://try.mlsystemsri.com | Product demo |
| Store | https://mlsystemsri.store | Reclaimed materials e-commerce |
| Data / TTP | https://mlsystemsri.info | Metered data access (moat) |
| API | https://api.mlsystemsri.com | Developer/data product |
| GitHub showcase | https://github.com/MLSystemsRI/ml-systems-showcase | Public overview |
| Yelp | https://www.yelp.com/biz/ml-systems-warwick | Local citation |
| Facebook | https://www.facebook.com/people/ML-Systems/61584698819319/ | Social |
| Bizapedia | https://www.bizapedia.com/ri/ml-systems-llc.html | Business directory |

## Current SEO status (as of 2026-09)

**Done / working:**
- ✅ `mlsystemsri.com` is **indexed** by Google — homepage and `/insights` pages rank for topical queries.
- ✅ **Google Search Console verified** (DNS TXT `google-site-verification` present).
- ✅ **Sitemap live** at `/sitemap.xml` — 55 URLs (marketing pages, insights, 23 town pages).
- ✅ **robots.txt live** — allows search engines + real-time AI readers; blocks bulk AI-training crawlers.
- ✅ **Programmatic local SEO** — one value-chain landing page per RI town at `/value-chain/<slug>`,
  each with unique human-written housing-stock prose (clears Google's thin/doorway bar).
- ✅ **AI-readable context** — `/llms.txt` and `/ai-context.json` (public preview tranche).
- ✅ **Google Business Profile** — created (verify status in the GBP dashboard).
- ✅ Local citations exist on Yelp, Facebook, Bizapedia, BBB category.

**Open / highest-leverage next moves:**
1. **Confirm indexing coverage** — Search Console → Pages: verify all 55 sitemap URLs are indexed,
   not just a few. Fix any "Discovered – not indexed."
2. **Google Business Profile optimization** — photos (10+), weekly Posts, seeded Q&A, Products from
   the store, and a review-generation flow. GBP is the #1 local ranking lever.
3. **NAP consistency** — make Name/Address/Phone identical across GBP, Yelp, Facebook, BBB. Set ONE
   phone number first (currently a TODO in `company-profile.json`).
4. **Structured data** — add `localbusiness-schema.jsonld` to the site `<head>` for a richer result.
5. **Content velocity** — `/insights` posts already rank; publish more (see keyword list) to widen
   first-page coverage and earn long-tail traffic.
6. **Backlinks** — the strongest off-page signal. Target RI news, local directories, partners,
   green-building / circular-economy orgs.
7. **Own the SERP for the brand** — a similarly-named `mlconstructionri.com` also ranks for
   construction-in-RI queries; make sure ML Systems' owned properties fill page one for the brand.

## Target keywords

**Primary:** Rhode Island construction company · home deconstruction Rhode Island · construction
loans Rhode Island · reclaimed building materials Rhode Island · general contractor Warwick RI.

**Secondary:** deconstruction vs demolition · salvaged building materials near me · sustainable
home building RI · material recovery construction · build home equity Rhode Island · green
construction Rhode Island · custom home builder Rhode Island · construction financing homeowner.

**Long-tail (content ideas):** how to finance a home build in Rhode Island · companies that
deconstruct houses in RI · where to buy reclaimed lumber Rhode Island · deconstruction service
Warwick Rhode Island.

(Full lists in `company-profile.json` → `seoKeywords`.)

## Content angles that fit the brand

- Deconstruction vs demolition — cost, materials recovered, environmental impact.
- Construction financing guides for RI homeowners (loan origination, building equity).
- Reclaimed-material buying guides (lumber, doors, fixtures) — feeds the store.
- Town-specific housing-stock notes (already the basis of the 23 town pages).
- Sustainability / circular-economy angle — near-zero-waste building.

## Honesty guardrails (important for a public, review-able brand)

- **Material recovery 80–90% is a TARGET (modeled), not a completed result.** Phrase as "designed
  to recover up to 80–90%," never "we recover 80–90%," until there's a completed job to cite.
- **No completed-project claims or fabricated reviews** — Google/BBB penalize this and it risks
  profile suspension. Let real work generate real reviews.
- Deeper construction data (full ontology, per-material provenance, benchmarks) is **intentionally
  gated** via the Transparency Trust Protocol — do not publish it to chase SEO; it's a paid product.

## Quick reference for an assistant helping here

- Need business facts? → `company-profile.json`
- Need drop-in structured data? → `localbusiness-schema.jsonld`
- Need the product narrative / AI reading order? → `../llms.txt`, `../ai-context.json`
- Writing a GBP description or meta tag? → `company-profile.json` → `descriptionVariants`
