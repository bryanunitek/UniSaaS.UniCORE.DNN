# UniSaaS.UniCORE.DNN

**SCAFFOLD-ANCHOR repository — initial commit 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 08:11 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.DNN` is the **DNN** family member: SaaS-deployment-shape public gift surface. Documentation today; source code at certification. Sister to the on-prem-shape repo.

**Family purpose:** Web content management and site framework. Long-running .NET-based CMS / portal platform.

**Role in UniCORE:** Web CMS / portal building block. Consumed by Vertical COREs that need a content-management surface, and by UniCORE.GVB where a hosted-site CMS is part of the substrate offering.

---

## Substrate

- **Substrate project:** DNN (.NET CMS / portal platform).
- **Substrate licence (upstream OSS):** MIT.
- **Our relationship:** Fork-and-extend. The substrate codebase is consumed under its original licence; our additions sit on top under CC BY 4.0.

**Our additions:** UniCORE.DNN adds CC BY 4.0 UniCORE-authored modules, adapters, and integrations on top of the DNN substrate base. Specific module set to be enumerated in the family kickoff arc.

**Note on outbound links:** This repository deliberately does not publish outbound URLs to substrate-vendor sites. Substrate provenance is captured locally in [`STARTING-POINT.md`](STARTING-POINT.md) via anchor SHA; that is sufficient to reproduce the substrate state without amplifying vendor-side traffic from the UniCORE public surface.

The merge discipline that governs how this repository absorbs upstream changes without losing UniCORE additions is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) at the root of this repository.

---

## Family — the four-repo pattern

UniCORE.DNN is published as a **four-repo family**:

- `bryanunitek/UniCORE.DNN` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.DNN` — public SaaS-deployment-shape gift surface
- `bryanunitek/UniCORE.DNN-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.DNN-Claw` (private) — SaaS-shape working repository

**This repository is the `UniSaaS.UniCORE.DNN` member of the family.**

Sister repos:

- [`UniCORE.DNN`](https://github.com/bryanunitek/UniCORE.DNN)
- `UniCORE.DNN-Claw (private)`
- `UniSaaS.UniCORE.DNN-Claw (private)`

---

## Status

**SCAFFOLD-ANCHOR ONLY** as of 2026-06-04 08:11 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown and what is and is not in this initial commit.

The work has been queued in `memory/2026-06-04-post-24h-arc-discussion-queue.md` (workspace-local) with explicit Bryan-authorised scope:

1. Fork MIT upstream into this repo (4 family members).
2. Author CC BY 4.0 UniCORE-equivalent features over the upstream base.
3. Apply the canonical upstream-merge discipline.
4. Enrol in UniCORE Sanity Check.

This initial commit accomplishes (4) only. Items (1)–(3) follow in fresh dedicated arcs.

---

## Files in this initial commit

- [`README.md`](README.md) — this file
- [`LICENSE.md`](LICENSE.md) — CC BY 4.0 for UniCORE additions
- [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim copy of the upstream OSS licence
- [`STATUS.md`](STATUS.md) — explicit scaffold-anchor status with what's pending
- [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline (applies once upstream is forked in)
- `.gitignore`

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://github.com/bryanunitek/UniVERSE) — programme
- [`TrueAI`](https://github.com/bryanunitek/TrueAI) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://github.com/bryanunitek/UniCORE-AI) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://github.com/bryanunitek/UniCORE) — on-prem-shape
- [`UniSaaS.UniCORE`](https://github.com/bryanunitek/UniSaaS.UniCORE) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://github.com/bryanunitek/UniCORE.GVB) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB) — SaaS-shape

**Forked-upstream building blocks (this family + siblings):**
- UniCORE.Avalonia family (4 repos)
- UniCORE.DNN family (4 repos)

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniSaaS.UniCORE.DNN/discussions) (public repos only)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
