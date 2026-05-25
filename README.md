# Yapily (yapily)
Yapily is a UK-headquartered Open Banking platform that exposes a single REST API across 2,000+ banks in the UK and 18+ European countries. The platform provides AISP (Account Information) and PISP (Payment Initiation) capabilities, Variable Recurring Payments (VRP), transaction enrichment (Data Plus), Account Validation, and Hosted Payment / Consent Pages. Yapily Connect Ltd is FCA-authorised in the UK and Yapily Connect UAB is authorised by the Bank of Lithuania for EU coverage, so customers can launch without holding their own PSD2 permissions.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/yapily/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Open Banking, AISP, PISP, Payments, Account Information, Variable Recurring Payments, Financial Services, PSD2, FCA, Berlin Group, UK, Europe, FinTech

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Coverage

- **2,000+ banks** across the UK and 18+ EU countries
- **3,500+ customer applications** including Google, Revolut, Adyen, and Pleo
- Regulated under **FCA** (Yapily Connect Ltd) and **Bank of Lithuania** (Yapily Connect UAB)

## APIs

### Yapily Platform API
Manage Applications, Users, Webhooks, Notifications, and Constraints that govern how downstream AIS/PIS interactions operate on the Yapily Open Banking platform.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-platform-api-openapi.yml)
- [Naftiko Capability — Platform](capabilities/platform.yaml)

### Yapily Institutions API
Discover and inspect the 2,000+ supported UK and European banks (ASPSPs), including features, payment methods, countries, identifiers, and authentication mechanisms.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-institutions-api-openapi.yml)
- [JSON Schema — Institution](json-schema/yapily-institution-schema.json)
- [Naftiko Capability — Institutions](capabilities/institutions.yaml)
- [Example — List Institutions](examples/yapily-get-institutions-example.json)

### Yapily Consents and Authorisations API
Create, retrieve, revoke, and re-authorise PSD2 consents for AIS and PIS interactions across UK Open Banking and Berlin Group ASPSPs. Supports redirect, embedded, and decoupled flows.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-consents-api-openapi.yml)
- [JSON Schema — Consent](json-schema/yapily-consent-schema.json)
- [Naftiko Capability — Consents](capabilities/consents.yaml)

### Yapily Data Access API (AIS)
AISP endpoints for retrieving accounts, balances, transactions, identity, beneficiaries, scheduled payments, standing orders, direct debits, and statements with active end-user consent. Supports cursor pagination on transactions.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-data-api-openapi.yml)
- [JSON Schema — Account](json-schema/yapily-account-schema.json)
- [JSON Schema — Transaction](json-schema/yapily-transaction-schema.json)
- [JSON Schema — Balance](json-schema/yapily-account-balance-schema.json)
- [JSON Structure — Account](json-structure/yapily-account-structure.json)
- [JSON-LD Context](json-ld/yapily-context.jsonld)
- [Naftiko Capability — Data Access](capabilities/data-access.yaml)
- [Example — Get Account Transactions](examples/yapily-get-account-transactions-example.json)

### Yapily Payments API (PIS)
PISP endpoints for initiating single, scheduled, periodic, bulk, and international payments directly from a customer's bank account. Single-use consent per payment.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-payments-api-openapi.yml)
- [JSON Schema — Payment Response](json-schema/yapily-payment-response-schema.json)
- [JSON Structure — Payment](json-structure/yapily-payment-structure.json)
- [Naftiko Capability — Payment Initiation](capabilities/payment-initiation.yaml)
- [Example — Create Payment](examples/yapily-create-payment-example.json)

### Yapily Variable Recurring Payments API
VRP endpoints for sweeping and commercial VRP including consent creation, funds confirmation, and payment execution under an active VRP consent.

- [Documentation](https://docs.yapily.com/payments/vrps/additional-information)
- [OpenAPI](openapi/yapily-vrp-api-openapi.yml)
- [Naftiko Capability — Variable Recurring Payments](capabilities/variable-recurring-payments.yaml)

### Yapily Hosted Pages API
Yapily-hosted UI flows for payment initiation and consent capture, including Pay By Link, single and bulk payments, VRP consent, and AIS consent capture.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-hosted-pages-api-openapi.yml)
- [Naftiko Capability — Hosted Pages](capabilities/hosted-pages.yaml)

