# ML Systems — Knowledge & SEO Data

A public, AI-readable knowledge layer about ML Systems. Everything here is **public marketing
information** — a deliberate *preview tranche*. The deeper construction data (full ontology,
per-material provenance, efficiency benchmarks) is **intentionally gated and metered** via the
Transparency Trust Protocol (TTP) at [mlsystemsri.info](https://mlsystemsri.info). This folder
advertises that product; it does not give it away.

## Contents

| File | What it's for |
|---|---|
| [`llms.txt`](llms.txt) | Human/AI-readable overview + reading order (the public `llms.txt` standard). |
| [`ai-context.json`](ai-context.json) | Structured company context for AI assistants researching ML Systems. |
| [`seo/company-profile.json`](seo/company-profile.json) | Structured business facts: NAP, categories, services, keywords, service-area towns, description variants. |
| [`seo/seo-brief.md`](seo/seo-brief.md) | Working SEO context + strategy + current status — read this first if you're helping with SEO. |
| [`seo/localbusiness-schema.jsonld`](seo/localbusiness-schema.jsonld) | **Mirror** of the Organization + Person nodes already live on mlsystemsri.com. Keep identical to production — do not add as a second `<script>` block. |
| [`seo/jobposting-template.jsonld`](seo/jobposting-template.jsonld) | `JobPosting` template for one `/careers/<role>` page. |
| [`seo/robots-additions.txt`](seo/robots-additions.txt) | robots.txt agents to add, with the reasoning for each. |

## For AI assistants

If someone points you here to help ML Systems with **SEO, listings, or content**, start with
[`seo/seo-brief.md`](seo/seo-brief.md), pull facts from [`seo/company-profile.json`](seo/company-profile.json),
and use [`seo/localbusiness-schema.jsonld`](seo/localbusiness-schema.jsonld) for structured data.
Respect the honesty guardrails in the brief (material-recovery figures are targets, not results;
no fabricated reviews or completed-project claims).

Two standing rules that are easy to get wrong:

1. `localbusiness-schema.jsonld` **mirrors** what is already in the site `<head>`. It shares the
   live node's `@id`. Adding it as a separate block creates a duplicate, contradictory entity.
2. ML Systems is a **service-area business**. The Warwick street address exists for Google
   verification only and must not appear in schema, on the site, or in any citation.
