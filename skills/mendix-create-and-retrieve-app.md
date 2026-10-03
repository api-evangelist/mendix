---
name: mendix-create-and-retrieve-app
description: Create a new free app and then retrieve its details.
api: openapi/mendix-apps-api-openapi.yml
operations:
- postApps
- getAppsByAppId
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mendix-apps-api-openapi.yml ; every operationId checked against the contract
---

# mendix-create-and-retrieve-app

Create a new free app and then retrieve its details.

## Steps

1. 1. Call `postApps` with the required request body fields as defined in the contract.
2. 2. Call `getAppsByAppId` using the `AppId` returned from `postApps` and include any required path parameters.

## Rules

- Auth: include either the `Mendix-ApiKey` header (mendixApiKey) or the `Authorization` header (mxtoken) as required by the API.
- Idempotency: `postApps` is not idempotent; avoid repeating the request to prevent duplicate app creation.
