# Andrew Smith: text version

[Back to the Tokyo Night card view](README.md)

I own [Domillio](https://domillio.org). I'm an independent developer in Mississippi. I build Linux tools, web apps, and games, and I like working on both the machinery underneath and the part people actually touch.

[Selected builds](#selected-builds) · [Release history](#engineering-in-public) · [Profile stats](#profile-stats) · [Experiments](#under-construction) · [andrewsmith.app](https://andrewsmith.app)

## Selected builds

### 01 / [Keep RAM Clean](https://github.com/Andrew-Smith-93/keep-ram-clean)

**Rust · Linux daemon and CLI.** Keep RAM Clean monitors RAM, swap, tmpfs, and memory pressure. Cleanup runs on thresholds and schedules you set.

[Source and setup](https://github.com/Andrew-Smith-93/keep-ram-clean#readme) · [v2.3.0 release](https://github.com/Andrew-Smith-93/keep-ram-clean/releases/tag/v2.3.0)

### 02 / [Domillio](https://domillio.org)

**Shopify-focused document workflows.** I'm working on ways to collect and review tax-exemption certificates, product-safety documents, and disclosures without losing track of what was submitted or reviewed. The public browser demos use sample data; they aren't real merchant approvals or a claim of production readiness.

[Public browser demos](https://domillio.org/demos)

### 03 / [Tessera](https://github.com/Andrew-Smith-93/Tessera)

**KDE Plasma 6 · keyboard-driven window tiling.** Tessera runs inside KWin rather than replacing the desktop. I wanted windows to stay on the intended monitor, preserve a deliberate resize, and stop being driven by the tiler when they enter fullscreen.

[v1.0.2 release](https://github.com/Andrew-Smith-93/Tessera/releases/tag/v1.0.2) · [Installation and architecture](https://github.com/Andrew-Smith-93/Tessera#readme)

<details>
<summary>See Tessera on two monitors</summary>

[Open the full-size v1.0.2 screenshot](https://github.com/Andrew-Smith-93/Tessera/blob/v1.0.2/docs/screenshots/tessera-multiscreen-live.png)

</details>

### 04 / [Codeward](https://github.com/Andrew-Smith-93/codeward)

**TypeScript · code review tooling.** A collaborative CLI and GitHub Action project exploring how specialized review passes can produce findings people can actually use. The released v2 GitHub Action runs in offline mock mode. Automated findings still need human judgment.

[v2.0.0 release](https://github.com/Andrew-Smith-93/codeward/releases/tag/v2.0.0) · [Offline quickstart](https://github.com/Andrew-Smith-93/codeward#-quickstart)

## Engineering in public

| Public repository | Stars received | Stable releases |
| --- | ---: | ---: |
| [Keep RAM Clean](https://github.com/Andrew-Smith-93/keep-ram-clean) | 3 | 5 |
| [Tessera](https://github.com/Andrew-Smith-93/Tessera) | 1 | 2 |
| [Codeward](https://github.com/Andrew-Smith-93/codeward) | 1 | 2 |

Tessera also has 17 merged pull requests: 12 authored by me and 5 by Dependabot.

[Sources and counting method](stats/public-engineering.md) · [GitHub contribution history](https://github.com/Andrew-Smith-93?tab=overview)

## Profile stats

**6 public non-fork repos · 6 stars received · 4 primary languages** (Assembly, HTML, Rust, and TypeScript). These counts exclude private work and forks. [Scope and source](stats/public-engineering.md#profile-wide-stats).

**C+ · Top 78.5%** in the [GitHub Readme Stats model](stats/public-engineering.md#modeled-rank). It is a third-party estimate, not GitHub’s ranking or a measured percentile of GitHub users.

## Under construction

- **Fieldwork, Table, and Outline:** small local browser apps for jobs and estimates, CSV preparation, and writing with revisions.
- **Bridge:** a private local console for agent activity, messages, and worktree review, with native and x86-64 assembly work in its preview.
- **Anvil:** a private, pre-release Rust job queue for Linux, backed by SQLite and designed for one machine.
- **Dies Irae & Lanternbound:** private Godot projects exploring action-roguelike and companion-card mechanics.

## How I build

An original CSV should survive an edit. An export should match what was reviewed. A window should stay on the right monitor. I like software that makes its state understandable, and I rely on tests, review, and hands-on debugging to see whether it does what I meant.

**What I work with:** Rust · TypeScript / JavaScript · Linux / KWin · SQLite · Godot / GDScript · x86-64 assembly · web UX
