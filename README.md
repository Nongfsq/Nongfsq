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
flowchart TB
    Work["Architecture work"]

    Work --> Domain["Domain ownership"]
    Domain --> Identity["Canonical content identity"]
    Domain --> Lifecycle["Lifecycle and moderation states"]
    Domain --> Reputation["Reputation and audit ledgers"]
    Domain --> Authority["Public versus administrative authority"]

    Work --> Contracts["Contract boundaries"]
    Contracts --> Rest["REST for protocol and data-plane reads"]
    Contracts --> Graphql["GraphQL for composed experience views"]
    Contracts --> Clients["Generated clients and DTOs"]
    Contracts --> Smoke["Contract smoke tests"]

    Work --> Data["Data behavior"]
    Data --> Viewport["Viewport-scoped map reads"]
    Data --> Location["Approximate location policy"]
    Data --> ReadModels["Search and cache read models"]
    Data --> Migration["Migration and index discipline"]

    Work --> Privilege["Privilege model"]
    Privilege --> Capabilities["Role-scoped capabilities"]
    Privilege --> AdminOrigin["Admin-origin separation"]
    Privilege --> StepUp["Step-up verification"]
    Privilege --> NonEnumerating["Non-enumerating responses"]

    Work --> Ops["Operability"]
    Ops --> Diagnostics["Structured diagnostics"]
    Ops --> Correlation["Request correlation"]
    Ops --> Failure["Failure evidence"]
    Ops --> Rollback["Deployment rollback path"]
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
flowchart TB
    Focus["Technical focus"]

    Focus --> Product["Product architecture"]
    Product --> DomainModeling["Domain modeling"]
    Product --> CanonicalObjects["Canonical objects"]
    Product --> Surfaces["Public and admin surfaces"]
    Product --> Workflows["Operational workflows"]

    Focus --> Frontend["Frontend platform"]
    Frontend --> NextStack["Next.js React TypeScript"]
    Frontend --> Seo["SSR RSC SEO"]
    Frontend --> Mapbox["Mapbox WebGL"]
    Frontend --> Accessibility["Accessibility and motion budgets"]

    Focus --> Backend["Backend platform"]
    Backend --> RustStack["Rust Axum Tokio"]
    Backend --> Sqlx["SQLx PostgreSQL migrations"]
    Backend --> Openapi["OpenAPI Hurl contracts"]
    Backend --> GraphqlBoundary["GraphQL experience boundary"]

    Focus --> DataSystems["Data systems"]
    DataSystems --> MapData["Map data plane"]
    DataSystems --> Cache["Cache keys and ETags"]
    DataSystems --> Search["Search vectors and indexes"]
    DataSystems --> Ledgers["Audit and reputation ledgers"]

    Focus --> Governance["Governance"]
    Governance --> Rbac["RBAC and WebAuthn"]
    Governance --> StepUpTech["Step-up verification"]
    Governance --> AdminSurface["Admin surface separation"]
    Governance --> NonEnumeratingTech["Non-enumerating responses"]

    Focus --> Delivery["Delivery and evidence"]
    Delivery --> Hosting["Vercel Railway Docker"]
    Delivery --> Observability["Sentry PostHog NDJSON"]
    Delivery --> Testing["Vitest Playwright Rust tests"]
    Delivery --> DiagnosticsTech["AI-readable diagnostics"]

    Focus --> Automation["Automation"]
    Automation --> Codex["Codex workflows"]
    Automation --> Planning["PM PLAN TASK documents"]
    Automation --> Skills["Vibe Coding Skills"]
    Automation --> Cli["GitHub CLI and PowerShell"]

    Focus --> Workstation["Workstation"]
    Workstation --> Neovim["Neovim LazyVim Lua"]
    Workstation --> Shell["Zsh shell tooling"]
    Workstation --> Rime["Rime input workflow"]
    Workstation --> Setup["Recoverable setup"]
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
