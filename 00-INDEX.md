# Civilization Stack LAB — Index & Overview

> Root-level reference files from the original repo.

---

## README.md

*Source: `README.md`*

# Civilization Stack

A multi-domain framework for thinking about how civilization can be kept stoppable, correctable, and bounded across the systems that actually shape daily life.

---

## What this is

Civilization Stack is an umbrella for several related framework domains. Each domain takes one slice of how power and infrastructure operate over people — and asks how that slice can be designed, or redesigned, to remain accountable, interruptible, and replaceable when it fails.

The domains share a single underlying question:

> **Is this system structured to remain stoppable, correctable, and bounded — or has it grown past the point where it can still be changed?**

The answer is allowed to be different in each domain. The question is not.

---

## The throughline

Across all domains, four structural properties show up as load-bearing:

- **Stoppability** — can this be halted by the people inside it?
- **Expiration** — does authority renew, or does it just persist?
- **Reversibility** — can decisions be undone?
- **Visibility** — can the operation be seen from outside?

When any of the four is missing, the system drifts. Bounded power is what the Stack tries to keep within reach as drift happens.

---

## The domains

*How these domains relate — the layered architecture, and what each one must never become — is mapped in [Architecture](Civilization-Stack-Architecture.md).*

### Mature

- **[01-Bounded-Power-Framework/](01-Bounded-Power-Framework/) — Bounded Power Framework.** A public structural-diagnostic tool for institutions and authorities that hold power over people. Anyone can use it to produce a written analysis of a police department, hospital, platform, HOA, regulator, or similar authority — without needing the authority's cooperation, legal training, or institutional access. The most-developed domain. **Start here:** [01-Bounded-Power-Framework/00-Reading/00-Start-Here.md](01-Bounded-Power-Framework/00-Reading/00-Start-Here.md).

### In development

- **[06-Governance/](06-Governance/) — Governance.** How governments can be structured so that authority remains limited, renewable, auditable, and subordinate to the people it serves. Institutional design rather than partisan platform.
- **[07-Landscape-Transition/](07-Landscape-Transition/) — Landscape Transition.** Land use, settlement patterns, transportation, food systems, and ecological design — how the physical layer of life can be made easier to maintain rather than harder.

### Early-stage

- **[02-Infrastructure/](02-Infrastructure/) — Infrastructure.** Resilient physical infrastructure: energy networks, water systems, communications, and the maintenance regimes that keep them repairable. The newest domain; see its README for current scope.

### Placeholders

Visible folders, not yet written:

- **[04-Data/](04-Data/)**
- **[03-Economics/](03-Economics/)**
- **[05-Technology/](05-Technology/)**

Placeholder folders are intentional. They mark known gaps rather than hide them. A domain folder existing with no content is more honest than the same domain existing only in someone's head.

---

## The workspace

**[zz-Absurdity/](zz-Absurdity/)** is the project's workspace and pre-history archive. It holds reflections, drafts, abandoned versions, cross-AI experiments, and the migration checklist that drives the current restructure. It is load-bearing, not decorative — the Stack's reasoning was developed inside it, and it stays visible so the path from kitchen-table sketch to current framework remains inspectable.

---

## Current status

The Stack is in active development. BPF is usable today as a working diagnostic. GOV and LT exist as reasoning documents with structural extensions in progress. INFRA is early-stage. DATA, ECON, and TECH are placeholders.

The Bounded Power Project is the current operator. The Project is maintained independently by one person and is not an incorporated organization. Contributions are accepted by GitHub pull request, by GitHub issue, or by email to [CONTACT EMAIL PENDING]. There is no submission fee, no review queue, and no editorial gatekeeping; submissions are reviewed informally and as time permits.

---

## Closing principle

Civilization should become wiser and easier to sustain over time — not harder to repair.

The Civilization Stack is one attempt to put structural-design tools in the hands of ordinary people who live inside systems they did not design.

---

## Civilization-Stack-Architecture.md

*Source: `Civilization-Stack-Architecture.md`*

# The Civilization Stack — How It Fits Together

*An architectural map of the domains. For the front-page overview and where to start, see the [README](README.md); this is the structure behind it.*

---

Civilizations rarely fail from a single blow. They fail when one part outgrows the rest — when economics captures government, when technology outruns anyone's ability to switch it off, when infrastructure forgets the ecology holding it up. The danger was never that a part is strong. It is that one part grows strong enough to override all the others, until nothing left can stop it.

The Stack is one answer to that: not a single system, but a set of domains, each bounded by the same rule, arranged so that no layer can dominate the whole.

## The one rule, in every domain

Every domain is built to the same throughline — stoppable, renewable, reversible, visible, and harm-limited before anything else. The practical answers differ (governance and economics do not look alike), but no domain is exempt from the rule. That shared constraint is what makes these one Stack rather than a shelf of unrelated manifestos.

## The layers

