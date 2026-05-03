# Tufin

Tufin provides security policy orchestration solutions for managing network security policies
across hybrid cloud environments, including firewalls, SDN, and cloud security controls.
The Tufin Orchestration Suite (TOS) combines SecureTrack, SecureChange, SecureApp, and
SecureCloud into a unified platform with comprehensive REST and GraphQL APIs.

**Website:** https://www.tufin.com

**APIs.yml:** https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/apis.yml

## Tags

- Cloud Security
- Compliance
- Firewall Management
- Network Security
- Network Topology
- Policy Orchestration
- Risk Management
- Security Policy Management
- Zero Trust

## APIs

### Tufin SecureTrack REST API (v R25-2)

Network security policy monitoring, topology analysis, and compliance.

- **Base URL:** `https://{tos_host}/securetrack/api`
- **Authentication:** HTTP Basic Auth
- **Documentation:** https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/securetrack_api.htm
- **Swagger UI:** https://forum.tufin.com/support/kc/rest-api/R24-1/securetrack/apidoc/
- **OpenAPI Spec:** [openapi/tufin-securetrack-openapi.yml](openapi/tufin-securetrack-openapi.yml)

### Tufin SecureChange REST API (v R25-2)

Security policy change workflow automation and ITSM integration.

- **Base URL:** `https://{tos_host}/securechangeworkflow/api/securechange`
- **Authentication:** HTTP Basic Auth
- **Documentation:** https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm
- **Swagger UI:** https://forum.tufin.com/support/kc/rest-api/R24-1/securechangeworkflow/apidoc/
- **OpenAPI Spec:** [openapi/tufin-securechange-openapi.yml](openapi/tufin-securechange-openapi.yml)

### Tufin SecureTrack GraphQL API

GraphQL API for flexible querying of security policy data with OAuth2 authentication.

- **Base URL:** `https://{tos_ip}/v2/api/sync/graphql`
- **Authentication:** OAuth2

### Tufin SecureCloud API

Cloud-native security posture management for AWS, Azure, GCP, and Kubernetes.

- **Base URL:** `https://{account}.securecloud.tufin.io/api/v1`

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/securetrack.yaml](capabilities/shared/securetrack.yaml) | SecureTrack API consumed definition (10 MCP tools) |
| [capabilities/shared/securechange.yaml](capabilities/shared/securechange.yaml) | SecureChange API consumed definition (6 MCP tools) |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/network-security-policy-management.yaml](capabilities/network-security-policy-management.yaml) | Unified network policy lifecycle management (13 MCP tools) |

## Schemas

### JSON Schema

| File | Description |
|---|---|
| [json-schema/tufin-device-schema.json](json-schema/tufin-device-schema.json) | Network device schema |
| [json-schema/tufin-ticket-schema.json](json-schema/tufin-ticket-schema.json) | SecureChange ticket schema |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/tufin-device-structure.json](json-structure/tufin-device-structure.json) | Device field structure |
| [json-structure/tufin-ticket-structure.json](json-structure/tufin-ticket-structure.json) | Ticket field structure |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/tufin-context.jsonld](json-ld/tufin-context.jsonld) | Linked data context for Tufin resources |

## Examples

| File | Description |
|---|---|
| [examples/tufin-getDevices-example.json](examples/tufin-getDevices-example.json) | List network devices |
| [examples/tufin-getTopologyPath-example.json](examples/tufin-getTopologyPath-example.json) | Network path analysis |
| [examples/tufin-getRulesByDevice-example.json](examples/tufin-getRulesByDevice-example.json) | Get firewall rules |
| [examples/tufin-createTicket-example.json](examples/tufin-createTicket-example.json) | Submit change ticket |

## Rules

| File | Description |
|---|---|
| [rules/tufin-securetrack-rules.yml](rules/tufin-securetrack-rules.yml) | Spectral ruleset for Tufin API conventions |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/tufin-vocabulary.yml](vocabulary/tufin-vocabulary.yml) | Domain vocabulary for network security policy management |

## Developer Resources

- **GitHub:** https://github.com/Tufin
- **Python SDK:** https://github.com/Tufin/pytos
- **Postman Collections:** https://github.com/Tufin/postman
- **Developer Portal:** https://www.tufin.com/developers
- **Community:** https://community.tufin.com/

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
