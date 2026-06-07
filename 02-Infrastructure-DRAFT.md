# Infrastructure — Draft Domain

> Collapsed from `Stack/02-Infrastructure/` — draft-stage content for future development.

---

## INFRA-00-Purpose-and-Scope

*Source: `INFRA-00-Purpose-and-Scope.md`*

# INFRA-00 — Purpose & Scope
*Civilization Stack · INFRA domain · Core block, module 00.*

This framework defines the structural architecture of infrastructure designed to stay repairable, redundant, reversible, and bounded across generations.

**First principle — build nothing you cannot repair, stop, or replace.** Infrastructure's first obligation is not to be efficient, fast, or cheap — it is to remain fixable when it breaks and removable when it fails. Capacity, performance, and scale are things permitted *inside* that limit, never goals that override it. A system is judged first by how easily it can be repaired and replaced, and only then by what it can do at peak.

It is a *constraint system*, not an engineering ideology — not "centralized" or "distributed" by label. It specifies what infrastructure **must not be allowed to become**: too entangled to repair, too entrenched to remove, dependent on a single point that takes everything down with it, locked to one vendor or one design, or built past what the ecological base beneath it can carry. Everything else is left open to the engineer.

## Stated wagers

This domain rests on value choices. They are named plainly here so they can be argued with, rather than smuggled in as if they were neutral:

- **Repairability over optimization** — a system you can fix outlasts a system tuned to its limit.
- **Redundancy over efficiency** — spare capacity that looks wasteful is what keeps a failure from becoming a collapse.
- **Modularity over integration** — parts that can be swapped beat a whole that must be replaced.
- **Reversibility over permanence** — the ability to unplug a system is worth more than the savings of locking it in.

These are defensible positions, not the only possible ones. They cost money up front and look inefficient on a spreadsheet; the wager is that they are cheaper than the failures they prevent.

## What INFRA governs

The structure of physical systems inside those limits: what infrastructure is for (INFRA-01); the core systems — energy (02), water (03), transport (04), communications (05); the ecological footing they all rest on (06); and the constraints that keep them repairable — maintenance and lifecycle (07), redundancy and resilience (08), reversibility and anti-lock-in (09), and the renewal of infrastructural authority (10).

## What INFRA does not govern (handoffs)

- **Who funds, owns, and prices infrastructure** → ECON. INFRA defines the physical and reliability requirements; ECON defines the economic ones.
- **Who decides what gets built and authorizes it** → GOV. INFRA defines the systems; GOV defines the authority.
- **Applying these rules to a specific built community** → NODE.
- **Diagnosing existing infrastructure for lock-in and capture** → BPF, whose records document the failures INFRA is built to prevent.
- **Land use, settlement pattern, and the long horizon** → LT.

## Standing rules

Every INFRA module operates under the domain's structural principles (see `INFRA-MASTER`): systems are built to be repaired before they are built to perform; infrastructural authority does not continue automatically; systems stay modular, redundant, and reversible; no system becomes a single point whose failure climbs into other layers; nothing becomes too entrenched to stop, replace, or leave; the ecological base is a hard limit, not an input; and capacity scales with the population and geography it serves.

---
*Next: INFRA-01 — What Infrastructure Is For.*

---

## INFRA-01-What-Infrastructure-Is-For

*Source: `INFRA-01-What-Infrastructure-Is-For.md`*

# INFRA-01 — What Infrastructure Is For
*Civilization Stack · INFRA domain · Core block, module 01.*

Infrastructure exists to **turn the ecological base into usable capacity** — to take water, energy, distance, and signal and make them reliably available to people who will never see the works that deliver them. That is its purpose. Everything else it does is either in service of that, or drift away from it.

**Provision.** Infrastructure's first useful function is carrying the essentials of a working life — clean water to the tap, power to the socket, goods and people across distance, a message from one end of a region to the other. It sits one layer above the ecological floor and one below the economy, and its job is to make the floor's gifts dependably reachable. Infrastructure that delivers enormous throughput while leaving the basics unreliable is not succeeding; it is mis-aimed.

