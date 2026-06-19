# Contributing to cdisc-org

Thank you for contributing to CDISC's open source work. This guide explains how we estimate and track work across all repositories in the `cdisc-org` organization so that progress can be reported consistently to CDISC leadership and the broader community.

---

## Table of Contents

1. [Work Estimation Overview](#work-estimation-overview)
2. [T-Shirt Size Scale](#t-shirt-size-scale)
3. [Submitting Issues](#submitting-issues)
4. [GitHub Project Workflow](#github-project-workflow)
5. [For Outside Collaborators](#for-outside-collaborators)
6. [How This Feeds Leadership Reporting](#how-this-feeds-leadership-reporting)

---

## Work Estimation Overview

We use **T-shirt sizing** to estimate the effort, complexity, and uncertainty of each issue. T-shirt sizes are a relative measure — not hours or days — which keeps estimates consistent across team members, time zones, and varying levels of technical background.

The core principle: every issue is estimated *relative to other issues*, not in absolute time. A Medium issue is roughly twice as complex as a Small one. Over time, the distribution of sizes across a milestone gives leadership a reliable picture of scope and progress.

This approach is used by the CDISC Data Science and COSA teams and is designed to be accessible to both internal contributors and outside collaborators.

---

## T-Shirt Size Scale

| Size | Meaning | Rough Guidance | Example |
|------|---------|----------------|---------|
| **XS** | Trivial | A few hours | Update a config value, fix a typo in documentation |
| **S** | Small | Half a day to a day | Add a field to an existing schema, update a README section |
| **M** | Medium | A few days | Implement a small new feature with clear requirements |
| **L** | Large | About a week | Refactor a module, new API endpoint, multi-repo coordination |
| **XL** | Extra Large | Multi-week | Major architectural change or new integration — consider breaking down |

> **Rule of thumb:** XL issues should be broken into smaller, independently deliverable issues before work begins whenever possible.

---

## Submitting Issues

When opening a new issue in any `cdisc-org` repository:

- **Set your own T-Shirt Size** — as the issue owner, you are responsible for selecting the size that best reflects the effort and complexity of your issue. Use the scale above as your guide.
- **Write clear acceptance criteria** — the single biggest driver of estimation accuracy is understanding *what done looks like*. Use the format:
  ```
  Given [context], when [action], then [expected result].
  ```
- **Link related issues** — if your issue depends on or is blocked by another, note it in the description.
- **Use the issue template** if one exists in the repository.

If you are unsure of the right size, pick your best estimate and add a comment explaining your reasoning — a maintainer may adjust it if needed.

---

## GitHub Project Workflow

All issues across `cdisc-org` repositories are tracked in the **CDISC IT & Open Source Org-Level Project**. Issues move through the following workflow:

| Status | Meaning |
|--------|---------|
| **Backlog** | Issue is open but not yet estimated or scheduled |
| **Ready** | Estimated and ready to be pulled into a sprint |
| **In Progress** | Actively being worked on in the current sprint |
| **In Review** | Pull request open, awaiting review |
| **Done** | Merged and closed |

**Custom fields on every issue:**

- **T-Shirt Size** — XS / S / M / L / XL, set by the issue owner when the issue is created
- **Iteration** — The sprint this issue is assigned to (2-week cycles)
- **Milestone** — The release or roadmap milestone this issue contributes to

---

## For Outside Collaborators

Welcome — we are glad to have you. Here is what you need to know:

- **Open issues freely.** Set the T-Shirt Size field to your best estimate of the effort involved — use the scale in this guide.
- **Pull requests are welcome** for issues labeled `good first issue` or `help wanted`.
- **If you are picking up an unassigned issue**, leave a comment so the team can confirm it is ready and assign it to you.
- **Milestone dates are set by the core team.** If you are working toward a milestone, check with the issue author or a maintainer to confirm the target date is still accurate.
- **Questions?** Open a discussion in the relevant repository or reach out via the COSA community channels.

All contributions, regardless of source, are tracked in the same GitHub Project so that reporting to CDISC leadership is unified.

---

## How This Feeds Leadership Reporting

T-shirt sizes and iterations feed two key views used for leadership reporting:

**Size distribution** — Shows the breakdown of XS / S / M / L / XL work remaining in a milestone. This gives leadership an at-a-glance read on scope: a milestone heavy in L and XL issues is a different conversation than one that is mostly S and M.

**Milestone roadmap** — Each repository's milestones have target end dates. The org-level project roadmap view shows all active milestones across repos on a timeline, giving leadership a single view of what is in flight and when it is expected to land.

These views are available in the GitHub Project's **Insights** tab and are refreshed automatically as issues are updated.

---

*This document is maintained by the CDISC IT team. For questions about the estimation process, contact [jbclark@cdisc.org](mailto:jbclark@cdisc.org).*
