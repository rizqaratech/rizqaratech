# Contributing to RizQara Tech Repositories

Thank you for your interest in contributing to RizQara Tech projects.

This document explains how team members, collaborators, and approved contributors should work on RizQara Tech repositories professionally.

---

## Contribution Policy

Most RizQara Tech repositories are company-owned or client-related. Contributions are accepted only from approved team members, collaborators, or invited contributors.

Before contributing, make sure you have permission from the RizQara Tech management or project lead.

---

## Our Development Workflow

We follow this simple workflow:

```text
Issue / Task → Branch → Development → Pull Request → Review → Merge → Deploy
```

### 1. Task Assignment
Every contribution should be connected to a task, feature request, bug report, or approved improvement.

### 2. Create a Branch
Use clear branch names:

```bash
feature/homepage-redesign
feature/payment-integration
fix/login-validation
fix/mobile-navbar
update/readme-docs
```

Avoid branch names like:

```bash
new-update
final-work
sami-change
last-final-version
```

### 3. Write Clean Code
Follow these rules:

- Use readable variable and function names.
- Keep components small and reusable.
- Remove unused code, logs, and test files before final commit.
- Keep UI consistent with the RizQara Tech design system.
- Do not expose private credentials or sensitive logic.

### 4. Commit Message Format
Use professional commit messages:

```bash
feat: add restaurant order dashboard
fix: resolve mobile menu overflow issue
update: improve README documentation
refactor: clean product card component
style: improve pricing section spacing
```

### 5. Pull Request Rules
Every pull request should include:

- Summary of changes
- Screenshots for UI changes
- Testing notes
- Related issue/task reference if available

Example:

```md
## Summary
Added responsive pricing cards for the service page.

## Changes
- Created pricing card component
- Added mobile responsive layout
- Updated CTA button style

## Testing
Checked desktop and mobile layout.
```

---

## Code Quality Rules

Before submitting work, check:

- The project runs without errors.
- Responsive design works on mobile and desktop.
- No secret keys or `.env` files are committed.
- No unnecessary files are uploaded.
- UI spacing and typography are consistent.
- Broken links are fixed.

---

## Security Rules

Never commit:

```text
.env
.env.local
API keys
Database passwords
Firebase private keys
Payment gateway credentials
Admin credentials
Client private data
```

Use `.env.example` for showing required environment variables.

---

## Design Guidelines

RizQara Tech prefers:

- Clean white background
- Deep maroon brand accents
- Minimal premium layouts
- Clear CTA buttons
- Mobile-first responsive design
- Trust-focused business UI
- Simple and readable content

---

## Documentation Rules

Every important repository should include:

```text
README.md
LICENSE
CONTRIBUTING.md
SECURITY.md
CODE_OF_CONDUCT.md
CHANGELOG.md
```

The README should explain:

- Project purpose
- Features
- Tech stack
- Installation
- Screenshots
- Live demo
- Status
- Contact

---

## Review Process

A project lead or manager will review:

- Functionality
- UI quality
- Security
- Code readability
- Business requirement match
- Deployment readiness

Work should not be merged until it is reviewed and approved.

---

## Contact

For contribution access or project questions:

**RizQara Tech**  
Website: https://www.rizqara.tech  
Email: rizqaratech@gmail.com  
Phone: 01343042761
