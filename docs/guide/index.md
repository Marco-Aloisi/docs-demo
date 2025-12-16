---
title: Guide
summary: How to add content and use templates
tags:
  - guide
  - how-to
  - templates
---

# Guide

This section explains how to add content and leverage templates.

## Structure → Automatic navigation

- Navigation is generated from the folder structure under `docs/`.
- To add a new section, create a folder (e.g., `docs/environments/customer-xyz/`).
- To add a section landing page, create an `index.md` inside that folder.
- Menu labels come from the page `title:` in the front matter or from the H1.

## Available templates

- Runbook: `docs/templates/template-runbook.md`
- Environment: `docs/templates/template-environment.md`
- ADR: `docs/templates/template-adr.md`

## Examples

```bash
# New runbook
cp docs/templates/template-runbook.md docs/runbooks/backup-restore.md

# New environment (customer-specific)
mkdir -p docs/environments/customer-xyz
cp docs/templates/template-environment.md docs/environments/customer-xyz/overview.md
```

## Good practices

- Use 1–3 consistent tags (see "Tagging guide" and "Official tags").
- Keep pages short, include prerequisites, steps, rollback, and validation.
- Add a `title:` in front matter for clean menu labels.