**Reliability.** Its second function is doing this *consistently* — not at peak on a good day, but on the worst day, under load, after a part fails. The grid that browns out in a heatwave and the main that bursts in a freeze were built for the average and met the extreme. Reliability is not a feature added at the end. It is the point.

**What it is not for.** Infrastructure is not for entrenchment — becoming so woven into daily life that it can no longer be questioned, repaired, or removed. It is not for capacity pursued as an end in itself, nor for the quiet conversion of a utility into an authority no one chose. These are the recurring ways the purpose inverts: the system built to serve becomes the system everyone must serve, because the cost of changing it has grown past reach.

**The test.** An infrastructure system is healthy to the degree that it provides reliably *and* can still be repaired, stopped, and replaced — and suspect to the degree that it has become too entangled to fix or too entrenched to remove. This is not an aesthetic preference for simplicity; it is the working measure the later modules apply, to maintenance (INFRA-07), redundancy (08), reversibility (09), and renewal (10).

All of this runs above the ecological footing set in INFRA-06, and inside the harm limit the whole Stack inherits from Bounded Power. Provision and reliability are what infrastructure is *for*; staying repairable and within the ecological base is what it must respect *while* doing it. Where they collide, the limit wins.

*Wager named: that infrastructure should be judged by reliable provision and the ability to repair and replace it — not by peak capacity or throughput. That is a choice, and a contestable one.*

---
*Next: INFRA-02 — Energy Networks.*

---

## INFRA-02-Energy-Networks

*Source: `INFRA-02-Energy-Networks.md`*

# INFRA-02 — Energy Networks
*Civilization Stack · INFRA domain · Core block, module 02.*

Energy is the system every other system runs on. Water pumps, signals travel, food keeps, and hospitals function only while the power holds. That makes the energy network the first place the domain's rules are tested: when it fails, the failure does not stay put — it climbs into everything above it.

**Core rule — an energy network must be able to lose any single part without going dark.** The defining risk is not scarcity of power but fragility of delivery: a grid arranged so that one plant, one line, or one substation can black out a region is a system optimized for the good day. The rule is the opposite of efficiency-at-the-margin — keep generation and routing diverse and overlapping enough that the network rides through the loss of any one piece. This is INFRA-08's redundancy principle applied where it matters most.

Two properties carry this:

- **Diverse, distributed generation.** Power should come from more than one source and more than one place — not because any single source is bad, but because a network leaning on one fuel, one plant, or one corridor inherits that single thing's every weakness. Distribution is not an ideological preference for small over large; it is how a network survives the failure of its biggest component.
- **Islandable segments.** A network should be able to break into parts that keep running on their own when the whole is in trouble. A neighborhood or facility that can island — run on local generation when the regional grid drops — turns a blackout into an inconvenience. The grid that can only run as one piece fails as one piece.

**Lock-in is the slow failure.** The fast failure is a blackout; the slow one is a network so tied to a single fuel, technology, or operator that switching becomes practically impossible (INFRA-09). An energy system locked to one supply chain has surrendered its reversibility one contract at a time, and will discover the cost only when that supply fails or that operator turns the terms.

**Energy is essential, and that raises the bar.** Power is a necessity in the ECON-04 sense: its absence is injury, not inconvenience. Where the network is also a natural monopoly — the one set of lines into a region — the case for public oversight is at its strongest and private capture at its least acceptable. INFRA defines the reliability requirement; ECON and GOV govern who owns and oversees it.

*Wager named: that an energy network should be built to survive the loss of its largest component, even where that redundancy looks wasteful in normal operation. The opposing view — that a tightly optimized, centralized grid is cheaper and adequate — is coherent and widely held; this framework does not take it, on resilience and anti-lock-in grounds.*

---
*Next: INFRA-03 — Water Systems.*

---

## INFRA-03-Water-Systems

*Source: `INFRA-03-Water-Systems.md`*

# INFRA-03 — Water Systems
*Civilization Stack · INFRA domain · Core block, module 03.*

Water is the shortest line between the ecological base and the body. There is no substitute, no stockpile that lasts, and no tolerance for failure measured in more than days. A water system is infrastructure at its least forgiving: the margin for error is the margin for survival.

