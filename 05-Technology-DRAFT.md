# Technology — Draft Domain

> Collapsed from `Stack/05-Technology/` — draft-stage content for future development.

---

## README (2)

*Source: `README (2).md`*

# Technology

Status: Framework (core complete)

## Purpose

Defines the structural rules under which technological capability is chosen, built, deployed, and retired across civilization-scale systems — so that tools stay tools the people who use them can still direct, rather than authorities those people can no longer switch off.

The Technology domain is not primarily concerned with engineering practice, software craft, or research and development as technical disciplines. It defines how *technological power* is bounded: which capabilities a society allows in, how far they may reach, and on what terms they must stay controllable, replaceable, and stoppable.

## Scope

- What technology is for, and the limit it runs inside
- Tools and authority — how capability stays under human command
- Capability and systemic risk
- Critical technological infrastructure
- Complexity bounds
- Renewal of technological authorization
- Selection, adoption, and lifecycle
- Interoperability and substitutability
- Automation and human authority
- Dependency and supply chains
- The capability floor
- Anti-lock-in, oversight, transparency, and interruption safeguards
- Cross-community technology exchange

## Failure Mode

Technological failure produces dependency and runaway complexity: systems too entangled to repair, too opaque to audit, and too embedded to stop — until the tool, not the people who built it, becomes the authority no one chose.

## Relationship to BPF

BPF defines the governing principles, limits, and civilizational boundary conditions.

The Technology domain operationalizes how capability may be adopted and run within those constraints — keeping technological systems controllable, interruptible, reversible, and bounded in how far they may reach.

## Canonical Files

- TECH-MASTER
- TECH-00 through TECH-17 (Core, Operational, Safeguards, External blocks)
- TECH-A0 through TECH-A5 (Appendix & Reference block — measurable standards)

## Draft / Archived Files

- `99-Archive/TECH-Framework-LEGACY.md` — the original placeholder framework note (human-auditability, oversight of high-impact systems, replaceable infrastructure), superseded by the modules above and retained for lineage.

## Open Questions

- How should TECH's safeguards (13–16) coordinate with GOV's enforcement authority and DATA's control of the records technological systems process?
- Where exactly should the boundary sit between TECH-10 (automation under human command) and DATA-10 (what an automated decision owes the person)?
- How should replaceability and shutdown guarantees survive across community borders (TECH-17)?
- Which future modules (research governance, dual-use and weaponization, shock and outage response) are next priority?

---

## README

*Source: `README.md`*

# Technology

Status: Placeholder

## Purpose

Defines technology selection, abstraction, lifecycle management, and systemic technological constraints.

## Scope

- Technology governance
- Lifecycle management
- Interoperability
- Technical debt boundaries
- Capability evaluation
- Tooling standards

## Failure Mode

Unbounded technological growth creates fragmentation, dependency instability, and governance failure.

## Relationship to BPF

BPF defines acceptable operational boundaries. Technology defines how implementation choices remain aligned to those constraints.

## Canonical Files

- Placeholder framework documents only

## Draft / Archived Files

- Experimental architecture notes
- Incomplete technology mappings

## Open Questions

- What technologies become mandatory infrastructure?
- How should technology lifecycles be managed?
- Which abstractions should remain domain-neutral?

---

## TECH-00-Purpose-and-Scope

*Source: `TECH-00-Purpose-and-Scope.md`*

# TECH-00 — Purpose & Scope
*Civilization Stack · TECH domain · Core block, module 00.*

This framework defines the structural architecture of a technological system designed to remain harm-limited, controllable, replaceable, and stoppable across generations.

**First principle — prevent and repair harm first; then build within that limit.** Technology's first obligation is not to advance, scale, or optimize — it is to prevent harm, and to repair the harm it causes. Capability, automation, and efficiency are activities *permitted inside* that limit, never goals that override it. A technological system is judged first by the harm it avoids and the control it keeps, and only then by what it can do.

It is a *constraint system*, not a verdict on technology — not "pro-progress" or "anti-progress" by label. It specifies what a technological system **must not be allowed to do**: cause harm it cannot repair, grow so complex no one can understand or audit it, embed so deeply it cannot be stopped, concentrate into a single point of failure, or accumulate capability that escapes human direction. Everything else is left open.

## Stated wagers

This domain rests on value choices. They are named plainly here so they can be argued with, rather than smuggled in as if they were neutral:

- **Controllability over capability** — a tool you can stop and steer is worth more than a more powerful one you cannot.
- **Replaceability over optimization** — a system you can swap out beats a locked-in optimum you are stuck with.
- **Complexity as a cost** — added complexity must earn its place; the simpler system that does the job is the default.
- **Tools stay tools** — technology serves human ends under human command, and may not become an authority no one chose.

These are defensible positions, not the only possible ones. They are the foundation, and a reader is meant to be able to see them and contest them.

## What TECH governs

The structure of technological life inside those limits: what technology is for (TECH-01), how it stays a tool rather than an authority (02), capability and systemic risk (03), critical systems (04), complexity bounds (05), and renewal of authorization (06); how it operates — selection, lifecycle, interoperability, automation, dependency, and the capability floor (07 → 12); and the safeguards and measurable standards that hold it all in place (13 → 16, A1 → A5).

## What TECH does not govern (handoffs)

- **Who may authorize, oversee, and shut down technology** → GOV. TECH defines the controllability requirement; GOV defines the authority.
- **What an automated decision owes the person it affects** → DATA-10. TECH governs that the automation stays under human command; DATA governs explainability, contest, and override of the decision.
- **The physical systems technology runs on** → INFRA (energy, water, transport, communications, settlement).
- **Applying these rules to a specific built community** → NODE.
- **Long-horizon and intergenerational technological stewardship** → LT.

## Standing rules

Every TECH module operates under the domain's structural principles (see `TECH-MASTER`, §5): harm is prevented and repaired before a technology is deployed; authorization does not continue automatically; systems stay interruptible, reversible, auditable, and replaceable; critical capability is a floor, not a market outcome; nothing becomes too embedded to stop, leave, or replace; complexity past comprehension and control is a hard limit; and technology stays under human command rather than becoming the authority.

---
*Next: TECH-01 — What Technology Is For.*

---

## TECH-01-What-Technology-Is-For

*Source: `TECH-01-What-Technology-Is-For.md`*

# TECH-01 — What Technology Is For
*Civilization Stack · TECH domain · Core block, module 01.*

Technology exists to **extend human capability** — to let people do what they could not do alone, reach what they could not reach, and solve problems that would otherwise defeat them. That is its purpose. Everything else it does is either in service of that, or drift away from it.

**Capability.** Technology's first useful function is enlarging what people can actually do — heal what was fatal, build what was impossible, move what was fixed, know what was hidden. A technological system that produces dazzling capability while solving no real problem is not succeeding; it is impressing.

**Leverage under direction.** Its second function is multiplying human effort without removing human hands from the controls — the tool that lets one person do the work of many while the person still decides what work gets done. Machines, models, and automated systems are leverage *under direction* — useful exactly to the degree they amplify human intent rather than replace human judgment with their own.

**What it is not for.** Technology is not for capability as an end in itself — power accumulated because it can be, regardless of whether anyone needs it. It is not for novelty pursued for its own sake, efficiency that quietly removes the human from the loop, or the conversion of technical capability into a dependency people cannot escape. These are the recurring ways the purpose inverts: the tool meant to serve quietly becomes the thing served.

**The test.** A technology is legitimate to the degree that it extends human capability and stays under human direction, and suspect to the degree that it merely accumulates power or builds a dependency no one can leave. This is not a mood about machines — it is the working measure the later modules apply: to selection (TECH-07), to automation (10), to dependency (11), and to the anti-lock-in safeguards (13–14).

All of this runs inside the harm limit set in TECH-00. Capability and leverage are what technology is *for*; not causing harm it cannot repair, and staying stoppable, are what it must respect *while* doing it. Where the two collide, harm-first wins.

*Wager named: that technology should be judged by how well it serves human ends under human control — not by how powerful or advanced it is. That is a choice, and a contestable one.*

---
*Next: TECH-02 — Tools and Authority.*

---

## TECH-02-Tools-and-Authority

*Source: `TECH-02-Tools-and-Authority.md`*

# TECH-02 — Tools and Authority
*Civilization Stack · TECH domain · Core block, module 02.*

A tool is something you pick up and put down. An authority is something you answer to. The whole danger this domain exists to prevent is the quiet passage from the first to the second — the navigation system you stop questioning, the scheduling algorithm the whole company now obeys, the platform a society cannot function without. Nobody chose to be ruled by it. It just became unrefusable.

**Core rule — technology stays a tool: chosen, directed, and refusable by people, never an authority no one selected.** A tool serves a person who can still say no to it; an authority is something the person has lost the standing to refuse. The contrast is the line the domain holds: *not a system you are subject to because leaving it is no longer possible; a system you use because you chose it and could choose otherwise.* When a technology can no longer be questioned, overridden, or done without, it has stopped being a tool — and it became the authority the Stack exists to prevent.

