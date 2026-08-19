<div align="center">

# Terraform Template Baseline

**Incubating infrastructure baseline for projects built from the
`@teo-garcia` application templates**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Terraform](https://img.shields.io/badge/Terraform-incubating-844FBA?logo=terraform&logoColor=white)](https://terraform.io)

Part of the [@teo-garcia/templates](https://github.com/teo-garcia/templates)
ecosystem

</div>

---

## Status

This repository is incubating. It defines the intended infrastructure boundary
but does not yet contain deployable modules. Planning and open design questions
live in the portfolio [roadmap](https://github.com/teo-garcia/templates/blob/main/ROADMAP.md#terraform-baseline).

---

## Intended Scope

| Capability | Contract |
| --- | --- |
| Networking | VPC, subnets, and constrained security groups |
| Identity | Least-privilege service roles and policies |
| Data | Managed Postgres and optional object storage |
| Secrets | Provider-native secrets management |
| Routing | DNS zones and application records |

---

## Non-Goals

- Deploying application code or containers
- Managing Kubernetes cluster internals
- Hiding provider behavior behind a single cross-cloud abstraction

---

## Activation Criteria

Scaffolding begins when a second real project needs the same infrastructure and
can validate which inputs and modules are genuinely reusable.

---

## License

MIT

---

<div align="center">
  <sub>Built by <a href="https://github.com/teo-garcia">teo-garcia</a></sub>
</div>
