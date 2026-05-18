# PROFILE Dashboard PLAN+TASK

## Summary

Turn `github.com/Nongfsq` into a useful remote cockpit. The page should show a polished profile README, stable public pins, and owner-only search paths into private work without exposing private repository details.

## Current Reality

- Profile repo: `Nongfsq/Nongfsq`, public, default branch `main`.
- README path: root `README.md`.
- The README did not render until the repository's `Share to Profile` button was clicked.
- Pinned repositories can only be public repositories or public gists.

## Architecture Decisions

- Use GitHub-compatible Markdown and sanitized HTML only.
- Use static local SVG for the hero banner.
- Use third-party image services only when they render reliably. Keep `shields.io` and `readme-typing-svg`; avoid `github-readme-stats` because it returned `DEPLOYMENT_PAUSED` during verification.
- Use GitHub Search URLs as the "search" interface because README pages cannot run JavaScript.
- Keep private work represented as topic-based owner-only searches, not explicit public private-repo lists.

## Tasks

- `PROFILE-001`: Document PM intent and current reality in `docs/product/profile-dashboard-pm.md`.
- `PROFILE-002`: Diagnose README non-display through GitHub repo state, root README presence, and browser verification.
- `PROFILE-003`: Enable profile rendering by using GitHub's `Share to Profile` control.
- `PROFILE-004`: Redesign README into hero, quick launch, owner cockpit, public project cards, search shelf, signal, and principles.
- `PROFILE-005`: Add dynamic visuals through reliable third-party image services without private tokens; remove services that render broken images.
- `PROFILE-006`: Keep and refine `assets/profile-console.svg` as the stable visual anchor.
- `PROFILE-007`: Verify all public and owner-only links.
- `PROFILE-008`: Reconfirm pinned repositories after README rendering is fixed.

## Test And QA Plan

- Run `git diff --check`.
- Verify `gh repo view Nongfsq/Nongfsq` reports public visibility and default branch `main`.
- Verify `gh api repos/Nongfsq/Nongfsq/readme` returns root `README.md`.
- Verify browser Overview text includes `Command Center` and `Active Launchpad`.
- Verify browser Overview still includes pinned repositories.
- Verify owner topic search links are valid GitHub URLs.
- Verify public README does not list private repository names beyond approved abstract project labels.

## Rollout And Rollback

- Rollout is a normal push to `main` plus browser verification on `https://github.com/Nongfsq`.
- If dynamic images fail or make the page feel cluttered, remove third-party cards first and keep static links.
- If Profile README disappears again, revisit the `Share to Profile` state on the repository page.
