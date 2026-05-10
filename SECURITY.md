# Security Policy

## Supported Versions

This project is a static frontend website. Security updates are applied to the latest version of the project.

| Version        | Supported |
| -------------- | --------- |
| Latest         | Yes       |
| Older versions | No        |

## Reporting a Vulnerability

If you discover a security issue, please report it responsibly.

Do not publicly disclose security vulnerabilities before they have been reviewed.

You can report a vulnerability by opening a GitHub issue with limited sensitive details or by contacting the maintainer directly through GitHub:

```txt
https://github.com/power0matin
```

## What to Report

Please report issues such as:

- Exposed sensitive data
- Insecure external links
- Malicious injected scripts
- Unsafe form integrations
- Incorrect deployment configuration
- Privacy issues caused by future integrations
- Vulnerabilities introduced by third-party services

## Out of Scope

The following are generally out of scope for this static project:

- Missing backend rate limits when no backend exists
- Server-side vulnerabilities when the project is hosted only as static files
- Payment security when no payment integration exists
- Authentication issues when no authentication system exists

## Security Notes

This project does not include by default:

- Backend code
- Authentication
- Database access
- Payment processing
- User data storage
- API keys

If these features are added later, make sure to:

- Use HTTPS
- Validate inputs server-side
- Never expose API keys in frontend code
- Add rate limiting
- Add spam protection
- Add a privacy policy
- Add terms of service
- Store only necessary user data

## Response Process

When a vulnerability is reported:

1. The report will be reviewed.
2. The issue will be reproduced if possible.
3. A fix will be prepared.
4. The fix will be released.
5. Credit may be given to the reporter if requested.

## Responsible Disclosure

Please give the maintainer reasonable time to investigate and resolve the issue before public disclosure.