A technology crosses from tool to authority along three paths:

- **Unrefusability.** When opting out costs you participation itself — the payment rail you cannot transact without, the identity system you cannot exist without — the "choice" to use it is no choice. The capability floor (TECH-12) and substitutability (TECH-09) are what keep refusal real.
- **Unaccountability.** When a system's workings cannot be seen, questioned, or overridden, its outputs become final by default — not because they are right, but because no one can reach inside. Transparency (TECH-15) and human override (TECH-10) are what keep it answerable.
- **Unstoppability.** When a system is so embedded that halting it would break everything around it, it has made itself permanent. Interruption (TECH-16) and the anti-lock-in firewall (TECH-13) are what keep it stoppable.

**This is the failure the architecture names.** The Stack's map gives TECH one specific failure mode: *tools that quietly become authorities no one chose.* This module is where that inversion is defined, and every other TECH module is, in some form, a defense against it. Capability (TECH-03), complexity (TECH-05), automation (TECH-10), and dependency (TECH-11) are all routes by which a tool slips its leash; the safeguards are the leash.

**This is not hostility to powerful tools.** Powerful technology is exactly what extends human capability (TECH-01), and the framework does not flinch from it. What it refuses is power that has become unanswerable — the tool you may no longer refuse, question, or stop. Strength is permitted; sovereignty over its users is not.

*Wager named: that technology must stay a refusable, directable, stoppable tool, even where surrendering control to it would be more convenient or efficient. The opposing view — that some systems work best when fully trusted and left to run, and that insisting on human control forfeits their benefit — is coherent and widely held; this framework does not take it, on the grounds that a tool you cannot refuse has already become a ruler.*

---
*Next: TECH-03 — Capability and Systemic Risk.*

---

## TECH-03-Capability-and-Systemic-Risk

*Source: `TECH-03-Capability-and-Systemic-Risk.md`*

# TECH-03 — Capability and Systemic Risk
*Civilization Stack · TECH domain · Core block, module 03.*

Every gain in capability is also a gain in reach — and reach is how a failure spreads. A tool that affects one task can fail one task. A system that runs a thousand hospitals, or steers a power grid, or decides credit for a population, fails at the scale it operates. Capability and systemic risk are not separate dials; they are the same dial read from two sides.

**Core rule — the greater a technology's systemic reach, the higher the bar it must clear before deployment, and the more it must stay controllable.** Scrutiny scales with reach. A tool that touches little owes little; a system that touches a whole population — its infrastructure, its decisions, its survival — owes a demonstration that it can be understood, bounded, and stopped *before* it is switched on. The threshold for "systemic" — how much reach triggers the heightened bar — tracks the lines in **TECH-A1 (Complexity & Concentration Thresholds)** and **TECH-A4 (Automation Risk-Tier Standard)**.

**Show the controllability before the capability runs, not after.** The standard move is to deploy first and manage consequences later — ship the system, watch what breaks, patch in oversight once harm appears. This framework reverses the order for systems with real reach. The more a technology can affect, the more its controllability must be shown in advance: that it can be audited, bounded, and halted without catastrophe. A capability deployed at scale before anyone has established it can be stopped is unbounded power on trust.

**Risk that cannot be contained is risk that does not get deployed at that scale.** Some failure modes do not stay local. A system whose breakdown cascades — taking down the systems that depend on it, faster than anyone can intervene — carries systemic risk regardless of how well it performs on a normal day. Where that cascade cannot be contained, the answer is not better monitoring; it is not deploying the capability at a reach where its failure becomes everyone's. This is the harm-first principle (TECH-00) applied to the blast radius.

**This is not a brake on capability as such.** Powerful technology is the point (TECH-01), and the framework does not cap capability out of caution. It caps *uncontained systemic risk* — the specific combination of vast reach and no off-switch. A capability that stays bounded and stoppable may grow as large as it usefully can; it is the unbounded, uncontainable version that the bar exists to stop.

*Wager named: that systemic reach must be matched by demonstrated controllability before deployment, even at the cost of slowing powerful systems to a more cautious pace. The opposing view — that front-loaded caution forfeits speed and benefit, and that risks are better managed in production than predicted in advance — is coherent and widely held; this framework does not take it, on the grounds that a system whose failure is everyone's must prove it can be stopped before it is trusted with everyone.*

---
*Next: TECH-04 — Critical Technological Infrastructure.*

---

## TECH-04-Critical-Technological-Infrastructure

*Source: `TECH-04-Critical-Technological-Infrastructure.md`*

# TECH-04 — Critical Technological Infrastructure
*Civilization Stack · TECH domain · Core block, module 04.*

Some technological systems are not conveniences a society could lose and carry on — they are the ones whose failure stops the lights, the water, the hospitals, the money, the means of talking to each other. The control system on the grid, the software steering water treatment, the network the emergency services run on: when these go down, people are not inconvenienced, they are endangered. That is what sets this category apart from everything else technology handles.

**Core rule — critical technological systems must stay replaceable, and no critical function may rest on a single irreplaceable system.** A society depends on these systems; it must not be captive to any one of them. The contrast is the design choice: *not a critical function welded to one vendor, one platform, or one technology with no fallback; a function that can survive the loss of any single system carrying it.* Replaceability here is not an optimization — it is what keeps a critical dependency from becoming a critical hostage.

Two protections carry this:

- **No single point of failure.** A function the society cannot live without may not run through one system with no alternative path. Redundancy and fallback are conditions of being trusted with a critical role — the same logic INFRA brings to physical systems, applied to the technology riding on them. A critical system with no replacement is a catastrophe waiting for one bad day.
- **No critical capture.** No actor may corner a critical technological capability — the dominant platform, the sole-source control software, the one provider everyone must route through — and set its terms. The bar here is stricter than the general anti-lock-in rule (TECH-13): for critical systems, entrenchment is suspect even when the provider behaves well, because the stakes are continuity, not preference.

**The category is bounded, and stays bounded.** "Critical" must be defined explicitly and held narrow — the systems whose failure is a danger, not every system that matters. If everything is critical, nothing gets the protection — inflating the category would hollow out the rule. The list is finite, public, and revisable; the measurable replaceability requirements live in **TECH-A2 (Critical-System Replaceability Standard)**.

**Critical systems and natural monopolies reinforce each other.** Much critical technology arrives through natural monopolies — the one grid-control system, the single national identity platform, the dominant payment rail. Where a critical system *and* a chokepoint coincide, the case for public oversight, mandated fallbacks, or direct provision is at its strongest, and private capture at its least acceptable. This is the TECH parallel to the essentials rule (ECON-04): the capability the rest depend on gets the firmest floor.

*Wager named: that critical technological systems must stay replaceable and redundant, even at the cost of the efficiency a single optimized system would offer. The opposing view — that consolidating critical functions into one best system is cheaper, cleaner, and often more reliable day to day — is coherent and widely held; this framework does not take it, on the grounds that a critical system you cannot replace is a single failure away from disaster.*

---
*Next: TECH-05 — Complexity Bounds.*

---

## TECH-05-Complexity-Bounds

*Source: `TECH-05-Complexity-Bounds.md`*

# TECH-05 — Complexity Bounds
*Civilization Stack · TECH domain · Core block, module 05.*

A technological system runs inside the limits of what people can still understand and control. Past a certain complexity, no one can say what a system will do, why it did what it did, or how to stop it safely — and a system no one comprehends is a system no one governs. Complexity sets an outer wall, and capability operates inside it or not at all.

**Hard bounds, not free trade-offs.** The standard move is to treat complexity as a cost like any other — worth paying whenever the capability it buys is worth more. This framework refuses that framing at the limit. Some complexity is *hard*: a ceiling activity may not cross at any benefit, because past it the system becomes incomprehensible, unauditable, or unstoppable — and a tool no one can understand or halt has already become the authority TECH-02 forbids. You cannot manage what you cannot understand, and you cannot stop what you cannot follow.

**Two tiers.** The bound separates the complexity that can be afforded from the complexity that cannot:

- **Hard limits — not for deployment.** Complexity that puts a system beyond human comprehension, outside the reach of audit, or past the point of safe shutdown is a ceiling. No capability gain clears it; "too complex to understand" and "too tangled to stop" are not features to be managed but lines not to be crossed. This is the runaway-complexity failure the architecture names, written as a wall.
- **Bounded complexity — accounted, not ignored.** Complexity below the threshold may be taken on, but it is a cost carried, not a free good. The system that adds it must show the capability is worth the loss of legibility, and must stay auditable and stoppable despite it. The measurable lines — what counts as beyond comprehension or control — live in **TECH-A1 (Complexity & Concentration Thresholds)**.

