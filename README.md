# Mendix (mendix)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mendix, a Siemens company, is an enterprise low-code application development platform for designing, building, deploying, and operating multi-experience applications across web, mobile, and conversational interfaces. The platform spans Studio Pro modeling, the Mendix Cloud and private cloud runtimes, and governance and operational tooling for the full application lifecycle. Mendix exposes a suite of platform APIs (Deploy, Build, App Repository, User Management, Content, Studio Pro, and Apps APIs) secured by API keys or personal access tokens (PATs).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mendix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mendix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Low-Code
- Application Development
- Enterprise Platform
- Application Lifecycle
- Deployment
- Governance

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Mendix Deploy API

REST API for managing apps, environments, deployment packages, transports, backups, and deployment lifecycle on Mendix Cloud. Authentication is via Mendix-Username and Mendix-ApiKey request headers tied to the requesting user's API key and platform permissions.

- **Human URL:** [https://docs.mendix.com/apidocs-mxsdk/apidocs/deploy-api/](https://docs.mendix.com/apidocs-mxsdk/apidocs/deploy-api/)
- **Base URL:** `https://deploy.mendix.com/api/1`

#### Tags

- Low-Code
- Deployment
- Application Lifecycle

#### Properties

- [Documentation](https://docs.mendix.com/apidocs-mxsdk/apidocs/deploy-api/)
- [Deploy  A P I v2](https://docs.mendix.com/apidocs-mxsdk/apidocs/deploy-api-2/)
- [Postman Collection](collections/mendix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mendix Build API

REST API for managing app projects, branches, revisions, and build packages in Mendix Team Server. Uses Mendix API key authentication.

- **Human URL:** [https://docs.mendix.com/apidocs-mxsdk/apidocs/build-api/](https://docs.mendix.com/apidocs-mxsdk/apidocs/build-api/)
- **Base URL:** `https://deploy.mendix.com/api/1`

#### Tags

- Low-Code
- Build
- Source Control

#### Properties

- [Documentation](https://docs.mendix.com/apidocs-mxsdk/apidocs/build-api/)
- [Postman Collection](collections/mendix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mendix App Repository API

REST API for managing apps, members, and repository metadata in the Mendix platform. Uses PAT or Mendix API key authentication.

- **Human URL:** [https://docs.mendix.com/apidocs-mxsdk/apidocs/app-repository-api/](https://docs.mendix.com/apidocs-mxsdk/apidocs/app-repository-api/)
- **Base URL:** `https://repository.api.mendix.com`

#### Tags

- Low-Code
- App Management
- Governance

#### Properties

- [Documentation](https://docs.mendix.com/apidocs-mxsdk/apidocs/app-repository-api/)
- [Postman Collection](collections/mendix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/mendix)
- [LinkedIn](https://www.linkedin.com/company/mendix)
- [Website](https://www.mendix.com)
- [Documentation](https://docs.mendix.com/apidocs-mxsdk/apidocs/)
- [Pricing](https://www.mendix.com/pricing/)
- [Sign Up](https://signup.mendix.com/)
- [L L Ms Txt](https://mendix.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
