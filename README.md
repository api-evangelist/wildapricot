# WildApricot (wildapricot)
WildApricot is a cloud-based membership management software platform designed for associations, nonprofits, and clubs. It provides tools for managing members, events, email communications, online payments, and websites. The WildApricot Admin API provides programmatic access to all platform features including contacts, events, event registrations, membership levels, invoices, payments, donations, email campaigns, and store orders via a REST API secured with OAuth2.

**URL:** [https://app.wildapricot.com/interfaces/api](https://app.wildapricot.com/interfaces/api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Membership Management, Associations, Nonprofit, Events, Payments

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-03

## APIs

### WildApricot Admin API
The WildApricot Admin API provides programmatic access to membership management features including contacts, events, event registrations, membership levels, invoices, payments, donations, email campaigns, and store orders. Secured with OAuth2 client credentials or authorization code flow.

**Human URL:** [https://app.wildapricot.com/interfaces/api](https://app.wildapricot.com/interfaces/api)

#### Tags:

 - Membership Management, Associations, Nonprofit, Contacts, Events, Payments

#### Properties

- [Documentation](https://app.wildapricot.com/interfaces/api)
- [APIReference](https://app.swaggerhub.com/apis/WildApricot/wild-apricot_public_api/7.24.0)
- [OpenAPI](openapi/wildapricot-admin-api-openapi.yml)
- [Authentication](https://gethelp.wildapricot.com/en/articles/484)
- [SDK - API Samples (.NET)](https://github.com/WildApricot/ApiSamples)
- [SDK - Python SDK (Community)](https://github.com/douglasdeodato/wildapricot-python-api)

## Common Properties

- [Website](https://www.wildapricot.com/)
- [Portal](https://app.wildapricot.com/interfaces/api)
- [Documentation](https://gethelp.wildapricot.com/en/articles/182)
- [GettingStarted](https://gethelp.wildapricot.com/en/articles/484)
- [Pricing](https://www.wildapricot.com/pricing)
- [TermsOfService](https://www.wildapricot.com/terms-of-use)
- [PrivacyPolicy](https://www.wildapricot.com/privacy-policy)
- [Support](https://gethelp.wildapricot.com/)
- [Blog](https://www.wildapricot.com/blog)
- [GitHubOrganization](https://github.com/WildApricot)

## Features

| Name | Description |
|------|-------------|
| Contact Management | Comprehensive member and contact database with custom fields, saved searches, and OData filtering. |
| Event Management | Full event lifecycle management including registration types, waitlists, check-in, and capacity management. |
| Membership Levels | Configurable membership tiers with pricing, renewal periods, access restrictions, and bundle support. |
| Online Payments | Integrated payment processing for membership fees, event registrations, donations, and store orders. |
| Email Campaigns | Built-in email campaign tool with draft management, recipient targeting, scheduling, and delivery tracking. |
| Donation Management | Track and manage charitable donations with custom fields and donor contact linking. |
| Member Portal | Self-service member portal for profile management, event registration, and membership renewals. |
| Store | Simple online store for merchandise and product sales with order management. |

## Use Cases

| Name | Description |
|------|-------------|
| Member Onboarding Automation | Automate new member welcome workflows by monitoring contact creation events and sending personalized onboarding sequences. |
| Event Registration Sync | Sync WildApricot event registrations to CRM or marketing platforms for post-event follow-up campaigns. |
| Membership Renewal Reminders | Query lapsed and soon-to-expire members to trigger renewal reminder emails or SMS notifications. |
| Financial Reporting | Extract invoice, payment, and donation data to build financial dashboards and audit reports. |
| Badge and Check-In Systems | Use the event check-in API to power custom badge printing or door access control at events. |
| Directory Integrations | Push member data to external directories, websites, or LDAP systems using the contacts API. |

## Integrations

| Name | Description |
|------|-------------|
| QuickBooks | WildApricot has a native QuickBooks integration for financial data sync and accounting workflows. |
| Zapier | WildApricot integrates with Zapier enabling no-code workflows connecting to 5000+ apps. |
| Stripe | Payments can be processed through Stripe as a payment gateway for online transactions. |
| PayPal | WildApricot supports PayPal as a payment gateway for member and event payments. |
| WordPress | WildApricot offers a WordPress integration for embedding member login and event lists. |
| Mailchimp | Member contact lists can be synced to Mailchimp for external email marketing campaigns. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [WildApricot Admin API](openapi/wildapricot-admin-api-openapi.yml)

### JSON Schema

- [Contact Schema](json-schema/wildapricot-contact-schema.json)
- [Event Schema](json-schema/wildapricot-event-schema.json)
- [Event Registration Schema](json-schema/wildapricot-event--registration-schema.json)
- [Membership Level Schema](json-schema/wildapricot-membership--level-schema.json)
- [Invoice Schema](json-schema/wildapricot-invoice-schema.json)
- [Payment Schema](json-schema/wildapricot-payment-schema.json)
- [Donation Schema](json-schema/wildapricot-donation-schema.json)
- [Account Schema](json-schema/wildapricot-account-schema.json)

### JSON Structure

- [Contact Structure](json-structure/wildapricot-contact-structure.json)
- [Event Structure](json-structure/wildapricot-event-structure.json)
- [Invoice Structure](json-structure/wildapricot-invoice-structure.json)

### JSON-LD

- [WildApricot Context](json-ld/wildapricot-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [WildApricot Admin API](capabilities/shared/wildapricot-admin-api.yaml) — 8 operations for membership management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Membership Management](capabilities/membership-management.yaml) | WildApricot Admin API | 9 | Association Administrator, Membership Coordinator, Nonprofit Operations |

## Vocabulary

- [WildApricot Vocabulary](vocabulary/wildapricot-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 11 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [WildApricot Spectral Rules](rules/wildapricot-spectral-rules.yml) — 25 rules across 10 categories enforcing WildApricot API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