**Why this is harm-first, not a taste for simplicity.** A system no one understands fails in ways no one predicted, and harms the people depending on it before anyone can trace the cause. Unbounded complexity is harm-first applied to the limits of human comprehension: the danger is not the complexity itself but the loss of the ability to see, check, and stop. The long-horizon stewardship of these limits is held with **LT**; TECH-05 is the deployment constraint — capability stays inside the wall of what can still be governed.

**This is not a demand that everything be simple.** Within the bounds, technology is free to be as sophisticated as the job requires; the framework does not romanticize the primitive. The bound is a limit, not a target. But honesty requires the corollary: where a system has already grown past comprehension or control, staying inside the wall means that complexity must come down — decomposed, simplified, or replaced — not merely better documented.

*Wager named: that some complexity is a hard wall, not a payable cost — that a system past human comprehension or control may not be deployed at any benefit. The opposing view — that complexity is always a trade-off worth making when the capability justifies it, and that tooling can manage what humans cannot directly grasp — is coherent and widely held; this framework does not take it, on the grounds that what cannot be understood cannot be governed and what cannot be stopped is already unbounded.*

---
*Next: TECH-06 — Renewal Logic.*

---

## TECH-06-Renewal-Logic

*Source: `TECH-06-Renewal-Logic.md`*

# TECH-06 — Renewal Logic
*Civilization Stack · TECH domain · Core block, module 06.*

No authorization to run a technology is permanent. Every deployment, every standard, every mandate to operate a system at scale is granted for a term and must earn its renewal — or it lapses. Continuation is the thing that has to be justified; expiration is the default. This is the Stack's renewal principle (TECH-00) turned directly on technological power.

**Why default-to-expiration.** Technology drifts toward entrenchment the way complexity drifts toward tangle (TECH-05): a system approved once keeps running into an era it no longer fits, a standard set for one generation locks in the next, a platform authorized as useful becomes load-bearing before anyone re-examines it. The usual defense is vigilance after the fact — discovering, years on, that some critical system is obsolete, unmaintained, or unstoppable. This framework chooses a structural defense instead: authorize nothing as standing, and the entrenched legacy system never forms, because it was always going to sunset unless actively renewed.

**What must renew.** The principle reaches every form of standing technological authority:

- the authorization to operate a deployed system, especially one with systemic reach (TECH-03);
- the mandated standards and protocols a community is required to build to;
- the designation of a system as critical infrastructure (TECH-04), and the fallbacks that designation requires;
- the operating license of platforms and automated systems running at scale;
- and the mandates of the oversight bodies themselves. The watchers renew too; there is no permanent technology regulator any more than a permanent standard.

**The renewal test.** To renew, an authorization must show its purpose still holds (TECH-01), that it remains the right tool rather than a legacy kept by habit, that it sits inside the harm and complexity limits (TECH-00, TECH-05), and that it stays auditable, replaceable, and stoppable. Meeting the test renews the term; failing it lets the term end. The review machinery is **TECH-A5 (Structural Renewal Review Protocol)**.

**Lapse is not punishment.** An authorization ending for lack of renewal is the ordinary, scheduled default — not a penalty, not a finding that anything failed. Keeping it neutral is what stops renewal from becoming a fight: nothing has to be proven *against* a system to let its authorization expire; it simply has to fail to prove it is still the right system. Removal *for cause* — emergency shutdown — is a separate path, and lives in **TECH-16**.

**Nothing is exempt, including this.** The renewal principle applies to itself. These rules, and the protocol that enforces them, are themselves subject to review and renewal. A framework that exempts its own machinery from the limits it imposes on everyone else has already failed the first test it sets.

*Wager named: that authority to run a technology should default to expiration and earn renewal again and again — standing assumed by nothing. The opposing view — that durable authorization gives the stability that long-lived systems and the investment in them depend on, and that constant renewal is friction — is coherent and widely held; this framework does not take it, on the grounds that the unrenewed, unexamined legacy system is the quiet path to runaway entrenchment.*

---
*End of the Core block (TECH-00 → TECH-06). Next group: Operational Structure, beginning with TECH-07 — Selection & Adoption.*

---

## TECH-07-Selection-and-Adoption

*Source: `TECH-07-Selection-and-Adoption.md`*

# TECH-07 — Selection & Adoption
*Civilization Stack · TECH domain · Operational block, module 07.*

Most technology does not arrive after a decision; it arrives instead of one. A tool spreads because it is new, because a competitor has it, because it is there — and by the time anyone asks whether it was the right choice, the choice has already been made by default. This module is where adoption is turned back into a decision.

**Core rule — adopting a technology is a decision that must be justified against the alternatives, including not adopting at all.** Bringing a system in is a choice with consequences, and it must be made as one: weighed against other options and against the status quo, not waved through because it is available or fashionable. The contrast names the failure: *not adoption by momentum — the new thing taken on because everyone is, its costs discovered later; but adoption by decision — the tool chosen because it was the best answer to a real problem, including the answer "none of these."* A technology adopted without a justified decision is a dependency acquired by accident.

Two requirements carry it:

- **A real problem, and a fair comparison.** Adoption answers to a need (TECH-01), and the candidate is compared honestly against alternatives and against doing nothing — including its full cost in complexity (TECH-05), dependency (TECH-11), and the effort to undo it later. "It is the latest" is not a reason; "it is the best fit for this problem, and we can leave it if it isn't" is.
- **Reversibility weighed up front.** The cost of *un*-adopting is part of the selection, not a surprise for later. A system that is cheap to adopt and ruinous to leave has hidden its real price; the easy-in, impossible-out tool is exactly how lock-in begins (TECH-13). What it takes to reverse the choice is priced at the moment the choice is made.

**Novelty is not a reason; fit is.** The pull toward the new — the newest model, the latest platform, the capability a rival just shipped — is real, and it is not a justification. A technology earns adoption by solving the problem better than the alternatives, not by being more advanced than what it replaces. The framework is neither eager nor reluctant about new tools; it is indifferent to their newness and interested only in their fit.

**This is not a barrier to moving fast.** Good selection is not slow bureaucracy; for low-reach, easily reversible tools it can be near-instant, because the cost of getting it wrong is small and the exit is cheap. The justification scales with the stakes (TECH-03): a reversible tool affecting little owes a light decision; a systemic one affecting many owes a serious one. The point is not to slow adoption but to keep it a choice.

*Wager named: that adopting a technology must be a justified decision weighed against alternatives and reversibility, not a default driven by novelty or momentum. The opposing view — that fast, low-friction adoption is how organizations stay competitive, and that deliberation forfeits the edge of moving first — is coherent and widely held; this framework does not take it, on the grounds that a tool adopted without a decision is a dependency no one chose.*

---
*Next: TECH-08 — Lifecycle & Decommissioning.*

---

## TECH-08-Lifecycle-and-Decommissioning

*Source: `TECH-08-Lifecycle-and-Decommissioning.md`*

# TECH-08 — Lifecycle & Decommissioning
*Civilization Stack · TECH domain · Operational block, module 08.*

Every technology has an end, and most are never given one. They are built, deployed, and left running — past their purpose, past their support, past the point anyone remembers how they work — because the work of retiring a system is never as urgent as the work of building the next one. The result is a landscape of systems no one can turn off and no one fully understands.

**Core rule — a technology is adopted with its decommissioning already designed.** The exit is built at the same time as the entrance, not improvised at the end. The contrast is the design discipline: *not a system deployed with no plan for its own death, accreting into permanent legacy; a system whose retirement, migration, and replacement were designed before it ever went live.* A technology you do not know how to turn off is a technology that will outlive its usefulness and become the entrenched legacy the domain exists to prevent.

Two structures carry it:

- **A designed end of life.** Each system carries, from the start, a plan for how it is wound down — how its functions migrate, how its data and dependencies are handed off (DATA-16), how it is removed without breaking what relied on it. A system with no decommissioning plan is non-compliant by default; the measurable form of "actually removable" tracks **TECH-A2**.
- **Technical debt as a bounded liability.** The accumulated shortcuts, unpatched dependencies, and deferred maintenance that make a system harder to change over time are a real cost, tracked and capped — not an invisible tax paid by whoever inherits the system. Debt past a threshold is itself a complexity bound (TECH-05): a system too tangled to safely modify is one already drifting past control.

**Orphaned systems are how authority accretes by neglect.** A system no one owns, maintains, or understands does not stop having power — it keeps running, keeps deciding, keeps being depended on, while the ability to govern it quietly disappears. This is TECH-02's inversion arriving through abandonment rather than design: the tool becomes an authority not because anyone willed it, but because no one retired it. Lifecycle discipline is what keeps the off-ramp from disappearing.

**This is not a demand to discard working systems.** A system that still serves its purpose, stays maintained, and can still be stopped is not retired for the sake of churn; longevity is a virtue, not a fault. The rule is not "replace constantly" — it is "always know how you would." The discipline is keeping the exit real, so that when a system should go, it can.

