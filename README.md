# Payhawk (payhawk)

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
