# Payhawk (payhawk)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Payhawk is a spend management platform that enables finance teams to issue corporate cards, capture and manage expenses, process invoices, enforce budget controls, and integrate with ERP and accounting systems. The platform serves businesses across Europe, the US, and the UK in over 32 countries. Payhawk exposes a RESTful Developer API that allows custom integrations over expenses, transactions, cards, employees, custom fields, fund accounts, and bank statements. The API is authenticated via API key, supports real-time webhooks for event-driven automation, and is free for all account holders.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/payhawk/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=payhawk-api-evangelist&utm_content=repo

## Tags

- Spend Management
- Corporate Cards
- Expense Management
- Invoice Management
- Budget Controls
- ERP Integration
- Accounts Payable
- FinTech
- Finance Automation
- Webhooks

## APIs

| Name | Type | Base URL | Documentation |
|------|------|----------|---------------|
| Payhawk API | REST | https://api.payhawk.io/api/v3 | https://developers.payhawk.com/ |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/payhawk-plans-pricing.yml](plans/payhawk-plans-pricing.yml) |
| Rate Limits | [rate-limits/payhawk-rate-limits.yml](rate-limits/payhawk-rate-limits.yml) |
| FinOps Profile | [finops/payhawk-finops.yml](finops/payhawk-finops.yml) |

- **Plans:** Three tiers — Premium Cards, All-in-one Spend, Enterprise — all custom-quoted. Developer API is free for all account holders.
- **Rate Limits:** 15 requests per second globally; 429 with Retry-After header on breach; pagination default 1,000 items per page.
- **FinOps:** Subscription billing with no per-API-call charges; meters cover cards issued, active users, ERP integrations, and expense transactions.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://payhawk.com |
| Documentation | https://developers.payhawk.com/ |
| Help Center | https://payhawk.com/help/payhawk-for-developers |
| GitHub Organization | https://github.com/payhawk |
| LinkedIn | https://www.linkedin.com/company/payhawk |
| X / Twitter | https://x.com/payhawk |
| Blog | https://payhawk.com/blog |
| Pricing | https://payhawk.com/pricing |
| Status Page | https://status.payhawk.com |

## Maintainers

**Kin Lane** — kin@apievangelist.com
