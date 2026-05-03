# Spacelift

Spacelift is an infrastructure-as-code (IaC) orchestration platform that combines AI-assisted
deployments, GitOps pipelines, and policy-as-code governance. It supports Terraform, OpenTofu,
Pulumi, CloudFormation, Kubernetes, and Ansible. Key features include drift detection,
OPA-based policies, self-service blueprints, dynamic credentials, and multi-tenancy.
Available as fully managed SaaS and FedRAMP-authorized self-hosted.

Spacelift exposes a GraphQL API (not REST) at `https://{account}.app.spacelift.io/graphql`.

## Artifacts

### Capabilities

- [Infrastructure Orchestration](capabilities/infrastructure-orchestration.yaml) — Workflow for managing IaC stacks, runs, policies, and worker pools

**Shared Definitions**
- [Spacelift GraphQL API](capabilities/shared/spacelift.yaml)

### JSON Schema

- [Stack Schema](json-schema/spacelift-stack-schema.json)

### JSON Structure

- [Stack Structure](json-structure/spacelift-stack-structure.json)

### JSON-LD

- [Spacelift Context](json-ld/spacelift-context.jsonld)

### Examples

- [Stack Example](examples/spacelift-stack-example.json)

### Vocabulary

- [Spacelift Vocabulary](vocabulary/spacelift-vocabulary.yml)

## Links

- [Website](https://spacelift.io/)
- [Documentation](https://docs.spacelift.io/)
- [GraphQL API](https://docs.spacelift.io/integrations/api)
- [GitHub](https://github.com/spacelift-io)
- [Pricing](https://spacelift.io/pricing)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