*Wager named: that a technology must be adopted with its end already planned, even at the cost of slowing deployment to design the exit. The opposing view — that planning decommissioning for systems that may run for decades is wasted effort better spent shipping, and that retirement can be handled when it comes — is coherent and widely held; this framework does not take it, on the grounds that the system with no planned end is the one that becomes impossible to end.*

---
*Next: TECH-09 — Interoperability & Substitutability.*

---

## TECH-09-Interoperability-and-Substitutability

*Source: `TECH-09-Interoperability-and-Substitutability.md`*

# TECH-09 — Interoperability & Substitutability
*Civilization Stack · TECH domain · Operational block, module 09.*

A component that only one supplier can provide becomes a component that holds you hostage. The proprietary connector, the closed protocol, the part that fits nothing else — each one quietly removes a choice, until replacing any piece means replacing everything, and so you replace nothing. Lock-in is rarely announced; it is built one closed interface at a time, until the exit is theoretical.

**Core rule — components are substitutable, and systems connect through open interfaces no single party controls.** A part can be swapped for another that does the job, and systems talk to each other without a gatekeeper deciding who may connect. The contrast is the design fork: *not a closed system that keeps you by making every piece irreplaceable and every connection proprietary; open interfaces and substitutable parts that keep the door out real.* This is the Stack's reversibility property (README) applied to technology — the same anti-lock-in logic INFRA brings to physical systems (INFRA-09) and DATA to information (DATA-11).

Two structures carry it:

- **Substitutability.** A component, vendor, or subsystem can be replaced with an alternative without rebuilding the whole. Where a part has no substitute, its provider holds the system; substitutability is what keeps any single piece from becoming a chokepoint, and it is the operational backbone of critical-system replaceability (TECH-04).
- **Interoperability.** Systems exchange function and data through open, documented interfaces rather than closed ones that let an incumbent decide who connects. Where the interface is the chokepoint, whoever controls it controls the system and everyone in it — the concentration TECH-13 and ECON-13 both guard against.

**Lock-in is how a tool becomes an authority.** A system you cannot leave stops being a tool you chose and becomes one you are subject to (TECH-02) — free to change its terms, raise its price, or alter what it does, because the cost of leaving is rebuilding from scratch. Substitutability keeps the relationship voluntary: the exit that stays open is what keeps the provider honest. This is the technological form of "nothing too big to leave."

**This is not a demand that everything be built in the open.** Substitutability is about *the ability to replace and connect*, not about exposing every internal design to all comers; a system can keep proprietary internals while still offering open interfaces and replaceable parts. Open interfaces and open implementations are different things — this module requires the first without requiring the second.

*Wager named: that components must be substitutable and interfaces open, so that leaving or replacing a system stays possible. The opposing view — that closed, tightly integrated ecosystems deliver better performance, security, and coherence, and that mandated openness erodes the incentive to build them — is coherent and widely held; this framework does not take it, on the grounds that a system you cannot leave is a system that no longer answers to you.*

---
*Next: TECH-10 — Automation & Human Authority.*

---

## TECH-10-Automation-and-Human-Authority

*Source: `TECH-10-Automation-and-Human-Authority.md`*

# TECH-10 — Automation & Human Authority
*Civilization Stack · TECH domain · Operational block, module 10.*

Automation earns its place by acting without waiting for a person — that is the whole point of it. But an automated system that cannot be directed, overridden, or switched off by a human has not just saved effort; it has taken the controls. The question this module answers is not whether machines may act on their own. It is whether a person can still take the wheel back.

**Core rule — automation may act and scale, but a human retains the authority to direct, override, and stop it.** Automated systems may run, decide, and operate at speeds and scales no person could match — provided a human keeps the standing to redirect them, set their output aside, and halt them. The contrast is exact: *not an automated system that runs past human reach because intervening is impossible or too slow; an automation a person can still command, override, and stop.* An automation that cannot be overridden has stopped being leverage under direction (TECH-01) and become the authority TECH-02 forbids.

Three requirements carry it:

- **Directable.** A human can set, change, and constrain what the automation does — its goals, its bounds, its permissions — rather than inheriting behavior no one can adjust. Automation that cannot be redirected is a decision frozen into a machine.
- **Overridable.** A person retains the authority to set a specific automated action aside. The override must be real — reachable in time, by someone empowered to use it — not a button that loops back into the same system or arrives after the action is irreversible.
- **Stoppable.** The automation can be halted, by a human, without catastrophe (TECH-16). An automated system that cannot be stopped without breaking everything around it is one that has already escaped command.

**The handoff to DATA, and the line TECH holds.** Where an automated action is a *decision about a person* — who gets the loan, the flag, the benefit — what that decision owes the person (to be explainable, contestable, and reversible) is DATA's domain (DATA-10). TECH's part is narrower and prior: that the automation *itself* stays under human command — directable, overridable, stoppable — whatever it is deciding and whomever it affects. DATA governs what the person is owed; TECH governs that a human still holds the controls. The risk-tiering of automated systems by stakes and reach lives in **TECH-A4 (Automation Risk-Tier Standard)**.

**This is not a ban on autonomy; it is a bound on autonomous authority.** Automation is often faster, safer, and more consistent than a human at the controls, and the framework does not forbid it — a human kept needlessly in every loop is its own failure mode. What is forbidden is the *unanswerable* version: automation that runs past the point where any person can redirect or stop it. Speed and independence are permitted; escape from human command is not.

*Wager named: that automation must stay directable, overridable, and stoppable by a human, even at the cost of the speed and consistency full autonomy would offer. The opposing view — that human control is precisely the bottleneck automation exists to remove, and that insisting on override forfeits its core benefit — is coherent and widely held; this framework does not take it, on the grounds that an automation no one can stop is exactly the authority no one chose.*

---
*Next: TECH-11 — Dependency & Supply Chains.*

---

## TECH-11-Dependency-and-Supply-Chains

*Source: `TECH-11-Dependency-and-Supply-Chains.md`*

# TECH-11 — Dependency & Supply Chains
*Civilization Stack · TECH domain · Operational block, module 11.*

Control rarely leaves through the front door. It leaks out through dependency — the one foreign foundry every chip passes through, the single library half the world's software imports, the cloud provider an entire sector runs on. None of it looks like surrender. It looks like efficiency, right up until the supplier raises the price, changes the terms, or simply stops.

**Core rule — no critical capability may rest on a dependency you cannot replace or do without.** A capability the society cannot lose must not hang on a single supplier, component, or upstream system with no alternative. The contrast names the trap: *not a critical function quietly resting on one irreplaceable upstream link, exposed to whoever controls it; a function whose dependencies are replaceable, multiple, or absent.* A critical capability with a single point of dependency is a critical capability someone else controls.

The danger concentrates at three layers:

- **Single-source components.** A part, chip, or material with one supplier is a hostage situation waiting to happen — one disruption, one decision, one border closing, and the capability stops. Critical functions require replaceable or multiple sources (TECH-04), because the join, not the part, is where the vulnerability lives.
- **Foundational dependencies.** The libraries, protocols, and platforms that countless systems quietly build on become systemic by accumulation — a flaw or failure in one propagates everywhere it was trusted. The more foundational a dependency, the more its concentration is a systemic risk (TECH-03), not a private convenience.
- **Concentration upstream.** When a whole sector depends on one provider — one cloud, one operating system, one vendor — that provider has acquired power over everyone downstream, the technological form of the concentration ECON-13 guards against. The measurable lines on dependency concentration track **TECH-A1**.

**Dependency is how a tool becomes an authority over its users.** A supplier you cannot replace is a supplier you must accept on its terms — free to set the price, dictate the conditions, or withdraw, because the cost of refusing is losing the capability. This is TECH-02's inversion arriving through the supply chain: the upstream provider becomes an authority no one chose, simply because there is no second source. Replaceability keeps the dependency from becoming dominion.

**This is not a demand for total self-sufficiency.** Specialization and interdependence are how technology gets built at all; the framework does not ask every community to make everything itself, and autarky is its own kind of fragility. The rule targets *unreplaceable* dependency for *critical* capability — the specific combination of high stakes and no alternative. Ordinary dependency, replaceable or non-critical, is the normal texture of a connected world.

*Wager named: that critical capabilities must not rest on dependencies that cannot be replaced or done without, even at the cost of the efficiency a single optimized supplier offers. The opposing view — that deep specialization and sole-sourcing are how cost falls and quality rises, and that redundancy is waste — is coherent and widely held; this framework does not take it, on the grounds that a critical capability with one source is a capability under someone else's control.*

---
*Next: TECH-12 — Capability Floor.*

---

## TECH-12-Capability-Floor

*Source: `TECH-12-Capability-Floor.md`*

# TECH-12 — Capability Floor
*Civilization Stack · TECH domain · Operational block, module 12.*

