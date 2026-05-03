# Tray.io

Tray.io (now also known as Tray.ai) is an AI-ready integration platform as a service (iPaaS) that enables businesses to integrate and automate workflows across cloud applications using a visual editor, pre-built connectors, and API-level access.

**URL:** [https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Agents, API Aggregation, Automation, Connectors, Integration, iPaaS, Workflow Automation

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-03

## APIs

### Tray.io Platform API

The Tray.io Platform API allows developers to leverage the power of Tray's service connectors without using the Builder UI, enabling native integration of third-party APIs into applications.

**Human URL:** [https://developer.tray.ai/openapi/trayapi-introduction/](https://developer.tray.ai/openapi/trayapi-introduction/)
**Base URL:** `https://api.tray.io/core/v1`

#### Tags

- API Management, Automation, Connectors, Integration, iPaaS

#### Properties

- [Documentation](https://developer.tray.ai/openapi/trayapi-introduction/)
- [Developer Portal](https://developer.tray.ai/)
- [OpenAPI](openapi/tray-io-platform-api-openapi.yml)
- [JSONSchema - Connector](json-schema/tray-io-connector-schema.json)
- [JSONSchema - Authentication](json-schema/tray-io-authentication-schema.json)
- [JSONSchema - Workspace](json-schema/tray-io-workspace-schema.json)
- [JSONLD](json-ld/tray-io-context.jsonld)
- [JSONStructure](json-structure/tray-io-connector-structure.json)
- [Example - List Connectors](examples/tray-io-list-connectors-example.json)
- [Example - Call Connector](examples/tray-io-call-connector-example.json)
- [SpectralRuleset](rules/tray-io-rules.yml)
- [NaftikoCapability](capabilities/shared/platform-api.yaml)

### Tray.io Embedded API

The Tray.io Embedded API provides GraphQL-based APIs for embedding Tray's automation capabilities into your own products, enabling end users to configure and manage integrations directly.

**Human URL:** [https://embedded-api-docs.tray.io/](https://embedded-api-docs.tray.io/)

#### Tags

- Embedded Integration, GraphQL, White Label

#### Properties

- [Documentation](https://embedded-api-docs.tray.io/)
- [Developer Portal](https://developer.tray.ai/)

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description | Tools |
|------------|-------------|-------|
| [Integration Platform](capabilities/integration-platform.yaml) | Full connector discovery, invocation, authentication, and workspace management | 9 tools |

### Shared Definitions

| Capability | Description |
|------------|-------------|
| [Platform API](capabilities/shared/platform-api.yaml) | Connectors, authentication, triggers, users, workspaces |

## Vocabulary

- [tray-io-vocabulary.yml](vocabulary/tray-io-vocabulary.yml) — Domain vocabulary for Tray.io integration platform concepts

## Common Properties

- [Website](https://tray.ai)
- [Documentation](https://tray.ai/documentation)
- [Developer Portal](https://developer.tray.ai/)
- [Pricing](https://tray.ai/pricing)
- [LinkedIn](https://www.linkedin.com/company/tray-io)
- [X (Twitter)](https://x.com/tray)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
