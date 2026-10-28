# TPL-001 — Confidential Security Reports

This repository provides a **security-reporting entry point only** for the **Reliable Callback Sender — PostgreSQL (TPL-001)** Railway template.

It does **not** contain application source code, container images, credentials, or customer data. The runtime and distribution repositories are private. The CC0 `LICENSE` file in this security-contact repository applies only to material published **in this repository**, not to any proprietary TPL-001 source code, container image, or separate repository.

## Report a vulnerability

Use this repository's **Security → Advisories → Report a vulnerability** feature to contact the maintainer privately. GitHub privately shares reports with the repository's authorized advisory participants; your report is **not a public issue**.

If the **Report a vulnerability** option is unavailable, the private intake is not functioning. **Do not post the report, exploit details, logs or secrets to a public issue, pull request or Railway discussion.**

For the initial private report, provide a concise description of the suspected flaw, affected TPL-001 version or image digest *if known*, expected impact and reproduction conditions using synthetic data. You may suggest a way to reproduce safely. **Do not include** live credentials, HMAC signing keys, registry access tokens, database URLs, personal data, third-party secrets or raw customer payloads. Arrange another secure transfer method with the maintainer if sensitive evidence is genuinely required.

## Supported scope

Reports about defects in the TPL-001 application or its provided template configuration are relevant. Railway platform incidents, other people's infrastructure, a customer's HTTPS receiver, or modifications to the software are outside the publisher's direct control; report those to their responsible maintainers.

The published GitHub repository is an **intake channel, not the affected software package**. GitHub advisories are repository-scoped: the maintainer will investigate and decide how to fix and disclose a TPL-001 vulnerability in the correct software/distribution context. No advisory should falsely identify this documentation-only repository as the vulnerable runtime.

## Coordination and support

Security reports are reviewed on a **best-effort** basis; **no SLA, 24/7 monitoring, bounty or guaranteed response or resolution time** is offered. Please allow the maintainer to investigate and coordinate a proportionate disclosure before releasing exploit details publicly.

For ordinary deployment or configuration questions, use the Railway template's **Discuss this Template / Template Queue** channel when the listing is available. The intended general-support policy is weekly queue review and best-effort acknowledgement within five business days, with no SLA. Do not post confidential security findings in that public discussion.
