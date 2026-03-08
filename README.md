<div align="center">

# 🦞 Awesome OpenClaw Ecosystem

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/hugomrvt/awesome-openclaw-ecosystem?style=social)](https://github.com/hugomrvt/awesome-openclaw-ecosystem/stargazers)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/hugomrvt/awesome-openclaw-ecosystem/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/hugomrvt/awesome-openclaw-ecosystem)](https://github.com/hugomrvt/awesome-openclaw-ecosystem/commits/main)

**A comprehensive, community-driven collection of projects, tools, and resources built around [OpenClaw](https://github.com/openclaw/openclaw) — the open-source personal AI agent.**

120+ projects across 20 categories · Rust to Zig · Cloud to ESP32

[Submit a Project](#contributing) · [Report Broken Link](https://github.com/hugomrvt/awesome-openclaw-ecosystem/issues) · [Suggest Category](https://github.com/hugomrvt/awesome-openclaw-ecosystem/issues)

</div>

---

## Contents

- [The Foundation](#the-foundation)
- [Official Ecosystem](#official-ecosystem)
- [Lightweight Assistants](#lightweight-assistants)
- [High-Performance Runtimes](#high-performance-runtimes)
- [Edge & Embedded](#edge--embedded)
- [Forks & Rewrites](#forks--rewrites)
- [Security & Privacy](#security--privacy)
- [Multi-Agent & Orchestration](#multi-agent--orchestration)
- [Autonomous & Specialized Agents](#autonomous--specialized-agents)
- [Platforms & Managed Services](#platforms--managed-services)
- [Hosted OpenClaw (OpenClaw-as-a-Service)](#hosted-openclaw-openclaw-as-a-service)
- [Deployment & Infrastructure](#deployment--infrastructure)
- [MCP Servers & Bridges](#mcp-servers--bridges)
- [SDKs & Client Libraries](#sdks--client-libraries)
- [Plugins & Extensions](#plugins--extensions)
- [Tooling, UIs & Dashboards](#tooling-uis--dashboards)
- [Memory & Knowledge](#memory--knowledge)
- [Voice & Home Automation](#voice--home-automation)
- [Benchmarks & Research](#benchmarks--research)
- [Agent Social Networks](#agent-social-networks)
- [Community Resources](#community-resources)
- [Learning Resources](#learning-resources)
- [Adjacent Alternatives](#adjacent-alternatives)
- [Contributing](#contributing)

---

## The Foundation

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [OpenClaw](https://github.com/openclaw/openclaw) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat-square) | The original open-source personal AI assistant — multi-agent routing, voice wake, live canvas, companion apps, 15+ messaging channels, 247K+ stars. |

## Official Ecosystem

> Repositories maintained under the [openclaw](https://github.com/openclaw) GitHub organization.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [ClawHub](https://github.com/openclaw/clawhub) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=flat-square) | Official public skill registry — 2,800+ skills with vector search, GitHub OAuth, and CLI (`clawhub install <skill>`). |
| [Lobster](https://github.com/openclaw/lobster) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=flat-square) | Native workflow shell and macro engine — composable typed pipelines with approval gates, resume tokens, and sub-lobster loops. |
| [acpx](https://github.com/openclaw/acpx) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/openclaw/acpx?style=flat-square) | Headless CLI client for stateful Agent Client Protocol (ACP) sessions — persistent sessions, prompt queueing, crash reconnect. |
| [openclaw-ansible](https://github.com/openclaw/openclaw-ansible) | Shell/YAML | ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=flat-square) | Official hardened Ansible playbook — Tailscale VPN + UFW firewall + Docker isolation + systemd hardening. |
| [nix-openclaw](https://github.com/openclaw/nix-openclaw) | Nix | ![GitHub stars](https://img.shields.io/github/stars/openclaw/nix-openclaw?style=flat-square) | Official Home Manager module for macOS and NixOS — instant rollback, deterministic builds. |
| [clawdinators](https://github.com/openclaw/clawdinators) | Nix | ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=flat-square) | Declarative infrastructure + NixOS modules for CLAWTINATOR hosts. |
| [clawgo](https://github.com/openclaw/clawgo) | Go | ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawgo?style=flat-square) | Minimal headless Go node client for Raspberry Pi/Linux — gateway pairing and voice streaming. |
| [homebrew-tap](https://github.com/openclaw/homebrew-tap) | Ruby | ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=flat-square) | Homebrew tap for installing OpenClaw on macOS via `brew`. |
| [skills](https://github.com/openclaw/skills) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=flat-square) | Official archive of all versions of all skills published to ClawHub. |
| [trust](https://github.com/openclaw/trust) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/trust?style=flat-square) | OpenClaw's trust and security resource documentation. |
| [voice-community](https://github.com/openclaw/voice-community) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/voice-community?style=flat-square) | Community voice integration resources. |
| [casa](https://github.com/openclaw/casa) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/casa?style=flat-square) | Home integration bridge — exposing your home base to OpenClaw. |
| [barnacle](https://github.com/openclaw/barnacle) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/barnacle?style=flat-square) | Lightweight companion bot utility that "sticks" around. |
| [flawd-bot](https://github.com/openclaw/flawd-bot) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/flawd-bot?style=flat-square) | OpenClaw's evil twin — intentionally adversarial test bot for red-teaming. |
| [butter.bot](https://github.com/openclaw/butter.bot) | — | ![GitHub stars](https://img.shields.io/github/stars/openclaw/butter.bot?style=flat-square) | Minimalist companion bot project. |

## Lightweight Assistants

> Minimal footprint, easy to self-host, quick to understand and extend.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [PicoClaw](https://github.com/sipeed/picoclaw) | Go | ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=flat-square) | Ultra-efficient assistant for low-cost hardware. Single-binary deploy, runs on old Android phones via Termux. |
| [NanoClaw](https://github.com/qwibitai/nanoclaw) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=flat-square) | Sandboxed container-based assistant. First to support Agent Swarms with real Apple Containers. |
| [nanobot](https://github.com/HKUDS/nanobot) | Python | ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=flat-square) | Ultra-lightweight OpenClaw-style assistant for research workflows. MCP support, 191 MB footprint on Raspberry Pi. |
| [BabyClaw](https://github.com/yogesharc/babyclaw) | JavaScript | ![GitHub stars](https://img.shields.io/github/stars/yogesharc/babyclaw?style=flat-square) | Single-file alternative built on Claude Agent SDK. Telegram control, voice, cron automation. |
| [Clawlet](https://github.com/Kxrbx/Clawlet) | Python | ![GitHub stars](https://img.shields.io/github/stars/Kxrbx/Clawlet?style=flat-square) | Lightweight AI agent framework with identity awareness. Operational in 2 minutes. |
| [picobot](https://github.com/louisho5/picobot) | Go | ![GitHub stars](https://img.shields.io/github/stars/louisho5/picobot?style=flat-square) | Self-hosted lightweight bot in a single binary. |
| [pickle-bot](https://github.com/czl9707/pickle-bot) | Python | ![GitHub stars](https://img.shields.io/github/stars/czl9707/pickle-bot?style=flat-square) | Lightweight self-hosted personal AI assistant. |

## High-Performance Runtimes

> Built for speed, safety, and minimal resource usage. Mostly Rust.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) | Rust | ![GitHub stars](https://img.shields.io/github/stars/zeroclaw-labs/zeroclaw?style=flat-square) | Trait-driven, zero-overhead AI infrastructure. Fully swappable core, one-command migration from OpenClaw. Runs on Raspberry Pi 1B. |
| [ZeptoClaw](https://github.com/qhkm/zeptoclaw) | Rust | ![GitHub stars](https://img.shields.io/github/stars/qhkm/zeptoclaw?style=flat-square) | ~4 MB binary with 7-layer security. Container isolation, prompt injection detection, secret scanning. |
| [Moltis](https://github.com/moltis-org/moltis) | Rust | ![GitHub stars](https://img.shields.io/github/stars/moltis-org/moltis?style=flat-square) | Single-binary personal AI gateway. Multi-provider LLM, long-term memory, sandboxed execution, voice, MCP. |
| [shrew](https://github.com/Masmedeam/shrew) | Rust | ![GitHub stars](https://img.shields.io/github/stars/Masmedeam/shrew?style=flat-square) | Compact autonomous assistant runtime optimized for speed. |
| [moxxy](https://github.com/moxxy-ai/moxxy) | Rust | ![GitHub stars](https://img.shields.io/github/stars/moxxy-ai/moxxy?style=flat-square) | Self-hosted multi-agent AI framework in Rust. |
| [Microclaw](https://github.com/microclaw/microclaw) | Rust | ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=flat-square) | Agentic AI assistant for chat surfaces, inspired by NanoClaw. |
| [OpenFang](https://github.com/RightNow-AI/openfang) | Rust | ![GitHub stars](https://img.shields.io/github/stars/RightNow-AI/openfang?style=flat-square) | Open-source Agent OS — 137K LOC, 14 crates, 1,767+ tests, zero clippy warnings. |
| [Carapace (Rust)](https://github.com/puremachinery/carapace) | Rust | ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=flat-square) | Hardened Rust alternative extensible via WASM plugins — "for when your assistant needs a hard shell." |

## Edge & Embedded

> AI agents that run on microcontrollers, old phones, and $5 boards.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [NullClaw](https://github.com/nullclaw/nullclaw) | Zig | ![GitHub stars](https://img.shields.io/github/stars/nullclaw/nullclaw?style=flat-square) | Autonomous infrastructure for tiny binaries (678 KB), ~1 MB RAM, boots in <2 ms on Apple Silicon. |
| [MimiClaw](https://github.com/memovai/mimiclaw) | C | ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=flat-square) | Pocket assistant for ESP32-S3. No OS required, low power, USB powered. |
| [zclaw](https://github.com/tnm/zclaw) | C | ![GitHub stars](https://img.shields.io/github/stars/tnm/zclaw?style=flat-square) | 888 KB AI firmware for ESP32-C3 — full agentic capabilities, WiFi, TLS, Telegram, GPIO/sensor tools. |
| [subzeroclaw](https://github.com/jmlago/subzeroclaw) | C | ![GitHub stars](https://img.shields.io/github/stars/jmlago/subzeroclaw?style=flat-square) | Skill-driven agentic daemon for edge hardware. |
| [femtoclaw](https://github.com/samiul000/femtoclaw) | C++ | ![GitHub stars](https://img.shields.io/github/stars/samiul000/femtoclaw?style=flat-square) | Ultra-lightweight MCU port for ESP32/Pico W — 64 KB RAM, 1 MB flash, Python GUI for firmware updates. |
| [pycoClaw](https://github.com/jetpax/pycoclaw) | MicroPython | ![GitHub stars](https://img.shields.io/github/stars/jetpax/pycoclaw?style=flat-square) | Full MicroPython OpenClaw for ESP32-S3 — in-browser flashing, LVGL touchscreen UI, GPIO control. [Website](https://pycoclaw.com). |
| [HeyClawy](https://github.com/omer9/Clawy) | C++ | ![GitHub stars](https://img.shields.io/github/stars/omer9/Clawy?style=flat-square) | ESP32-based voice assistant — wake word, push-to-talk, WebSocket integration, cron notifications. |
| [openclaw-esp32](https://github.com/hrwtech/openclaw-esp32) | C++ | ![GitHub stars](https://img.shields.io/github/stars/hrwtech/openclaw-esp32?style=flat-square) | Desktop companion for Arduino ESP32 — menu bar control, voice wake, SSH gateway control. |

## Forks & Rewrites

> Full reimplementations and language ports of OpenClaw core.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [go-claw](https://github.com/withgoclaw/go-claw) | Go | ![GitHub stars](https://img.shields.io/github/stars/withgoclaw/go-claw?style=flat-square) | Full rewrite in Go — single binary ~10 MB, ~15 ms startup, minimal RAM, native concurrency. |
| [openclaw-python](https://github.com/zhaoyuong/openclaw-python) | Python | ![GitHub stars](https://img.shields.io/github/stars/zhaoyuong/openclaw-python?style=flat-square) | Production-ready Python port, cross-platform — Telegram, Discord, Slack, WhatsApp. |
| [OpenBrowserClaw](https://github.com/sachaa/openbrowserclaw) | JavaScript | ![GitHub stars](https://img.shields.io/github/stars/sachaa/openbrowserclaw?style=flat-square) | Browser-native personal AI assistant — zero infrastructure, the browser is the server. |
| [MonClaw](https://cefboud.com/posts/monclaw-a-light-openclaw-with-opencode-sdk/) | TypeScript | — | Minimal OpenClaw clone built with OpenCode SDK — Telegram + WhatsApp adapters. |
| [mini-openclaw](https://gist.github.com/dabit3/bc60d3bea0b02927995cd9bf53c3db32) | Python | — | "You Could've Invented OpenClaw" — ~500-line reference implementation of gateway, sessions, memory, multi-agent, cron. |

## Security & Privacy

> Projects where trust, encryption, and sandboxing come first.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [IronClaw](https://github.com/nearai/ironclaw) | Rust | ![GitHub stars](https://img.shields.io/github/stars/nearai/ironclaw?style=flat-square) | Privacy-first. Local encrypted data, WebAssembly sandboxing, capability-based permissions. |
| [safeclaw](https://github.com/princezuda/safeclaw) | Python | ![GitHub stars](https://img.shields.io/github/stars/princezuda/safeclaw?style=flat-square) | Secure text/voice interactions without LLM dependency. |
| [TrustClaw](https://www.trustclaw.app) | — | — | Full OpenClaw rebuild — OAuth only, remote sandboxed execution, 1,000+ integrations, full audit trail. |
| [ChaosClaw](https://github.com/ChaosChain/chaosclaw) | — | ![GitHub stars](https://img.shields.io/github/stars/ChaosChain/chaosclaw?style=flat-square) | Trust agent using ERC-8004 for AI agents to verify and reason about other agents' reputation. |
| [Carapace (prompt injection)](https://github.com/xampla/carapace) | Python/TS | ![GitHub stars](https://img.shields.io/github/stars/xampla/carapace?style=flat-square) | Prompt injection detection plugin — Nova Framework + PromptIntel integration. |
| [Carapace (container)](https://github.com/justmiles/carapace) | Docker | ![GitHub stars](https://img.shields.io/github/stars/justmiles/carapace?style=flat-square) | Robust container environment for OpenClaw — isolated workspace, GUI, persistent services. |
| [openclaw-security-practice-guide](https://github.com/slowmist/openclaw-security-practice-guide) | Markdown | ![GitHub stars](https://img.shields.io/github/stars/slowmist/openclaw-security-practice-guide?style=flat-square) | Definitive security guide — 20 red-team test cases from prompt injections to OS privilege escalations. |
| [openclaw-hardened-ansible](https://github.com/Next-Kick/openclaw-hardened-ansible) | Ansible | ![GitHub stars](https://img.shields.io/github/stars/Next-Kick/openclaw-hardened-ansible?style=flat-square) | 3-tier hardened deployment — rootless Podman, LiteLLM credential brokering, multi-agent risk separation. |

## Multi-Agent & Orchestration

> Coordinate teams of agents, fan-out tasks, compose workflows.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [TinyClaw](https://github.com/TinyAGI/tinyclaw) | Shell / TS | ![GitHub stars](https://img.shields.io/github/stars/TinyAGI/tinyclaw?style=flat-square) | Multi-agent, multi-team, multi-channel with chain execution and fan-out. |
| [Flowly AI](https://github.com/Nocetic/flowlyai) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/Nocetic/flowlyai?style=flat-square) | Flow-oriented framework for composing agent workflows and tool-driven tasks. |
| [troublemaker](https://github.com/tinyfatco/troublemaker) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/tinyfatco/troublemaker?style=flat-square) | Cross-platform AI agent runtime. |
| [openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) | — | ![GitHub stars](https://img.shields.io/github/stars/abhi1693/openclaw-mission-control?style=flat-square) | Multi-agent orchestration dashboard — management, task assignment, collaborative coordination. |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | Python | ![GitHub stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat-square) | Extensible open-source multi-agent framework for autonomous AI agents. |

## Autonomous & Specialized Agents

> Agents with a specific mission or domain expertise.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [HermitClaw](https://github.com/brendanhogan/hermitclaw) | Python | ![GitHub stars](https://img.shields.io/github/stars/brendanhogan/hermitclaw?style=flat-square) | Autonomous AI creature living in a folder — continuously researches, generates reports, scripts, notes. |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) | Python | ![GitHub stars](https://img.shields.io/github/stars/AstrBotDevs/AstrBot?style=flat-square) | Agentic chatbot infrastructure for instant messaging platforms with plugins and LLM integrations. |
| [droidclaw](https://github.com/unitedbyai/droidclaw) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/unitedbyai/droidclaw?style=flat-square) | Android-first workflow assistant with lightweight deployment and mobile automation. |
| [AngelClaw](https://github.com/Abdur-rahmaanJ/angel-claw) | Python | ![GitHub stars](https://img.shields.io/github/stars/Abdur-rahmaanJ/angel-claw?style=flat-square) | Lean, OpenClaw-compatible agent focused on implementing research concepts. |
| [Agent-Zero](https://github.com/frdel/agent-zero) | Python | ![GitHub stars](https://img.shields.io/github/stars/frdel/agent-zero?style=flat-square) | Autonomous agent framework for deep research. Runs in Docker, praised for great UX. |
| [OneRingAI](https://github.com/Intail/onai) | Python | ![GitHub stars](https://img.shields.io/github/stars/Intail/onai?style=flat-square) | Open-source desktop-installed alternative with flexible LLM support and user-friendly GUI. |
| [Agent S3 (Simular)](https://simular.ai) | — | — | GUI automation specialist — top OpenClaw alternative for desktop/browser agent tasks. |

## Platforms & Managed Services

> Full-stack solutions, cloud deploys, and integrated platforms.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [Moltworker](https://github.com/cloudflare/moltworker) | — | ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=flat-square) | By **Cloudflare**. Run OpenClaw on Workers with container sandbox, R2 storage, Cloudflare Access auth. |
| [LettaBot](https://github.com/letta-ai/lettabot) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/letta-ai/lettabot?style=flat-square) | AI assistant with persistent memory on Telegram, Slack, WhatsApp, Signal. |
| [SupaClaw](https://github.com/vincenzodomina/supaclaw) | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/vincenzodomina/supaclaw?style=flat-square) | Built entirely on native Supabase features. Self-host or use in your Supabase account. |
| [Autobot](https://github.com/crystal-autobot/autobot) | Crystal | ![GitHub stars](https://img.shields.io/github/stars/crystal-autobot/autobot?style=flat-square) | AI assistant with kernel sandboxing, multi-provider LLM, voice, vision, cron, MCP tools. |
| [Jan.ai](https://jan.ai) | — | — | 100% offline, privacy-first desktop application for local chat. |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | JavaScript | ![GitHub stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=flat-square) | Open-source LLM orchestration hub for private knowledge bases. |

## Hosted OpenClaw (OpenClaw-as-a-Service)

> Deploy and run OpenClaw without managing infrastructure.

| Service | Description | Pricing |
|---------|-------------|---------|
| [ClawTank](https://clawtank.dev) | Fastest managed OpenClaw — under 1 minute setup, SuperMemory, isolated containers, encrypted data, auto-TLS. | 7-day free trial |
| [KiloClaw](https://kilo.ai/kiloclaw) | Hosted by Kilo — one-click deploy, 500+ models via Kilo Gateway. | $25–49/mo |
| [ClawSimple](https://clawsimple.com) | Managed hosting — spin up a dedicated server in 1 click, BYOK or bundled credits. | Subscription |
| [Agent37](https://www.agent37.com) | Managed at $9.99/month with skill monetization infrastructure. | $9.99/mo |
| [EasyClaw](https://easyclaw.co) | Fastest way to run OpenClaw — one-click deploy wired to Telegram. | Subscription |
| [MyClaw.ai](https://myclaw.ai) | One-click hosted OpenClaw on a secure, isolated VPS, accessible 24/7. | Subscription |
| [Kimi Claw](https://kimi.com) | Moonshot AI's managed implementation — 5,000+ ClawHub skills, 40 GB cloud storage, BYOC. | Freemium |
| [ClawHost](https://github.com/bfzli/clawhost) | Open-source self-hostable cloud deployer for OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/bfzli/clawhost?style=flat-square) | Free |
| [SunClaw](https://sunclaw.kiisha.io) | Web wizard deploying to 8 platforms, 16+ LLM providers, zero CLI. | Free |
| [Emergent.sh](https://emergent.sh/tutorial/moltbot-on-emergent) | Pre-built MoltBot chip — auto-provisioned managed VMs, 2–8 min setup. | 50 credits/mo |

## Deployment & Infrastructure

### One-Click Deploy Platforms

| Platform | Type | Description |
|----------|------|-------------|
| [Railway](https://docs.openclaw.ai/install/railway) | Official | One-click deploy with Gateway + Control UI + web setup wizard. Free tier + pay-as-you-go. |
| [Render](https://docs.openclaw.ai/install/render) | Official Blueprint | `render.yaml` in repo — persistent disk, auto-generated token. Free–$7+/mo. |
| [Fly.io](https://github.com/openclaw/openclaw/blob/main/fly.toml) | Official | `fly.toml` in repo — deploy via `fly launch`. |
| [DigitalOcean](https://marketplace.digitalocean.com/apps/openclaw) | Marketplace | Security-hardened 1-click Droplet — Docker isolation, TLS proxy, production defaults. ~$12/mo. |
| [Contabo](https://contabo.com/en/openclaw-hosting/) | 1-click VPS | Free add-on during VPS provisioning — boots pre-configured. From €4.50/mo. |
| [Hostinger](https://www.hostinger.com/vps/clawdbot-hosting) | Docker Template | One-click in hPanel Docker Catalog — Nexos AI credits or BYOK. From $4/mo. |
| [Tencent Cloud](https://www.tencentcloud.com/act/pro/intl-openclaw) | Lighthouse | 1-click template — 30-second startup, Chinese messaging platform support. |
| [Coolify](https://github.com/wiselancer/openclaw-coolify) | Self-hosted PaaS | Docker config for Coolify — Traefik, TLS, secrets, multi-server from a web dashboard. |

### Container & Orchestration

| Project | Type | Description |
|---------|------|-------------|
| [Official Docker](https://docs.openclaw.ai/install/docker) | Docker | `ghcr.io/openclaw/openclaw` — gateway + sandbox images (slim, common, browser/Chromium). |
| [Docker Model Runner](https://www.docker.com/blog/run-openclaw-securely-in-docker-sandboxes/) | Docker | Fully local AI inference — no API keys, no cloud costs. By Docker. |
| [Podman Rootless](https://docs.openclaw.ai/install/podman) | Podman | Official rootless Podman deployment with systemd Quadlet — no root required post-setup. |
| [alpine/openclaw](https://hub.docker.com/r/alpine/openclaw) | Docker Hub | Community mirror of the official GHCR image. |
| [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) | Helm | Production Helm chart — Chromium sidecar, init containers, network policies, ArgoCD-compatible. |
| [Chrisbattarbee/openclaw-helm](https://github.com/Chrisbattarbee/openclaw-helm) | Helm | Community Helm chart for standard Kubernetes deployment. |
| [openclaw-with-brain](https://artifacthub.io/packages/helm/openclaw-with-brain/openclaw-with-brain) | Helm | Helm chart with git-backed "brain" repository for bidirectional config sync. |

### Cloud Provider Guides

| Provider | Guide |
|----------|-------|
| AWS EC2 | [Video tutorial](https://www.youtube.com/watch?v=Qx97iDCCccM) — Ubuntu 24.04, Docker Compose, t2.medium. |
| Azure | [LinkedIn guide](https://www.linkedin.com/posts/desivillanueva_openclaw-azure-install-tips-and-security-activity-7425052724502908929-Kfiw) — Caddy + LiteLLM + 3-tier security hardening. |
| Hetzner | [Reddit guide](https://www.reddit.com/r/openclaw/comments/1r9tv3d/how_i_set_up_openclaw_on_a_hetzner_vps_full_guide/) — EU data centers (GDPR), full walkthrough. |
| Oracle Cloud | [Cognio.so guide](https://cognio.so/clawdbot/self-hosting) — Always Free tier ($0/mo), Ollama, Docker Compose. |
| NVIDIA Jetson | [Jetson AI Lab](https://www.jetson-ai-lab.com/tutorials/openclaw/) — 100% local on AGX Thor/Orin with vLLM. |
| Raspberry Pi | [Official docs](https://docs.openclaw.ai/platforms/raspberry-pi) + [Adafruit guide](https://learn.adafruit.com/openclaw-on-raspberry-pi/installing-openclaw). |
| Multi-cloud | [openclawn.com](https://openclawn.com/openclaw-cloud-security-aws-azure-gcp/) — security guide for AWS, Azure, GCP. |

### Reverse Proxy

| Proxy | Guide |
|-------|-------|
| Caddy / Nginx / Traefik | [ClawTank reference](https://clawtank.dev/blog/openclaw-reverse-proxy-trusted-proxies) — complete configs + `trustedProxies` setup. |
| Nginx + SSL | [Tencent Cloud guide](https://www.tencentcloud.com/techpedia/139939) — Certbot, WebSocket support, HTTPS redirect. |
| Nginx load balancer | [dev.to guide](https://dev.to/linou518/openclaw-guide-ch9-multi-server-cluster-deployment-4h72) — `upstream` block, failover, rate limiting. |

## MCP Servers & Bridges

> Connect OpenClaw to the Model Context Protocol ecosystem.

| Project | Description |
|---------|-------------|
| [mcporter](https://github.com/steipete/mcporter) | Core MCP-to-CLI bridge used natively by OpenClaw — converts MCP tool calls to shell commands, avoids context bloat. By the OpenClaw creator. ![GitHub stars](https://img.shields.io/github/stars/steipete/mcporter?style=flat-square) |
| [openclaw-mcp](https://github.com/freema/openclaw-mcp) | MCP server bridging Claude.ai ↔ self-hosted OpenClaw via OAuth 2.1. ![GitHub stars](https://img.shields.io/github/stars/freema/openclaw-mcp?style=flat-square) |
| [openclaw-mcp-bridge](https://openclawdir.com/plugins/mcp-bridge-1volrr) | Bridge connecting any HTTP MCP server as native OpenClaw tools. |
| [MCP360](https://mcp360.ai) | Universal MCP gateway — 100+ production tools through a single endpoint. |
| [Composio](https://composio.dev/toolkits/browser_tool/framework/openclaw) | 20,000+ tools across 850+ apps with managed auth via MCP. |
| [Latenode MCP](https://www.latenode.com) | Visual workflow engine — 1,000+ app integrations exposed as MCP tools. |
| [Bright Data MCP](https://brdta.com/bytegrad) | Web access tools (fetch, search, browser) — 5,000 free requests/month. |

### MCP Directories

| Directory | Description |
|-----------|-------------|
| [Official MCP Registry](https://registry.modelcontextprotocol.io) | The canonical registry — verified servers, moderation, public/private sub-registries. |
| [MCP.so](https://mcp.so) | Community-maintained directory with thousands of servers across categories. |
| [Glama](https://glama.ai/mcp/servers) | ~10,000 MCP servers with quality checks and category filters. |
| [MCP Server Hub](https://mcpserverhub.com/en) | Curated hub with both official and community MCP servers. |
| [Cursor Directory](https://cursor.directory/mcp) | MCP listings for 250,000+ monthly active developers. |
| [awesome-mcp-list](https://github.com/MobinX/awesome-mcp-list) | Continuously-updated curated GitHub list by category. |

## SDKs & Client Libraries

| Project | Language | Description |
|---------|----------|-------------|
| [openclaw-go](https://github.com/a3tai/openclaw-go) | Go | Most complete third-party SDK — 7 packages covering WebSocket, Chat Completions, Tools Invoke, mDNS discovery, and ACP. ![GitHub stars](https://img.shields.io/github/stars/a3tai/openclaw-go?style=flat-square) |
| [acpx](https://github.com/openclaw/acpx) | TypeScript | Official headless ACP CLI for programmatic interaction without a UI. |
| [vscode-acp](https://github.com/formulahendry/vscode-acp) | TypeScript | VS Code extension — connects to OpenClaw + 8 other coding agents via Agent Client Protocol. ![GitHub stars](https://img.shields.io/github/stars/formulahendry/vscode-acp?style=flat-square) |
| [LobeHub Market CLI](https://lobehub.com/skills/openclaw-skills-lobster) | Node.js | Cross-agent skill marketplace CLI — install skills for OpenClaw, Claude Code, Codex, Cursor. |

## Plugins & Extensions

> Extend OpenClaw's capabilities with plugins, skills, and custom channels.

| Project | Type | Description |
|---------|------|-------------|
| [openclaw-foundry](https://github.com/lekt9/openclaw-foundry) | Meta-extension | Self-writing extension that observes workflows and auto-generates new skills, tools, and hooks. ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=flat-square) |
| [lossless-claw](https://www.npmjs.com/package/@martian-engineering/lossless-claw) | Core plugin | DAG-based context management replacing built-in sliding-window compaction. |
| [openclaw-grafana-lens](https://github.com/openclaw/openclaw/discussions/34122) | Observability | 15 agent tools for PromQL/LogQL, auto-alert creation, prompt injection monitoring. |
| [openclaw-observability-plugin](https://github.com/henrikrexed/openclaw-observability-plugin) | Observability | Full OpenTelemetry — traces, metrics, logs, LLM token usage, tool executions. ![GitHub stars](https://img.shields.io/github/stars/henrikrexed/openclaw-observability-plugin?style=flat-square) |
| [wp-openclaw](https://github.com/Sarai-Chinwag/wp-openclaw) | WordPress | AI agent that controls a WordPress site — not just edits, but runs it. ![GitHub stars](https://img.shields.io/github/stars/Sarai-Chinwag/wp-openclaw?style=flat-square) |
| [openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) | Channel | DingTalk bot channel plugin using Stream Mode. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=flat-square) |

### Built-in Messaging Channels

OpenClaw natively supports 15+ messaging platforms via its Gateway:

| Platform | Integration | Platform | Integration |
|----------|-------------|----------|-------------|
| WhatsApp | Baileys (WebSocket) | Signal | signal-cli |
| Telegram | grammY framework | Matrix | Open protocol |
| Discord | discord.js | iMessage | AppleScript / BlueBubbles |
| Slack | Socket Mode / HTTP | Nostr | NIP-04 |
| Microsoft Teams | Plugin (bundled) | Nextcloud Talk | Self-hosted |
| Zalo | Bot API + Personal | WebChat | Browser-based |
| Tlon | Peer-to-peer | | |

## Tooling, UIs & Dashboards

> GUIs, dashboards, marketplaces, project management, and developer tools.

| Project | Type | Description |
|---------|------|-------------|
| [Nerve](https://github.com/daggerhashimoto/openclaw-nerve) | Web UI | Most feature-complete self-hosted frontend — voice I/O, Kanban, CodeMirror, TradingView charts, 14 themes. [Website](https://nerve.zone). ![GitHub stars](https://img.shields.io/github/stars/daggerhashimoto/openclaw-nerve?style=flat-square) |
| [ClawX](https://github.com/ValueCell-ai/ClawX) | Desktop app | Native GUI for OpenClaw — turns CLI orchestration into a visual experience. ![GitHub stars](https://img.shields.io/github/stars/ValueCell-ai/ClawX?style=flat-square) |
| [openclaw-dashboard](https://github.com/tugcantopaloglu/openclaw-dashboard) | Dashboard | Secure real-time monitoring — TOTP MFA, cost tracking, live feed, memory browser. ![GitHub stars](https://img.shields.io/github/stars/tugcantopaloglu/openclaw-dashboard?style=flat-square) |
| [openclaw-dashboard](https://github.com/mudrii/openclaw-dashboard) | Dashboard | Zero-dependency monitoring — token usage, cost tracking, agent hierarchy, model routing. ![GitHub stars](https://img.shields.io/github/stars/mudrii/openclaw-dashboard?style=flat-square) |
| [LobsterBoard](https://github.com/Curbob/LobsterBoard) | Dashboard | Self-hosted drag-and-drop builder — 50+ widgets, cron tracking, Docker stats. ![GitHub stars](https://img.shields.io/github/stars/Curbob/LobsterBoard?style=flat-square) |
| [FlowBoard](https://github.com/rasimme/FlowBoard) | Project mgmt | Agent-native Kanban — the agent itself creates tasks, writes specs, updates status. ![GitHub stars](https://img.shields.io/github/stars/rasimme/FlowBoard?style=flat-square) |
| [Clawmit](https://clawmit.xyz) | Versioning | "GitHub for AI Agents" — versioning, forking, prompt mutation, instant rollback. |
| [TrustClaw Marketplace](https://trustclaw.xyz) | Marketplace | Security-verified skill marketplace with automated scanning and human review. |
| [explain-openclaw](https://github.com/centminmod/explain-openclaw) | Documentation | Multi-AI architecture deep dives, security audits, deployment guides. ![GitHub stars](https://img.shields.io/github/stars/centminmod/explain-openclaw?style=flat-square) |

## Memory & Knowledge

> Long-term memory, knowledge graphs, and proactive agents.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [memU](https://github.com/NevaMind-AI/memU) | Python | ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=flat-square) | Proactive agent with hierarchical knowledge graph, RAG + non-embedding retrieval, anticipated actions. |

## Voice & Home Automation

> Voice pipelines, smart home integrations, and Home Assistant bridges.

| Project | Type | Description |
|---------|------|-------------|
| [OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) | HA Add-on | Home Assistant OS add-on running OpenClaw inside HAOS with SSH tunnel. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=flat-square) |
| [OpenClawHomeAssistantIntegration](https://github.com/techartdev/OpenClawHomeAssistantIntegration) | HA Integration | Bidirectional entity and voice control between Home Assistant and OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistantIntegration?style=flat-square) |
| [openclaw-ha-addon](https://github.com/ngutman/openclaw-ha-addon) | HA Add-on | Home Assistant add-on for `clawdbot_gateway` with SSH tunnel support. ![GitHub stars](https://img.shields.io/github/stars/ngutman/openclaw-ha-addon?style=flat-square) |
| [openclaw_conversation](https://github.com/Djelibeybi/openclaw_conversation) | HA Component | Custom component using OpenClaw as AI backend for HA conversation and task pipelines. ![GitHub stars](https://img.shields.io/github/stars/Djelibeybi/openclaw_conversation?style=flat-square) |
| [openclaw-conversation](https://github.com/nolasgl/openclaw-conversation) | HACS | Connects HA voice pipeline to OpenClaw Gateway (Whisper STT → OpenClaw → Piper TTS). ![GitHub stars](https://img.shields.io/github/stars/nolasgl/openclaw-conversation?style=flat-square) |

## Benchmarks & Research

> Evaluate, test, and push the boundaries of the ecosystem.

| Project | Language | Stars | Description |
|---------|----------|-------|-------------|
| [ClawWork](https://github.com/HKUDS/ClawWork) | Python | ![GitHub stars](https://img.shields.io/github/stars/HKUDS/ClawWork?style=flat-square) | Turns agents into economically responsible AI Coworkers — 220 GDP tasks across 44 industries. |
| [PinchBench](https://pinchbench.com) | TypeScript | — | Open-source real-world benchmark — 23 tasks (calendar, research, email, coding). [Leaderboard](https://pinchbench.com). |

## Agent Social Networks

> Where AI agents socialize, discover, and govern each other.

| Project | Description |
|---------|-------------|
| [moltbook](https://www.moltbook.com) | Social network for AI agents — 1.5M+ agents, 140K+ posts in first week. Covered by NYT, WIRED, Forbes, CNBC. |
| [Moltweet](https://www.producthunt.com/categories/openclaw) | Twitter-like platform for AI agents. |
| [Molthunt](https://www.producthunt.com/categories/openclaw) | Product Hunt-style "front page of the agent internet." |
| [Moltcraft](https://www.producthunt.com/categories/openclaw) | Minecraft-inspired visualization of agent activities. |
| [Claw And Order](https://www.producthunt.com/categories/openclaw) | "The court of law for AI agents" — accountability and arbitration. |

## Community Resources

> Curated lists, skill registries, and ecosystem hubs.

| Resource | Description |
|----------|-------------|
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 5,400+ skills filtered and categorized from ClawHub. |
| [awesome-openclaw (vincentkoc)](https://github.com/vincentkoc/awesome-openclaw) | Curated list — skills, plugins, memory, MCP, deployment stacks. |
| [awesome-openclaw (rohitg00)](https://github.com/rohitg00/awesome-openclaw) | Community resources, plugins, deployment guides, alternatives. |
| [awesome-openclaw (SamurAIGPT)](https://github.com/SamurAIGPT/awesome-openclaw) | Self-hosted AI agent workflows and messaging integrations. |
| [awesome-claws](https://github.com/machinae/awesome-claws) | The original curated list of 28 awesome AI agents inspired by OpenClaw. |
| [OpenClaw Ecosystem Hub](https://openclaw-ai.dev) | Official ecosystem hub. |
| [ClawHub](https://clawhub.com) | Official skill registry — 2,800+ skills with CLI install. |
| [Official Discord](https://discord.gg/openclaw) | "Friends of the Crustacean" — tens of thousands of members. |
| [r/openclaw](https://www.reddit.com/r/openclaw/) | Main Reddit community. |
| [r/openclawsetup](https://www.reddit.com/r/openclawsetup/) | Setup-focused subreddit. |
| [ClawCon](https://www.claw-con.com) | Official event series — 20+ cities worldwide. |

## Learning Resources

### Video Tutorials

| Title | Author | Description |
|-------|--------|-------------|
| [Full Course: Setup, Skills, Voice, Memory](https://www.youtube.com/watch?v=vte-fDoZczE) | Tech With Tim | 47-min comprehensive course — VPS, Docker, models, Telegram, skills, cronjobs. |
| [SECURE Setup Guide](https://www.youtube.com/watch?v=tnsrnsy_Lus) | Tech With Tim | 50-min security-hardened setup — 301K+ views. VPS, SSH, Tailscale, gateway lockdown. |
| [Professional Developer Setup](https://www.youtube.com/watch?v=NO-bOryZoTE) | Tech With Tim | Daily workflow, model selection, GitHub integration, ClawHub skills. |
| [21 INSANE Use Cases](https://www.youtube.com/watch?v=ssYt09bCgUY) | Matthew Berman | 251K+ views — creative and powerful OpenClaw use cases. |
| [Raspberry Pi 24/7 Agent](https://www.youtube.com/watch?v=GO5WVQ-lds8) | Community | Install on Pi, connect Gemini + Telegram for private self-hosted agent. |
| [Multi-Agent Team](https://www.youtube.com/watch?v=WqWMszBB9t0) | Clearmud | Build and coordinate a team of multiple OpenClaw agents. |
| [OpenClaw + MCP](https://www.youtube.com/watch?v=WT-Q0tB0zNo) | NetworkCoder | Integrating OpenClaw with MCP for custom AI capabilities. |
| [19 Agents for $6/Month](https://www.youtube.com/watch?v=-MtzLiQ9w1c) | Moe Lueker | Cost-optimization for running many agents on minimal infrastructure. |
| [Build AI Agent SaaS (2h36)](https://www.youtube.com/watch?v=WG_5HSq-Tt4) | Ankita Kulkarni | Build an OpenClaw-style autonomous AI agent SaaS from scratch. |

### Podcasts

| Title | Host / Guest | Description |
|-------|-------------|-------------|
| [Lex Fridman #491](https://www.youtube.com/watch?v=YFjfBk8HI5o) | Lex Fridman / Peter Steinberger | Origin story, viral explosion, architecture, privacy philosophy. |
| [Scott Hanselman Podcast](https://www.youtube.com/watch?v=Wm7tsiJ1nIo) | Scott Hanselman / Peter Steinberger | Developer tooling shift from prompts to agents, safety tradeoffs. |
| [Builders Unscripted Ep. 1](https://www.youtube.com/watch?v=9jgcT0Fqt7U) | Romain Huet (OpenAI) / Peter Steinberger | OpenClaw's open-source journey, building with Codex. |
| [OpenClaw Foundation](https://www.youtube.com/watch?v=KEHMoI00q3w) | Dave Morin | Foundation creation, governance, long-term sustainability. |

### Articles & Written Guides

| Title | Source | Description |
|-------|--------|-------------|
| [Full Tutorial for Beginners](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/) | freeCodeCamp | Comprehensive written guide — install to WhatsApp to skills. |
| [Self-Hosted AI Agent Guide](https://contabo.com/blog/what-is-openclaw-self-hosted-ai-agent-guide/) | Contabo | Architecture, deployment, Docker, security model, Raspberry Pi. |
| [What are OpenClaw Skills](https://www.digitalocean.com/resources/articles/what-are-openclaw-skills) | DigitalOcean | Skills architecture, YAML frontmatter, skill hierarchy, ClawHub. |
| [Building Custom Skills](https://www.datacamp.com/tutorial/building-open-claw-skills) | DataCamp | Hands-on — build Jupyter-to-Word converter + image generator skill. |
| [Security Professional's Journey](https://simonroses.com/2026/02/my-experience-using-openclaw-a-security-professionals-journey/) | Simon Roses | Two-week security audit running on Raspberry Pi 5 with Claude Sonnet 4. |
| [Top Alternatives](https://www.datacamp.com/blog/openclaw-alternatives) | DataCamp | OpenClaw vs coding agents, workflow platforms, enterprise tools. |
| [Architecture Deep Dive](https://entreconnect.substack.com/p/we-went-deep-on-openclaws-architecture) | EntreConnect | Post-OpenAI acquisition architectural analysis. |
| [OpenClaw, OpenAI and the Future](https://steipete.me/posts/2026/openclaw) | Peter Steinberger | Creator announces joining OpenAI, OpenClaw moves to a foundation. |

## Adjacent Alternatives

> Enterprise-grade alternatives and complementary platforms.

| Project | Description |
|---------|-------------|
| [Knolli](https://www.knolli.ai) | No-code AI copilot for businesses — SOC 2/GDPR, enterprise-grade security. |
| [Adopt AI](https://www.adopt.ai) | Enterprise agent platform — ZAPI zero-shot API discovery, SOC 2 Type II / ISO 27001 / GDPR / HIPAA. |
| [Happycapy](https://www.producthunt.com/categories/openclaw) | Agent-native computer — browser-based sandboxed workspace for AI agents. |

---

## Ecosystem at a Glance

```
                        ┌─────────────────────────────────┐
                        │        OpenClaw (Core)           │
                        │   TypeScript · 247K+ ⭐ · 15+ ch │
                        └──────────────┬──────────────────┘
                                       │
         ┌─────────────┬───────────────┼───────────────┬─────────────┐
         │             │               │               │             │
   ┌─────▼─────┐ ┌────▼────┐   ┌─────▼─────┐  ┌─────▼─────┐ ┌────▼────┐
   │ Lightweight│ │  Rust   │   │   Edge    │  │ Forks &   │ │Official │
   │ Assistants │ │Runtimes │   │& Embedded │  │ Rewrites  │ │  Repos  │
   │            │ │         │   │           │  │           │ │         │
   │ NanoClaw   │ │ZeroClaw │   │ NullClaw  │  │ go-claw   │ │ClawHub  │
   │ PicoClaw   │ │ZeptoClaw│   │ MimiClaw  │  │ oc-python │ │Lobster  │
   │ nanobot    │ │Moltis   │   │ zclaw     │  │ BrowserCl │ │acpx     │
   │ BabyClaw   │ │OpenFang │   │ femtoclaw │  │ Carapace  │ │Ansible  │
   │ Clawlet    │ │Carapace │   │ pycoClaw  │  │ mini-oc   │ │Nix      │
   └────────────┘ └─────────┘   │ HeyClawy  │  └───────────┘ └─────────┘
                                └───────────┘
         │             │               │               │             │
   ┌─────▼─────┐ ┌────▼────┐   ┌─────▼─────┐  ┌─────▼─────┐ ┌────▼────┐
   │ Security   │ │ Multi-  │   │ Platforms │  │  Hosted   │ │ MCP &   │
   │ & Privacy  │ │ Agent   │   │ & Cloud   │  │  Services │ │Tooling  │
   │            │ │         │   │           │  │           │ │         │
   │ IronClaw   │ │TinyClaw │   │Moltworker │  │ ClawTank  │ │mcporter │
   │ TrustClaw  │ │Flowly AI│   │SupaClaw   │  │ KiloClaw  │ │Nerve UI │
   │ ChaosClaw  │ │SuperAGI │   │ Jan.ai    │  │ EasyClaw  │ │ClawX    │
   │ safeclaw   │ │mission- │   │ Autobot   │  │ Agent37   │ │Foundry  │
   │ SlowMist   │ │ control │   │AnythingLLM│  │ SunClaw   │ │ClawHub  │
   └────────────┘ └─────────┘   └───────────┘  └───────────┘ └─────────┘
```

### Deployment Options

| Method | Difficulty | Cost |
|--------|-----------|------|
| Local (macOS/Linux) | Easy | Free |
| Raspberry Pi | Medium | $0 (hardware) |
| Docker / Podman | Medium | Free |
| One-click PaaS (Railway, Render) | Easy | $0–7/mo |
| VPS (Hetzner, Contabo, DO) | Medium | $4–20/mo |
| Kubernetes (Helm) | Hard | Varies |
| Managed (ClawTank, KiloClaw) | Easy | $10–50/mo |
| Infrastructure-as-Code (Ansible, Nix) | Medium | Free |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

### How to add a project

1. Fork this repository
2. Add your project to the appropriate category in `README.md`
3. Follow the existing format: `[Project Name](URL) | Language | Description ending with a period.`
4. Submit a Pull Request

### Quality standards

- Project must be related to the OpenClaw ecosystem or be a direct alternative
- Project must have a README with clear documentation
- Project should be actively maintained (commit within last 6 months)
- No duplicate entries

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hugomrvt/awesome-openclaw-ecosystem&type=Date)](https://star-history.com/#hugomrvt/awesome-openclaw-ecosystem&Date)

---

<div align="center">

**If you find this list useful, please give it a ⭐ — it helps others discover these projects!**

Made with ❤️ by [Hugo Mourlevat](https://github.com/hugomrvt)

</div>