**Core rule — a water system must deliver safe water and carry waste away, continuously, with no single failure that can stop both.** Supply and sanitation are one system seen from two ends, and the rule binds the whole: the source must hold, the treatment must work, the distribution must reach, and the wastewater must leave — and none of these may depend on a single part whose loss strands a population. A city that draws from one reservoir through one plant has built its survival on a single thread.

Two properties carry this:

- **Source and treatment redundancy.** More than one source, and treatment that can keep running when a unit drops. A system fed by a single aquifer or river is hostage to that one body of water's every drought, spill, and contamination event. Redundancy here is not luxury; it is the difference between a boil-water notice and a city without water.
- **Repairable distribution.** The pipes are the part that ages out of sight and fails all at once. A network built to be inspected, isolated section by section, and repaired without shutting down the whole is a network that degrades gracefully. One built as a sealed monolith degrades silently and then breaks catastrophically. This is INFRA-07's maintenance principle in its most literal form.

**Water sits closest to the ecological footing.** Drawing faster than a source can recharge, or fouling it past recovery, is not an externality to be priced later — it is the destruction of the system's own foundation (INFRA-06). A water utility that depletes its aquifer has not made a trade-off; it has spent the thing it exists to deliver. The hard ecological limits apply here first and hardest.

**Water is the clearest essential.** Its absence is injury within hours, and it arrives almost always through a natural monopoly — one main, one network. That combination, in ECON-04 terms, is where guaranteed access and public oversight matter most and private capture is least acceptable. INFRA sets the reliability and repairability requirement; ECON and GOV govern access and ownership.

*Wager named: that water systems must carry redundant sources and repairable distribution, even at higher up-front cost, because the failure mode is measured in days without water. The opposing view — that a single optimized source and network is sufficient and affordable — is coherent and widely held; this framework does not take it, on irreversibility and essential-access grounds.*

---
*Next: INFRA-04 — Transport & Mobility.*

---

## INFRA-04-Transport-and-Mobility

*Source: `INFRA-04-Transport-and-Mobility.md`*

# INFRA-04 — Transport & Mobility
*Civilization Stack · INFRA domain · Core block, module 04.*

Transport is how everything else moves — food to the shelf, people to work, materials to the repair crew that keeps the other systems running. It is the circulatory layer: when it seizes, the failure spreads to every system that depends on parts, fuel, or workers arriving.

**Core rule — a region must not have only one way to move.** The defining risk is the single corridor: the one bridge, the one rail line, the one highway whose closure isolates a place. A transport system is resilient to the degree that any given trip has more than one path, and brittle to the degree that everything funnels through a chokepoint. The rule is redundancy of *route*, not abundance of capacity — two adequate paths beat one large one.

Two properties carry this:

- **Mode diversity.** More than one way to make the same journey — rail and road, freight by more than one method, local routes that do not all depend on the same arterial. A region that can move only by one mode inherits that mode's every vulnerability: the fuel shortage, the washed-out road, the strike. Diversity of mode is what lets movement reroute when one channel closes.
- **Graceful degradation.** A network should lose a link and slow down, not lose a link and stop. Built right, a closed bridge means a longer trip; built wrong, it means a severed region. The design question is always what happens when the busiest single piece is gone.

**Transport entrenches quietly.** The slow failure is not a closed road but a settlement pattern that makes one mode mandatory — places built so that the only way to live there is the car, the single line, the one port. That is lock-in written into the landscape (INFRA-09), and it removes choices from people who never agreed to them. Reversibility here means keeping more than one way to live and move available, not paving the last alternative.

**The handoff to land use is direct.** How settlement, density, and corridor placement are arranged is **LT's** domain; INFRA defines the requirement that movement stay multi-path and repairable. The two meet at every road, and the boundary is worth keeping clear: INFRA says *don't build a region with one exit*, LT decides *where the region goes*.

*Wager named: that transport networks must preserve route and mode diversity, even where consolidating onto one efficient corridor would be cheaper. The opposing view — that optimized single corridors carry more for less and redundancy is waste — is coherent and widely held; this framework does not take it, on resilience and anti-lock-in grounds.*

