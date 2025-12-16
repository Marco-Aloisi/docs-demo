---
title: Getting started
summary: How to run, navigate, and search the SRE docs
tags:
  - onboarding
  - setup
  - how-to
---

# Getting started

This page explains how to run the site locally, navigate it, and find relevant content.

## Requirements

- Python 3.8+
- pip

## Install

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## First build

```bash
mkdocs build
```

or for development:

```bash
mkdocs serve
```

## Using the site

- Navigation: main sections (Onboarding, Environments, Runbooks, Operations, Architecture).
- Tags: shown under each page title; click to filter related content.
- Search: use the search bar with suggestions and highlights.
- Templates: see the Guide section for templates.

## Where to find things

- Onboarding: access, tools, and first steps.
- Environments: environment profiles (PROD, STAGING, customer-specific).
- Runbooks: operational procedures and incident response.
- Operations: observability standards and alerts.
- Architecture: ADRs and technical decisions.
