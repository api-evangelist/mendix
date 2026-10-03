---
name: mendix-start-environment
description: Start an app environment and monitor its startup status.
api: openapi/mendix-environments-api-openapi.yml
operations:
- postAppsByAppIdEnvironmentsByModeStart
- getAppsByAppIdEnvironmentsByModeStartByJobId
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mendix-environments-api-openapi.yml ; every operationId checked against the contract
---

# mendix-start-environment

Start an app environment and monitor its startup status.

## Steps

1. 1. Call `postAppsByAppIdEnvironmentsByModeStart` with path parameters `AppId` and `Mode`.
2. 2. Call `getAppsByAppIdEnvironmentsByModeStartByJobId` with path parameters `AppId`, `Mode` and the returned `JobId` to check start status.

## Rules

- Use one of the authentication schemes: `basicAuth`, `mendixApiKey` (header `Mendix-ApiKey`), or `mxtoken` (header `Authorization`).
- The `JobId` returned from the start request must be used in the status request.