---
*Next: INFRA-05 — Communications.*

---

## INFRA-05-Communications

*Source: `INFRA-05-Communications.md`*

# INFRA-05 — Communications
*Civilization Stack · INFRA domain · Core block, module 05.*

Communications is the layer that lets every other system coordinate. The grid balances, the water utility monitors, the transport network reroutes, and people reach help, all over the same nervous system. When it goes down, the other systems do not just lose contact — they lose the ability to respond to their own failures.

**Core rule — communications must keep working when the network is partitioned, and must not bind a region to a single provider or standard.** Two failures threaten it, one fast and one slow. The fast one is the outage that cuts a region off entirely. The slow one is lock-in — a population dependent on one carrier, one platform, or one proprietary standard that can raise terms or fail wholesale. The rule addresses both: keep the network able to run in pieces, and keep it open enough to switch.

Two properties carry this:

- **Interoperability and open standards.** Systems that speak a common, open protocol can be swapped, bridged, and repaired by more than one party. Systems locked to a proprietary standard can be changed only by their owner — and that owner becomes an authority no one elected (INFRA-09). Openness here is not a preference for any technology; it is what keeps the network replaceable.
- **Partition tolerance.** A communications network should degrade into working local pieces rather than fail as one. A town that can still reach itself when the long-haul link drops, a mesh that routes around a downed node — these turn a total outage into a local one. The network that only works whole fails whole.

**Communications carries a risk the physical systems do not.** What moves through it is information about people, and a comms layer is also a surveillance layer if it keeps more than it needs. That boundary — what may be recorded, retained, and seen — is **DATA's** to govern, not INFRA's. INFRA defines the physical reliability and openness of the carrying system; DATA defines the limits on what it remembers. Keeping that line clean matters: a communications network built for reliability should not quietly become an instrument built for memory.

**The bar rises as comms becomes essential.** When reaching emergency services, coordinating work, and accessing basic services all run over the same network, its absence becomes injury in the ECON-04 sense. Where it is also delivered through a natural monopoly — the one cable, the one tower — public oversight matters most and capture is least acceptable.

*Wager named: that communications must stay open-standard and partition-tolerant, even where a single integrated proprietary system would be cheaper or faster to deploy. The opposing view — that one well-run integrated provider serves a region best — is coherent and widely held; this framework does not take it, on anti-lock-in and resilience grounds.*

---
*Next: INFRA-06 — Ecological Footing.*

---

## INFRA-06-Ecological-Footing

*Source: `INFRA-06-Ecological-Footing.md`*

# INFRA-06 — Ecological Footing
*Civilization Stack · INFRA domain · Core block, module 06.*

Infrastructure rests directly on the ecological base — closer to it than any other layer in the Stack. The dam holds back a real river, the grid runs on a real watershed and a real climate, the road crosses real soil. These are not site conditions to be engineered around; they are the footing the whole works stands on, and when the footing moves, the works fail.

**Core rule — infrastructure operates inside the ecological base, never against it.** The standard move is to treat ecological damage as a cost of construction — drain the wetland, draw down the aquifer, build on the floodplain, and absorb the consequences later. This framework refuses that at the limit. Some ecological boundaries are *hard*: an infrastructure system may not cross them at any budget, because crossing them destroys the base it depends on — and irreparable harm is the bright line the whole Stack is built around (INFRA-00, ECON-05). You cannot engineer your way past a foundation you have already wrecked.

**Two tiers.** The footing separates what can be built within from what cannot be built at all:

- **Hard limits — not for sale.** Siting and operation that would cause irreversible damage — draining a fossil aquifer, building across a known fault or active floodway, destroying living soil or a keystone ecosystem to lay the works — are ceilings. No throughput justifies them, because the system that destroys its own base does not outlast it. This is the outermost ring of reliability: a grid is not reliable if the climate it assumed no longer holds.
- **Bounded costs — accounted, not ignored.** Reversible, sub-threshold ecological costs may be measured and carried, so the project that creates them bears their weight instead of pushing it downstream. Mitigation and design are allowed here, as tools — but only beneath the hard limits, never as a way to reach past them.

