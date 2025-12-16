---
title: Contributing
summary: How to create and add new pages to the SRE docs
tags:
  - guidelines
  - how-to
  - contributing
---

# Contributing

This guide explains how to create new pages, use templates, and keep tags consistent.

## Add a new page

1. Choose the correct section (Runbooks, Environments, Operations, Architecture, Onboarding).
2. Create a Markdown file with front matter:
   ```yaml
   ---
   title: Page title
   summary: Short description
   tags:
     - how-to
     - backend
   ---
   ```
3. Save the file under `docs/` in the appropriate folder.
4. No menu changes needed: navigation is generated automatically from the folder structure.

## Useful templates

- Runbook: `docs/templates/template-runbook.md`
- Environment: `docs/templates/template-environment.md`
- ADR: `docs/templates/template-adr.md`

Examples:
```bash
# New runbook
cp docs/templates/template-runbook.md docs/runbooks/backup-restore.md

# New environment (customer-specific)
mkdir -p docs/environments/customer-xyz
cp docs/templates/template-environment.md docs/environments/customer-xyz/overview.md
```

## Tag conventions

- Use 1–3 primary tags, lowercase-kebab-case: `runbook`, `prod`, `observability`.
- Reuse official tags listed in `docs/guide/official-tags.md`; propose new tags via PR.
- Types: `runbook`, `how-to`, `adr`, `reference`.
- Domain: `backend`, `frontend`, `devops`, `data`, `security`, `observability`.
- Environment: `prod`, `staging`, `dev`, `customer-xyz`.