### Yapily Data Plus API
Transaction enrichment endpoints providing merchant detection, MCC categorisation, and spending insights across consumer and business accounts.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-data-plus-api-openapi.yml)
- [Naftiko Capability — Data Plus](capabilities/data-plus.yaml)

### Yapily Beneficiaries API
Application-level and user-level beneficiary management to speed up repeat payment flows with reusable counterparties.

- [Documentation](https://docs.yapily.com/)
- [OpenAPI](openapi/yapily-beneficiaries-api-openapi.yml)
- [Naftiko Capability — Beneficiaries](capabilities/beneficiaries.yaml)

## Common Resources

- [Website](https://www.yapily.com/)
- [Documentation](https://docs.yapily.com/)
- [Getting Started](https://docs.yapily.com/getting-started/overview)
- [GitHub Organization](https://github.com/yapily)
- [Canonical OpenAPI Spec](https://github.com/yapily/yapily-openapi)
- [Java SDK](https://github.com/yapily/yapily-sdk-java)
- [Python SDK](https://github.com/yapily/yapily-sdk-python)
- [Node.js SDK](https://github.com/yapily/yapily-sdk-nodejs)
- [MuleSoft Connector](https://github.com/yapily/yapily-mulesoft-connector)
- [Helm Charts](https://github.com/yapily/helm-charts)
- [Open Banking Registration Scripts](https://github.com/yapily/registration-scripts)
- [Flutter PISP Demo](https://github.com/yapily/yapily-demo-pisp-flutter)
- [Pricing](https://www.yapily.com/pricing)
- [Plans (API Commons)](plans/yapily-plans-pricing.yml)
- [Rate Limits (API Commons)](rate-limits/yapily-rate-limits.yml)
- [FinOps (FOCUS)](finops/yapily-finops.yml)
- [Spectral Ruleset](rules/yapily-rules.yml)
- [Vocabulary](vocabulary/yapily-vocabulary.yml)

## Solutions

- **Account-to-Account Checkout** — Replace card rails with PISP-initiated A2A payments at checkout using single payments or Pay By Link.
- **Subscription Billing via VRP** — Replace card-on-file with Variable Recurring Payments for commercial subscriptions, with consent-bound caps.
- **Affordability and Underwriting** — Use AIS plus Data Plus enrichment to score affordability for lending, BNPL, and rentals.
- **Personal Finance Management** — Power PFM apps with consented bank data across 19 European markets through a single API.
- **Treasury and Reconciliation** — Pull balances and transactions across multiple business accounts for cash management and reconciliation.
- **Account Ownership Validation** — Verify customer-provided bank details at onboarding using Yapily Validate.

## Integrations

- **UK Open Banking** — UK Open Banking Standard ASPSPs (CMA9 plus long tail) under FCA regulation.
- **Berlin Group NextGenPSD2** — EU ASPSPs implementing the Berlin Group NextGenPSD2 spec.
- **Yapily Connect (FCA)** — Yapily Connect Ltd as regulated AISP/PISP of record in the UK.
- **Yapily Connect (Bank of Lithuania)** — Yapily Connect UAB as regulated AISP/PISP of record across the EU.
- **MuleSoft** — Drag-and-drop integration via yapily-mulesoft-connector.
- **Java / Python / Node.js SDKs** — Official SDKs published from the canonical OpenAPI spec.
- **Kubernetes (Helm)** — helm-charts repo for deploying Yapily-adjacent workloads.

## Use Cases

- Pay-ins for Marketplaces
- Bill Payments and Direct-to-Account Refunds
- Salary Advance and Income Verification
- Wealth and Investment Funding
- Charity Donations
- Bureaux de Change and FX Onboarding
- Bulk Payouts (Payroll, Supplier Payments)
- B2B Sweeping (Cash Concentration)
