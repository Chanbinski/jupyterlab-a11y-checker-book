---
title: User Guide
---

# User Guide

## Running checks
- Open a notebook in JupyterLab.
- Open the A11y Checker panel.
- Run the scan to populate issues.

## Applying fixes
- Image alt text: enter alt text (AI suggestion optional).
- Headings: ensure a single H1, correct order, and non-empty content.
- Tables: add header(s), caption, and set `scope`.
- Color: note contrast issues and adjust content or theme.

See [](components/rules) and [](components/fix) for details.

## Configuring AI assistance
- Go to `Settings > Settings Editor > A11y Checker Settings`.
- Provide API endpoint, key, and model.

```{note}
Models are optional and used only within certain fix interfaces.
```
