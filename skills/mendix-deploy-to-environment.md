---
name: mendix-deploy-to-environment
description: Deploy a package to a newly created environment for an app.
api: openapi/openapi-deploy-v1.yaml
operations:
- createEnvironment
- requestActionOnAppInEnv
- getEnvironment
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/openapi-deploy-v1.yaml ; every operationId checked against the contract
---

# mendix-deploy-to-environment

Deploy a package to a newly created environment for an app.

## Steps

1. 1. Call `createEnvironment` with path parameters `appId` and request body fields as defined in the contract.
2. 2. Call `requestActionOnAppInEnv` with path parameters `appId`, `environmentId` and request body fields to trigger the deployment.
3. 3. Call `getEnvironment` with path parameters `appId`, `environmentId` to verify the deployment status.

## Rules

- Auth: Include the Mendix API key in the `Mendix-ApiKey` header (mendixApiKey scheme).
- Idempotency: `createEnvironment` is not idempotent; avoid duplicate calls.
- Errors: Handle standard HTTP error responses (4xx, 5xx) as defined by the API.
