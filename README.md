# Shruti Sonavane · Portfolio

Personal portfolio for Shruti Sonavane, AI/ML Engineer: RAG systems, LLM agents, and production ML.

**Live:** https://shruti052001.github.io/

## Features

- Light / dark theme toggle (follows system preference, remembers your choice)
- "Ask about Shruti" mini retrieval bot with cited answers
- Interactive experience tabs, project cards with detail modals, filterable skills
- Responsive on laptop and mobile, with a one-click résumé download

## Stack

A single static `index.html` (HTML, CSS, and vanilla JS) with no build step. Fonts come from Google Fonts.

```
index.html
assets/
  Shruti_Sonavane_Resume.pdf
  og-image.png        # link preview image for LinkedIn and other social sites
```

## Run locally

```bash
python3 -m http.server 5173
```

Then open http://localhost:5173.

## Deploy

Hosted on GitHub Pages from the `main` branch of the `shruti052001.github.io` repository.
