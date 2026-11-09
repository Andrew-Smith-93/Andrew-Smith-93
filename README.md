# Andrew Smith

**Software, systems, and tools that do real work.**

Independent developer in Mississippi. I build desktop systems, business applications, developer tools, and original games. My current work spans native assembly, Rust, TypeScript, and Godot.

[Portfolio & live apps](https://andrewsmith.app/work/) · [Email](mailto:andrewsmith.independent@gmail.com)

## What I'm building now

### Bridge · Native desktop tooling

A local console for agent reports, messages, and worktree review. The limited native preview uses **x86-64 assembly for its desktop UI and backend**, with native-library dependencies and a JavaScript browser interface. It is an ongoing engineering project, not a claim that every legacy feature has been replaced or that every dependency is assembly.

### Domillio · Merchant workflow applications

A suite of Shopify-focused applications for tax-exemption certificates, product-safety documentation, and disclosure workflows. The work includes **Tax Exemption Desk, CPC Desk, GPSR Desk, and Prop 65 Desk**. These are development and review projects; listing them here does not imply Shopify approval or guarantee legal compliance.

### Dies Irae · Action roguelike

An original Godot horde-survivor with a refuge hub, three-act campaign, weapon sets, backpack management, and persistent forge progression. The current build unlocks a harder Crucible mode through campaign completion. A larger world and story are the next direction, not features I'm claiming are finished.

### Lanternbound · Companion-card roguelike

A playable Godot prototype built around a **cast-or-channel card system**, affinity resonance, and three companion lanes. Three acts, three keepers, 41 cards, visible enemy intentions, and local run saves give it a complete run loop. Balance, animation, and accessibility are still developing.

### Anvil · Rust systems software

A pre-release local job queue for Linux: a daemon and CLI, durable SQLite-backed jobs, bounded workers, retries, and restart recovery. Built for one machine rather than a distributed service.

These projects have private source. Public demos and case studies are linked where available; a profile mention is not a public-source release.

## Featured: Tessera

**Dynamic tiling inside KDE Plasma 6's window manager.**

[Tessera](https://github.com/Andrew-Smith-93/Tessera) runs as a KWin script, with native System Settings integration, multi-monitor layouts, snap zones, and keyboard controls.

The interesting work is in the details: keeping windows attached to the right monitor during animation, handling vertically stacked displays, and making configuration feel like part of KDE rather than a separate application.

The [v1.0.2 release](https://github.com/Andrew-Smith-93/Tessera/releases/tag/v1.0.2) documents:

- Explicit monitor-affinity tracking and fixes for cross-screen snap relocation.
- Native shortcut settings covering 22 starting keybindings.
- 452 passing unit tests and 25 matching golden simulation traces.
- Live X11 verification across three physical displays. Wayland hotplug testing is separate, not claimed here.

[Source](https://github.com/Andrew-Smith-93/Tessera) · [Releases](https://github.com/Andrew-Smith-93/Tessera/releases) · [KDE Store](https://store.kde.org/p/2375512/)

## Live browser projects

My [app collection](https://andrewsmith.app/work/#showcase-title) includes eight working local browser applications and three prototypes. These are focused workspaces, with real editing and export flows, rather than screenshots of dashboards.

### Business workflows

- **[Fieldwork](https://andrewsmith.app/tools/fieldwork/)**: contractor customers, estimates, daily visits, job checklists, service history, and local invoices. Designed for fast entry on a phone.
- **[Forma](https://andrewsmith.app/tools/forma/)**: suppliers, purchase orders, partial receiving, SKU stock, sales, and reasoned returns.
- **[Relay](https://andrewsmith.app/tools/relay/)**: client proposals, accepted scope, delivery milestones, invoices, and manually recorded payments.

### Data and document workflows

- **[Table](https://andrewsmith.app/tools/table/)**: CSV preparation with immutable source snapshots, reviewed column mapping, before-and-after changes, and reproducible transformation recipes.
- **[Outline](https://andrewsmith.app/tools/outline/)**: manuscripts, revision-specific reviews, preserved ready editions, and portable documents.
- **[Minutes](https://andrewsmith.app/tools/minutes/)**: recurring agendas, owned actions, preserved numbered minutes, and calendar exports.
- **[Sprint](https://andrewsmith.app/tools/sprint/)**: planned work, timed or manual actuals, and dated actual-versus-plan reports.
- **[Kit](https://andrewsmith.app/tools/kit/)**: trip planning, equipment reservations, partial returns, and maintenance readiness.

**Scope:** records stay on the device, with portable exports. Examples use synthetic data. These apps do not provide team sync, server accounts, outbound messaging, or real payment processing.

### Prototypes and visual experiments

[Wayfinder](https://andrewsmith.app/tools/wayfinder/) explores stock movements and fulfillment; [Linework](https://andrewsmith.app/tools/linework/) provides an editable diagram canvas with checkpoints; [Daybook](https://andrewsmith.app/tools/daybook/) connects wedding RSVPs, seating, budgets, and a dated run sheet. These are local browser prototypes.

I also build interactive visual studies: [Workbox](https://andrewsmith.app/lab/workbox/) explores mechanical packing in Three.js, and [Open Orbit](https://andrewsmith.app/lab/kinetic-hero/) explores a navigable 3D workstation scene.

## Other public work

- **[Codeward](https://github.com/Andrew-Smith-93/codeward)**: a collaborative TypeScript CLI and GitHub Action for structured AI-assisted code review. Security, logic, reliability, and architecture findings organized into reports.
- **[Cozy Solutions](https://www.cozysolutions.org/)**: a live plumbing and HVAC website with residential and commercial service paths, team photography, and direct contact options.

## Engineering priorities

I care about state that survives the next step: a window staying on its monitor, an original CSV remaining intact, an accepted scope staying fixed, or an exported document matching the version reviewed.

My work spans x86-64 assembly, Rust, TypeScript/JavaScript, React/Next.js, Godot/GDScript, Linux/KWin, browser storage, Web Workers, Three.js, and CLI workflows. I use AI-assisted development alongside source review, reproducible checks, and release verification.

[andrewsmith.app](https://andrewsmith.app) · [andrewsmith.independent@gmail.com](mailto:andrewsmith.independent@gmail.com)
