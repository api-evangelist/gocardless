# GoCardless

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

GoCardless is a global account-to-account payments platform specializing in pull-based bank debit (UK Bacs, SEPA Direct Debit, ACH, BECS, PAD, Autogiro) and open-banking instant bank payments, used by businesses to collect recurring subscriptions, invoices, and one-off payments directly from customer bank accounts. The GoCardless REST API exposes customers, bank accounts, mandates, payments, payouts, subscriptions, refunds, events, webhooks, and verification flows. Authentication uses Bearer access tokens issued from the dashboard, with separate sandbox and live environments; every request must include a GoCardless-Version header.

**Areas:** Payments · Direct Debit · Bank Debit · Recurring Payments · Subscription · SEPA · Bacs · ACH · Open Banking · Fintech

## GoCardless on APIs.io

Everything profiled for GoCardless is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gocardless/](https://apis.io/providers/gocardless/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [GoCardless Billing Request Flows API](https://apis.io/apis/gocardless/gocardless-billing-request-flows-api/) — The billing_request_flows API from GoCardless — 2 operation(s) for billing_request_flows.
- [GoCardless Billing Requests API](https://apis.io/apis/gocardless/gocardless-billing-requests-api/) — The billing_requests API from GoCardless — 2 operation(s) for billing_requests.
- [GoCardless Blocks API](https://apis.io/apis/gocardless/gocardless-blocks-api/) — The blocks API from GoCardless — 2 operation(s) for blocks.
- [GoCardless Creditor Bank Accounts API](https://apis.io/apis/gocardless/gocardless-creditor-bank-accounts-api/) — The creditor_bank_accounts API from GoCardless — 1 operation(s) for creditor_bank_accounts.
- [GoCardless Creditors API](https://apis.io/apis/gocardless/gocardless-creditors-api/) — The creditors API from GoCardless — 2 operation(s) for creditors.
- [GoCardless Customer Bank Accounts API](https://apis.io/apis/gocardless/gocardless-customer-bank-accounts-api/) — The customer_bank_accounts API from GoCardless — 2 operation(s) for customer_bank_accounts.
- [GoCardless Customers API](https://apis.io/apis/gocardless/gocardless-customers-api/) — The customers API from GoCardless — 2 operation(s) for customers.
- [GoCardless Events API](https://apis.io/apis/gocardless/gocardless-events-api/) — The events API from GoCardless — 2 operation(s) for events.
- [GoCardless Instalment Schedules API](https://apis.io/apis/gocardless/gocardless-instalment-schedules-api/) — The instalment_schedules API from GoCardless — 2 operation(s) for instalment_schedules.
- [GoCardless Institutions API](https://apis.io/apis/gocardless/gocardless-institutions-api/) — The institutions API from GoCardless — 1 operation(s) for institutions.
- [GoCardless Mandates API](https://apis.io/apis/gocardless/gocardless-mandates-api/) — The mandates API from GoCardless — 3 operation(s) for mandates.
- [GoCardless Payer Authorisations API](https://apis.io/apis/gocardless/gocardless-payer-authorisations-api/) — The payer_authorisations API from GoCardless — 2 operation(s) for payer_authorisations.
- [GoCardless Payments API](https://apis.io/apis/gocardless/gocardless-payments-api/) — The payments API from GoCardless — 3 operation(s) for payments.
- [GoCardless Payouts API](https://apis.io/apis/gocardless/gocardless-payouts-api/) — The payouts API from GoCardless — 2 operation(s) for payouts.
- [GoCardless Refunds API](https://apis.io/apis/gocardless/gocardless-refunds-api/) — The refunds API from GoCardless — 2 operation(s) for refunds.
- [GoCardless Subscriptions API](https://apis.io/apis/gocardless/gocardless-subscriptions-api/) — The subscriptions API from GoCardless — 3 operation(s) for subscriptions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [GoCardless Webhooks](https://apis.io/asyncapis/gocardless/gocardless-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/gocardless/untitled/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [gocardless](https://apis.io/servers/gocardless/gocardless/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gocardless Agentic Access](https://apis.io/agentic-access/gocardless/gocardless-agentic-access/)

#### Collections (17)

Postman and Open Collection request collections.

- [GoCardless REST API](https://apis.io/collections/gocardless/open-gocardless/)
- [GoCardless REST billing_request_flows API](https://apis.io/collections/gocardless/open-gocardless-billing-request-flows-api/)
- [GoCardless REST billing_request_flows billing_requests API](https://apis.io/collections/gocardless/open-gocardless-billing-requests-api/)
- [GoCardless REST billing_request_flows blocks API](https://apis.io/collections/gocardless/open-gocardless-blocks-api/)
- [GoCardless REST billing_request_flows creditor_bank_accounts API](https://apis.io/collections/gocardless/open-gocardless-creditor-bank-accounts-api/)
- [GoCardless REST billing_request_flows creditors API](https://apis.io/collections/gocardless/open-gocardless-creditors-api/)
- [GoCardless REST billing_request_flows customer_bank_accounts API](https://apis.io/collections/gocardless/open-gocardless-customer-bank-accounts-api/)
- [GoCardless REST billing_request_flows customers API](https://apis.io/collections/gocardless/open-gocardless-customers-api/)
- [GoCardless REST billing_request_flows events API](https://apis.io/collections/gocardless/open-gocardless-events-api/)
- [GoCardless REST billing_request_flows instalment_schedules API](https://apis.io/collections/gocardless/open-gocardless-instalment-schedules-api/)
- [GoCardless REST billing_request_flows institutions API](https://apis.io/collections/gocardless/open-gocardless-institutions-api/)
- [GoCardless REST billing_request_flows mandates API](https://apis.io/collections/gocardless/open-gocardless-mandates-api/)
- [GoCardless REST billing_request_flows payer_authorisations API](https://apis.io/collections/gocardless/open-gocardless-payer-authorisations-api/)
- [GoCardless REST billing_request_flows payments API](https://apis.io/collections/gocardless/open-gocardless-payments-api/)
- [GoCardless REST billing_request_flows payouts API](https://apis.io/collections/gocardless/open-gocardless-payouts-api/)
- [GoCardless REST billing_request_flows refunds API](https://apis.io/collections/gocardless/open-gocardless-refunds-api/)
- [GoCardless REST billing_request_flows subscriptions API](https://apis.io/collections/gocardless/open-gocardless-subscriptions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [GoCardless — asyncapi rules](https://apis.io/rules/gocardless/gocardless-asyncapi-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Gocardless Authentication](https://apis.io/security/gocardless/gocardless-authentication/)
- [Gocardless Domain Security](https://apis.io/security/gocardless/gocardless-domain-security/)
- [Gocardless Trust Center](https://apis.io/security/gocardless/gocardless-trust-center/)
- [Gocardless Vulnerability Disclosure](https://apis.io/security/gocardless/gocardless-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Gocardless Scopes](https://apis.io/scopes/gocardless/gocardless-scopes/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Gocardless Plans Pricing](https://apis.io/plans/gocardless/gocardless-plans-pricing/)
- [Gocardless Price Estimates](https://apis.io/plans/gocardless/gocardless-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Gocardless Rate Limits](https://apis.io/rate-limits/gocardless/gocardless-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://gocardless.com)
- [Documentation](https://developer.gocardless.com)
- [Pricing](https://gocardless.com/pricing/)
- [Support](https://hub.gocardless.com)
- [Blog](https://gocardless.com/blog/)
- [GitHub](https://github.com/gocardless)
- [Status](https://www.gocardless-status.com)

## API Evangelist rating

**Kin Score 50.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 52.8 |
| Contract governance | 11.4 |
| Operational transparency | 44.7 |
| Developer ergonomics | 45.2 |
| Access clarity | 63.2 |

**Agent readiness 51.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
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

**Regulatory alignment 31.5** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gocardless/](https://apis.io/providers/gocardless/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for GoCardless: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gocardless/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