**Why this is reliability, not a green add-on.** Infrastructure built against its ecological footing is infrastructure built to fail — on a delay. The seawall sized for yesterday's sea, the reservoir planned for a rainfall that no longer comes: these are not separate environmental concerns, they are the system mis-designed at its base. The Architecture names this domain's failure as forgetting the ecology holding it up. INFRA-06 is the rule against forgetting.

**This is not "build less" as a goal.** Within the footing, infrastructure is free to be built, expanded, and run. The base is a limit, not a target. But honesty requires the corollary: where existing systems already draw beyond what the base can sustain, staying inside the footing means those draws must come down. The framework does not pretend otherwise. The long-horizon stewardship of these limits is held with **LT**.

*Wager named: that some ecological limits are hard footings, not costs to be priced — that you cannot build past the destruction of the base you stand on. The opposing view — that ecological costs can be priced, mitigated, or engineered around like any other — is coherent and widely held; this framework does not take it, on irreversibility grounds.*

---
*Next: INFRA-07 — Maintenance & Lifecycle.*

---

## INFRA-07-Maintenance-and-Lifecycle

*Source: `INFRA-07-Maintenance-and-Lifecycle.md`*

# INFRA-07 — Maintenance & Lifecycle
*Civilization Stack · INFRA domain · Core block, module 07.*

Most infrastructure does not fail because it was built badly. It fails because it was never built to be kept. The ribbon is cut, the budget moves on, and the system begins a slow decline that no one is funded to notice until a bridge falls or a main bursts. Maintenance is where the domain's first principle lives or dies: a system you cannot afford to repair is a system you are choosing to lose.

**Core rule — a system must be designed to be maintained, and funded to be maintained, for its whole life.** Repairability is not a property you add to a finished design; it is a constraint on the design from the start. A system whose parts cannot be reached, inspected, or swapped without tearing the whole thing open was built to be replaced, not maintained — and replacement is the expensive failure that maintenance exists to prevent.

Three properties carry this:

- **Designed for access.** The parts that wear must be the parts you can reach. A pump you can pull, a section you can isolate, a component you can test in place — these let a system be kept alive piece by piece. A sealed, monolithic design hides its decay until it fails all at once.
- **Funded across the lifecycle.** Maintenance that depends on each year's discretionary budget is maintenance that gets cut in every lean year, until the deferred cost arrives as a catastrophe. The cost of keeping a system must be planned and committed when it is built, not scraped together after it starts to fail.
- **Known lifespan and planned succession.** Every system ages out. A system with a named expected life and a plan for its replacement degrades on schedule; one assumed to last forever degrades by surprise. Knowing when a thing must be retired is part of building it.

**Deferred maintenance is lock-in by neglect.** A system left to decay does not stay neutral — it becomes harder and costlier to fix each year, until repair is no longer realistic and the only option is wholesale replacement under emergency conditions, on the vendor's terms. Letting a system rot is one of the surest ways to lose the ability to choose what replaces it (INFRA-09).

**Maintenance is what makes reliability real.** Redundancy (INFRA-08) and reversibility (INFRA-09) both assume the system is actually being kept up; a spare that has quietly failed is no spare, and a part you meant to be swappable is not swappable once it has seized in place. Maintenance is the discipline the other constraints rest on.

*Wager named: that maintenance funding and repairable design must be committed when a system is built, not left to annual discretion — even though deferring them is always the cheaper choice this year. The opposing view — that maintenance can be funded as needed and deferred when budgets are tight — is coherent and widely practiced; this framework does not take it, on the grounds that deferral is how systems are lost.*

---
*Next: INFRA-08 — Redundancy & Resilience.*

---

## INFRA-08-Redundancy-and-Resilience

*Source: `INFRA-08-Redundancy-and-Resilience.md`*

# INFRA-08 — Redundancy & Resilience
*Civilization Stack · INFRA domain · Core block, module 08.*

A system is not resilient because it is strong. It is resilient because it can lose a part and keep going. Strength delays the first failure; redundancy decides whether that failure stays small or takes everything with it. The whole domain turns on the second question.

