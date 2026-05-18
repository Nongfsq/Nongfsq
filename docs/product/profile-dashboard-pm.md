# GitHub Profile Dashboard PM

## Problem And Product Intent

`github.com/Nongfsq` should be more than a public profile. It should be a remote cockpit: a polished public surface for visitors, and a fast owner-facing launchpad into active repositories, private project categories, and search routes.

The previous state had two gaps:

- GitHub Overview showed pinned public repositories but did not show the profile README.
- The README existed, but it needed to behave as a navigable repository dashboard rather than a static bio.

## Target Users And Jobs

- Owner: quickly reopen active work, search by topic, and jump into private categories after logging in.
- Public visitor: understand the technical focus and open public projects without seeing private repository details.
- Future agent/session: inspect the profile repo and understand the intended IA without re-deciding the product direction.

## PM Judgment

Essential promise: opening the profile should answer, in seconds, "what is active, where do I click, and what is publicly safe to show?"

Taste bar:

- Command center over resume.
- Search routes over long repository lists.
- Public project cards over badge clutter.
- Abstract private categories over leaking private repo inventory.

Rejected compromises:

- Do not rely on `Popular repositories` as the management surface; GitHub pins only support public repositories and gists.
- Do not pile on dynamic widgets unless they improve navigation or signal.
- Do not expose private repository names publicly beyond already-approved abstract categories.

## Current Reality

- `Nongfsq/Nongfsq` is public, default branch `main`, and contains root `README.md`.
- GitHub required a manual `Share to Profile` action before rendering the README on the Overview page.
- Profile pins are configured for five public repositories: `clarity_lazyvim`, `codex-custom-model-picker-repair`, `zsh_config`, `Nongfsq`, and `pi-monitor`.
- Private repositories can be reached by the owner through GitHub search links, but cannot be shown as public pinned cards.

## Proposed Behavior

- The Overview page renders the profile README above the pinned repositories.
- The top of the README presents a clear dashboard banner and quick-launch actions.
- Owner-focused links use GitHub search by topic and language.
- Public project cards point only to public repositories.
- Private categories remain abstract and owner-only by access control.

## Success Criteria

- `https://github.com/Nongfsq` visibly includes the README dashboard.
- Public pins remain stable and clickable.
- Logged-in owner search links return private and public results as allowed by GitHub.
- Public visitors do not see private repository names or links that reveal private repo metadata.
- README images do not break under normal GitHub rendering.

## Non-Goals

- No private repository visibility changes.
- No repo rename, archive, delete, or migration.
- No token-backed private metrics.
- No JavaScript-dependent UI.

## Risks

- Third-party dynamic image services may be slow or temporarily unavailable.
- GitHub search behavior differs for logged-in owner versus public visitor.
- Profile README rendering can be affected by GitHub caching after changes.
