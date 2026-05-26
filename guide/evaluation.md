# Evaluation Guide

Use this page to evaluate whether Skybridge App Packager MCP fits a real workflow.

## What To Test

- Skybridge
- Skybridge App Packager MCP
- Skybridge App Packager MCP documentation
- Skybridge App Packager MCP remote MCP
- skybridgepackager server card

## Expected Evidence

- Open Skybridge App Packager MCP and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://skybridgepackager.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call package_skybridge_app with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://skybridgepackager.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=skybridgepackager_public_docs&utm_content=evaluation_checkout