**Core rule — no single failure may be allowed to bring down the whole, or climb into other layers.** This is the Architecture's containment rule made physical: a failure must be able to happen without spreading. A system with a single point of failure is a system that has bet everything on one part never breaking — and parts break. The rule is not "prevent all failure"; that is impossible. It is "build so that failure is survivable."

Two properties carry this:

- **No single point of failure.** Every critical function should have more than one way to be met — a second source, a second path, a spare that can take over. The test is concrete and unforgiving: name the one part whose loss stops the system, and you have named what must be doubled. A network with no such part is resilient; a network with one is waiting.
- **Graceful degradation.** A resilient system loses capacity in proportion to what failed — half the generation, half the throughput — rather than dropping from full to nothing. Built right, a failure is a reduction; built wrong, it is a collapse. The difference is whether the system can run in a degraded state at all.

**Redundancy looks like waste, and that is the wager.** Spare capacity sits idle on the good day, and on the good day it always looks like money that could have been saved. The framework names this plainly: the redundancy you resent in normal operation is the only thing standing between a fault and a catastrophe. An infrastructure system optimized until it has no slack has been optimized until it has no resilience — the two are the same cut.

**Resilience and lock-in pull in opposite directions.** A system consolidated onto one vendor, one fuel, or one design is efficient and brittle at once; the same integration that lowers cost removes the alternatives a failure would need. Redundancy and reversibility (INFRA-09) are therefore the same discipline seen twice: keep more than one of everything that matters, so that no single failure — and no single owner — can take the whole.

**Containment is the inter-layer duty.** Infrastructure failure must not climb. A blackout should not collapse the water system; a comms outage should not bring down governance. Each system is built to fail without dragging its neighbors down, because the Stack's rule is that a failure in one layer must not become a failure in all of them.

*Wager named: that critical systems must carry redundancy and degrade gracefully, even though the spare capacity looks wasteful in normal operation. The opposing view — that lean, optimized systems are cheaper and adequate, and redundancy is over-engineering — is coherent and widely held; this framework does not take it, on the grounds that the failure it prevents costs more than the slack it keeps.*

---
*Next: INFRA-09 — Reversibility & Anti-Lock-In.*

---

## INFRA-09-Reversibility-and-Anti-Lock-In

*Source: `INFRA-09-Reversibility-and-Anti-Lock-In.md`*

# INFRA-09 — Reversibility & Anti-Lock-In
*Civilization Stack · INFRA domain · Core block, module 09.*

The most dangerous infrastructure failure is not the one that breaks loudly. It is the one that can no longer be removed. A system that has grown so entangled with everything around it that unplugging it is unthinkable has become an authority — and it acquired that authority without anyone deciding to grant it. This module is the domain's root stated as its sharpest rule: keep the exit real.

**Core rule — every system must remain practically removable and replaceable across its life.** Lock-in is when removal becomes infeasible, replacement becomes prohibitively costly, or dependence on one vendor or design quietly strips away the freedom to choose otherwise. It rarely arrives as a decision. It accumulates — one proprietary standard, one exclusive contract, one integration at a time — until a system that was once a choice has become a fact no one can change.

Four places lock-in accumulates, drawn from the domain's own diagnostic work:

- **Technical architecture.** Proprietary standards and tight coupling mean replacing one part requires rebuilding the whole. Open standards and modular design mean a part can be swapped by more than one party. The test: can a component be replaced without redesigning the system around it?
- **Contracts and vendors.** Automatic renewals, exit penalties, and exclusive provisions convert a service agreement into a trap that springs only when you try to leave. The test: what does it cost to walk away, and who set that cost?
- **Ecosystem coupling.** When one system's removal would disrupt unrelated systems that came to depend on it, the cost of exit spreads far beyond the system itself. The test: how many other things break if this one is removed?
- **Habit and institutional memory.** When the people, training, and processes are all built around one tool, the system is entrenched in minds as well as wires, and replacement means relearning everything. The test: could the people who run this operate a replacement?

**Reversibility is built in, not retrofitted.** A system can be made removable cheaply at design time and almost never afterward. The choice of an open standard, a modular boundary, a contract with a real exit — these cost little when the system is drawn up and become impossible to add once the system is woven in. Anti-lock-in is therefore a constraint on the original design, the same way repairability is (INFRA-07).

