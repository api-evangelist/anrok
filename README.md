# Anrok

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Anrok is a SaaS-focused global sales tax and VAT compliance platform built for modern commerce. It provides a REST API that enables software companies to calculate sales tax in real time, manage nexus registrations across 11,000+ US jurisdictions, handle exemption certificates, and validate customer tax IDs. The platform integrates with billing systems such as Stripe, Chargebee, and Recurly, and automates tax filing and remittance across 100+ countries. Anrok also offers Anrok Atlas, an AI-native agentic tax partner for proactive compliance monitoring.

**Areas:** Sales Tax · VAT · Tax Compliance · Software-as-a-Service · Fintech · Tax Automation · Nexus · E-Invoicing · Tax

## Anrok on APIs.io

Everything profiled for Anrok is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anrok/](https://apis.io/providers/anrok/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Anrok Customer certificates API](https://apis.io/apis/anrok/anrok-customer-certificates-api/) — A sales tax exemption certificate documents the exemption claimed by a purchaser to legally make a tax-free purchase. Certificates can be uploaded to Anrok…
- [Anrok Filings API](https://apis.io/apis/anrok/anrok-filings-api/) — **The Filings endpoint is a premium feature. Please contact hello@anrok.com for more information to enable this on your seller account.** This endpoint can…
- [Anrok Product mappings API](https://apis.io/apis/anrok/anrok-product-mappings-api/) — The Anrok Product Mappings API endpoint allows you to dynamically map product IDs for [Anrok-built billing system…
- [Anrok Products API](https://apis.io/apis/anrok/anrok-products-api/) — The Anrok Products API endpoints allow you to manage the products on your seller account. Each product is identified by an external ID and is assigned a…
- [Anrok Tax ID validation API](https://apis.io/apis/anrok/anrok-tax-id-validation-api/) — **The Anrok Tax ID Validation endpoint is a premium feature. Please contact hello@anrok.com for more information to enable this on your Anrok seller…
- [Anrok Transactions API](https://apis.io/apis/anrok/anrok-transactions-api/) — This documentation describes how to use Anrok's Transactions API to synchronize transactions between Anrok and your billing system, as well as calculate…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [anrok](https://apis.io/servers/anrok/anrok/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anrok Agentic Access](https://apis.io/agentic-access/anrok/anrok-agentic-access/)

#### JSON Schema (33)

The data models the API reads and writes.

- [CommonTransactionProperties](https://apis.io/schemas/anrok/common-transaction-properties/)
- [CreateEphemeralTransaction](https://apis.io/schemas/anrok/create-ephemeral-transaction/)
- [CreateEphemeralTransactionSuccess](https://apis.io/schemas/anrok/create-ephemeral-transaction-success/)
- [CreateOrUpdateTransaction](https://apis.io/schemas/anrok/create-or-update-transaction/)
- [CreateOrUpdateTransactionSuccess](https://apis.io/schemas/anrok/create-or-update-transaction-success/)
- [CreateProduct](https://apis.io/schemas/anrok/create-product/)
- [CreateTransactionCannotComputeTaxAmount](https://apis.io/schemas/anrok/create-transaction-cannot-compute-tax-amount/)
- [CreateTransactionCannotUpdate](https://apis.io/schemas/anrok/create-transaction-cannot-update/)
- [Address](https://apis.io/schemas/anrok/customer-address/)
- [CustomerCertificate](https://apis.io/schemas/anrok/customer-certificate/)
- [CustomerCertificateFile](https://apis.io/schemas/anrok/customer-certificate-file/)
- [CustomerCertificateJuris](https://apis.io/schemas/anrok/customer-certificate-juris/)
- [CustomerCertificateJurisResponse](https://apis.io/schemas/anrok/customer-certificate-juris-response/)
- [CustomerCertificateResponse](https://apis.io/schemas/anrok/customer-certificate-response/)
- [CustomerId](https://apis.io/schemas/anrok/customer-id/)
- [Legacy US only address](https://apis.io/schemas/anrok/customer-legacy-us-only-address/)
- [CustomerName](https://apis.io/schemas/anrok/customer-name/)
- [CustomerTaxId](https://apis.io/schemas/anrok/customer-tax-id/)
- [FilingInfoFilter](https://apis.io/schemas/anrok/filing-info-filter/)
- [JurisSummary](https://apis.io/schemas/anrok/juris-summary/)
- [LastModifiedAfterFilter](https://apis.io/schemas/anrok/last-modified-after-filter/)
- [LineItem](https://apis.io/schemas/anrok/line-item/)
- [LineItemJurisTax](https://apis.io/schemas/anrok/line-item-juris-tax/)
- [NormalTransactionBody](https://apis.io/schemas/anrok/normal-transaction-body/)
- [NormalTransactionResponse](https://apis.io/schemas/anrok/normal-transaction-response/)
- …and 8 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Anrok Context](https://apis.io/jsonld/anrok/anrok-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Anrok Vocabulary](https://apis.io/vocabularies/anrok/anrok-vocabulary/)

#### Examples (7)

Example requests and responses.

- [Conflict Accounting Time Zone Not Set For Seller](https://apis.io/examples/anrok/conflict-accounting-time-zone-not-set-for-seller/)
- [Conflict Product External Id Unknown](https://apis.io/examples/anrok/conflict-product-external-id-unknown/)
- [Conflict Tax Date Too Far In Future](https://apis.io/examples/anrok/conflict-tax-date-too-far-in-future/)
- [Conflict Tax Date Too Far In Past](https://apis.io/examples/anrok/conflict-tax-date-too-far-in-past/)
- [Create Certificate Request](https://apis.io/examples/anrok/create-certificate-request/)
- [Create Or Update Transaction Request](https://apis.io/examples/anrok/create-or-update-transaction-request/)
- [Validate Tax Id Request](https://apis.io/examples/anrok/validate-tax-id-request/)

#### Collections (6)

Postman and Open Collection request collections.

- [Anrok Customer certificates API](https://apis.io/collections/anrok/open-anrok-customer-certificates-api/)
- [Anrok Customer certificates Filings API](https://apis.io/collections/anrok/open-anrok-filings-api/)
- [Anrok Customer certificates Product mappings API](https://apis.io/collections/anrok/open-anrok-product-mappings-api/)
- [Anrok Customer certificates Products API](https://apis.io/collections/anrok/open-anrok-products-api/)
- [Anrok Customer certificates Tax ID validation API](https://apis.io/collections/anrok/open-anrok-tax-id-validation-api/)
- [Anrok Customer certificates Transactions API](https://apis.io/collections/anrok/open-anrok-transactions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Anrok — jsonschema rules](https://apis.io/rules/anrok/anrok-jsonschema-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Anrok Authentication](https://apis.io/security/anrok/anrok-authentication/)
- [Anrok Domain Security](https://apis.io/security/anrok/anrok-domain-security/)
- [Anrok Trust Center](https://apis.io/security/anrok/anrok-trust-center/)
- [Anrok Vulnerability Disclosure](https://apis.io/security/anrok/anrok-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Anrok Plans Pricing](https://apis.io/plans/anrok/anrok-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Anrok Rate Limits](https://apis.io/rate-limits/anrok/anrok-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Anrok Finops](https://apis.io/finops/anrok/anrok-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.anrok.com/)
- [Documentation](https://apidocs.anrok.com/)
- [Pricing](https://www.anrok.com/pricing)
- [Blog](https://anrok.com/resources/blog)
- [GitHub](https://github.com/Anrok)

## API Evangelist rating

**Kin Score 43.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 63.4 |
| Contract governance | 23.5 |
| Operational transparency | 18.4 |
| Developer ergonomics | 23.8 |
| Access clarity | 23.7 |

**Agent readiness 57.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anrok/](https://apis.io/providers/anrok/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Anrok: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anrok/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
