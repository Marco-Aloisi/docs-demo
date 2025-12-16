---
title: Tagging guide
summary: How to use and maintain tags on pages
tags:
  - guidelines
  - tagging
  - how-to
---

# Tagging guide

Tags help classify pages by activity and scope (e.g., `onboarding`, `incident`, `devops`, `backend`, `runbook`).

## How to add tags

Add front matter at the beginning of the Markdown file:

```yaml
---
title: Page name
summary: Optional description
tags:
  - runbook
  - devops
---
```

## Conventions

- Use 1–3 primary tags and reuse them (avoid unnecessary synonyms).
- Prefer lowercase-kebab-case: `devops`, `how-to`, `incident-response`.
- Avoid tags that duplicate the section name (e.g., `guide`, `docs`).
- Operational: `runbook`, `incident`, `maintenance`.
- Technical domain: `backend`, `frontend`, `data`, `infra`, `security`.
- Lifecycle: `onboarding`, `setup`, `troubleshooting`, `best-practices`.

## Search by tag

- Tags appear as chips under the title.
- Use the search box and type the tag name to quickly filter related pages.