**This is the domain's failure mode, named.** The Architecture identifies INFRA's failure as lock-in and brittle fragility — systems too entangled to repair or replace. Reversibility is the direct answer: a system you can still unplug is a system that still serves you, and a system you cannot unplug is one you have started to serve. Keeping the exit real is what keeps infrastructure bounded.

*Wager named: that systems must be kept practically removable and replaceable, even where deeper integration with a single vendor or standard would be cheaper and smoother. The opposing view — that integration delivers real efficiencies and lock-in is an acceptable price — is coherent and widely held; this framework does not take it, on the grounds that a system you cannot leave is a system that can no longer be held to account.*

---
*Next: INFRA-10 — Renewal Logic.*

---

## INFRA-10-Renewal-Logic

*Source: `INFRA-10-Renewal-Logic.md`*

# INFRA-10 — Renewal Logic
*Civilization Stack · INFRA domain · Core block, module 10.*

Infrastructure outlives the decisions that built it. The contract signed once runs for thirty years; the standard chosen once shapes every system built after it; the operator awarded a franchise keeps it long after anyone remembers why. Left alone, infrastructural arrangements do not renew — they simply persist, and persistence is how a choice hardens into a fact no one chose.

**Core rule — infrastructural authority does not continue automatically; it has to be renewed on the evidence.** This is the Stack's expiration principle applied to physical systems: the right to operate, supply, or set standards should run for a defined term and then have to be re-earned, against the question of whether the arrangement still serves. The default must be expiry, not continuation — because an authority that renews itself by inertia is one that has stopped being accountable to anything.

Two properties carry this:

- **Time-bound arrangements.** Operating franchises, supply contracts, and standards mandates should carry defined terms and real review points, not roll over by default. An arrangement that auto-renews has converted a periodic decision into a permanent one — exactly the contractual lock-in INFRA-09 warns against, dressed as routine.
- **Renewal on evidence, not habit.** When a term ends, continuation should turn on whether the system still performs, stays repairable, and keeps its exit real — not on the cost or awkwardness of changing it. "It would be disruptive to switch" is the sound of lock-in defending itself, and it is the argument renewal exists to override.

**Renewal is the anti-lock-in principle over time.** INFRA-09 keeps a system removable; INFRA-10 makes sure someone actually looks at whether to remove it. A system can stay technically reversible for decades and still become entrenched, simply because no one is ever required to reconsider it. The scheduled renewal point is what forces the reconsideration that habit would otherwise skip.

**The authority is held elsewhere; the requirement is held here.** *Who* grants, reviews, and revokes these terms is **GOV's** to define; INFRA defines only that the terms must expire and be re-earned rather than persist. Keeping that line clean matters: INFRA does not claim the power to decide who operates a system — it claims that no one should operate it forever without being asked again.

*Wager named: that infrastructural authority should expire and be renewed on evidence, even though continuation is almost always cheaper and less disruptive than review. The opposing view — that stable, long-term arrangements provide certainty and that frequent renewal is costly churn — is coherent and widely held; this framework does not take it, on the grounds that authority which never has to be re-earned stops being accountable.*

---
*Next: INFRA-11+ — Appendix & Reference Strategy.*

---

## INFRA-11+-Appendix-Reference-Strategy

*Source: `INFRA-11+-Appendix-Reference-Strategy.md`*

# INFRA-11+ Appendix and Reference Strategy

Status: Placeholder

## Purpose

This document defines the future appendix, reference, glossary, registry, and support-module strategy for the Infrastructure domain.

It exists to prevent uncontrolled growth and structural fragmentation as the domain expands.

## Possible Future Areas

- Glossary and terminology
- Infrastructure definitions
- Reliability and resilience metrics
- Lock-in and reversibility assessment references
- Maintenance and lifecycle standards
- Cross-domain mappings
- Registry structures
- Transitional and retrofit references
- Historical infrastructure case material
- Comparative system models

## Structural Questions

- What belongs in appendices versus core modules?
- What should remain domain-local versus shared globally?
- How should references and standards be versioned?
- Which registries become authoritative?

