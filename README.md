# Fluentd (fluentd)

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

Open source data collector for unified logging layer that allows you to unify data collection and consumption for better use and understanding of data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Collection
- Logging
- Open Source

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Fluentd Plugin API

The Fluentd Plugin API allows developers to write custom input, output, filter, parser, formatter, and buffer plugins in Ruby. Plugins are distributed as RubyGems and integrate with Fluentd's plugin management system to extend data collection and processing pipelines.

- **Human URL:** [https://docs.fluentd.org/plugin-development](https://docs.fluentd.org/plugin-development)

#### Tags

- Open Source
- Plugin Development
- Ruby

#### Properties

- [Documentation](https://docs.fluentd.org/plugin-development)
- [Reference](https://docs.fluentd.org/plugin-development/api-plugin-base)
- [Postman Collection](collections/fluentd-http-input.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fluentd-http-input.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fluentd Forward Protocol

The Fluentd Forward Protocol is a binary protocol used to transport event streams between Fluentd nodes and compatible agents over TCP. It supports multiple transport modes including Message, Forward, PackedForward, and CompressedPackedForward, and includes authentication and heartbeat mechanisms.

- **Human URL:** [https://github.com/fluent/fluentd/wiki/Forward-Protocol-Specification-v1](https://github.com/fluent/fluentd/wiki/Forward-Protocol-Specification-v1)

#### Tags

- Logging
- Networking
- Protocol

#### Properties

- [Documentation](https://github.com/fluent/fluentd/wiki/Forward-Protocol-Specification-v1)
- [Reference](https://docs.fluentd.org/input/forward)
- [AsyncAPI](asyncapi/fluentd-forward-protocol-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/fluentd-http-input.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fluentd-http-input.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fluentd HTTP Input API

The Fluentd HTTP Input plugin exposes an HTTP endpoint that accepts log records posted as JSON or form-encoded data. It allows applications to send events to Fluentd over standard HTTP, making it accessible from any language or platform that can make HTTP requests.

- **Human URL:** [https://docs.fluentd.org/input/http](https://docs.fluentd.org/input/http)

#### Tags

- HTTP
- Input
- Logging

#### Properties

- [Documentation](https://docs.fluentd.org/input/http)
- [OpenAPI](openapi/fluentd-http-input-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fluentd-http-input.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fluentd-http-input.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [JSON Schema](json-schema/fluentd-log-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/fluentd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Website](https://www.fluentd.org/)
- [Documentation](https://docs.fluentd.org/)
- [Getting Started](https://docs.fluentd.org/quickstart)
- [GitHub Organization](https://github.com/fluent)
- [GitHub Repository](https://github.com/fluent/fluentd)
- [Blog](https://www.fluentd.org/blog/)
- [Changelog](https://github.com/fluent/fluentd/blob/master/CHANGELOG.md)
- [Community](https://www.fluentd.org/community/)
- [Support](https://docs.fluentd.org/quickstart/support)
- [Slack](https://slack.fluentd.org/)
- [L L Ms Txt](https://docs.fluentd.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
