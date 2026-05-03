# Vizion

Vizion provides a container tracking API that delivers clean, standardized, and detailed shipment tracking events from ocean carriers, terminals, rail, and customs data sources. The REST API returns JSON-encoded responses and supports real-time webhook delivery.

**Human URL:** https://www.vizionapi.com  
**Documentation:** https://docs.vizionapi.com  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/vizion/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Container Tracking, Logistics, Ocean Freight, Shipping, Supply Chain, Webhooks

## APIs

### Vizion Container Tracking API

Subscribe to a container by ID and carrier SCAC code. Receive real-time webhook updates or poll for tracking milestones. All events follow a standardized JSON schema.

**Human URL:** https://docs.vizionapi.com/docs/overview

#### Properties

- [Documentation](https://docs.vizionapi.com/docs/overview)
- [Reference](https://docs.vizionapi.com/reference/introduction)
- [Getting Started](https://docs.vizionapi.com/docs/quick-start)
- [OpenAPI](openapi/vizion-container-tracking-openapi.yml)

---

## OpenAPI Specifications

| File | Description |
|---|---|
| [vizion-container-tracking-openapi.yml](openapi/vizion-container-tracking-openapi.yml) | References CRUD, tracking updates, authentication, and event schemas |

## Spectral Rules

| File | Description |
|---|---|
| [vizion-rules.yml](rules/vizion-rules.yml) | Spectral ruleset enforcing Vizion API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | APIs |
|---|---|
| [shared/container-tracking.yaml](capabilities/shared/container-tracking.yaml) | Vizion Container Tracking API |

### Workflow Capabilities

| File | Description |
|---|---|
| [shipment-visibility.yaml](capabilities/shipment-visibility.yaml) | Unified REST + MCP for shipment visibility workflows |

## JSON Schema

| File | Description |
|---|---|
| [vizion-reference-schema.json](json-schema/vizion-reference-schema.json) | Container tracking reference/subscription schema |
| [vizion-tracking-update-schema.json](json-schema/vizion-tracking-update-schema.json) | Tracking update payload with events, ETA, vessel, and location data |

## JSON Structure

| File | Description |
|---|---|
| [vizion-reference-structure.json](json-structure/vizion-reference-structure.json) | Field-level structure for Vizion Reference |

## JSON-LD Context

| File | Description |
|---|---|
| [vizion-context.jsonld](json-ld/vizion-context.jsonld) | Linked data context aligned with schema.org/ParcelDelivery |

## Examples

| File | Description |
|---|---|
| [vizion-container-tracking-create-reference-example.json](examples/vizion-container-tracking-create-reference-example.json) | POST /references — subscribe to a container |
| [vizion-container-tracking-list-updates-example.json](examples/vizion-container-tracking-list-updates-example.json) | GET /references/{id}/updates — milestone events |

## Vocabulary

| File | Description |
|---|---|
| [vizion-vocabulary.yml](vocabulary/vizion-vocabulary.yml) | Vizion terminology: SCAC, Reference, Tracking Event, Webhook, UN/LOCODE |

## Common Properties

- [Website](https://www.vizionapi.com/)
- [Documentation](https://docs.vizionapi.com/)
- [Reference](https://docs.vizionapi.com/reference/introduction)
- [Integrations](https://www.vizionapi.com/container-tracking/integrations)
- [GitHub Organization](https://github.com/vizionapi)
- [Postman Collection](https://docs.vizionapi.com/docs/use-the-vizion-postman-collection)
- [Support](https://support.vizionapi.com/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