## Future Naming Possibilities

- INFRA-A1+ → appendices
- INFRA-R1+ → references
- INFRA-X1+ → experimental modules

## Notes

This file is intentionally incomplete and exists only as a structural placeholder for future expansion planning.

---

## INFRA-MASTER

*Source: `INFRA-MASTER.md`*

# 1. Purpose

The Infrastructure domain defines the operational systems governing energy, water, transport, communications, maintenance, redundancy, and replacement across civilization-scale physical systems.

Its purpose is not to study engineering as a discipline, but to define the actual infrastructural architecture required for long-term civilizational continuity within the constraints established by BPF.

The domain establishes:

- what infrastructure is for
- how core physical systems stay reliable under failure
- how systems remain repairable across their whole life
- how redundancy keeps a fault from becoming a collapse
- how reversibility keeps systems removable and replaceable
- how infrastructural authority renews rather than persists
- how the ecological base is held as a hard limit

The Infrastructure domain exists to ensure that civilization can physically sustain itself without producing systems too entangled to repair, too entrenched to remove, or built past what the ecological base can carry.

---

# 5. Structural Principles

Every INFRA module operates under these principles:

- Systems are built to be repaired before they are built to perform.
- Infrastructural authority does not continue automatically; it is renewed on evidence.
- Systems stay modular, redundant, and reversible.
- No system becomes a single point of failure whose loss climbs into other layers.
- Nothing becomes too entrenched to stop, replace, or leave.
- The ecological base is a hard limit, not an input.
- Capacity scales with the population and geography served.

---

# 7. Current Module Structure

## Core Modules

- INFRA-00 — Purpose and Scope
- INFRA-01 — What Infrastructure Is For
- INFRA-02 — Energy Networks
- INFRA-03 — Water Systems
- INFRA-04 — Transport and Mobility
- INFRA-05 — Communications
- INFRA-06 — Ecological Footing
- INFRA-07 — Maintenance and Lifecycle
- INFRA-08 — Redundancy and Resilience
- INFRA-09 — Reversibility and Anti-Lock-In
- INFRA-10 — Renewal Logic

## Planned Future Modules

Future modules may include:

- logistics and resource distribution
- deployment and construction systems
- operational continuity and emergency operation
- reliability standards and measurable thresholds
- scaling systems
- infrastructure lifecycle management
- inter-domain infrastructure coordination
- transition and retrofit of existing systems

Additional appendix and reference modules may be added later as the stack matures.

---

## README

*Source: `README.md`*

# Infrastructure

Status: Partial Framework

## Purpose

Defines the operational energy, water, transport, communications, maintenance, and reliability systems required for civilization-scale continuity.

The Infrastructure domain is not primarily concerned with engineering as a discipline. It defines the actual infrastructural architecture required to physically sustain a stable civilization over long time horizons, within the constraints set by BPF.

## Scope

- Energy networks
- Water systems
- Transport and mobility
- Communications
- Ecological footing
- Maintenance and lifecycle
- Redundancy and resilience
- Reversibility and anti-lock-in
- Renewal of infrastructural authority

## Failure Mode

Infrastructure failure produces lock-in and brittle fragility — systems too entangled to repair, too entrenched to remove, dependent on single points whose loss climbs into other layers, and built past what the ecological base can sustain.

## Relationship to BPF

BPF defines the governing principles, limits, and civilizational boundary conditions.

The Infrastructure domain operationalizes resilient, repairable, reversible physical systems within those constraints.

## Canonical Files

- INFRA-MASTER
- INFRA-00 through INFRA-10 modules
- INFRA-11+ Appendix & Reference Strategy (placeholder)

## Draft / Archived Files

Historical and exploratory materials reside in `99-Archive/`, including the infrastructure lock-in diagnostics. These are retained for continuity and recovery but are not authoritative.

## Open Questions

- How should reliability and resilience be measured and thresholded?
- What mechanisms prevent infrastructural lock-in across renewal cycles?
- Which systems must remain redundant rather than consolidated?
- How should maintenance funding be committed across a system's whole life?
- How should the ecological footing propagate into siting and design rules?

---

