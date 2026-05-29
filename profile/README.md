<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/gatewaze-logo-white.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/gatewaze-logo-black.svg">
    <img alt="Gatewaze" src="assets/gatewaze-logo-black.svg" width="320">
  </picture>
</p>

<p align="center">
  <strong>The AI-native open-source platform for communities</strong>
</p>

<p align="center">
  Members, events, content, and communications — and the AI to run them.
</p>

<p align="center">
  <a href="https://github.com/gatewaze/gatewaze">Platform</a> |
  <a href="https://github.com/gatewaze/gatewaze-modules">Modules</a> |
  <a href="https://opensource.org/licenses/Apache-2.0">License</a>
</p>

Gatewaze is a modular, open-source platform for managing communities and the people in them — members, events, content, newsletters, sites, and communications. What sets it apart is that AI is built in: you can ship AI features to production on your own infrastructure, without bolting on a separate AI platform.

## Run AI in production — in-house

- **One provider router** — OpenAI, Anthropic, and Google Gemini behind a single interface, with per-user and per-use-case credentials and model allow-lists.
- **Bring your own agent** — author a [Goose](https://github.com/aaif-goose/goose) recipe locally and run it *unchanged* in production. Gatewaze runs the Goose CLI server-side, so there's no rewrite, no serverless wrapper, and no local-to-cloud translation — the recipe that works on your laptop is the one that runs in prod.
- **MCP server library** — expose your platform to agents through bundled MCP servers: platform data (events, speakers, sponsors, health), a whitelisted API proxy, and a headless browser (local Chromium or Browserbase).
- **AI chat & custom use cases** — drop in a streamed, multi-turn chat widget, or build your own AI surface (like an automated daily briefing) with its own credentials, tools, and budget.
- **Governance & cost control** — encrypted credentials, per-use-case model/tool allow-lists, a per-call usage ledger, and hard budget caps so AI spend never runs away.

## Built for automation

A headless browser for agents, a governed web-fetch API (quotas, domain rules, robots.txt, audit + billing ledger), and a scraper system backed by a fetch service with eight swappable residential-proxy providers.

## Own your whole stack

Self-host everything — including the AI. Start in minutes with Docker Compose, then run it in production on Kubernetes with the bundled Helm chart. No SaaS lock-in, no data leaving your cluster.

## Getting Started

- 🚀 Start with the core platform — [gatewaze/gatewaze](https://github.com/gatewaze/gatewaze)
- 🧩 Browse the 76-module open-source collection — [gatewaze/gatewaze-modules](https://github.com/gatewaze/gatewaze-modules)
- 📖 Build your own modules with the Module System Guide in the core repository

## Project Structure

- [gatewaze](https://github.com/gatewaze/gatewaze) — Core platform: member management, admin app, public portal, API, AI runtime, and the module system
- [gatewaze-modules](https://github.com/gatewaze/gatewaze-modules) — Official open-source module collection (Apache-2.0): events, content, sites, marketing, communications, integrations, AI, and platform infrastructure
- [gatewaze-template-site](https://github.com/gatewaze/gatewaze-template-site) — Next.js boilerplate for Gatewaze sites (default theme)
- [gatewaze-template-email](https://github.com/gatewaze/gatewaze-template-email) — HTML email boilerplate for newsletter modules
- [gatewaze-template-blocks](https://github.com/gatewaze/gatewaze-template-blocks) — Starter block library for website-kind sites
- [gatewaze-skills](https://github.com/gatewaze/gatewaze-skills) — Reusable developer skills for building and maintaining the platform

## Contributing

We welcome contributions of all kinds — bug fixes, documentation, new modules, and feature proposals. Each repository includes a contributing guide, and most ask you to sign a Contributor License Agreement before your first pull request is merged.

## About

Gatewaze is an open source project hosted by [The Linux Foundation](https://lfprojects.org) and open to contributions from the entire community.
