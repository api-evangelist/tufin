# Tufin (tufin)

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

Tufin provides security policy orchestration solutions for managing network security policies across hybrid cloud environments, including firewalls, SDN, and cloud security controls. The Tufin Orchestration Suite (TOS) includes SecureTrack for network topology and policy analysis, SecureChange for automated policy change workflows, SecureApp for application-centric policy management, and SecureCloud for cloud-native security posture management. Tufin offers comprehensive REST APIs and GraphQL APIs for integrating with ITSM, SIEM, and other security tools.

**APIs.json:** [https://www.tufin.com](https://www.tufin.com)

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

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### Tufin SecureTrack API

The SecureTrack REST API enables programmatic access to Tufin's network security policy management platform. It supports querying network devices and firewall rules, analyzing network topology and path queries, retrieving policy compliance data, performing risk and cleanup analysis, managing rule documentation and recertification, and searching for network objects, services, and interfaces across multi-vendor firewall infrastructure. Authentication uses HTTP Basic Auth with TOS credentials.

- **Human URL:** [https://www.tufin.com/products/securetrack](https://www.tufin.com/products/securetrack)
- **Base URL:** `https://{tos_host}/securetrack/api`

#### Tags

- Compliance
- Firewall Rules
- Network Devices
- Network Topology
- Policy Analysis
- Risk Analysis

#### Properties

- [Documentation](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/securetrack_api.htm)
- [Swagger U I](https://forum.tufin.com/support/kc/rest-api/R24-1/securetrack/apidoc/)
- [Authentication](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm)
- [Reference](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4420.htm)
- [Getting Started](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm)
- [OpenAPI](openapi/tufin-securetrack-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tufin-securetrack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securetrack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tufin SecureChange API

The SecureChange REST API automates security policy change workflows, enabling programmatic submission and management of access request tickets, approval workflows, and change implementation across network infrastructure. Supports integration with ITSM platforms including ServiceNow, Jira, and Remedy for end-to-end change automation.

- **Human URL:** [https://www.tufin.com/products/securechange](https://www.tufin.com/products/securechange)
- **Base URL:** `https://{tos_host}/securechangeworkflow/api`

#### Tags

- Approvals
- Change Management
- ITSM Integration
- Policy Changes
- Ticketing
- Workflow Automation

#### Properties

- [Documentation](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm)
- [Swagger U I](https://forum.tufin.com/support/kc/rest-api/R24-1/securechangeworkflow/apidoc/)
- [Reference](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm)
- [Authentication](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm)
- [OpenAPI](openapi/tufin-securechange-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tufin-securechange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securechange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tufin SecureApp API

API for application-centric security policy management and micro-segmentation. SecureApp enables teams to manage security policies at the application level, define connectivity requirements, and automate policy changes for application deployments.

- **Human URL:** [https://www.tufin.com/products/secureapp](https://www.tufin.com/products/secureapp)
- **Base URL:** `https://{tos_host}/securechangeworkflow/api`

#### Tags

- Application Security
- Micro-Segmentation
- Policy Management
- Zero Trust

#### Properties

- [Documentation](https://forum.tufin.com/support/kc/secureapp/)
- [Reference](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/6481.htm)
- [Postman Collection](collections/tufin-securechange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securechange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tufin-securetrack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securetrack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tufin SecureTrack GraphQL API

GraphQL API for the Tufin Orchestration Suite providing flexible querying capabilities for security policy data, network topology, and compliance information. Uses OAuth2 authentication and supports complex nested queries across SecureTrack resources including devices, policies, rules, and topology.

- **Human URL:** [https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm](https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm)
- **Base URL:** `https://{tos_ip}/v2/api/sync/graphql`

#### Tags

- GraphQL
- Network Topology
- OAuth2
- Policy Analysis
- Security Data

#### Properties

- [Documentation](https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm)
- [Authentication](https://forum.tufin.com/support/kc/latest/Content/ST2/API/OAuth2.htm)
- [Postman Collection](collections/tufin-securechange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securechange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tufin-securetrack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securetrack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tufin SecureCloud API

REST API for Tufin SecureCloud, the cloud-native security policy management platform. Provides endpoints for managing cloud accounts, applications, assets, Kubernetes clusters, and security policies across AWS, Azure, and GCP environments. Enables cloud security posture management (CSPM) and Kubernetes network policy enforcement through API integration.

- **Human URL:** [https://www.tufin.com/tufin-orchestration-suite/securecloud](https://www.tufin.com/tufin-orchestration-suite/securecloud)
- **Base URL:** `https://{account}.securecloud.tufin.io/api/v1`

#### Tags

- Cloud Security
- CSPM
- Kubernetes
- Multi-Cloud
- Policy Management

#### Properties

- [Documentation](https://forum.tufin.com/support/kc/securecloud/)
- [Reference](https://securecloud.tufin.io/api-documentation/index.html)
- [Postman Collection](collections/tufin-securechange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securechange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tufin-securetrack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tufin-securetrack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tufin-technologies)
- [Portal](https://forum.tufin.com/)
- [Support](https://www.tufin.com/support)
- [Documentation](https://forum.tufin.com/support/kc)
- [Blog](https://www.tufin.com/blog)
- [Login](https://portal.tufin.io/)
- [Contact](https://www.tufin.com/company/contact-us)
- [Privacy Policy](https://www.tufin.com/privacy-policy)
- [Terms of Service](https://www.tufin.com/terms-of-use)
- [Website](https://www.tufin.com)
- [Getting Started](https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm)
- [Community](https://community.tufin.com/)
- [GitHub Organization](https://github.com/Tufin)
- [SDK](https://gitlab.com/tufinps/pytos2-ce)
- [SDK](https://github.com/Tufin/pytos)
- [Postman Collection](https://github.com/Tufin/postman) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Sign Up](https://www.tufin.com/demo)
- [Videos](https://www.tufin.com/resources/type/videos)
- [Developers](https://www.tufin.com/developers)
- [OpenAPI](openapi/tufin-securetrack-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/tufin-securechange-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Vocabulary](vocabulary/tufin-vocabulary.yml)
- [JSON-LD](json-ld/tufin-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tufin-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tufin-ticket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Integrations](https://www.tufin.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
