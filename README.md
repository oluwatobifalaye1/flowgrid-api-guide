# FlowGrid API Documentation

**FlowGrid Help Centre — HTTP Integrations**

This repository contains the technical documentation for connecting external systems to FlowGrid using webhooks and HTTP Request nodes.

> **Documentation status:** Fictional technical documentation for demonstration and development purposes. Endpoint URLs, credentials, workflow IDs, signatures, execution IDs, and example data are placeholders.

## Documentation structure

- **Integration Guide** — concepts, request format, headers, payloads, and response handling.
- **HTTP Reference** — endpoint and request/response reference.
- **Error Reference** — documented HTTP error codes and troubleshooting actions.
- **OpenAPI Specification** — machine-readable API definition.

## Base URL

```text
https://api.flowgrid.io
```
    
## Example endpoint

```text
POST /v1/hooks/catch/wf_98234712
```

## Important security note

The examples in this repository are not credentials and do not grant permission to connect external software to FlowGrid. A production integration would require credentials, permissions, endpoint details, and security requirements supplied by the actual service owner.
