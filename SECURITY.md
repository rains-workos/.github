# Security Policy

## Reporting a Vulnerability

We take the security of RAINS WorkOS seriously.

If you believe you have discovered a security vulnerability in one of our repositories, please **do not report it through a public GitHub Issue, Pull Request, or Discussion**.

Instead, report the vulnerability privately to the RAINS WorkOS maintainers.

When reporting a vulnerability, please provide as much relevant information as possible, including:

* A description of the vulnerability
* The affected repository, component, or service
* Steps to reproduce the issue
* Potential impact
* Proof of concept, if available
* Any suggested mitigation

Please avoid including sensitive information beyond what is necessary to demonstrate the issue.

## What to Expect

After receiving a security report, the maintainers will:

1. Acknowledge the report when possible.
2. Assess and reproduce the reported issue.
3. Determine its severity and impact.
4. Develop and test an appropriate fix.
5. Coordinate disclosure when appropriate.

Please allow the maintainers reasonable time to investigate and address the issue before publicly disclosing the vulnerability.

## Security Best Practices

When contributing to RAINS WorkOS:

* Never commit passwords, API keys, access tokens, or private keys.
* Never commit production credentials or environment files containing secrets.
* Use environment variables or approved secret-management systems for sensitive configuration.
* Review dependencies for known vulnerabilities.
* Keep dependencies reasonably up to date.
* Avoid logging sensitive information.
* Follow the principle of least privilege.
* Do not expose internal infrastructure details unnecessarily.

## Sensitive Information

Do not include the following in Git commits, Issues, Pull Requests, or Discussions:

* Passwords
* API keys
* Access tokens
* Private keys
* Database credentials
* Production secrets
* Personal information
* Internal security configuration
* Other confidential information

If a secret is accidentally committed, **assume it is compromised** and rotate or revoke it immediately.

## Scope

This security policy applies to security issues affecting RAINS WorkOS repositories and associated software maintained by this organization.

Individual repositories may provide additional security requirements. Always follow the more restrictive requirement when applicable.

Thank you for helping keep RAINS WorkOS and its users secure.
