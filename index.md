---
title: Introduction
---

## jupyterlab-a11y-checker

jupyterLab-a11y-checker is a JupyterLab extension that helps authors detect and fix accessibility issues in Jupyter Notebooks, aligning with WCAG 2.1 AA guidelines. It combines the strengths of axe-core, a widely used accessibility engine, with custom notebook-specific detection algorithms that address issues axe cannot reliably cover in JupyterLab. Specifically the extension can:

- Detect issues in image, heading, table, and color contrast category (see [Rules](components/rules#rules-index)).
- Apply targeted fixes via guided interfaces (see [Fix Interfaces](components/fix#fix-ui-index)).
- Optionally use AI assistance (LLM / VLM) to draft suggestions for certain issues.

Repository: [jupyterlab-a11y-checker on GitHub](https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker)

```{figure} images/overview.png
:name: fig-overview
:alt: Screenshot of the a11y checker panel in JupyterLab

The extension detects accessibility issues in a notebook and provides fixes.
```

## Components
- [Rules](components/rules)
- [Fix Interfaces](components/fix)
- [AI Assistance](components/ai-assistance)

## More
- [Examples Intro](examples/intro)
