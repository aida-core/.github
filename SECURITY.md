# Security Policy

We take security seriously across all repos in the [AIDA](https://github.com/aida-core) organization. This document is the org-wide default — individual repos may publish a more specific policy, which takes precedence.

## Reporting a vulnerability

**Please do not file public GitHub issues for security vulnerabilities.** Public reports give attackers a head start before we can ship a fix.

Report vulnerabilities privately by either:

1. **GitHub private vulnerability reporting** — preferred. On the affected repo, click `Security` → `Report a vulnerability`. This routes the report to the maintainers privately and creates a tracking advisory.
2. **Email** — send to **github@oakensoul.com**. If you'd like to encrypt the report, request a public key in your initial message and we'll respond with one.

When reporting, please include:

- The affected repo, version, and (if applicable) commit SHA
- A description of the issue and its impact
- Steps to reproduce, including a proof-of-concept if you have one
- Any suggested mitigation
- How you'd like to be credited (or not) in the eventual advisory

## What to expect

| Stage | Target |
|---|---|
| Acknowledgement of report | Within **3 business days** |
| Initial triage / severity assessment | Within **7 days** of acknowledgement |
| Fix or mitigation plan communicated | Within **30 days** of acknowledgement, or sooner for critical issues |
| Public advisory & credit | After a fix ships and downstream users have had a reasonable patch window |

For high- or critical-severity issues we'll work toward shipping a coordinated disclosure with you.

## Scope

In scope:

- Vulnerabilities in code published in `aida-core/*` repos
- Issues in plugin update tooling, marketplace metadata, or CI workflows that could enable supply-chain compromise
- Credential or secret leaks in repo history or releases

Out of scope:

- Bugs in third-party dependencies (please report upstream; we're happy to coordinate)
- Issues requiring physical access to a developer's machine
- Social engineering of maintainers
- Vulnerabilities in unsupported, deprecated, or end-of-life versions

## Recognition

We're happy to credit reporters in the published advisory unless you prefer to remain anonymous. We don't currently run a paid bug-bounty program.

Thank you for helping keep AIDA users safe.
