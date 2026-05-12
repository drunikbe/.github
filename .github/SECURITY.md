# Security Policy

DRUNIK BV takes the security of our software seriously. This policy applies to all repositories under the [drunikbe](https://github.com/drunikbe) GitHub organization.

## Reporting a vulnerability

**Please do not open a public issue for security vulnerabilities.**

Email **security@drunik.be** with:

- A description of the vulnerability and its potential impact
- Steps to reproduce, or a proof of concept
- The affected repository and version/commit (if known)
- Your name and a way to credit you in the disclosure, if you'd like

You can encrypt your email with our PGP key on request.

## What to expect

- **Acknowledgement**: within 5 business days of your report
- **Triage and assessment**: within 10 business days, including a severity estimate and a rough timeline for the fix
- **Coordinated disclosure**: we agree a public disclosure date with you once a fix is ready; we'll credit you in the advisory unless you'd rather stay anonymous

## Scope

In scope: any code, container image, or service published under [github.com/drunikbe](https://github.com/drunikbe).

Out of scope: third-party services we depend on (report those to the vendor), social-engineering attacks, denial-of-service that requires unreasonable resources.

## Supported versions

We patch the `main` branch of each repository. Older versions are not maintained unless a repository's own README specifies otherwise.
