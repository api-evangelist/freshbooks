# FreshBooks (freshbooks)

FreshBooks is a cloud-based accounting and small business management platform offering invoicing, expense tracking, time tracking, project management, payments, estimates, and financial reporting for freelancers, self-employed professionals, and small businesses. The FreshBooks REST API provides access to clients, invoices, expenses, estimates, projects, time entries, payments, and reports using OAuth 2.0 Bearer token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/freshbooks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/freshbooks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Accounting
- Invoicing
- Expense Tracking
- Time Tracking
- Small Business
- Bookkeeping

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### FreshBooks REST API

REST API for FreshBooks providing CRUD access to clients, invoices, estimates, expenses, projects, time entries, tasks, payments, items, taxes, and accounting reports. Uses OAuth 2.0 Bearer tokens and is scoped per account via /accounting/account/{accountId}/* endpoints.

- **Human URL:** [https://www.freshbooks.com/api/start](https://www.freshbooks.com/api/start)
- **Base URL:** `https://api.freshbooks.com`

#### Tags

- Accounting
- Invoicing
- Expenses
- Time Tracking
- Projects

#### Properties

- [Documentation](https://www.freshbooks.com/api/start)
- [Authentication](https://www.freshbooks.com/api/authentication)
- [Postman  Collection](https://www.freshbooks.com/api/start)
- [Postman Collection](collections/freshbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freshbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FreshBooks Webhooks (Callbacks API)

Event delivery surface for the FreshBooks Callbacks API. Subscribers register an HTTPS endpoint, complete a verifier handshake, and then receive HMAC-SHA256 signed POSTs (application/x-www-form-urlencoded) for noun.verb events across bills, bill vendors, categories, clients, credit notes, estimates, expenses, invoices, items, payments, projects, recurring templates, services, taxes, and time entries.

- **Human URL:** [https://www.freshbooks.com/api/webhooks](https://www.freshbooks.com/api/webhooks)
- **Base URL:** `https://api.freshbooks.com`

#### Tags

- Webhooks
- Events
- Callbacks
- Accounting
- Invoicing

#### Properties

- [Documentation](https://www.freshbooks.com/api/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/freshbooks/refs/heads/main/asyncapi/freshbooks-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/freshbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freshbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/freshbooks)
- [Website](https://www.freshbooks.com)
- [Documentation](https://www.freshbooks.com/api/start)
- [Developer  Portal](https://www.freshbooks.com/developers)
- [Sign Up](https://www.freshbooks.com/signup)
- [Pricing](https://www.freshbooks.com/pricing)
- [Login](https://my.freshbooks.com/)
- [Support](https://support.freshbooks.com/)
- [Blog](https://www.freshbooks.com/blog)
- [GitHub Organization](https://github.com/freshbooks)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
