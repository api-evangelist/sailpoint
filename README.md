# SailPoint (sailpoint)
Enterprise identity security and governance platform providing identity management, access governance, and compliance solutions for workforce and non-employee identities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sailpoint/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Access Governance, Compliance, IAM, Identity Management, Identity Security, Security

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-02

## APIs

### SailPoint Developer Portal
**Human URL:** https://developer.sailpoint.com/

#### Properties
- [Documentation](https://developer.sailpoint.com/)

---

### SailPoint Identity Security Cloud V3 API
The V3 APIs provide core endpoints covering access profiles, certifications, identities, roles, search, sources, transforms, workflows, and more.

**Human URL:** https://developer.sailpoint.com/docs/api/v3/

#### Tags
- Access Governance, IAM, Identity Security

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/v3/)
- [OpenAPI](openapi/identity-security-cloud-v3.yml)
- [JSON Schema](json-schema/sailpoint-identity-schema.json)
- [JSON-LD Context](json-ld/sailpoint-context.jsonld)
- [Spectral Rules](rules/sailpoint-rules.yml)
- [Capabilities](capabilities/identity-governance.yaml)
- [Vocabulary](vocabulary/sailpoint-vocabulary.yml)

---

### SailPoint Identity Security Cloud V2024 API
**Human URL:** https://developer.sailpoint.com/docs/api/v2024/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/v2024/)

---

### SailPoint Identity Security Cloud V2025 API
**Human URL:** https://developer.sailpoint.com/docs/api/v2025/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/v2025/)

---

### SailPoint Identity Security Cloud Beta API
**Human URL:** https://developer.sailpoint.com/docs/api/beta/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/beta/)

---

### SailPoint IdentityIQ SCIM API
**Human URL:** https://developer.sailpoint.com/docs/api/iiq/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/iiq/)

---

### SailPoint Non-Employee Risk Management V1 API
**Human URL:** https://developer.sailpoint.com/docs/api/nerm/v1/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/nerm/v1/)

---

### SailPoint Non-Employee Risk Management V2025 API
**Human URL:** https://developer.sailpoint.com/docs/api/nerm/v2025/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/nerm/v2025/)

---

### SailPoint Identity Security Cloud V2026 API
**Human URL:** https://developer.sailpoint.com/docs/api/v2026/

#### Properties
- [Documentation](https://developer.sailpoint.com/docs/api/v2026/)

---

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/identity-security-cloud-v3.yaml](capabilities/shared/identity-security-cloud-v3.yaml) | Shared consumed definition for Identity Security Cloud V3 API |

### Workflow Capabilities

| File | Description | APIs |
|------|-------------|------|
| [capabilities/identity-governance.yaml](capabilities/identity-governance.yaml) | Identity governance and access management workflow | Identity Security Cloud V3 |

## Artifacts

| Artifact | Path |
|----------|------|
| OpenAPI Spec (V3) | [openapi/identity-security-cloud-v3.yml](openapi/identity-security-cloud-v3.yml) |
| JSON Schema | [json-schema/sailpoint-identity-schema.json](json-schema/sailpoint-identity-schema.json) |
| JSON Structure | [json-structure/sailpoint-identity-security-cloud-structure.json](json-structure/sailpoint-identity-security-cloud-structure.json) |
| JSON-LD Context | [json-ld/sailpoint-context.jsonld](json-ld/sailpoint-context.jsonld) |
| Spectral Rules | [rules/sailpoint-rules.yml](rules/sailpoint-rules.yml) |
| Vocabulary | [vocabulary/sailpoint-vocabulary.yml](vocabulary/sailpoint-vocabulary.yml) |

## Examples

- [List Identities](examples/sailpoint-list-identities-example.json)
- [Create Access Profile](examples/sailpoint-create-access-profile-example.json)
- [Certification Decision](examples/sailpoint-certification-decision-example.json)

## Common Properties

- [Developer Portal](https://developer.sailpoint.com)
- [Getting Started](https://developer.sailpoint.com/idn/api/getting-started)
- [SDKs](https://developer.sailpoint.com/idn/tools/sdk)
- [CLI](https://developer.sailpoint.com/docs/tools/cli/)
- [MCP Server](https://developer.sailpoint.com/docs/extensibility/mcp-getting-started/)
- [Community](https://developer.sailpoint.com/discuss)
- [Blog](https://www.sailpoint.com/blog)
- [Support](https://www.sailpoint.com/support)
- [Status Page](https://status.sailpoint.com)
- [Terms of Service](https://www.sailpoint.com/legal/terms-of-use)
- [Privacy Policy](https://www.sailpoint.com/legal/privacy)
- [Authentication](https://developer.sailpoint.com/docs/api/authentication/)
- [API Guidelines](https://sailpoint-oss.github.io/sailpoint-api-guidelines/)
- [GitHub Organization](https://github.com/sailpoint-oss)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

**FN:** SailPoint Technologies
**Email:** developer@sailpoint.com
