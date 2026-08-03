# Anrok (anrok)

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