To take part in a society built on technology, a person needs the means to use it: a way to connect, a working device, the basic tools the society now assumes, and the skill to operate them. When those are locked behind cost or distance or know-how a person does not have, they are shut out — not by a rule that bars them, but by a capability gap that does the same work quietly. This module sets the baseline below which no one should fall.

**Core rule — everyone has baseline access to the essential technological capability needed to participate, and the means to use it.** There is a floor of essential capability — and of the access and literacy to use it — beneath the open market in technology, never beneath the person. This is the TECH parallel to the provision floor (ECON-12) and the information floor (DATA-12): some capability is guaranteed because its absence is exclusion, not preference. To be cut off from the technology a society runs on is to be cut off from the society itself.

Two parts carry it:

- **Access to essential capability.** The connectivity, devices, and basic tools a person needs to function — to reach services, work, learn, and exercise their rights — are reachable without a prohibitive cost or a connection a person does not have. The measurable content lives in **TECH-A3 (Capability Floor Standard)**.
- **The means to use it.** Access without the literacy or support to use it is a floor in name only. The floor includes a baseline ability to operate essential technology and to get help when it fails — because a tool a person cannot reach or use is not capability they hold.

**Capability poverty is exclusion, not misfortune.** When the people with the least access are the ones who cannot reach a service that has moved online, apply for the job that requires a device, or operate the system a benefit now flows through, the harm lands exactly where TECH-00's first principle forbids it. A capability gap is not a neutral fact about who happens to be equipped; it is a distribution of exclusion, and the floor exists to close it.

**The category is bounded, and stays bounded.** "Essential capability" is held narrow — the connectivity, tools, and skills whose absence is exclusion — not every device or service a person might want. As with the essentials rule it parallels (ECON-04), inflating the category would hollow out the guarantee. The floor secures what participation requires, and leaves the open market in technology above it.

*Wager named: that baseline technological capability, and the means to use it, is a floor beneath the market rather than a market outcome — that participation should not be rationed by ability to pay or connect. The opposing view — that technology is a good like any other, best provided and priced by the market, and that guaranteed floors are costly and distortive — is coherent and widely held; this framework does not take it, on the grounds that exclusion from essential capability is exclusion from civic life.*

---
*End of the Operational block (TECH-07 → TECH-12). Next group: Structural Safeguards, beginning with TECH-13 — Anti-Lock-In Firewall.*

---

## TECH-13-Anti-Lock-In-Firewall

*Source: `TECH-13-Anti-Lock-In-Firewall.md`*

# TECH-13 — Anti-Lock-In Firewall
*Civilization Stack · TECH domain · Safeguards block, module 13.*

This is the limit the rest of the domain keeps pointing at. Adoption drifts toward dependency (TECH-07), components toward irreplaceability (TECH-09), suppliers toward concentration (TECH-11) — and every one of those modules names a firewall that holds the line. This is that firewall: the structural cap on how entrenched and irreplaceable any single technology may become.

**Core rule — no technology, public or private, may become so embedded that it can no longer be replaced or left.** The bar is not "is this system behaving well." It is "could this system, by virtue of how deeply everything depends on it, become impossible to stop, swap, or escape" — because by the time the lock-in is felt, the power to prevent it is already entrenched. Entrenchment is treated as a hazard in itself, before any abuse, the same way ECON-13 treats concentration. The measurable lines — how much dependency, switching cost, and market share trip the limit — live in **TECH-A1 (Complexity & Concentration Thresholds)**.

**Structural, not behavioral.** The standard move is to permit any degree of entrenchment and police the abuses — let the lock-in grow, then punish the provider who exploits it. This framework refuses that order. Policing the abuse fights the symptom and leaves the cause; a system everyone *must* use is one price hike, one policy change, or one new owner away from exploiting that fact, regardless of today's restraint. The firewall caps the *capacity to lock in*, not merely the *conduct*, because structure is what holds when vigilance lapses.

The firewall works by breaking the mechanisms lock-in is built from:

- **Replaceability limits.** No critical function comes to rest on a system with no substitute (TECH-04, TECH-09). The danger is rarely any one tool; it is the point where leaving it means rebuilding everything, and so no one can.
- **Switching-cost limits.** Where the cost of leaving a system grows high enough, the exit becomes theoretical even when it nominally exists. A door that cannot be afforded is not a door; capping switching cost is what keeps it real.
- **Dependency-depth limits.** A system that quietly becomes foundational to everything above it (TECH-11) acquires power by depth alone. The firewall watches the join — how many critical things now rest on one thing — not just the conduct of the thing itself.

**The state and the market are both inside the wall.** Lock-in does not become safe because a government built the system for the public good, or because a company built it for convenience and profit. The firewall binds both, and binds its own enforcers: an anti-lock-in authority that itself becomes the indispensable, unstoppable system (TECH-14, TECH-15) has reproduced the disease it was built to prevent.

*Wager named: that no technology should become impossible to replace or leave, even where deep integration delivers real efficiency, coherence, and convenience. The opposing view — that consolidation around dominant systems is how technology matures and interoperates, and that forced replaceability sacrifices those gains — is coherent and widely held; this framework does not take it, because the system that cannot be left is the exact failure the domain exists to prevent.*

---
*Next: TECH-14 — Systemic Oversight.*

---

## TECH-14-Systemic-Oversight

*Source: `TECH-14-Systemic-Oversight.md`*

# TECH-14 — Systemic Oversight
*Civilization Stack · TECH domain · Safeguards block, module 14.*

The firewall (TECH-13) sets the lines; someone has to watch whether the largest technological systems stay inside them. A platform a whole sector runs on, a model deciding outcomes at population scale, a control system steering critical infrastructure — these are systemic actors, and a limit no one is checking is a limit in name only. This module is the standing watch over technological power at scale.

**Core rule — the larger a technological system's reach, the more it must show its controllability to an outside overseer.** Oversight scales with reach: a small tool owes little, a system that touches a whole population owes continuous, examinable demonstration that it remains comprehensible, replaceable, and stoppable. The threshold for "systemic" — how much reach triggers the duty — tracks the lines in **TECH-A1** and **TECH-A4**. Below it, the lighter rules of the core block suffice; above it, the system operates under watch.

**Show the real controllability, not a summary.** The overseer must be able to see whether a systemic system can actually be audited, replaced, and halted — its true complexity, its dependencies, its shutdown path — not a reassuring report that it can. The standard mirrors ECON-14's demand that systemic actors show their true position: a demonstration that conceals the part that matters is not oversight, it is its appearance.

**Nothing too big to stop.** A technological system can become so embedded that halting it would break everything depending on it — and at that point it has stopped being a tool and become an authority no one can remove (TECH-02). Oversight watches for exactly this: a system that *cannot* be interrupted or unwound (TECH-16) is, for that reason alone, already too entrenched, the technological form of "too big to fail." Resolvability — the demonstrated ability to stop or replace the system without catastrophe — is a condition of operating at scale, not an afterthought.

**The watchers are watched, and the authority is GOV's.** The oversight bodies renew like everything else (TECH-06) and operate transparently (TECH-15); an overseer that becomes a permanent, indispensable system of its own has become the entrenched authority it was meant to bound. And as throughout, TECH defines *that* systemic technological power must be overseen and on *what* terms; *who* holds the enforcing authority — the bodies, the powers, the process — is GOV's to define. TECH builds the requirement; GOV supplies the office.

*Wager named: that technological power at scale owes continuous, examinable oversight to those it affects — that reach brings scrutiny. The opposing view — that oversight burdens the systems people rely on, slows them, and exposes their internals — is coherent and widely held; this framework does not take it, on the grounds that an unwatched system at population scale is unbounded power by default.*

---
*Next: TECH-15 — Transparency & Auditability.*

---

## TECH-15-Transparency-and-Auditability

*Source: `TECH-15-Transparency-and-Auditability.md`*

# TECH-15 — Transparency & Auditability
*Civilization Stack · TECH domain · Safeguards block, module 15.*

A technological system you cannot inspect is a power operating in the dark. Every safeguard in this domain — the firewall, the oversight, the renewal test — assumes someone can actually check what a system is, how it works, and whether it can still be stopped, and none of them work if the system's own operation is opaque. Visibility is one of the Stack's four load-bearing properties (README), and this module is where technological systems are required to provide it.

**Core rule — a technological system's operation must be examinable from outside.** It must be possible for an authorized party to see what a system does, what it depends on, how it decides, and how it can be stopped. The contrast is the design choice: *not a black box whose workings are unknowable even to its overseers; a system that keeps a true, inspectable account of what it is and does.* A system that cannot show its own workings cannot be checked, and a power that cannot be checked is the one the Stack exists to bound.

Two mechanisms carry it:

