# GoCardless (gocardless)

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

GoCardless is a global account-to-account payments platform specializing in pull-based bank debit (UK Bacs, SEPA Direct Debit, ACH, BECS, PAD, Autogiro) and open-banking instant bank payments, used by businesses to collect recurring subscriptions, invoices, and one-off payments directly from customer bank accounts. The GoCardless REST API exposes customers, bank accounts, mandates, payments, payouts, subscriptions, refunds, events, webhooks, and verification flows. Authentication uses Bearer access tokens issued from the dashboard, with separate sandbox and live environments; every request must include a GoCardless-Version header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gocardless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gocardless/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Payments
- Direct Debit
- Bank Debit
- Recurring Payments
- Subscriptions
- SEPA
- Bacs
- ACH
- Open Banking
- Fintech

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### GoCardless REST API

Versioned REST API for collecting bank debit and open-banking payments worldwide. Resources include customers, customer bank accounts, mandates, payments, payouts, subscriptions, refunds, billing requests, events, and webhook endpoints. Authentication uses Bearer access tokens; a GoCardless-Version header is required on every request. Sandbox available at api-sandbox.gocardless.com.

- **Human URL:** [https://developer.gocardless.com/api-reference/](https://developer.gocardless.com/api-reference/)
- **Base URL:** `https://api.gocardless.com`

#### Tags

- Payments
- Direct Debit
- Subscriptions
- Bearer Auth
- Versioned API

#### Properties

- [Documentation](https://developer.gocardless.com/api-reference/)
- [OpenAPI](https://developer.gocardless.com/api-reference/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.gocardless.com/getting-started/set-up/)
- [Sandbox](https://api-sandbox.gocardless.com)
- [Postman  Collection](https://www.postman.com/gocardlessapi/gocardless-api/overview)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/gocardless/refs/heads/main/asyncapi/gocardless-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/gocardless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gocardless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/gocardless)
- [LinkedIn](https://www.linkedin.com/company/gocardless)
- [Website](https://gocardless.com)
- [Documentation](https://developer.gocardless.com)
- [Pricing](https://gocardless.com/pricing/)
- [Sign Up](https://manage.gocardless.com/signup)
- [Support](https://hub.gocardless.com)
- [Status Page](https://www.gocardless-status.com)
- [L L Ms Txt](https://developer.gocardless.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
