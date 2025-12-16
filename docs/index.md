---
title: Home
summary: Navigation hub for SRE documentation
hide:
    - toc
    - navigation
---

# Welcome

This is the SRE documentation hub. Start with the Guide to learn how to add content, then explore Environments, Operations, and Architecture.

[Get started](guide/getting-started.md){ .md-button .md-button--primary }
[Contributing](guide/contributing.md){ .md-button }
[Tagging guide](guide/tagging-guide.md){ .md-button }
[Official tags](guide/official-tags.md){ .md-button }

---

## Explore

<div class="grid cards" markdown>

- **Guide**  
	How to write docs, templates, and tagging.  
	[Open](guide/index.md)

- **Onboarding**  
	First steps, access, tools.  
	[Open](onboarding/index.md)

- **Environments**  
	PROD, STAGING, and customer-specific profiles.  
	[Open](environments/index.md)

- **Operations**  
	Observability, monitoring, and alerts standards.  
	[Open](operations/index.md)

- **Architecture**  
	ADRs and architectural guidelines.  
	[Open](architecture/index.md)

</div>

---

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Local site: http://127.0.0.1:8000/
