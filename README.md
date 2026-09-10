<div align="center">

# Skillar.ai / .github

**Organization defaults, community health templates, and workflow blueprints.**

[![Organization](https://img.shields.io/badge/Organization-Skillar.ai-blueviolet?style=for-the-badge)]()
[![Scope](https://img.shields.io/badge/Scope-Global_Defaults-blue?style=for-the-badge)]()
[![Maintenance](https://img.shields.io/badge/Maintained_by-Core_Team-cyan?style=for-the-badge)]()

</div>

---

### Overview

This repository acts as the global blueprint for the **Skillar.ai** GitHub organization. Files placed here provide organization-wide defaults that automatically apply to every repository in `skillar-ai`, eliminating the need to duplicate standard templates and policies across projects.

---

### Repository Architecture

| Path | Type | Purpose |
| :--- | :--- | :--- |
| **`.github/ISSUE_TEMPLATE/bug_report.md`** | Issue Template | Structured bug intake with reproduction steps, logs, and environment specs. |
| **`.github/ISSUE_TEMPLATE/feature_request.md`** | Issue Template | Feature intake capturing problem context, target users, and proposed workflows. |
| **`.github/PULL_REQUEST_TEMPLATE.md`** | PR Template | Structured pull request format with change categorization and verification checklist. |
| **`profile/README.md`** | Organization Profile | Public profile rendered on the [github.com/skillar-ai](https://github.com/skillar-ai) landing page. |
| **`CONTRIBUTING.md`** | Engineering Policy | Branching rules, PR requirements, code review policies, and merge conventions. |

---

### Global Inheritance

GitHub uses this repository to enforce organization-wide consistency:

| Mechanism | Description |
| :--- | :--- |
| **Default Fallback** | Any repository under `skillar-ai` that lacks its own templates or guidelines inherits these files automatically. |
| **Granular Overrides** | Any repository can override a global template by adding its own version under its local `.github/` folder. |
| **Unified Triage** | Contributors across all repos receive consistent issue forms labeled for streamlined triage. |

---

### Quick Links

| Resource | Destination |
| :--- | :--- |
| **Organization Landing Page** | [github.com/skillar-ai](https://github.com/skillar-ai) |
| **Contribution Guidelines** | [CONTRIBUTING.md](./CONTRIBUTING.md) |
| **Bug Report Template** | [.github/ISSUE_TEMPLATE/bug_report.md](./.github/ISSUE_TEMPLATE/bug_report.md) |
| **Feature Request Template** | [.github/ISSUE_TEMPLATE/feature_request.md](./.github/ISSUE_TEMPLATE/feature_request.md) |
| **Pull Request Template** | [.github/PULL_REQUEST_TEMPLATE.md](./.github/PULL_REQUEST_TEMPLATE.md) |

---

<div align="center">

### Engineering Operations

Core infrastructure and repository standards maintained by the Skillar.ai team.

`hello@skillar.ai`

Operating Global Remote | Based in Jaipur, India

</div>