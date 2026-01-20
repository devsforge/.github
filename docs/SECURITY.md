---
status: draft
owner: /orgs/devsforge/teams/security @security
---

[draft]: https://img.shields.io/badge/document_status-draft-orange
[ready]: https://img.shields.io/badge/document_status-ready-cyan
[final]: https://img.shields.io/badge/document_status-final-blue

# Security Policy

![document status][draft]

<details>
<summary>Document Changelog</summary>

| Ver. | Date       | Author           | Change description         |
|------|------------|------------------|----------------------------|
| 0.9  | 2025-01-20 | Serhii Horodilov | Final draft                |
| 0.2  | 2025-01-19 | Serhii Horodilov | Update Attribution section |
| 0.1  | 2025-01-19 | Serhii Horodilov | Initial draft              |

</details>

## Reporting a Vulnerability

We take security vulnerabilities seriously and appreciate responsible
disclosure from the community.

### Primary Channel: GitHub Private Vulnerability Reporting

For all security-related reports, please use GitHub's private vulnerability
reporting feature. This is available on each repository under the "Security"
tab.

1. Navigate to the affected repository
2. Click on the "Security" tab
3. Select "Report a vulnerability"
4. Fill out the vulnerability report form

This method ensures your report remains confidential and reaches our security
team directly.

### Secondary Channel: Email

If you are unable to use GitHub's reporting feature, you may contact us via
email at [todo: add email].

Please encrypt sensitive information when possible.

### What to Include in Your Report

To help us address the issue efficiently, please include:

- A clear description of the vulnerability
- Steps to reproduce the issue
- Affected repository and version (if applicable)
- Potential impact assessment
- Any proof-of-concept code or screenshots (if available)
- Your recommendations for remediation (optional)

### What Not to Do

- Do not publicly disclose the vulnerability before it has been addressed
- Do not exploit the vulnerability beyond what is necessary to demonstrate it
- Do not access, modify, or delete data belonging to others

## What to Expect

### Response Timeline

- **Initial acknowledgment**: within 24 hours
- **Status update**: within 7 days of acknowledgment
- **Resolution timeline**: varies depending on severity and complexity

### Our Process

1. **Acknowledgment**: We confirm receipt of your report
2. **Assessment**: Our security team evaluates the vulnerability
3. **Remediation**: We develop and test a fix
4. **Release**: We deploy the fix and notify affected parties
5. **Disclosure**: We coordinate with you on public disclosure (if applicable)

We will keep you informed throughout the process and credit you for the
discovery (unless you prefer to remain anonymous).

## Scope

This security policy applies to all repositories within the OpenRoost
organization, including both public and private repositories.

### In Scope

- Security vulnerabilities in OpenRoost-maintained code
- Configuration issues that could lead to security exposure
- Authentication and authorization flaws
- Data exposure risks

### Out of Scope

- Vulnerabilities in third-party dependencies (please report these to the
  respective maintainers, but do let us know so we can update)
- Social engineering attacks
- Physical security concerns
- Denial-of-service attacks that do not reveal an underlying vulnerability

## Security Practices for Contributors

We encourage all contributors to follow these security practices:

- **Never commit secrets**: Do not commit API keys, passwords, tokens, or other
  sensitive credentials to repositories
- **Keep dependencies updated**: Regularly update dependencies to patch known
  vulnerabilities
- **Review your code**: Check for common security issues before submitting pull
  requests
- **Use signed commits**: Where possible, sign your commits with GPG to verify
  authenticity
- **Report suspicious activity**: If you notice anything unusual in our
  repositories or dependencies, please let us know

## Supply Chain Security

We are committed to maintaining the integrity of our software supply chain.
Contributors should be vigilant about the packages and dependencies they
introduce:

- Verify the authenticity of packages before adding them as dependencies
- Prefer well-maintained packages with active communities
- Report any suspicious packages or unexpected behavior to our security team

## Security Team

Security reports and incidents are handled by our dedicated security team. For
general security inquiries, please use the channels listed above.

---

## Attribution

This Support document is inspired by community best practices and open source
community standards.

**License:**

This Support document is licensed under
[Creative Commons Attribution 4.0 International License][CC-BY-4.0].

You are free to adapt and use this document for your own community, with
attribution to OpenRoost.

[CC-BY-4.0]: https://creativecommons.org/licenses/by/4.0/
