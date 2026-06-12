# Anrok (anrok)

Anrok is a SaaS-focused global sales tax and VAT compliance platform built for modern commerce. It provides a REST API enabling software companies to calculate sales tax in real time, manage nexus registrations across 11,000+ US jurisdictions, handle exemption certificates, and validate customer tax IDs. The platform integrates with billing systems such as Stripe, Chargebee, and Recurly and automates tax filing and remittance across 100+ countries. Anrok also offers Anrok Atlas, an AI-native agentic tax partner for proactive compliance monitoring.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/anrok/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anrok/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=anrok-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=anrok-api-evangelist&utm_content=repo)

## Tags

- Sales Tax
- VAT
- Tax Compliance
- SaaS
- Fintech
- Tax Automation
- Nexus
- E-Invoicing

## APIs

### Anrok API

The Anrok REST API enables real-time sales tax calculation, transaction management, exemption certificate handling, product tax category mapping, customer tax ID validation, and retrieval of sales tax filing information. All requests are HTTP POST with JSON bodies authenticated via Bearer token. The API is versioned at 1.1 and exposes an OpenAPI specification.

- Documentation: [https://apidocs.anrok.com/](https://apidocs.anrok.com/)
- Base URL: https://api.anrok.com
- Tutorials: [https://apidocs.anrok.com/tutorials](https://apidocs.anrok.com/tutorials)

## Plans / Rate Limits / FinOps

- Plans: [plans/anrok-plans-pricing.yml](plans/anrok-plans-pricing.yml)
- Rate Limits: [rate-limits/anrok-rate-limits.yml](rate-limits/anrok-rate-limits.yml)
- FinOps: [finops/anrok-finops.yml](finops/anrok-finops.yml)

**Pricing summary:** Starter at $100/market/month; Custom at $400/market/month + 0.25% per transaction. Add-on packages (Pro $500/mo, Enterprise $1,000/mo, Physical Nexus Monitoring $300/mo) billed annually.

**Rate limits:** 10 API requests per second per seller account. HTTP 429 returned when exceeded.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.anrok.com/ |
| Documentation | https://apidocs.anrok.com/ |
| GitHub Organization | https://github.com/Anrok |
| LinkedIn | https://www.linkedin.com/company/anrok |
| X | https://x.com/Anrok |
| Blog | https://anrok.com/resources/blog |
| Pricing | https://www.anrok.com/pricing |

## Maintainers

- Kin Lane / kin@apievangelist.com
