# Yapily (yapily)

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
