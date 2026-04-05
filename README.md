# Morgenruf Documentation

[![Docs](https://img.shields.io/website?url=https%3A%2F%2Fdocs.morgenruf.dev&label=docs.morgenruf.dev&color=brightgreen)](https://docs.morgenruf.dev)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> 📚 Source for [docs.morgenruf.dev](https://docs.morgenruf.dev) — the official Morgenruf documentation site.

## Overview

This repo contains the HTML documentation for [Morgenruf](https://github.com/morgenruf/morgenruf), a self-hosted Slack standup bot with per-project tracking and Kubernetes-ready deployment.

## Pages

- **Getting Started** — Installation, configuration, and first standup
- **Configuration** — All environment variables and options
- **Slash Commands** — Full command reference
- **API Reference** — REST API for integrations
- **Deployment** — Docker, Kubernetes/Helm, and cloud deployment guides
- **FAQ** — Frequently asked questions

## Structure

- `index.html` — Home / overview
- `getting-started.html` — Installation guide
- `configuration.html` — Configuration reference
- `self-hosting.html` — Self-hosting guide (k8s, Docker)
- `helm.html` — Helm chart reference
- `faq.html` — Frequently asked questions

## Local Development

```bash
# Serve locally (Python)
python -m http.server 8080

# Or with Node
npx serve .
```

Then open http://localhost:8080.

## Deployment

Docs are automatically deployed to GitHub Pages via `.github/workflows/pages.yml` on every push to `main`.

## Contributing

Found a mistake or want to improve the docs? PRs welcome! Please keep the existing HTML/CSS style consistent.

See also [github.com/morgenruf/morgenruf/blob/main/CONTRIBUTING.md](https://github.com/morgenruf/morgenruf/blob/main/CONTRIBUTING.md).
