# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in OpenCrMS, please report it responsibly. **Do not open a public GitHub issue.**

To report a vulnerability, use one of the following methods:

* **GitHub Private Vulnerability Reporting:** [Report a vulnerability](https://github.com/opencrms/OpenCrMS/security/advisories/new)
* **Email:** Send a report to [TODO: security email, e.g. security@opencrms.dev]

Please include in your report:

* Description of the vulnerability
* Steps to reproduce the issue
* Affected versions
* Any potential impact you have identified

## Response Timeline

The OpenCrMS security team will acknowledge receipt of your report within **3 business days** and will provide an estimated timeline for a fix within **10 business days**.

The team will keep you informed of progress toward a fix and may ask for additional information.

## Supported Versions

<!-- TODO: Update this table with your project's supported versions -->

| Version | Supported |
| ------- | --------- |
| x.y.z   | Yes       |
| < x.y   | No        |

## Disclosure Policy

When a security issue is confirmed, the OpenCrMS team will:

1. Develop and test a fix
2. Assign a CVE identifier if appropriate
3. Release a patched version
4. Publish a security advisory via [GitHub Security Advisories](https://github.com/opencrms/OpenCrMS/security/advisories)

## Security Response Team

The security response team handles all reports of security vulnerabilities according to this policy. See [GOVERNANCE.md](GOVERNANCE.md) for how the security response team is appointed and maintained.

Current security response team members are listed in [MAINTAINERS.md](MAINTAINERS.md) or designated by the maintainer council.

## Security Best Practices

Projects advancing through the [LF Decentralized Trust project lifecycle](https://lf-decentralized-trust.github.io/governance/governing-documents/) are expected to demonstrate:

* [OpenSSF Best Practices Badge](https://www.bestpractices.dev/) - [TODO: Add your badge link, e.g. ![OpenSSF Best Practices](https://www.bestpractices.dev/projects/NNNN/badge)]
* A completed security self-assessment, reviewed as part of the LFDT Technical Advisory Council (TAC) project review process
* Dependency management via automated tools (e.g. Dependabot, Renovate)
* Signed releases and/or Software Bill of Materials (SBOM)
