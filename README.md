# Dev Testing Account for App Pre-Release

This repository is used exclusively for **testing and validating new features, updates, and fixes** before the final deployment to production or public release channels.

## Purpose

The dev testing account provides a safe environment to:

- Test in-development builds of the app
- Validate feature behavior before public release
- Perform QA checks, bug fixes, and regression testing
- Simulate user interactions in a pre-production environment

## Usage

- All builds pushed to this account should be considered **unstable** or **in testing**.
- Feedback and bug reports should be logged through the issue tracker or designated testing feedback system.
- Do **not** share or distribute builds from this account externally unless explicitly approved.

## Workflow

1. **Develop features** in feature branches or test environments.
2. **Deploy** builds to this dev account.
3. **Test** functionality thoroughly (manual QA or automated).
4. **Fix issues** and re-test.
5. Once stable, **promote the build** to staging/production/public channels.

## Notes

- Ensure sensitive data (API keys, credentials, etc.) are not hardcoded in test builds.
- This account may have access to internal tools or test-only APIs that differ from production.
---

**Disclaimer:** This account is for internal testing purposes only and is not intended for public distribution or review.

## 🛠 Setup

To set up the app locally for testing:

```bash
git clone git@github.com:alidev-acc/test.git

cd test
npm install