- **Auditable design.** A system is built so that its behavior, dependencies, and decision logic can be examined — not sealed behind proprietary opacity that conceals the substance. Auditability that requires reverse-engineering the system's private workings is not auditability; it is the appearance of it.
- **Examinable operation.** What a system is actually doing in production — what it is connected to, what it is deciding, whether its shutdown path still works — is observable to those who oversee it (TECH-14), not just described in a document written once. A control no one can confirm still works is a control that may already have failed.

**Auditability is a precondition, not a report.** Disclosure that arrives too late, too vague, or only after a failure is not visibility. The standard is whether an overseer (TECH-14), or the public where systemic power is concerned, can see enough, in time, to check the system in question and confirm it remains controllable. The measurable forms of that sufficiency are carried by the standards the safeguards reference (TECH-A1, TECH-A4); this module sets the requirement they must meet.

**This watches the system, not the person.** The line matters enough to state plainly: auditability targets the *operation of the technological system* — what it does, depends on, and decides — not the lives of the people using it. A transparency regime that became a record of every user's every action would have failed DATA's anti-surveillance firewall (DATA-13) and this domain's first principle alike. Watching the system is the job; the audit exists to bound technological power, not to extend surveillance through it.

*Wager named: that technological systems at scale owe an examinable account of their own operation to those who oversee and depend on them. The opposing view — that auditability requirements expose security-relevant internals and proprietary design, and burden the systems people rely on — is coherent and widely held; this framework does not take it, on the grounds that a system whose workings cannot be seen cannot be bounded.*

---
*Next: TECH-16 — Interruption & Shutdown.*

---

## TECH-16-Interruption-and-Shutdown

*Source: `TECH-16-Interruption-and-Shutdown.md`*

# TECH-16 — Interruption & Shutdown
*Civilization Stack · TECH domain · Safeguards block, module 16.*

Renewal handles the ordinary case: an authorization's term ends, and it must earn another (TECH-06). This module handles the other case — when something has gone wrong enough that you cannot wait for the term to lapse. It is the domain's stop button: the power to halt a technological system *for cause*, when the harm is real and waiting is not an option.

**Core rule — every technological system must be stoppable, and stoppable without the world around it collapsing.** Stoppability is one of the Stack's four load-bearing properties (README), and a technological regime honors it only if its systems can actually be halted — cleanly, by a human, in time. The corollary is hard: a system that *cannot* be stopped, or that cannot be stopped without catastrophe, is for that reason already too entrenched — the over-embedding TECH-14 forbids. A working off-switch is not a feature added at the end; it is a condition of being allowed to run at scale.

**The stop must be real, not cosmetic.** This is where TECH-02's "refusable" and TECH-10's "stoppable" become enforceable. A shutdown path that exists on paper but has never been tested, that would take down critical functions if used, or that the system has quietly grown around, is not a stop button — it is the belief in one. A real stop can be exercised in the conditions it is meant for, leaving the things that depended on the system able to fall back (TECH-04, TECH-A2), not stranded. A switch that cannot safely be thrown has not been built.

**Interruption is distinct from lapse, and kept distinct on purpose.** Lapse (TECH-06) is neutral and scheduled and proves nothing against anyone. Interruption is active and for-cause: a finding that a system is causing harm it cannot repair, has grown past control (TECH-05), or has become an unstoppable dependency (TECH-13), and must be halted now. Keeping the two paths separate is what stops the emergency power from becoming a routine one — for-cause shutdown must clear a real bar, precisely because it is the sharper tool.

**A stop is itself a power, and bounded like one — and the authority is GOV's.** The power to halt a system sits under the same limits as the rest of the domain: due process, transparency (TECH-15), and disrupting no more than the harm requires. A regime that could shut down any system at will, unchecked, would have relocated the unaccountable power, not removed it. And as throughout, TECH defines *that* systems must be stoppable and on *what* trigger; *who* holds and exercises that authority is GOV's. TECH builds the off-switch into the design; GOV decides whose hand is on it.

*Wager named: that every technological system must remain genuinely stoppable, even at the cost of the continuity and integration that make some systems hard to halt. The opposing view — that always-on, deeply embedded systems deliver reliability and value precisely because they are not easily interrupted, and that built-in kill switches are themselves a risk — is coherent and widely held; this framework does not take it, on the grounds that a system that cannot be stopped is the authority no one chose.*

---
*End of the Structural Safeguards block (TECH-13 → TECH-16). Next: the External block, TECH-17 — Technology Exchange Between Communities.*

---

## TECH-17-Technology-Exchange-Between-Communities

*Source: `TECH-17-Technology-Exchange-Between-Communities.md`*

# TECH-17 — Technology Exchange Between Communities
*Civilization Stack · TECH domain · External block, module 17.*

Everything so far governs technology looking inward. This module turns it outward — to capability moving between one community and another, across the border where one community's rules stop and another's begin. The border changes who built the system, who controls it, and who can turn it off. It does not change the rule.

**Core rule — a technology's controllability limits travel with it across the border.** Capability shared with or imported from another community carries its replaceability, its auditability, and its shutdown path with it; exchange may not become the channel for fielding across a line what would be forbidden within it. The contrast names the evasion exactly: *not a border that launders away the limits — import a system you could never stop, export one that locks the recipient in, route control through where the firewall does not reach; but limits that bind the technology wherever it goes.* A community that keeps its own systems stoppable while exporting unstoppable ones, or importing them, has not honored the framework — it has offshored the failure.

Three limits bind hardest across borders:

- **Stoppability survives transfer.** A system adopted from elsewhere must still be one the receiving community can halt (TECH-16). Importing a capability whose off-switch is held by its origin is importing a dependency, not a tool — the cross-border form of TECH-02's inversion.
- **Replaceability survives transfer.** Exchange may not be used to build the single irreplaceable dependency the domain forbids at home (TECH-04, TECH-11). A capability available from only one outside community is a chokepoint that happens to cross a border; the join is no safer for being international.
- **The lock-in firewall survives transfer.** A community may not export a technology engineered to trap the recipient — closed, unsubstitutable, designed so that leaving means rebuilding (TECH-13). Lock-in banned within is not permitted by selling it abroad.

**Exchange is coordination between communities, judged the same way.** The test for cross-border technology flow is the test for all technology (TECH-01): legitimate to the degree it lets communities extend each other's real capability — a shared standard, an interoperable system (TECH-09), a capability one community lacks — and suspect to the degree it merely extends one party's control over the other. The asymmetry of power between communities is exactly where that inversion hides, and the weaker partner is where the dependency lands.

**Sovereignty and the long horizon sit elsewhere.** TECH defines the technological conduct of cross-border exchange. The *authority* to make technology agreements and bind a community to them is GOV's; the *long-term stewardship* of shared technological capability and its consequences is held with LT. TECH's claim is narrow and firm: whatever the agreement says, technology may not be used to field across a border the uncontrollable, unstoppable, or locking-in systems the framework forbids at home.

*Wager named: that technology crossing a border carries its stoppability, replaceability, and anti-lock-in limits with it — that you may not export or import what you may not field at home. The opposing view — that free technology transfer accelerates development and cooperation, and that binding it to the origin's controllability rules fragments a shared technological commons — is coherent and widely held; this framework does not take it, on the grounds that an uncontrollable system is uncontrollable on either side of a border.*

---
*End of the External block. Next: the Appendix & Reference block, beginning with TECH-A0 — Appendix & Reference Strategy.*

---

## TECH-A0-Appendix-Reference-Strategy

*Source: `TECH-A0-Appendix-Reference-Strategy.md`*

# TECH-A0 — Appendix & Reference Strategy
*Civilization Stack · TECH domain · Appendix & Reference block, module A0.*

Status: Active scaffold

> Lineage note: the original placeholder framework note for this domain (human-auditability, independent oversight of high-impact systems, reviewability of automated decisions, replaceable critical infrastructure) has been superseded by the core modules and retained at `99-Archive/TECH-Framework-LEGACY.md`. Its principles are now carried canonically by TECH-00 through TECH-06; this A-series carries the measurable standards behind them.

## Purpose

Defines the appendix, reference, glossary, registry, and standards strategy for the Technology domain. It exists to prevent uncontrolled growth and structural fragmentation as the domain expands, and to keep the measurable standards that back the core modules in one predictable place.

## The A-series

The core modules state principles in prose; the A-series carries the measurable standards those principles reference. Each standard backs a specific constraint:

- **TECH-A1 — Complexity & Concentration Thresholds** — the measurable lines behind the complexity bound and the anti-lock-in firewall (TECH-05, TECH-13).
- **TECH-A2 — Critical-System Replaceability Standard** — behind critical infrastructure and real shutdown (TECH-04, TECH-16).
- **TECH-A3 — Capability Floor Standard** — behind the capability floor (TECH-12).
- **TECH-A4 — Automation Risk-Tier Standard** — behind capability-and-risk and automation under human command (TECH-03, TECH-10).
- **TECH-A5 — Structural Renewal Review Protocol** — behind renewal logic (TECH-06).

