---
name: mendix-manage-tags
description: Manage environment tags for a Mendix app by listing, creating, and deleting them.
api: openapi/mendix-tags-api-openapi.yml
operations:
- getAppsByAppIdEnvironmentsByModeTags
- postAppsByAppIdEnvironmentsByModeTags
- deleteAppsByAppIdEnvironmentsByModeTags
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mendix-tags-api-openapi.yml ; every operationId checked against the contract
---

# mendix-manage-tags

Manage environment tags for a Mendix app by listing, creating, and deleting them.

## Steps

1. 1. List existing tags using `getAppsByAppIdEnvironmentsByModeTags` with path parameters `AppId` and `Mode`.
2. 2. Create a new tag using `postAppsByAppIdEnvironmentsByModeTags` with path parameters `AppId` and `Mode` and a request body containing the tag definition.
3. 3. Delete tags using `deleteAppsByAppIdEnvironmentsByModeTags` with path parameters `AppId` and `Mode`.

## Rules

- Authentication: include either the `Mendix-ApiKey` header (mendixApiKey) or the `Authorization` header (mxtoken) on each request.
- Idempotency: the POST operation should be safe to retry; include an `Idempotency-Key` header if supported by the API.
- Errors: handle standard HTTP error codes (4xx for client errors, 5xx for server errors) as defined by the API.
