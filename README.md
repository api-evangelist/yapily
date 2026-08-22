# Yapily (yapily)

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

Yapily is a UK-headquartered Open Banking platform that exposes a single REST API across 2,000+ banks in the UK and 18+ European countries. The platform provides AISP (Account Information) and PISP (Payment Initiation) capabilities, Variable Recurring Payments (VRP), transaction enrichment (Data Plus), Account Validation, and Hosted Payment/Consent Pages. Yapily Connect Ltd is FCA-authorised in the UK and Yapily Connect UAB is authorised by the Bank of Lithuania for EU coverage, allowing customers to launch without holding their own PSD2 permissions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yapily/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yapily/refs/heads/main/apis.yml)

## Tags

- Open Banking
- AISP
- PISP
- Payments
- Account Information
- Variable Recurring Payments
- Financial Services
- PSD2
- FCA
- Berlin Group
- UK
- Europe
- FinTech

## Timestamps

- **Created:** Sun May 24 2026 20:00:00 GMT-0400 (Eastern Daylight Time)
- **Modified:** Sun May 24 2026 20:00:00 GMT-0400 (Eastern Daylight Time)

## APIs

### Yapily Platform API

Manage Applications, Users, Webhooks, Notifications, and Constraints that govern how downstream AIS/PIS interactions operate on the Yapily Open Banking platform.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Applications
- Users
- Webhooks
- Notifications
- Constraints
- Platform

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yapily Institutions API

Discover and inspect the 2,000+ supported UK and European banks (ASPSPs), including supported features, payment methods, countries, BIC/BBAN identifiers, media assets, and authentication mechanisms.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Institutions
- ASPSP
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-institutions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-institutions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-institutions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/yapily-institution-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/yapily-get-institutions-example.json)

### Yapily Consents and Authorisations API

Create, retrieve, revoke, and re-authorise PSD2 consents for AIS and PIS interactions across UK Open Banking and Berlin Group ASPSPs. Supports redirect, embedded, and decoupled flows.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Consents
- Authorisations
- PSD2
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-consents-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-consents-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-consents-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/yapily-consent-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Yapily Data Access API (AIS)

Account Information Service Provider (AISP) endpoints for retrieving accounts, balances, transactions, identity, beneficiaries, scheduled payments, standing orders, direct debits, and statements with active end-user consent. Supports cursor pagination on transactions.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Account Information
- AISP
- Accounts
- Balances
- Transactions
- Identity
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/yapily-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yapily-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yapily-account-balance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/yapily-account-structure.json)
- [JSON-LD](json-ld/yapily-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/yapily-get-account-transactions-example.json)

### Yapily Payments API (PIS)

Payment Initiation Service Provider (PISP) endpoints for initiating single, scheduled, periodic, bulk, and international payments directly from a customer's bank account. Single-use consent per payment.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Payments
- PISP
- Payment Initiation
- Open Banking
- PSD2

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-payments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-payments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-payments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/yapily-payment-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/yapily-payment-structure.json)
- [Example](examples/yapily-create-payment-example.json)

### Yapily Variable Recurring Payments API

Variable Recurring Payments (VRP) endpoints for sweeping and commercial VRP including consent creation, funds confirmation, and payment execution under an active VRP consent.

- **Human URL:** [https://docs.yapily.com/payments/vrps/additional-information](https://docs.yapily.com/payments/vrps/additional-information)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Variable Recurring Payments
- VRP
- Sweeping
- Open Banking
- Payments

#### Properties

- [Documentation](https://docs.yapily.com/payments/vrps/additional-information)
- [OpenAPI](openapi/yapily-vrp-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-vrp-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-vrp-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yapily Hosted Pages API

Yapily-hosted UI flows for payment initiation and consent capture, including Pay By Link, single and bulk payments, VRP consent, and AIS consent capture — so customers don't have to build their own consent UI.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Hosted Pages
- Pay By Link
- Consent UI
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-hosted-pages-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-hosted-pages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-hosted-pages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yapily Data Plus API

Transaction enrichment endpoints providing merchant detection, MCC categorisation, and spending insights across consumer and business accounts.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Enrichment
- Categorisation
- Merchant Detection
- Insights
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-data-plus-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-data-plus-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-data-plus-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yapily Beneficiaries API

Application-level and user-level beneficiary management endpoints to speed up repeat payment flows with reusable counterparties.

- **Human URL:** [https://docs.yapily.com/api/reference/](https://docs.yapily.com/api/reference/)
- **Base URL:** `https://api.yapily.com`

#### Tags

- Beneficiaries
- Payments
- Open Banking

#### Properties

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-beneficiaries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yapily-beneficiaries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yapily-beneficiaries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.yapily.com/)
- [Documentation](https://docs.yapily.com/)
- [Getting Started](https://docs.yapily.com/getting-started/overview)
- [GitHub Organization](https://github.com/yapily)
- [Source Code](https://github.com/yapily/yapily-openapi)
- [SDK](https://github.com/yapily/yapily-sdk-java)
- [SDK](https://github.com/yapily/yapily-sdk-python)
- [SDK](https://github.com/yapily/yapily-sdk-nodejs)
- [Tools](https://github.com/yapily/helm-charts)
- [Tools](https://github.com/yapily/yapily-mulesoft-connector)
- [Tools](https://github.com/yapily/registration-scripts)
- [Samples](https://github.com/yapily/yapily-demo-pisp-flutter)
- [Pricing](https://www.yapily.com/pricing)
- [Plans](plans/yapily-plans-pricing.yml)
- [Rate Limits](rate-limits/yapily-rate-limits.yml)
- [Fin Ops](finops/yapily-finops.yml)
- [Spectral Rules](rules/yapily-rules.yml)
- [Vocabulary](vocabulary/yapily-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