## Naming scheme

- **TECH-A1+** → appendices and measurable standards
- **TECH-R1+** → references and external source material
- **TECH-X1+** → experimental or provisional modules

## Structural questions (open)

- What belongs in a core module versus an A-series standard?
- What stays domain-local versus shared globally across the Stack (especially where TECH-A1 meets ECON-A1 on concentration and DATA-A4 on systemic scale)?
- How are thresholds versioned as they are revised?
- Which registries — of critical-system designations, of systemic-system designations — become authoritative?

## Notes

The A-series is written in a standards register — terse, criteria- and threshold-driven — distinct from the prose voice of the core modules. Where a standard sets numbers, those numbers are provisional until reviewed; the structure is canonical, the specific values are not.

---
*Next: TECH-A1 — Complexity & Concentration Thresholds.*

---

## TECH-A1-Complexity-and-Concentration-Thresholds

*Source: `TECH-A1-Complexity-and-Concentration-Thresholds.md`*

# TECH-A1 — Complexity & Concentration Thresholds
*Civilization Stack · TECH domain · Appendix & Reference block, module A1.*

Status: Standard (provisional values)

## Purpose

Defines the measurable lines that separate manageable systems from systems that have grown past comprehension, replaceability, or control — the content behind the complexity bound (TECH-05) and the anti-lock-in firewall (TECH-13), and the trigger for systemic oversight (TECH-14). The core modules establish that complexity and entrenchment have hard limits; this standard sets where the lines sit, so a limit cannot be honored in principle while crossed in fact.

Structure is canonical. The specific thresholds are provisional and set to context (sector, scale, criticality) by the overseeing authority; this document defines what is measured and how a limit is judged crossed, not the final values.

## I. Complexity lines (behind TECH-05)

A system is assessed against:

1. **Comprehensibility** — can a qualified human understand what it does and why, in time to act? A system no one can follow has crossed the hard limit.
2. **Auditability** — can its behavior and decisions be examined from outside (TECH-15)? Opacity that cannot be pierced is a failure, not a feature.
3. **Stoppability** — can it be halted safely (TECH-16)? A system that cannot be stopped without catastrophe has crossed the line regardless of its benefit.

A system failing comprehensibility, auditability, or safe stoppability is over the hard bound and is not deployed at that complexity, whatever capability it offers.

## II. Concentration lines (behind TECH-13)

A technology is assessed for entrenchment against:

1. **Replaceability** — does a critical function depend on it with no substitute (TECH-04, TECH-09)?
2. **Switching cost** — has the cost of leaving risen high enough that the exit is theoretical?
3. **Dependency depth** — how many critical things now rest on this one thing (TECH-11)?
4. **Market reach** — does one provider hold enough of a critical capability to set its terms?

Crossing the concentration lines triggers the firewall (TECH-13) and, at systemic reach, mandatory oversight (TECH-14).

## III. Failure conditions

- Systems deployed past comprehension or safe shutdown because the capability was judged worth it.
- Entrenchment reached step by step, each increment passed over as minor (cumulative lock-in).
- Thresholds set so high the limit never binds, or measured only after the system is already indispensable.
- A critical function resting on a single system with the switching cost never assessed.

## IV. Review

Thresholds are reviewed and renewed (TECH-A5) on a defined cycle and adjusted to real conditions, with TECH-A1 coordinated against ECON-A1 (economic concentration) and DATA-A4 (data scale) where a single actor crosses more than one. The lines are revisable; the existence of hard limits on complexity and entrenchment is not.

---
*Next: TECH-A2 — Critical-System Replaceability Standard.*

---

## TECH-A2-Critical-System-Replaceability-Standard

*Source: `TECH-A2-Critical-System-Replaceability-Standard.md`*

# TECH-A2 — Critical-System Replaceability Standard
*Civilization Stack · TECH domain · Appendix & Reference block, module A2.*

Status: Standard (provisional values)

## Purpose

Defines what "replaceable" and "really stoppable" must mean in operation for systems a society cannot do without — the measurable content of the critical-infrastructure rule (TECH-04) and the shutdown guarantee (TECH-16). The core modules establish that critical systems stay replaceable and every system stays stoppable; this standard sets what a fallback must deliver and what a shutdown must achieve, so a guarantee cannot be satisfied in name while failing in fact.

Structure is canonical. The specific tolerances are provisional and set to context (function, criticality, recovery window) by the overseeing authority; this document defines what must be demonstrated and how, not the final values.

## I. Designating a critical system

A system is designated critical, before reliance deepens, when its failure would endanger — not merely inconvenience — the people depending on it (TECH-04). Each designation carries:

1. **A named function** it is critical to.
2. **A fallback** — an alternative path that keeps the function alive if the system fails.
3. **A recovery window** — how long the function can survive on the fallback, and how fast the primary is restored or replaced.

A critical function with no designated fallback is non-compliant by default.

## II. Demonstrating replaceability

Replaceability is shown, not assumed:

1. **Substitute exists** — an actual alternative system or provider can carry the function (TECH-09), not a hypothetical one.
2. **Migration is exercised** — the switch from primary to substitute has been tested under realistic conditions, not only diagrammed.
3. **Switching cost is bounded** — the cost and time to replace stay within the limits of TECH-A1, so the exit is real.

## III. What real shutdown requires

On a for-cause halt or a planned retirement (TECH-16, TECH-08), the stop:

1. **Can be exercised** — the shutdown path has been tested in the conditions it is meant for, not merely documented.
2. **Leaves dependents able to fall back** — things relying on the system degrade to the fallback, not to failure.
3. **Is clean** — the system is genuinely stopped, not paused into a state from which it silently resumes or cannot be restarted safely.

## IV. Failure conditions

- Critical systems with no tested fallback ("we assume we could replace it").
- Shutdown paths that exist on paper but have never been exercised.
- Migration plans that would themselves break the function if used.
- Switching cost grown past the line while the designation went un-reviewed.

## V. Review

Designations, fallbacks, and recovery windows are reviewed and renewed (TECH-A5) on a defined cycle. The tolerances are revisable; the requirement that critical systems stay replaceable and stoppable is not.

---
*Next: TECH-A3 — Capability Floor Standard.*

---

## TECH-A3-Capability-Floor-Standard

*Source: `TECH-A3-Capability-Floor-Standard.md`*

# TECH-A3 — Capability Floor Standard
*Civilization Stack · TECH domain · Appendix & Reference block, module A3.*

Status: Standard (provisional values)

## Purpose

Defines what counts as adequate baseline access to essential technological capability — the measurable content of the capability floor (TECH-12). The core module establishes that a floor of capability and the means to use it exists and is unconditional; this standard sets what the floor must actually deliver, so a guarantee cannot be satisfied in name while failing in fact.

Structure is canonical. The specific adequacy levels are provisional and set to context (geography, infrastructure, the tools a society currently assumes) by the overseeing authority; this document defines what must be guaranteed and how adequacy is judged, not the final levels.

## I. Covered capability

The floor covers the finite, exclusion-defined set of TECH-12: the connectivity, devices, and basic tools a person needs to reach essential services (ECON-12, DATA-12), to work and learn, and to exercise their rights — together with the baseline literacy and support to use them. The set is held narrow on purpose; additions require justification on exclusion-harm grounds, not convenience.

## II. Adequacy test

For each covered capability, the floor must define and meet:

1. **Reachability** — available without a prohibitive cost or a connection the person lacks.
2. **Usability** — paired with the literacy and support to operate it (TECH-12); capability a person cannot use is access in name only.
3. **Reach** — actually reaching everyone, including those hardest to serve (remote, low-income, low-literacy); coverage gaps are failures, not edge cases.
4. **Reliability** — working when needed, with a path to help when it fails, not available only in principle.
5. **Currency** — keeping pace as the baseline a society assumes moves, so the floor does not quietly fall below what participation now requires.

## III. Failure conditions

- Essential capability gated behind cost or connection the worst-off lack.
- Devices or access provided without the literacy or support to use them — a floor in name only.
- Coverage that reaches most but strands those the floor exists for.
- A floor frozen while the assumed baseline moves on, excluding by obsolescence.

## IV. Review

Adequacy levels are reviewed and renewed (TECH-A5) on a defined cycle and adjusted to real conditions. The floor's content is revisable; its unconditional character is not.

---
*Next: TECH-A4 — Automation Risk-Tier Standard.*

---

## TECH-A4-Automation-Risk-Tier-Standard

*Source: `TECH-A4-Automation-Risk-Tier-Standard.md`*

# TECH-A4 — Automation Risk-Tier Standard
*Civilization Stack · TECH domain · Appendix & Reference block, module A4.*

Status: Standard (provisional values)

## Purpose

