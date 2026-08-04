# Spacelift (spacelift)

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

Spacelift is an infrastructure-as-code (IaC) orchestration platform that combines AI-assisted deployments, GitOps pipelines, and policy-as-code governance. It supports Terraform, OpenTofu, Pulumi, CloudFormation, Kubernetes, and Ansible. Key features include drift detection, OPA-based policies, self-service blueprints, dynamic credentials, and multi-tenancy. Available as fully managed SaaS and FedRAMP-authorized self-hosted.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Infrastructure as Code
- FinOps
- DevOps
- Platform Engineering
- Terraform
- GitOps

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## APIs

### Spacelift GraphQL API

Spacelift exposes a GraphQL API for programmatic control of all platform resources including stacks, runs, policies, contexts, worker pools, modules, and blueprints. Authentication uses JWT tokens obtained by exchanging a Spacelift API key ID and secret via the apiKeyUser mutation. The endpoint is account-specific at https://{account}.app.spacelift.io/graphql.

- **Human URL:** [https://spacelift.io/](https://spacelift.io/)
- **Base URL:** `https://{account}.app.spacelift.io/graphql`

#### Tags

- Infrastructure as Code
- DevOps
- Platform Engineering
- Terraform
- GraphQL

#### Properties

- [Documentation](https://docs.spacelift.io/)
- [Graph Q L](https://docs.spacelift.io/integrations/api)
- [Getting Started](https://docs.spacelift.io/)
- [GitHub Repository](https://github.com/spacelift-io/spacectl)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-schema/spacelift-stack-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-structure/spacelift-stack-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-ld/spacelift-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/vocabulary/spacelift-vocabulary.yml)
- [Postman Collection](collections/spacelift.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spacelift.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/spacelift-io)
- [Website](https://spacelift.io/)
- [Documentation](https://docs.spacelift.io/)
- [Graph Q L](https://docs.spacelift.io/integrations/api)
- [Git Hub](https://github.com/spacelift-io)
- [Pricing](https://spacelift.io/pricing)
- [Blog](https://spacelift.io/blog)
- [Changelog](https://spacelift.io/changelog)
- [Integrations](https://spacelift.io/platform/integrations)
- [L L Ms Txt](https://docs.spacelift.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
