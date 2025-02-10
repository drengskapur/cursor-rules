# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Here are the versions that are currently being supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take the security of Cursor Rules seriously. If you believe you have found a security vulnerability, please report it to us as described below.

### Where to Report

**Please DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to <security@cursor.sh> (if this email is not yet set up, please report to the repository maintainers directly).

You should receive a response within 48 hours. If for some reason you do not, please follow up via email to ensure we received your original message.

### What to Include

Please include the following information in your report:

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### What to Expect

- We will acknowledge your email within 48 hours
- We will send a more detailed response within 96 hours indicating the next steps in handling your report
- We will handle your report with strict confidentiality and not pass on your personal details to third parties without your permission
- We will keep you informed of the progress towards a fix
- We will credit you as the discoverer of the issue (unless you prefer to remain anonymous)

## Disclosure Policy

When we receive a security bug report, we will:

1. Confirm the problem and determine the affected versions
2. Audit code to find any potential similar problems
3. Prepare fixes for all supported versions
4. Release new versions and patches

## Comments on this Policy

If you have suggestions on how this process could be improved, please submit a pull request or open an issue to discuss.