Defines how automated and high-capability systems are tiered by stakes and reach, and what each tier must demonstrate before and during operation — the measurable content behind capability-and-systemic-risk (TECH-03) and automation under human command (TECH-10). The core modules establish that scrutiny scales with reach and that automation stays directable, overridable, and stoppable; this standard sets the tiers and the controls each requires, so the bar cannot be honored loosely for systems that warrant the most.

Structure is canonical. The specific tier boundaries and control levels are provisional and set to context by the overseeing authority; this document defines the dimensions and the escalating requirements, not the final cutoffs.

## I. Tiering dimensions

A system's tier rises with:

1. **Reach** — how many people or critical functions it touches (TECH-03).
2. **Stakes** — how severe and reversible the harm if it acts wrongly.
3. **Autonomy** — how far it acts without a human in the loop (TECH-10).
4. **Opacity** — how hard its behavior is to understand and audit (TECH-05, TECH-15).

Higher on any dimension raises the tier; a system high on several is systemic and falls under mandatory oversight (TECH-14).

## II. Escalating requirements by tier

- **Low tier** — local, low-stakes, reversible, transparent. Core-block rules suffice; light-touch.
- **Mid tier** — meaningful reach or stakes. Requires demonstrated human override and stop (TECH-10, TECH-16), documented decision basis, and a tested fallback.
- **High / systemic tier** — population-scale reach or critical stakes. Requires pre-deployment demonstration of controllability (TECH-03), continuous external oversight (TECH-14), a tested and exercised shutdown path (TECH-A2), and renewal on evidence (TECH-06). Where its actions are decisions about persons, the per-person duties of **DATA-10** apply in addition.

## III. The TECH / DATA line

This standard tiers the *automation's controllability* — whether a human can direct, override, and stop it. Where the automated action is a decision about a person, the duties owed *to that person* — explanation, contest, reversal — are governed by DATA-10 and its standards, not here. A high-tier system deciding about people answers to both: TECH for command, DATA for the person.

## IV. Failure conditions

- High-reach systems deployed at a low tier's scrutiny because they performed well in testing.
- Override or shutdown claimed but never exercised (TECH-A2).
- Autonomy raised without re-tiering ("it only advises" after it began to decide).
- Tier boundaries set so the systemic tier never triggers.

## V. Review

Tiers and control levels are reviewed and renewed (TECH-A5) on a defined cycle, coordinated with DATA-A4 where systems span both domains. The cutoffs are revisable; the principle that scrutiny and control scale with reach and stakes is not.

---
*Next: TECH-A5 — Structural Renewal Review Protocol.*

---

## TECH-A5-Structural-Renewal-Review-Protocol

*Source: `TECH-A5-Structural-Renewal-Review-Protocol.md`*

# TECH-A5 — Structural Renewal Review Protocol
*Civilization Stack · TECH domain · Appendix & Reference block, module A5.*

Status: Standard (provisional values)

## Purpose

Defines the procedure by which standing technological authority is reviewed for renewal — the machinery behind renewal logic (TECH-06). TECH-06 establishes that authorization to run a technology defaults to expiration and must earn continuation; this protocol sets what an operator must demonstrate, how the review runs, and what happens when evidence is absent.

The protocol mirrors the Stack's wider renewal-evidence approach: continuation requires affirmative demonstration, and absence of evidence defaults to non-renewal.

## I. What is subject to review

Per TECH-06: the authorization to operate a deployed system, especially at systemic reach (TECH-03); mandated standards and protocols; designations of critical infrastructure (TECH-04) and their fallbacks; the operating license of platforms and automated systems at scale; and the mandates of the oversight bodies themselves. Nothing is exempt, including this protocol.

## II. Renewal evidence (the test from TECH-06)

To renew, an authorization must demonstrate, with documented evidence, that the system:

1. **Still serves its purpose** (TECH-01) — the right tool for a real need, not a legacy kept by habit.
2. **Stays inside the complexity bound** (TECH-05, TECH-A1) — comprehensible, auditable, not grown past control.
3. **Remains replaceable and stoppable** (TECH-04, TECH-16, TECH-A2) — with a fallback and a shutdown path that have been exercised.
4. **Remains under human command and auditable** (TECH-10, TECH-15) — directable, overridable, and examinable by those it affects.

Absence of documented evidence in any one of these defaults to non-renewal. The burden is on the operator to prove *for* continuation, never on others to prove *against* it.

## III. Lapse versus for-cause removal

- **Lapse** — an authorization ending for failed or absent renewal. Neutral, scheduled, no finding of wrongdoing (TECH-06). The ordinary default.
- **For-cause removal** — active interruption or forced shutdown mid-term on a finding of harm or loss of control (TECH-16). A separate, sharper path with a higher bar.

This protocol governs lapse. It hands the for-cause path to TECH-16, and the authority to act in either case to GOV.

## IV. Failure conditions

- Renewal granted by inertia, without affirmative evidence ("the system is too embedded to stop").
- Burden inverted — requiring proof against an operator rather than proof from it.
- Oversight bodies exempting their own mandates from review.
- Cumulative drift — complexity, reach, or dependency expanding step by step, each move passed over as minor.

## V. Review

The protocol is itself reviewed and renewed on a defined cycle. A renewal procedure that exempted itself from renewal would fail the first test it sets (TECH-06).

---
*End of the TECH Appendix & Reference block (TECH-A0 → TECH-A5).*

---

## TECH-MASTER

*Source: `TECH-MASTER.md`*

# 1. Purpose

The Technology domain defines the operational rules governing how technological capability is selected, built, deployed, scaled, and retired across civilization-scale systems.

Its purpose is not to study engineering or computer science as disciplines, but to define the actual constraints on technological power required for long-term civilizational continuity within the limits established by BPF.

The domain establishes:

- what technology is for
- how capability stays under human direction instead of becoming an authority of its own
- how systemic risk is held down as reach grows
- how critical systems stay replaceable
- how complexity is bounded before it outruns anyone's ability to manage it
- how automation, dependency, and lock-in are walled off before they become irreversible

The Technology domain exists to ensure that a civilization can expand its capability without losing control of it — without letting tools entangle past the point of repair, accumulate into authorities no one chose, or outgrow the ability of the people who depend on them to stop them.

---

# 5. Structural Principles

Every TECH module operates under these principles:

- Harm is prevented and repaired before a technology is deployed or scaled.
- Authorization to run a technology does not continue automatically; it is renewed on evidence.
- Technological systems stay interruptible, reversible, auditable, and replaceable.
- Critical capability is a floor, not a market outcome; no one is priced out of the means to participate.
- Nothing becomes too embedded to stop, leave, or replace.
- Complexity past the point of comprehension and control is a hard limit, not a trade-off.
- Technology serves human ends and stays under human command; it does not become the authority.

---

# 7. Current Module Structure

TECH-00 is the canonical spine; this list reconciles to it. Module titles and cross-references are fixed by the modules themselves.

## Core block (00–06)

- TECH-00 — Purpose and Scope
- TECH-01 — What Technology Is For
- TECH-02 — Tools and Authority
- TECH-03 — Capability and Systemic Risk
- TECH-04 — Critical Technological Infrastructure
- TECH-05 — Complexity Bounds
- TECH-06 — Renewal Logic

## Operational block (07–12)

- TECH-07 — Selection and Adoption
- TECH-08 — Lifecycle and Decommissioning
- TECH-09 — Interoperability and Substitutability
- TECH-10 — Automation and Human Authority
- TECH-11 — Dependency and Supply Chains
- TECH-12 — Capability Floor

## Structural Safeguards block (13–16)

- TECH-13 — Anti-Lock-In Firewall
- TECH-14 — Systemic Oversight
- TECH-15 — Transparency and Auditability
- TECH-16 — Interruption and Shutdown

## External block (17)

- TECH-17 — Technology Exchange Between Communities

## Appendix & Reference block (A0–A5)

- TECH-A0 — Appendix and Reference Strategy
- TECH-A1 — Complexity and Concentration Thresholds
- TECH-A2 — Critical-System Replaceability Standard
- TECH-A3 — Capability Floor Standard
- TECH-A4 — Automation Risk-Tier Standard
- TECH-A5 — Structural Renewal Review Protocol

## Planned Future Modules

Further modules may be added as the stack matures, including: research and development governance, dual-use and weaponization limits, outage and shock response, and inter-domain technological coordination. Additional references (TECH-R series) and experimental modules (TECH-X series) may be added per the strategy in TECH-A0.

---

## TECH-Framework

*Source: `01-Technology/TECH-Framework.md`*

# TECH --- Technology Governance Framework (SCBP Implementation)

Purpose: Ensure technological systems remain aligned with human autonomy
and civilizational safety.

Principles: - Technology must remain human-auditable. - High-impact
systems require independent oversight. - Automated decision systems
affecting rights must be reviewable. - Critical technological
infrastructure must remain replaceable.

Structural safeguards: - Algorithmic transparency standards. - Public
auditability for high-risk AI systems. - Periodic review of technology
systems with systemic impact.

---

