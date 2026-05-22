# Security Policy

RizQara Tech takes security seriously. This document explains how security issues should be handled across RizQara Tech repositories and projects.

---

## Supported Projects

Security support applies to active RizQara Tech repositories, demos, internal systems, SaaS products, and client-approved projects.

| Project Type | Security Support |
|---|---|
| Active company products | Supported |
| Client projects | Supported based on agreement |
| Public demos | Best-effort support |
| Archived projects | Not actively supported |
| Experimental concepts | Best-effort support |

---

## Reporting a Security Issue

If you discover a security issue, do not open a public GitHub issue.

Please report it privately:

**Email:** rizqaratech@gmail.com  
**Subject:** Security Report – [Repository Name]

Include:

- Repository name
- Description of the issue
- Steps to reproduce
- Impact level
- Screenshots or logs if available
- Suggested fix if you have one

---

## What Not to Share Publicly

Please do not publicly disclose:

- API keys
- Authentication bypass methods
- Database credentials
- Admin panel URLs with private access
- User data
- Client-sensitive information
- Payment gateway details
- Exploit scripts

---

## Security Best Practices for Team Members

### Environment Variables
Never commit `.env` or `.env.local` files.

Use:

```text
.env.example
```

for showing required environment variable names without real values.

### Access Control
Only approved team members should have repository access. Access should be removed when a member leaves a project.

### Passwords and Credentials
Use strong passwords and avoid sharing credentials in chat, screenshots, commits, or public documents.

### Dependencies
Keep dependencies updated and review security warnings before deployment.

### Client Data
Client data must be handled carefully and should never be added to public repositories.

---

## Common Security Checklist

Before deployment, check:

- No secrets are committed.
- Admin routes are protected.
- Authentication works properly.
- User roles and permissions are tested.
- Forms have validation.
- API endpoints are protected.
- Payment or order data is handled safely.
- Database rules are configured correctly.
- Error messages do not reveal sensitive details.

---

## Response Process

When a security issue is reported:

1. RizQara Tech reviews the report.
2. The issue is confirmed and prioritized.
3. A fix is prepared and tested.
4. The fix is deployed or released.
5. The reporter may be updated when appropriate.

---

## Responsible Disclosure

We appreciate responsible security reporting. Please give RizQara Tech reasonable time to review and fix the issue before any public disclosure.

---

## Contact

**RizQara Tech**  
Website: https://www.rizqara.tech  
Email: rizqaratech@gmail.com  
Phone: 01343042761