Each layer rests on the one beneath it and is bounded by the one above. Each also has a failure mode — the specific way it goes wrong when the rule lapses.

- **Ecological base — the floor.** Climate, water, soil, the living systems everything else runs on. No domain may override it; it is the one layer not for sale. *Failure: ecological collapse — the floor gives way, and nothing above it survives.*
- **INFRA — infrastructure.** Turns the base into usable capacity: energy, water, transport, communications, settlement. Healthy infrastructure is modular, redundant, reversible. *Failure: lock-in and brittle fragility — systems too entangled to repair or replace.*
- **ECON — economics.** Coordinates provision across strangers without letting power concentrate beyond reach. *Failure: capture and monopolization — coordination curdles into extraction.*
- **DATA — information.** Records, communication, knowledge. Must stay transparent, auditable, and limited in what it keeps. *Failure: permanent surveillance — people defined forever by records that never expire.*
- **TECH — technology.** Expands capability, and with it systemic risk. Must stay controllable, interruptible, reversible. *Failure: dependency and runaway complexity — tools that quietly become authorities no one chose.*
- **GOV — governance.** Organizes collective decisions. Must stay accountable, interruptible, replaceable. *Failure: institutional capture and irreversible authority — power that can no longer be removed.*
- **LT — the long horizon.** Not stacked but running alongside all of it: generational stewardship, ecological repair, continuity for people who cannot vote yet. *Failure: short-termism — the present spending a future that never agreed to it.*
- **NODE — the built place.** Where the whole Stack is applied to one real, opt-in community: governance and physical form together. *Failure: a design that cannot be left — the exit that turns out to be theoretical.*
- **SCBP / Bounded Power — the meta-constraint.** The highest layer: the limits on authority itself — expiration, stop mechanisms, renewal, containment. It governs every layer below and exempts none, including itself. *Failure: constitutional drift — the rules that bound everyone quietly eroding.*

## Two directions, one containment rule

**Authority flows down. Constraints flow up.** Decisions made high in the Stack reach the layers below; limits set below hold the layers above — an economy may not breach the ecological floor, a government may not outrun its constitutional bounds. And one rule runs across all of it: **if a layer fails, the failure must not be allowed to climb.** Infrastructure failure should not collapse governance; a captured government should not be able to wreck the ecological base. Each layer is built to fail without taking the others down with it.

## Why arrange it this way

Most models of how a society should work describe political structure alone — who governs, and how they are chosen. The Stack treats that as one layer among several, and binds ecology, infrastructure, economics, information, technology, and governance into a single architecture held to one rule. The aim is not to make any layer strong. It is to make sure no layer can grow past the reach of the others.

*The layering is a lens, not a ranking of worth — a way to see what each domain depends on and what it must never override. In one sentence: the Civilization Stack is a layered architecture built so that power, technology, and institutions stay bounded by ecological reality and by the people who live inside them.*

---

## README.md

*Source: `Stack/README.md`*

# Data

Status: Framework (core complete)

## Purpose

Defines the structural rules under which information is collected, kept, seen, and acted on across civilization-scale systems — so that records serve the people they describe rather than becoming a permanent watch those people cannot escape.

The Data domain is not primarily concerned with database engineering, schema design, or data science as technical disciplines. It defines how *information power* is bounded: who may know what about whom, for how long, and under what conditions that knowledge may be used or must be deleted.

## Scope

- Personal data and informational autonomy
- Collection limits and purpose-binding
- Retention, expiry, and deletion
- Records, access, and correction
- Identity and credentials
- Public records and open information
- Classification and access control
- Algorithmic and automated decisions
- Interoperability and portability
- The information floor
- Anti-surveillance, oversight, transparency, and interruption safeguards
- Cross-community data exchange

## Failure Mode

Data failure produces permanent surveillance: records that never expire, watch that cannot be switched off, and people defined forever by information they cannot see, correct, or escape — until the record, not the person, becomes the authority.

## Relationship to BPF

BPF defines the governing principles, limits, and civilizational boundary conditions.

The Data domain operationalizes how information may be governed and trusted within those constraints — keeping records transparent, auditable, and limited in what they keep.

## Canonical Files

- DATA-MASTER
- DATA-00 through DATA-17 (Core, Operational, Safeguards, External blocks)
- DATA-A0 through DATA-A5 (Appendix & Reference block — measurable standards)

## Draft / Archived Files

- `99-Archive/DATA-Framework-LEGACY.md` — the original placeholder framework note, superseded by the modules above and retained for lineage.

## Open Questions

- How should DATA's safeguards (13–16) coordinate with GOV's enforcement authority and TECH's control of the tools that process data?
- Where exactly should the boundary sit between DATA-08 (public records) and ECON-15 (transparency of economic power)?
- How should retention clocks and deletion guarantees survive across community borders (DATA-17)?
- Which future modules (data commons, breach and shock response, provenance and authenticity) are next priority?

---

