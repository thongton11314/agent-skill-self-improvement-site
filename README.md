# SkillForge Website

Showcase website for [SkillForge](https://github.com/thongton11314/agent-skill-self-improvement) — a self-evolving skill synthesis framework for AI systems.

**Live site:** [https://thongton11314.github.io/agent-skill-self-improvement-site/](https://thongton11314.github.io/agent-skill-self-improvement-site/)

## Overview

This repository contains the static website for the SkillForge project, separated from the main [agent-skill-self-improvement](https://github.com/thongton11314/agent-skill-self-improvement) source code repository.

The website showcases:

- **Architecture** — Modular component diagram (Generator, Verifier, Evolution Engine, Memory, Retrieval)
- **Workflow** — Interactive Mermaid flowchart of the co-evolutionary skill synthesis cycle
- **Benchmarks** — Demonstrative pass-rate charts and cross-model transfer results
- **Human vs AI Simulation** — Side-by-side comparison of human-authored vs AI-generated skills
- **Agentic Platform** — Discoverable agents and integration protocols
- **Platform Setup** — Quick-start guides for VS Code Copilot, Claude Code, and OpenAI Codex
- **Integration** — SDK, middleware, REST API, evaluation pipeline, and plug-in modes

## Project Structure

```
agent-skill-self-improvement-site/
├── .github/
│   └── workflows/
│       └── deploy-website.yml   # GitHub Pages deployment workflow
├── website/
│   ├── index.html               # Main website page
│   ├── styles.css               # Stylesheet
│   └── images/                  # Platform icons
│       ├── icon-vscode.png
│       ├── icon-claude.png
│       └── icon-codex.png
└── README.md
```

## Deployment

The website is automatically deployed to GitHub Pages on every push to `main` that modifies files in `website/` or the workflow file.

**Workflow:** `.github/workflows/deploy-website.yml`

### Manual Setup

1. Go to **Settings → Pages** in this repository
2. Source should be set to **GitHub Actions**
3. Push any change to `website/` on the `main` branch to trigger deployment

### Local Preview

Open `website/index.html` directly in a browser — no build step required.

## Tech Stack

- **HTML5** + **CSS3** (no framework, pure static)
- **Mermaid.js** — Workflow diagram rendering
- **Marked.js** — Markdown rendering for file previews
- **GitHub Pages** — Hosting via GitHub Actions

## Related

- [agent-skill-self-improvement](https://github.com/thongton11314/agent-skill-self-improvement) — Main SkillForge source code, SDK, benchmarks, and documentation
