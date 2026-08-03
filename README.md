# ORVEX Aviation Legacy Launcher

This repository is a **static compatibility launcher only**.

The canonical ORVEX Aviation application, THY module, Part 145 work, deployment workflows, tests, and production source code live in:

- `hansmex0929-sudo/ORVEX-Aviation-AI-Enterprise`
- Production: `https://www.orvex-aviation.com`

## Repository boundary

Do not implement Aviation, THY, Part 145, Quant, Foundation/Charity, Historical Replay, database, authentication, quoting, deployment, or regulatory functionality in this repository.

Allowed changes are limited to:

- maintaining the static `index.html` compatibility launcher;
- keeping launcher links pointed at the canonical production site;
- static-host configuration required to serve that launcher;
- tests or workflows that enforce this boundary.

Any product or module work must be reconciled against active work in the canonical enterprise repository before a branch or pull request is created.
