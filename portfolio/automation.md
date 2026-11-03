# Automation and desktop adaptations

This work includes original tools and adaptations of existing applications. All my development described here used AI assistance; upstream authorship remains separate.

## Brops for Windows

**Work:** A Windows adaptation of [Bops](https://github.com/nickvasilescu/bops), with an Electron runtime, installer/portable packaging, Windows controls, protected local configuration and optional cloud services.

**My contribution:** Windows packaging and native interaction, local memory, official Codex/Claude Code client connections, provider onboarding and local virtual-computer workflows. The base interface, bots and original application are inherited from Bops.

**Stack and status:** TypeScript, Next.js, Electron, Windows APIs and QEMU-based local computers. The private implementation documents Windows builds and native checks. Bops's FSL license and branding notices remain in place; this is an adaptation, not a claim of original authorship of Bops.

## Riverz Harness

**Work:** A separate Windows application combining Brops-derived agent-team workflows, Rivo voice and a persistent operations center for goals, tasks, projects and documents.

**My contribution:** Connecting the team and voice flows, independent application identity/profile, project worktrees, persistent schedules, interruption recovery and review of uncertain external actions.

**Stack and status:** TypeScript, Next.js, Electron and an integrated Python voice companion. The repository contains installer and native-QA documentation. The foundation remains Brops/Bops plus Rivo; the inherited FSL and third-party notices are retained.

## Screenplay

**Work:** A browser/desktop recording tool for repeatable product demonstrations and application-review screencasts. A route is mapped, rehearsed and then recorded.

**My contribution:** Flow definitions, readiness checks, route fingerprints, observable step completion, cursor/caption behavior and owned-window capture. Changing the route invalidates the old rehearsal rather than treating recorded clicks as proof of success.

**Stack and status:** Python, Chrome debugging and Windows recording/interaction tools. Implemented internal tooling with route/readiness tests; individual recordings still depend on their own account access and verified route.

## Odylic Constellation for Windows

**Work:** A Windows adaptation of [Odylic Media's advertising visualization app](https://github.com/peterquads/odylic-constellation).

**My contribution:** Installer and portable packaging, bundled runtime, Windows launch/stop handling and local-storage integration. The original 3D interface and core advertising application belong to Odylic Media.

**Stack and status:** Python, TypeScript/React and Windows packaging. The [public MIT fork](https://github.com/excelenciaempire/odylic-constellation) contains the actual adaptation code and its Windows notes. It is not a separate advertising product built entirely from scratch.

## LeadSwarm

**Work:** A lead-prospecting prototype with chat/table interaction, enrichment, ICP scoring, cost previews, scheduled agents, campaign sequencing and CRM write-back flows.

**My contribution:** The shared run engine and contracts, streaming UI, budget/credit logic, composable columns, deterministic replay and mock-backed workflows.

**Stack and status:** TypeScript, Next.js, NestJS and shared engine packages. The documented end-to-end demo uses deterministic mock adapters, and real outreach is disabled by default. It demonstrates implemented prototype behavior, not a live prospect database or proven delivery campaign.

[Full portfolio](../README.md)
