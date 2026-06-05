# Fluentd (fluentd)

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
