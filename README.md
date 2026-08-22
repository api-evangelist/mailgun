# Mailgun (mailgun)

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

Mailgun (by Sinch) is a transactional email API service for developers to send, receive, validate, and track emails at scale. The platform provides SMTP and HTTP APIs for sending email, inbound message routing, deliverability analytics, suppression management, and email validation with regional endpoints for US and EU data residency.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mailgun/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mailgun/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Email
- Transactional Email
- SMTP
- Email Validation
- Email Delivery
- Messaging

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Mailgun Send API

REST API for sending transactional and marketing email, managing domains, mailing lists, templates, suppressions, webhooks, events, and inbound routes. Authentication uses HTTP Basic Auth with an API key.

- **Human URL:** [https://documentation.mailgun.com/docs/mailgun/api-reference/](https://documentation.mailgun.com/docs/mailgun/api-reference/)
- **Base URL:** `https://api.mailgun.net`

#### Tags

- Email
- Send
- Domains
- Webhooks
- Routes
- Events

#### Properties

- [Documentation](https://documentation.mailgun.com/docs/mailgun/api-reference/)
- [A P I  Overview](https://documentation.mailgun.com/docs/mailgun/api-reference/api-overview)
- [Authentication](https://documentation.mailgun.com/docs/mailgun/api-reference/mg-auth)
- [OpenAPI](https://documentation.mailgun.com/_spec/docs/mailgun/api-reference/send/mailgun.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/mailgun/refs/heads/main/openapi/mailgun-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/mailgun.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailgun.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mailgun Email Validation API

REST API for verifying email addresses in real time, bulk list validation, and deliverability scoring to reduce bounces and improve sender reputation.

- **Human URL:** [https://documentation.mailgun.com/docs/validate/api-overview](https://documentation.mailgun.com/docs/validate/api-overview)
- **Base URL:** `https://api.mailgun.net`

#### Tags

- Email Validation
- Verification
- Deliverability

#### Properties

- [Documentation](https://documentation.mailgun.com/docs/validate/api-overview)
- [Postman Collection](collections/mailgun.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailgun.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/mailgun)
- [LinkedIn](https://www.linkedin.com/company/mailgun)
- [Website](https://www.mailgun.com)
- [Documentation](https://documentation.mailgun.com/)
- [Sign Up](https://signup.mailgun.com/new/signup)
- [Pricing](https://www.mailgun.com/pricing/)
- [Developer  Portal](https://documentation.mailgun.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
