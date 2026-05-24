<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=900&color=0F766E&center=true&vCenter=true&width=960&lines=Company-scale+private+product+systems;Typed+platforms%2C+data+planes%2C+security+boundaries;AI-assisted+delivery%2C+production-grade+verification)](https://git.io/typing-svg)

[![Systems practice](https://img.shields.io/badge/Systems%20practice-product%20%7C%20platform%20%7C%20ops-111827?style=for-the-badge&logo=github&logoColor=white)](#systems-i-build)
[![Architecture](https://img.shields.io/badge/Architecture-data%20%7C%20API%20%7C%20security-0f766e?style=for-the-badge&logo=graphql&logoColor=white)](#current-work)
[![Engineering stack](https://img.shields.io/badge/Engineering%20stack-full--stack%20%7C%20DevOps%20%7C%20QA-2563eb?style=for-the-badge&logo=typescript&logoColor=white)](#technical-focus)
[![Public repositories](https://img.shields.io/badge/Public%20repositories-selected%20artifacts-7c2d12?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nongfsq?tab=repositories&q=&type=public&language=&sort=pushed)

</div>

## Systems I Build

I build private, company-scale product systems where product design, platform architecture, data governance, security, delivery, and AI-assisted execution are treated as one operating system.

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

The public repositories are selected artifacts from a broader private engineering practice. The deeper work lives in integrated systems with public UX, dedicated admin operations, typed API boundaries, role-governed security, privacy-aware analytics, deployment discipline, and internal tooling designed to keep a serious product organization moving.

## Current Work

The current flagship work is a company-grade private product platform with geospatial discovery, canonical archives, profile and social systems, admin operations, reputation governance, hosted commerce, media workflows, and deployment discipline.

```mermaid
mindmap
  root((Current work))
    Product platform
      Geospatial discovery
      Canonical archive
      Profile and social systems
      Commerce and media workflows
    Platform core
      Rust Axum API
      PostgreSQL plus SQLx
      OpenAPI plus GraphQL boundary
      Cache and search read models
    Governance
      Auth and RBAC
      Admin surface separation
      WebAuthn and step up flows
      Audit evidence
    Operations
      Vercel and Railway delivery
      Sentry PostHog NDJSON
      Playwright Hurl Rust tests
      Mobile QA evidence
    AI execution
      PM to architecture to task plans
      Codex workflows
      Agent instructions
      Multi session handoffs
```

```mermaid
flowchart TB
    Web["Public web\nNext.js, SEO, maps"] --> Boundary["Experience boundary\nsame-origin proxy, typed clients"]
    Admin["Admin operations\nmoderation, governance, observability"] --> Boundary
    Boundary --> API["Rust API\nservices, queries, contracts"]
    API --> PG[("PostgreSQL\nstate, ledgers, search")]
    API --> Providers["Provider plane\nCloudflare, Mapbox, commerce, email"]
    API --> Evidence["Evidence loop\nlogs, tests, diagnostics"]
```

Current tracks: product-surface architecture, map data plane, API contracts, security governance, media pipeline, observability, QA evidence, and AI-assisted delivery infrastructure.

## Public Projects

Selected public artifacts from a broader private engineering practice.

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

| Layer | Tools and domains |
| --- | --- |
| **Product and systems architecture** | Independent product ownership, domain modeling, canonical content objects, public/admin surfaces, permissions, governance, SEO, commerce boundaries, and operational workflows. |
| **Frontend platform** | Next.js, React, TypeScript, SSR/RSC, Tailwind, shadcn/ui, Framer Motion, Mapbox/WebGL, TanStack Query, Zustand, accessibility, and premium interaction design. |
| **Backend platform** | Rust, Axum, Tokio, SQLx, PostgreSQL, migrations, auth/RBAC, OpenAPI, Hurl, GraphQL Experience API planning, service/query layering, and typed contracts. |
| **Data and scale** | Map Data Plane, cache keys, request coalescing, ETags, search vectors, indexing, audit/reputation ledgers, large-data processing, structured archives, dictionary data, and media metadata pipelines. |
| **Security and governance** | WebAuthn/passkeys, elevated verification, admin-surface separation, role-scope visibility, high-privilege guardrails, non-enumerating responses, and audit evidence. |
| **DevOps and observability** | Vercel, Railway, Docker, GitHub Actions, Sentry, PostHog, structured NDJSON logs, request tracing, diagnostic CLIs, deployment checks, and Windows-native local operations. |
| **Quality and verification** | Vitest/RTL, Playwright, Rust integration tests, Hurl contracts, OpenAPI type generation, Android mobile QA, privacy guardrails, and AI-readable diagnostic reports. |
| **Media and automation** | Python, Rust, PowerShell, FFmpeg-style media processing, image/video compression, YouTube/content workflows, object storage pipelines, and GitHub CLI automation. |
| **AI engineering** | Codex workflows, PM/PLAN/TASK documents, Vibe Coding Skills, agent rules, multi-session collaboration, instruction systems, branch/worktree protocols, and repeatable task handoff. |
| **Developer environment** | Neovim, LazyVim, Lua, Zsh, shell tooling, terminal migration, Rime/input-method work, and recoverable workstation setup. |

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
