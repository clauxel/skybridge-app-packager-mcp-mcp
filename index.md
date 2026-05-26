# Skybridge App Packager MCP

Skybridge App Packager MCP is a hosted remote MCP for Skybridge.

This repository is a public documentation project for Skybridge App Packager MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://skybridgepackager.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=skybridgepackager_public_docs&utm_content=readme_home
- Pricing: https://skybridgepackager.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=skybridgepackager_public_docs&utm_content=readme_pricing
- Checkout: https://skybridgepackager.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=skybridgepackager_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://skybridgepackager.clauxel.com/mcp
- Server card: https://skybridgepackager.clauxel.com/server-card.json
- Registry name: `com.clauxel.skybridgepackager/skybridgepackager-mcp`
- Tools: `package_skybridge_app`, `validate_app_schema`, `run_client_compatibility_test`, `export_app_manifest`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: package_skybridge_app
- MCP tool: validate_app_schema
- MCP tool: run_client_compatibility_test
- MCP tool: export_app_manifest

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
