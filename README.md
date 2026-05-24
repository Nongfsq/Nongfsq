<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=900&color=0F766E&center=true&vCenter=true&width=960&lines=Private+product+systems+architecture;Typed+boundaries%2C+data+planes%2C+governance+models;AI-assisted+delivery%2C+verification+loops)](https://git.io/typing-svg)

[![Systems practice](https://img.shields.io/badge/Systems%20practice-product%20%7C%20platform%20%7C%20ops-111827?style=for-the-badge&logo=github&logoColor=white)](#systems-i-build)
[![Architecture](https://img.shields.io/badge/Architecture-data%20%7C%20API%20%7C%20security-0f766e?style=for-the-badge&logo=graphql&logoColor=white)](#current-work)
[![Engineering stack](https://img.shields.io/badge/Engineering%20stack-full--stack%20%7C%20DevOps%20%7C%20QA-2563eb?style=for-the-badge&logo=typescript&logoColor=white)](#technical-focus)
[![Public repositories](https://img.shields.io/badge/Public%20repositories-workbench%20tools-7c2d12?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nongfsq?tab=repositories&q=&type=public&language=&sort=pushed)

</div>

## Systems I Build

I build private product systems where product design, platform architecture, data governance, security, delivery, and AI-assisted execution are treated as one coordinated delivery system.

```mermaid
flowchart LR
    Intent["Product intent\nmarket, domain, UX"] --> Surfaces["Product surfaces\npublic web, admin ops, commerce"]
    Surfaces --> Contracts["Typed contracts\nREST, GraphQL, DTOs"]
    Contracts --> Core["Platform core\nRust services, PostgreSQL"]
    Core --> Data["Data plane\nmaps, search, media, ledgers"]
    Data --> Ops["Operations\nobservability, QA, deployment"]
    Ops --> Intent

    Security["Security + governance\nauth, RBAC, audit"] -. guards .-> Surfaces
    Security -. guards .-> Core
    AI["AI delivery system\nplans, tasks, agent handoffs"] -. accelerates .-> Contracts
    AI -. accelerates .-> Ops
```

## Current Work

Current work centers on a private production system. I keep the public description at the architecture level: domain ownership, API boundaries, data behavior, privilege separation, and the evidence needed to operate changes safely.

```mermaid
mindmap
  root((Architecture work))
    Domain ownership
      Canonical content identity
      Lifecycle and moderation states
      Reputation and audit ledgers
      Public versus administrative authority
    Contract boundaries
      REST for protocol and data-plane reads
      GraphQL for composed experience views
      Generated clients and DTOs
      Contract smoke tests
    Data behavior
      Viewport-scoped map reads
      Approximate location policy
      Search and cache read models
      Migration and index discipline
    Privilege model
      Role-scoped capabilities
      Admin-origin separation
      Step-up verification
      Non-enumerating responses
    Operability
      Structured diagnostics
      Request correlation
      Failure evidence
      Deployment rollback path
```

```mermaid
flowchart TB
    Web["Public surface\nrendering, SEO, interaction"] --> Proxy["Same-origin API boundary\ncookies, typed clients"]
    Admin["Admin surface\ngovernance, moderation, operations"] --> Proxy
    Proxy --> API["Application API\nRust Axum, policy, orchestration"]
    API --> Services["Domain services\ntransactions, invariants, side effects"]
    Services --> Queries["Query layer\nread models, search, map slices"]
    Services --> PG[("PostgreSQL\nstate, ledgers, indexes")]
    Services --> Adapters["Provider adapters\nmedia, maps, commerce, email"]
    API --> Evidence["Verification surface\nOpenAPI, Hurl, logs, traces"]
```

Current architecture tracks: contract design, domain-service boundaries, map read-model behavior, role-scoped governance, provider isolation, observability events, and repeatable verification.

## Public Workbench

Small public pieces from my own workbench: configs, repair scripts, monitors, and experiments that were useful enough to keep outside private systems. Not the main body of work, but usually practical.

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/Nongfsq/clarity_lazyvim">
        <strong>clarity_lazyvim</strong>
      </a>
      <br />
      Accessible LazyVim configuration focused on readability, contrast, and long-session comfort.
      <br />
      <sub>Lua · public template · editor environment</sub>
    </td>
    <td width="50%">
      <a href="https://github.com/Nongfsq/pi-monitor">
        <strong>pi-monitor</strong>
      </a>
      <br />
      Raspberry Pi website monitoring with RGB LED status and a small web interface.
      <br />
      <sub>Python · Raspberry Pi · monitoring</sub>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <a href="https://github.com/Nongfsq/zsh_config">
        <strong>zsh_config</strong>
      </a>
      <br />
      Shell and Zsh configuration files for a portable, recoverable command-line setup.
      <br />
      <sub>Shell · configuration · development environment</sub>
    </td>
    <td width="50%">
      <a href="https://github.com/Nongfsq/codex-custom-model-picker-repair">
        <strong>codex-custom-model-picker-repair</strong>
      </a>
      <br />
      PowerShell repair tooling for Codex model picker configuration.
      <br />
      <sub>PowerShell · Codex tooling · repair script</sub>
    </td>
  </tr>
</table>

## Technical Focus

<p>
  <a href="https://github.com/search?q=user%3ANongfsq+language%3ATypeScript&type=repositories"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript"></a>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs">
  <img alt="React" src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-111827?style=flat-square&logo=tailwindcss">
  <img alt="Framer Motion" src="https://img.shields.io/badge/Framer_Motion-111827?style=flat-square&logo=framer">
  <img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-111827?style=flat-square&logo=reactquery">
  <a href="https://github.com/search?q=user%3ANongfsq+language%3APython&type=repositories"><img alt="Python" src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python"></a>
  <a href="https://github.com/search?q=user%3ANongfsq+language%3ARust&type=repositories"><img alt="Rust" src="https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust"></a>
  <img alt="Axum" src="https://img.shields.io/badge/Axum-111827?style=flat-square&logo=rust">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql">
  <img alt="SQLx" src="https://img.shields.io/badge/SQLx-111827?style=flat-square&logo=postgresql">
  <img alt="OpenAPI" src="https://img.shields.io/badge/OpenAPI-111827?style=flat-square&logo=openapiinitiative">
  <img alt="GraphQL" src="https://img.shields.io/badge/GraphQL-111827?style=flat-square&logo=graphql">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis">
  <img alt="WebAuthn" src="https://img.shields.io/badge/WebAuthn-111827?style=flat-square">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-111827?style=flat-square&logo=vercel">
  <img alt="Railway" src="https://img.shields.io/badge/Railway-111827?style=flat-square&logo=railway">
  <img alt="Cloudflare R2" src="https://img.shields.io/badge/Cloudflare_R2-111827?style=flat-square&logo=cloudflare">
  <img alt="Shopify" src="https://img.shields.io/badge/Shopify-111827?style=flat-square&logo=shopify">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-111827?style=flat-square&logo=githubactions">
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-111827?style=flat-square&logo=sentry">
  <img alt="PostHog" src="https://img.shields.io/badge/PostHog-111827?style=flat-square&logo=posthog">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-111827?style=flat-square&logo=playwright">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-111827?style=flat-square&logo=vitest">
  <img alt="Hurl" src="https://img.shields.io/badge/Hurl-111827?style=flat-square">
  <img alt="FFmpeg" src="https://img.shields.io/badge/FFmpeg-111827?style=flat-square&logo=ffmpeg">
  <img alt="Mapbox" src="https://img.shields.io/badge/Mapbox-111827?style=flat-square&logo=mapbox">
  <img alt="Bun" src="https://img.shields.io/badge/Bun-111827?style=flat-square&logo=bun">
  <a href="https://github.com/search?q=user%3ANongfsq+language%3AShell&type=repositories"><img alt="Shell" src="https://img.shields.io/badge/Shell-111827?style=flat-square&logo=gnubash"></a>
  <img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-111827?style=flat-square&logo=powershell">
  <a href="https://github.com/search?q=user%3ANongfsq+language%3ALua&type=repositories"><img alt="Lua" src="https://img.shields.io/badge/Lua-111827?style=flat-square&logo=lua"></a>
  <a href="https://github.com/search?q=user%3ANongfsq+language%3AVue&type=repositories"><img alt="Vue" src="https://img.shields.io/badge/Vue-111827?style=flat-square&logo=vuedotjs"></a>
  <a href="https://github.com/search?q=user%3ANongfsq+language%3AC%2B%2B&type=repositories"><img alt="C++" src="https://img.shields.io/badge/C%2B%2B-111827?style=flat-square&logo=cplusplus"></a>
  <img alt="Neovim" src="https://img.shields.io/badge/Neovim-111827?style=flat-square&logo=neovim">
</p>

<p align="center">
  <sub><em>Plot twist: none of the above matters. Just learn <strong>Vibe Coding</strong>.</em></sub>
</p>

```mermaid
mindmap
  root((Technical focus))
    Product architecture
      Domain modeling
      Canonical objects
      Public and admin surfaces
      Operational workflows
    Frontend platform
      Next.js React TypeScript
      SSR RSC SEO
      Mapbox WebGL
      Accessibility and motion budgets
    Backend platform
      Rust Axum Tokio
      SQLx PostgreSQL migrations
      OpenAPI Hurl contracts
      GraphQL experience boundary
    Data systems
      Map data plane
      Cache keys and ETags
      Search vectors and indexes
      Audit and reputation ledgers
    Governance
      RBAC and WebAuthn
      Step-up verification
      Admin surface separation
      Non-enumerating responses
    Delivery and evidence
      Vercel Railway Docker
      Sentry PostHog NDJSON
      Vitest Playwright Rust tests
      AI-readable diagnostics
    Automation
      Codex workflows
      PM PLAN TASK documents
      Vibe Coding Skills
      GitHub CLI and PowerShell
    Workstation
      Neovim LazyVim Lua
      Zsh shell tooling
      Rime input workflow
      Recoverable setup
```

## Operating Standard

| Product | Architecture | Delivery |
| --- | --- | --- |
| Own the product, domain model, public/admin split, and operational rules as one system. | Typed contracts, auditable data flows, permission boundaries, and observable failure evidence. | AI-assisted execution backed by PM plans, tests, diagnostics, and durable handoff artifacts. |

<div align="center">

`readable systems` · `operable environments` · `research-grade workflows`

<sub>Product architecture, typed platforms, DevOps observability, media/data pipelines, and AI-assisted execution.</sub>

</div>

<p align="center">
  <sub><em>“Economics has always maintained that wealth emerges solely from production and services, and never originates from distribution.”</em></sub><br />
  <sub>Frank X.</sub>
</p>
