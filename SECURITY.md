# Security Policy

This policy applies to reports concerning **Reliable Callback Sender — PostgreSQL (TPL-001)**. This GitHub repository is a **confidential reporting entry point** and does not contain the TPL-001 application or distributable image.

## In-scope reports

Security weaknesses affecting the TPL-001 application, its signed HTTPS callback behavior, authentication controls, distributed container image or Railway template configuration are welcome. Describe the affected installed version or digest if known. The maintainer determines whether a version is still maintained; this intake policy does not promise fixes for every historical version.

Railway platform faults, third-party service flaws, other customers' infrastructure, and customer-modified variants should also be reported to their respective operators or maintainers.

## Private reporting procedure

1. Open **Security → Advisories → Report a vulnerability** in this repository.
2. Submit the report **privately** through the GitHub advisory form.
3. Explain the suspected impact and use a **synthetic, non-destructive reproduction**. Include affected versions if known, but never paste live keys, tokens, raw logs, personal data or sensitive customer information.
4. Continue clarification and remediation discussion in the private GitHub advisory thread. If sensitive evidence is required, agree a separate protected channel with the maintainer before transmitting it.

If **Report a vulnerability** is not available, **do not** open a public issue or discussion containing vulnerability details. The private intake needs repair.

## Responsible handling

Do not test systems you do not own or have permission to assess, exfiltrate data, cause outages, or exploit other customers. We aim to assess valid findings privately and coordinate appropriate remediation and disclosure.

This is **not** a paid bug bounty, guarantee of security assurance, legal safe-harbor promise, SLA or 24-hour security-response service. There is **no guaranteed acknowledgement or fix deadline**. Publishing an advisory against this intake-only documentation repository must not misrepresent it as the vulnerable application.
