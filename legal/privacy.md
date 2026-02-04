# PRNudge Privacy Policy

_Last updated: 2026/02/04

This Privacy Policy explains how **PRNudge** ("we", "us") collects, uses, and shares information when you install and use the PRNudge GitHub App (the "Service").

If you have questions, contact us at: **support@prnudge.com**.

## 1. What data we collect

When you install the GitHub App and enable repositories, we may process:

- **GitHub identifiers and metadata**
  - Installation ID, repository ID, repository name/full name, owner/org login.
- **Pull Request and Review metadata**
  - PR number, PR ID, PR title, PR URL, open/closed state, draft state, timestamps (opened, closed, first review time).
- **Operational data**
  - Webhook delivery IDs and minimal payload metadata used for idempotency and debugging.
  - Logs related to job execution (daily nudges, weekly reports).

We do **not** need or intend to collect:
- Your GitHub password
- Private code contents from your repository (unless required by GitHub API responses; PRNudge focuses on PR metadata)
- Sensitive personal data

## 2. How we use the data

We use the data to:
- Detect pull requests that have not received a first review within a configured threshold (default: 3 days).
- Post PR comments ("nudges") to help teams reduce time-to-first-review.
- Generate a weekly report issue per repository.
- Maintain reliability and security (rate limiting, retries, abuse prevention).
- Provide support and troubleshoot incidents.

## 3. Legal basis (EEA/UK users)

Where applicable, we process data under:
- **Legitimate interests** to provide and improve the Service (nudges and reporting), and to secure operations.
- **Contract necessity** when you use the Service under these Terms.

## 4. Data retention

We keep data only as long as needed to operate the Service:
- Webhook delivery records used for idempotency and debugging are retained for a limited period (for example, **14 days**).
- Repository/PR metadata may be retained while the installation remains active, and for a limited period after uninstall for support and integrity reasons.

You can request deletion of stored data associated with an installation by contacting **support@prnudge.com**.

## 5. Sharing and third-party processors

We share data only with service providers needed to run PRNudge, such as:
- Hosting and compute (e.g., **Fly.io**)
- Database (e.g., **Neon / PostgreSQL**)
- DNS/TLS or security services (e.g., **Cloudflare**)

We do **not** sell personal data.

GitHub is a separate controller for your GitHub account and repository data. The Service operates via GitHub’s APIs and webhooks.

## 6. Security

We implement reasonable technical and organizational measures, including:
- Token-based authentication for internal job endpoints
- Principle of least privilege for GitHub App permissions
- Access controls for infrastructure and databases

No system is 100% secure. If you believe your installation is compromised, contact **support@prnudge.com**.

## 7. Your rights

Depending on your location, you may have rights to:
- Access, correct, or delete your information
- Object to or restrict processing
- Data portability

To exercise rights, contact **support@prnudge.com**.

## 8. International transfers

If you are located outside the country where our infrastructure runs, your data may be processed in other jurisdictions. We take reasonable steps to protect data during transfers.

## 9. Changes to this policy

We may update this policy from time to time. We will update the "Last updated" date and, when appropriate, provide additional notice.

## 10. Contact

**PR Nudge Inc.**  
Email: **support@prnudge.com**
