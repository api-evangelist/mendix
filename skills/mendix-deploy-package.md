---
name: mendix-deploy-package
description: Upload a deployment package, transport it to a target environment, and retrieve the deployed package details.
api: openapi/mendix-packages-api-openapi.yml
operations:
- postAppsByAppIdPackagesUpload
- postAppsByAppIdEnvironmentsByModeTransport
- getAppsByAppIdEnvironmentsByModePackage
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mendix-packages-api-openapi.yml ; every operationId checked against the contract
---

# mendix-deploy-package

Upload a deployment package, transport it to a target environment, and retrieve the deployed package details.

## Steps

1. 1. Use `postAppsByAppIdPackagesUpload` with the `AppId` path parameter and the package file in the request body.
2. 2. Use `postAppsByAppIdEnvironmentsByModeTransport` with `AppId` and `Mode` path parameters to transport the uploaded package to the specified environment.
3. 3. Use `getAppsByAppIdEnvironmentsByModePackage` with `AppId` and `Mode` path parameters to get the deployed package information.

## Rules

- Authentication: include either the `Mendix-ApiKey` header (mendixApiKey) or the `Authorization` header (mxtoken) as required by the endpoint.
- Idempotency: the upload (`postAppsByAppIdPackagesUpload`) is not idempotent; repeat calls may create duplicate uploads.
- Errors: standard HTTP error codes are returned (e.g., 400 for bad request, 401 for unauthorized, 404 for not found).
