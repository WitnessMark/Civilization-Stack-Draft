# Education — Draft Domain

> Collapsed from `Stack/09-Education/` — draft-stage content for future development.

---

## 00-Start-Here

*Source: `00-Start-Here.md`*

# Start Here — Education

Read in order:

1. **EDU-MASTER** — the map and the standing rules.
2. **EDU-00 — Purpose & Scope** — what this domain constrains, and the wagers it rests on.
3. **EDU-01 → EDU-09** — the core block: what education is for, the architecture, design principles, the five literacies, the Red Button Doctrine, lifelong artifact, harm bounds, renewal logic, and inter-domain handoffs.
4. **EDU-A1 and EDU-A2** — the two largest literacy frameworks, retained as appendices because they are big enough to stand on their own.

One note on register. EDU is a *spec*, not a curriculum. It tells an implementing author what a curriculum must do, why, and what it must not do — not what to put on page 47 of Book A. Implementation lives elsewhere. Reading this domain expecting lesson plans is reading it wrong.

Canonical files live in `01-Education/`. Earlier research material is preserved in `98-Lab/` and `99-Archive/` for continuity.

---

## 01-Domain-SUMMARY

*Source: `01-Domain-SUMMARY.md`*

# 01-Domain

Purpose: Canonical domain framework content.

This folder contains:
- canonical framework documents
- master documents
- numbered modules
- operational specifications
- stable reference architecture

Files placed here should be treated as authoritative within the current state of the stack.

This folder is the primary active framework layer for the domain.

---

## ASSESSMENT

*Source: `ASSESSMENT.md`*

# Education Domain Assessment

Status: Active Assessment

## Current State

The Education domain contains substantial conceptual material but remains structurally unstable.

The domain currently mixes:

- curriculum structures
- institutional models
- developmental theory
- literacy systems
- prompts
- operational tooling
- governance education
- civic onboarding
- pedagogical experimentation
- project management systems
- civilization continuity concepts

without a fully stabilized architectural boundary.

## Primary Risks

### 1. Scope Explosion

Education naturally touches nearly every other domain in the stack.

Without strong boundaries, the domain can absorb:

- governance
- culture
- philosophy
- psychology
- administration
- workforce systems
- communication systems
- civic onboarding

resulting in uncontrolled expansion.

### 2. Structural Instability

Many current materials appear:

- exploratory
- generative
- partially overlapping
- iterative
- prompt-derived
- structurally unresolved

This is not necessarily a flaw, but it prevents immediate canonical stabilization.

### 3. Canonical Ambiguity

The domain currently lacks:

- a stable master framework
- stabilized reading order
- finalized educational philosophy
- clear institutional layering
- finalized lifecycle structure

## Current Cleanup Strategy

The current strategy is:

```text
containment before normalization
```

Meaning:

- preserve valuable research material
- avoid premature structural hardening
- isolate experimentation safely
- establish recoverable organization
- defer major decomposition decisions

## Recommended Near-Term Goals

### Structural Goals

- maintain clean folder structure
- separate lab work from canonicals
- isolate archives
- preserve recoverability

### Conceptual Goals

Clarify:

- what education is for
- what literacy means
- how capability develops
- how civilization continuity is preserved
- how governance and education interact
- what should remain universal versus local

### Long-Term Goals

Eventually stabilize:

- institutional architecture
- curriculum hierarchy
- developmental sequencing
- educational governance
- operational competence frameworks
- civilization onboarding pathways

## Current Recommendation

Do not aggressively rewrite or normalize the Education domain yet.

The domain currently benefits more from:

- preservation
- containment
- indexing
- recoverability
- conceptual observation

than from premature consolidation.

## Current Status

Education is not yet canonically stabilized, but it is successfully isolated and protected for future development.

---

## EDU-00-Purpose-and-Scope

*Source: `EDU-00-Purpose-and-Scope.md`*

# EDU-00 — Purpose & Scope
*Civilization Stack · EDU domain · Core block, module 00.*

This framework defines the structural specification of an educational system designed to keep a civilization *readable to the people who live inside it* — across generations, in plain language, without dependence on any one institution.

**First principle — orientation, not performance.** Education's first obligation is not to certify, sort, or prepare workers. It is to give every person a usable map of the systems they are about to enter, before they enter them. The standing rule is short: *we do not leave page 2 until page 2 is real.* Production, evaluation, credentialing, and advancement are activities permitted *inside* that obligation, never goals that override it.

It is a *constraint system*, not a curriculum and not a pedagogy ideology. It does not specify what to teach on a Tuesday. It specifies what a curriculum **must do** — keep page 2 real before page 20, demonstrate before naming, leave the book usable for life — and what it **must not do**: compress without grounding, evaluate at exposure, replace orientation with training, moralize, or perform authority. Everything else is left open to the implementing author.

## Why this is a domain and not a school

Every other domain in the Stack guards a way power escapes correction. EDU guards the prerequisite that makes any of those corrections possible: *people who can read the system they are inside.* Stoppability does nothing if no one knows where the stop is. Renewal means nothing if no one can read what is being renewed. Visibility is empty if the audience is functionally illiterate in the system being made visible. The other domains assume an informed reader; **EDU is the domain that produces the reader.**

The Stack is full of correction machinery. EDU's job is to make sure the machinery has people behind it.

## Stated wagers

This domain rests on value choices, named plainly so they can be argued with:

- **Orientation outranks training.** Knowing the shape of the systems you live inside is worth more than being optimized for one of them.
- **The reader, not the school.** Curriculum belongs to the learner as a lifelong artifact, not to an institution as a record of attendance.
- **No compression without grounding.** Speed without understanding produces credentialed confusion, not literacy.
- **Stoppability is a basic literacy.** The right to pause, refuse, delay, and exit is taught at every age — not as ethics, as structural feature.

These are defensible positions, not the only ones. A reader is meant to see them and contest them.

## What EDU governs

The structural specification of curriculum: what education is for (EDU-01); the age-spine and subject-book architecture (02); the design principles (03); the five literacies and the functionally-literate outcome standard (04); the Red Button Doctrine (05); the lifelong-artifact requirement (06); the harm bounds (07); curriculum renewal without drift (08); and the handoffs to other domains (09). The two largest literacy frameworks live as appendices (A1, A2).

## What EDU does not govern (handoffs)

- **Implementation of actual curriculum** — Books A through I, age-by-age lessons, examples, the *Number Six*. The spec describes what those books must do; the books themselves are produced separately and referenced rather than absorbed.
- **Rights of learners and public access to materials** → GOV.
- **Material provision of the conditions for learning** (time, materials, access) → ECON.
- **Generational continuity rationale** (the long-horizon case for any of this) → LT.
- **Records of learners and the limits on those records** → DATA.
- **Diagnosing failed educational institutions** → BPF.

## Standing rules

Every EDU module runs under the domain's principles (see `EDU-MASTER`, §4): orientation before training; no compression without grounding; demonstrate before naming; no evaluation at exposure; plain language and calm tone; stoppability is a literacy; the book remains; the spec applies to itself.

---
*Next: EDU-01 — What Education Is For.*

---

## EDU-01-What-Education-Is-For

*Source: `EDU-01-What-Education-Is-For.md`*

# EDU-01 — What Education Is For
*Civilization Stack · EDU domain · Core block, module 01.*

Education exists to **orient a person to the systems they live inside, and to keep those systems readable to ordinary people across generations.** That is its purpose. Everything else it does — teaching a trade, conferring a credential, producing a graduate — is either in service of that, or drift away from it.

**Orientation.** Education's first useful function is providing a map of the world the learner is about to enter — administrative, civic, ecological, economic, technological — before the learner is required to navigate it. Most adults discover these systems slowly, through mistakes, in the order the mistakes happen. The framework's claim is that the map should arrive *first*. A person who walks into adult life with a map of the systems waiting for them is operating from a different posture than one who is decoding the systems as they take hits from them.

**Structural literacy.** Its second function is teaching how systems are shaped — not which laws were passed in which year, but how authority operates, how incentives work, how feedback loops form, where capture happens, what failure looks like. This is the literacy the rest of the Stack assumes. Without it, every other domain's correction mechanisms are theoretical: stops no one can find, renewals no one can read, expirations no one can verify.

**Intellectual independence.** Its third function is producing the capacity to question — to evaluate a claim, examine an authority, notice when a thing has stopped making sense. This is not adversarial. It is the working condition for consent, correction, and refusal. A population that cannot evaluate the systems it lives inside cannot meaningfully agree to them.

**What it is not for.** Education is not for institutional training — preparing people to be inputs to a school, a profession, or an employer. It is not for evaluation at exposure — grading people on what they have just been shown. It is not for compression — pushing learners through material faster than they can ground it, in the name of pace. It is not for performance — producing certificates, rankings, or displays of mastery that displace the underlying competence. These are the recurring ways the purpose inverts: the tool of orientation quietly becomes a tool of sorting (EDU-07).

**The test.** A piece of education is legitimate to the degree that it gives a person a clearer map of the systems they live inside, builds structural understanding from grounded experience, or strengthens the capacity to evaluate — and suspect to the degree that it merely sorts, credentials, performs, or accelerates past comprehension. This is the working measure the later modules apply.

*Wager named: that orientation outranks training, and that a population's ability to read the systems it lives inside is part of what makes the Stack's other correction mechanisms real. The opposing view — that education's proper job is producing workers and citizens prepared for existing institutions, and that "orientation" is a luxury added after the basics — is coherent and widely held; this framework does not take it, holding that training without orientation produces compliant confusion rather than capability.*

---
*Next: EDU-02 — Architecture: Age Spine and Subject Books.*

---

## EDU-02-Architecture

*Source: `EDU-02-Architecture.md`*

# EDU-02 — Architecture — Age Spine and Subject Books
*Civilization Stack · EDU domain · Core block, module 02.*

Curriculum that meets this spec is organized along two axes: a **chronological spine** that runs from age 1 to age 28, and a **conceptual set of subject books** that runs across that spine. Every concept lives at the intersection of both, with a permanent reference that never changes once issued. The architecture is plain on purpose — it has to be re-derivable by anyone holding a single volume in their hands.

**Primary axis — the age spine (1 → 28).** One volume per age. Each volume contains everything from that age across every subject. The volume is calibrated to where a person actually is — cognitively, socially, administratively — at that age, not to where an institution wishes they were. A volume preserves what came before and expands forward; it does not replace earlier material. The series, taken together, is a lifelong archive (EDU-06).

**Secondary axis — subject books (A → I).** Subjects are organized by *conceptual domain*, not by academic department:

- **A — Number & Pattern**
- **B — Matter, Energy, Life**
- **C — Story, Language, Meaning**
- **D — People, Power, Agreements**
- **E — Trade, Value, Exchange**
- **F — Earth, Systems, Continuity**
- **G — Orientation & Self-Governance**
- **H — Image, Sound, Expression**
- **I — Tools, Machines, Construction**

This list is intentionally close to the way pre-modern education was organized before subjects were fragmented into school departments. The naming is in human language rather than discipline language because the spec is for a reader, not for a faculty meeting.

**Permanent numbering.** Each concept receives a permanent reference of the form `[Book].[Age].[Concept]`. `A.7.2` means: Book A (Number & Pattern), age 7, concept 2. Once assigned, the number is permanent — across editions, revisions, expansions, errata. A citation written today still resolves twenty years from now.

**Why numbering is structural, not clerical.** A curriculum that renumbers under editorial pressure cannot be cited reliably, cannot be cross-referenced across volumes, and cannot function as a lifelong artifact (EDU-06). The non-renumbering rule is what turns the books into stable infrastructure rather than another product line. The cost — slightly ugly numbering as material accumulates — is paid willingly.

**Expansion rules.** New material is added only by:

- new concept numbers within an existing age volume,
- new age entries within an existing book,
- or new books (alphabetically extending the set).

Existing numbers are never reassigned, even if the material at that number is superseded. Superseded material is annotated, not deleted, and the new material gets the next available number. This is the same logic the rest of the Stack applies to authority: nothing earns permanence without earning it, and once issued, an identifier is honored.

**Each age contains all books.** Every volume crosses every relevant subject at the level appropriate for that age. A learner reading the age-9 volume meets number and pattern, matter and energy, story and meaning, people and power, all at age-9 depth — not nine years of one subject followed by nine years of another. This is the structural defense against fragmentation: the systems people live inside do not arrive sorted by department, and the orientation to those systems should not be either.

*Wager named: that a curriculum organized as a permanent, numbered, lifelong reference is more useful across a life than a curriculum organized as a sequence of school grades — and that the cost of permanent numbering (ugliness over time) is small compared to the benefit (stable citation, lifelong access, expansion without drift). The opposing view, that curriculum should be free to reorganize as understanding advances, is reasonable; this framework treats reorganization as drift in disguise and forbids it structurally.*

---
*Next: EDU-03 — Design Principles.*

---

## EDU-03-Design-Principles

*Source: `EDU-03-Design-Principles.md`*

# EDU-03 — Design Principles
*Civilization Stack · EDU domain · Core block, module 03.*

Six principles govern how material is sequenced inside any volume that conforms to this spec. They are not stylistic preferences. Each one is the structural defense against a specific failure mode that has been observed to recur whenever education is built without it.

**1. Structure before procedure.** Before a learner is taught the rules of a system, they must be shown the *shape* of the system — what it is, what it is for, where its edges are. Rules without structure produce people who can follow instructions and cannot recognize when the instructions have stopped applying. The traditional order — symbol → rule → example → application — gets reversed: **reality → tension → pattern → compression → use**. Symbols arise from observed patterns, not the other way around.

**2. Demonstrate before naming.** Concepts arrive through experience first. Vocabulary is introduced only after the underlying pattern has been felt, recognized, and noticed as worth a name. *Do not introduce "variable." Demonstrate repeated pattern first. Let the abstraction emerge from necessity.* The discipline here is patience — refusing to name a thing the learner has not yet encountered, even when the schedule wants the word said.

**3. Pattern before symbol.** Structures are recognized before they are notated. Repeating groups before multiplication signs; scaling relationships before exponents; proportional patterns before ratio notation. Symbols function as compression of already-grasped patterns, never as the entry point. A learner who meets the symbol first treats it as a rule to memorize; a learner who meets the pattern first treats the symbol as a shorthand they can re-derive.

**4. Friction before abstraction.** Concepts must arise from a real problem the learner has encountered, not from a definition the curriculum has scheduled. Tension before resolution. *Concepts must feel inevitable before they are labeled.* Abstraction without friction produces vocabulary the learner can repeat and cannot use — the recurring failure mode of credentialed confusion.

**5. Plain language first.** All material is readable without prior technical knowledge. Discipline vocabulary is introduced only after the underlying idea is held in plain language, and the plain-language form remains available in every later volume. This is not anti-rigor; it is the rigorous form of accessibility. A concept that cannot be stated in plain language has not yet been understood by whoever is writing it.

**6. No compression without grounding.** No volume advances past a concept until the concept is real for the reader at that age. This is the spec's most-repeated rule, and the one that costs the most to enforce: it means slowing pace when the material has not landed, refusing to schedule mastery, and accepting that some learners need page 2 longer than others. *We do not leave page 2 until page 2 is real.* The opposite failure — forward motion without orientation — is the failure the entire framework was built to prevent.

**Why these are structural, not pedagogy preferences.** Each principle is the wall against a specific kind of harm: rules without structure produce rule-following without understanding; symbols without patterns produce notation without competence; abstractions without friction produce credentials without capability; compression without grounding produces accelerated confusion that compounds for years. The principles do not describe how to teach well. They describe what an implementing curriculum **must not be allowed to skip**, no matter how convenient skipping would be.

*Wager named: that the design principles, taken together, produce slower but durable competence — and that durable competence at age 14 is worth more than credentialed confusion at age 18. The opposing view, that students fall behind without scheduled pace and that the structural rigor proposed here is a luxury only some learners can afford, is serious; this framework answers that scheduled pace produces the very falling-behind it claims to prevent, and that the cost of slowness is paid once where the cost of confusion is paid for decades.*

---
*Next: EDU-04 — The Five Literacies and the Functionally Literate Standard.*

---

## EDU-04-Five-Literacies

*Source: `EDU-04-Five-Literacies.md`*

# EDU-04 — The Five Literacies and the Functionally Literate Standard
*Civilization Stack · EDU domain · Core block, module 04.*

The framework names five literacies as load-bearing. A person who has reached working competence across all five is, in this spec's vocabulary, **functionally literate** — capable of reading the systems they live inside well enough to navigate them, participate in them, and stop them when stopping is the right move. This is the outcome standard EDU produces.

The five are not a ranking. They are a coverage set — each closes a category of confusion that has been observed to compound, across a lifetime, for people who never received it.

## The five

**1. Ecological literacy.** Soil systems, water cycles, ecosystems, regenerative agriculture, environmental stability. The reader understands what the living systems beneath civilization actually do, what they require, and what irreversibly damages them. *Maps to the ecological base in the Architecture, and to LT.*

**2. Systems literacy.** Feedback loops, dependencies, failure modes, resilience design. The reader can recognize a system, trace its inputs and outputs, predict where it will fail, and tell whether it is repairable. *Maps to INFRA, TECH, and the Stack's structural throughline. Treated in depth in EDU-A2.*

**3. Administrative literacy.** Identity, contracts, taxes, insurance, regulatory systems, personal records. The reader has a map of the institutional systems that attach to a human across a life, before those systems attach. *The competence schools rarely teach. Treated in depth in EDU-A1.*

**4. Engineering / construction literacy.** Materials, mechanics, fabrication, repair, the intuition for how things are physically made and held together. Not professional engineering — the basic structural sense that lets a non-specialist participate in physical infrastructure rather than only consume it. *Maps to INFRA.*

**5. Civic literacy.** How institutions function, how authority operates and expands, where governance fails, what accountability looks like, how to participate meaningfully. The framework's own SCBP and GOV vocabulary lives here, introduced quietly and developmentally rather than ideologically. *Maps to GOV and BPF.*

## What functionally literate means

A person is functionally literate, in this framework, when they can:

- read the shape of a system they have never met before and place it in the right category;
- identify what the system is for, what it requires, and where its failure modes are;
- locate the stops, exits, and refusal points (EDU-05) that apply to their participation;
- recognize when a system has drifted from its stated purpose;
- and operate inside the system without being captured by it.

This is the *competence* the spec aims at. Not a credential, not a test score, not a grade-level — a functional state. A learner reaches it gradually, in pieces, across the age spine, and may reach it earlier in some literacies than others. That is expected.

## Why these five and not others

This is a coverage choice and is contestable. The five are named because the absence of each one has been observed to cause specific recurring harm:

- without **ecological** literacy, people consent to irreversible damage to the systems holding them up;
- without **systems** literacy, people cannot read failure or repair;
- without **administrative** literacy, adult life is a slow accumulation of self-inflicted mistakes;
- without **engineering** literacy, the physical world becomes a black box maintained by specialists;
- without **civic** literacy, governance becomes something done *to* the population rather than *by* it.

Other literacies — emotional, aesthetic, spiritual, vocational — are real and matter. The framework does not contest their value; it names *these five* as the structural floor required for the rest of the Stack's correction mechanisms to be usable. Other literacies sit above this floor and are not the spec's concern.

## Handoffs to appendices

The administrative and systems literacies are large enough to deserve their own appendix-level treatment:

- **EDU-A1 — Administrative Literacy** — the 20 systems, the lifecycle phases, the recurring mistakes, the habits, the questions every adult should be able to answer.
- **EDU-A2 — Systems Literacy** — the three layers of civilization, the seven flows, the four responsibilities, the macro inventory.

The other three literacies (ecological, engineering, civic) await appendix expansion. Their absence from the appendix layer is a known gap, not an omission of importance.

*Wager named: that these five together constitute the functional-literacy floor — that a population competent across all five can correct most of what the Stack is built to keep correctable, and a population missing any of them cannot. The opposing view, that "literacy" is being asked to do too much work and that real competence cannot be defined this broadly, is fair; this framework answers that defining it narrowly is how the gap got this big.*

---
*Next: EDU-05 — The Red Button Doctrine.*

---

## EDU-05-Red-Button-Doctrine

*Source: `EDU-05-Red-Button-Doctrine.md`*

# EDU-05 — The Red Button Doctrine
*Civilization Stack · EDU domain · Core block, module 05.*

The Stack asks of every system: can it be stopped by the people inside it? EDU's answer is to teach the stop, developmentally, from the earliest volumes onward. **Stoppability is not a civics topic introduced at age 16. It is a literacy taught from age 5, and it is in every age volume thereafter.** That is the Red Button Doctrine.

## What the Red Button is

A *red button* is a pre-defined action a person can take when their judgment becomes unreliable, when pressure makes thinking hard, or when a system has begun to push past their consent. Its properties:

- requires minimal reasoning to use
- protects immediate safety
- is reversible where possible
- requires no justification, no consensus, and no permission
- remains available during urgency
- should be easy and visible

The button does not require the user to win an argument with the system. It allows the user to *exit the moment* in which the argument was being demanded.

## Developmental sequence

The right to stop is named and re-named at each age, in vocabulary appropriate to the learner. The sequence is layered, not replaced — each age inherits and extends the prior ages' forms.

- **Ages 5–8: "You can say stop."** The earliest form. A child has the standing to halt an interaction. The word *stop* is given full structural weight, not treated as a rudeness to be managed.
- **Ages 9–12: "If something pressures or confuses you, pause."** The right to step out of escalation. Confusion is treated as a legitimate reason to stop and re-orient — not a deficiency to push through.
- **Ages 13–18: "You can question, leave, or refuse escalation."** Three distinct moves: ask, withdraw, decline-to-amplify. The learner is taught that all three are available, separately, in any situation that demands compliance under pressure.
- **Ages 18–22: "You do not have to sign immediately."** The administrative red button. Adult systems demand signatures under time pressure as a routine practice; the right to delay is named as a structural feature, not as a special accommodation.
- **Ages 22–28: "You can leave structures before they calcify."** The exit red button. Jobs, relationships, contracts, communities, identities — the learner is taught that exit remains an option even after entry has been made, and that exit is easier *before* a structure has hardened than after.

## Stops are resets, not attacks

A red button is a structural feature of the system being stopped, not an aggression against it. The doctrine refuses the framing — common in institutional culture — that pausing, refusing, or leaving is a kind of misconduct that must be justified. **A stop does not need to be earned. It is what the stop mechanism is for.** Teaching this early is the only way it survives the first time a learner is told otherwise by an authority figure who finds the stop inconvenient.

## Why this is in EDU and not only GOV

GOV (and BPF) specify the *institutional* stop machinery — rights, procedures, the legal architecture that makes stops enforceable. That machinery is theoretical if the population it protects does not know it exists or does not feel entitled to use it. EDU is where the *literacy* of stoppability lives: the recognition that one is allowed to stop, the vocabulary to say so, the social posture of not apologizing for it. The two halves only function together. Institutional stop mechanisms with no Red Button literacy in the population are protections no one uses; Red Button literacy with no institutional backing is an attitude that gets punished.

## Connection to LEV-02

Levity's stop mechanism — the joke that punctures power — and EDU's stop mechanism — the explicit *no* — are the same structural function expressed in different registers. LEV-02 protects laughter as a public puncture; EDU-05 protects the explicit refusal as a private one. A civilization in which neither is available to its members has lost stop mechanisms at the cultural floor, regardless of what the law on paper provides.

*Wager named: that the right to stop, refuse, pause, and exit is a literacy and must be taught — not assumed, not "common sense," and not deferred to adulthood. The opposing view, that teaching children to refuse breeds defiance and undermines necessary instruction, is widely held; this framework answers that the alternative — populations who do not know they may stop — is how every captured system survives.*

---
*Next: EDU-06 — Lifelong Artifact.*

---

## EDU-06-Lifelong-Artifact

*Source: `EDU-06-Lifelong-Artifact.md`*

# EDU-06 — Lifelong Artifact
*Civilization Stack · EDU domain · Core block, module 06.*

The books produced under this spec are designed to be kept for a lifetime — not consumed during a school year and shelved. Each volume is simultaneously curriculum, reference manual, personal record, and annotation archive. The series becomes the reader's own intellectual archive: when memory fails, when a system arrives that was last met at age 14, when a child asks a question the parent vaguely remembers learning the answer to — **the book remains.**

## What a lifelong artifact requires

A volume conforms to the lifelong-artifact requirement when it is:

- **portable** — readable without an institution, an app, or a network connection;
- **permanently referenced** — every concept addressable by the `[Book].[Age].[Concept]` number (EDU-02), valid for the life of the reader;
- **annotatable** — designed to accept the reader's own notes, milestones, dated additions; the reader's marks are part of the artifact, not vandalism of it;
- **physically durable** — built to survive at the timescale of a human life, not a textbook adoption cycle;
- **structurally stable** — earlier material never reorganized out from under a citation; expansions append.

These are design constraints on the implementing author. A volume that requires an app, a login, a subscription, or a current edition to function fails this module regardless of how good its content is.

## Why this is structural, not nostalgic

A curriculum that cannot be kept cannot be returned to. A curriculum that cannot be returned to cannot serve the reader at the moment they actually need it — which is rarely the moment the school assigned it. The administrative literacy taught at 16 is consulted at 32. The civic literacy taught at 14 is needed at 47 when an institution begins to drift. The Red Button vocabulary learned at 8 is what someone reaches for at 19, in a room they want to leave. **None of this works if the material has been thrown away, paywalled, deprecated, or reorganized.**

The lifelong-artifact requirement is the structural defense against a quiet failure mode: education that produces knowledge the reader can no longer access. Most curricula fail this test, not deliberately, but through institutional convenience — editions are revised, platforms are sunset, subscriptions lapse. The spec refuses convenience here.

## The annotation principle

The book is not finished when it is delivered. The reader's marginalia, dates, names, examples, and corrections are part of the artifact's lifetime function. A volume that discourages annotation — by glossy paper, by digital-only delivery, by tone — has failed half its job. The right design assumes the reader will write in it, and is the better for being written in.

## Non-renumbering, again

The permanent-numbering rule from EDU-02 belongs here too, from the reader's side rather than the author's. If `A.7.2` meant one thing in the reader's age-7 volume and a different thing in the edition their child receives twenty years later, the citation graph collapses and the lifelong artifact becomes a lifetime of confusion. Numbers are honored across editions, supersessions, and corrections. New material gets new numbers; old material at a known number is annotated as superseded but the number is not reused.

## Relationship to monetization and access

A lifelong artifact can be sold and can also be available freely; these are not in conflict, and the spec does not require either. What the spec does require is that the artifact, once acquired, *remains the reader's*. Access cannot be revoked, the artifact cannot be remotely altered, and the reader's annotations cannot be lost to a platform change. Implementations that fail this test do not conform, regardless of their distribution model.

*Wager named: that curriculum should be designed for the reader's lifetime, not the institution's adoption cycle — and that the cost of durable design (slower revisions, harder editing, lower platform leverage) is paid willingly to keep the reader in possession of their own learning. The opposing view, that modern learning should be delivered through continuously updated digital platforms that improve over time, is reasonable; this framework treats that improvement as a benefit purchased at the price of dependency, and declines the trade.*

---
*Next: EDU-07 — Harm Bounds.*

---

## EDU-07-Harm-Bounds

*Source: `EDU-07-Harm-Bounds.md`*

# EDU-07 — Harm Bounds
*Civilization Stack · EDU domain · Core block, module 07.*

Education is a system that touches people at the moments they are most open to being shaped. That openness is the source of both its value and its capacity for harm. This module draws the bright lines, on the same harm-first basis as the rest of the Stack: an implementing curriculum that crosses these lines does not conform, regardless of how well it teaches what it sets out to teach.

**Bound 1 — No compression without grounding.** A curriculum may not advance past a concept that has not yet been understood at the level appropriate for that age. The pacing failure — *page 20 before page 2 was real* — is treated as harm, not as enthusiasm. Speed measured against a schedule is irrelevant; speed measured against the reader's grounding is the only legitimate measure. The page-2 rule is the most-violated rule in the spec, and the bound here is what gives it teeth.

**Bound 2 — No evaluation at exposure.** A learner is not graded, ranked, or sorted on material they have just been shown. Evaluation, when it occurs at all, occurs after a concept has had time to land — and is itself bounded (it does not become a stake on which advancement turns at every age). The harm prevented here is structural: evaluation at exposure produces credentialed confusion, anxiety attached to learning itself, and the unteaching of curiosity. A curriculum that grades first and grounds second has inverted EDU-01's purpose.

**Bound 3 — No moralizing, no ideological framing, no authority posture, no alarmist tone, no hero narratives.** The five things the tone of the material must not do. The spec is not neutral about content — it has positions, named in each module's "wager" — but the *delivery* refuses the registers that bypass understanding. Moralizing teaches obedience to the writer; ideological framing teaches sides; authority posture teaches submission; alarm teaches paralysis; hero narrative teaches the wrong shape of agency. Each of these is a way the writer's force replaces the reader's reasoning, and each is structurally forbidden.

**Bound 4 — Plain language; stable vocabulary; calm tone.** The positive form of bound 3. Plain words, short sentences, concrete examples, vocabulary that does not shift between volumes. This is not anti-rigor; it is the rigorous form of accessibility. A concept that cannot be stated in plain language has not yet been understood by whoever is writing it (EDU-03, principle 5). The bound here means the curriculum cannot retreat into technical jargon to obscure its own gaps.

**Bound 5 — No mandatory performance of learning.** Learning is not a display. A reader is not required to demonstrate engagement, enthusiasm, mastery, or attention as a condition of receiving the next page. Performance demands convert education into theater — the learner produces the appearance of learning rather than the thing itself. The bound here mirrors LEV-05's *no mandatory joy*: protect the conditions, refuse to require the result.

**Bound 6 — No compression of the Red Button.** The right to stop, pause, refuse, delay, and exit (EDU-05) is taught at every age, in every volume, and is not editable down to fit pace constraints. The temptation to abbreviate the stoppability literacy in a "tight" curriculum is itself the failure mode the bound exists to prevent. A curriculum that finds the Red Button material inconvenient has revealed something about itself worth noticing.

**Bound 7 — The book stays the reader's.** Per EDU-06: no remote alteration, no revocation of access, no loss of annotation to a platform change. The lifelong-artifact promise is enforceable, not aspirational. Implementations that violate it harm the reader by quietly taking back what was provided.

**Why these are structural, not classroom etiquette.** Each bound marks a point where an educational system, while still claiming to teach, has begun to do something else — sort, certify, intimidate, perform, evict. The bounds are the wall that keeps an implementing curriculum doing the job EDU-00 named, rather than the adjacent job institutions tend to drift toward when no one is watching.

*Wager named: that "what education must not do" deserves to be specified as carefully as "what education must do" — and that an implementing curriculum is at least as likely to be captured by harm modes 1-7 as it is to be captured by overt corruption. The opposing view, that these bounds will be felt as restrictive by talented authors and may chill good work, is real; this framework answers that the bounds restrict almost nothing actually useful, and that the work most chilled by them is the work most worth chilling.*

---
*Next: EDU-08 — Renewal Logic.*

---

## EDU-08-Renewal-Logic

*Source: `EDU-08-Renewal-Logic.md`*

# EDU-08 — Renewal Logic
*Civilization Stack · EDU domain · Core block, module 08.*

No curriculum is permanent. Every module, every age volume, every named concept is granted standing for a term and must earn its renewal — or it lapses. This is the Stack's renewal principle (mirrored from ECON-06 and GOV-04) applied to educational material. Continuation is what has to be justified; expiration is the default. The non-renumbering rule (EDU-02) is not in tension with this — material can be superseded, annotated, and replaced at a new number while the original number is honored as a stable citation. Permanence of *the identifier* is a structural feature; permanence of *the content at that identifier* is not.

## Why curriculum renews

Two reasons, separately load-bearing. First, the systems EDU teaches about *change* — administrative regimes, technologies, ecological conditions, governance forms. A curriculum that cannot incorporate change drifts into irrelevance and produces literacy in a world the reader does not actually live in. Second, the spec itself accumulates errors over time, and the discipline of renewal is what surfaces them. A curriculum that never gets reviewed is a curriculum whose mistakes never get caught.

## What gets renewed

The principle reaches every layer of the framework:

- the standing of each concept at its assigned number (still useful? still accurate? still the right age?);
- the design principles in EDU-03 (still the right principles?);
- the literacy coverage in EDU-04 (still the right five? are new literacies now load-bearing?);
- the harm bounds in EDU-07 (still the right bounds? new ones needed?);
- the inter-domain handoffs in EDU-09 (still drawing the lines correctly?);
- and *this module itself* (still the right renewal cadence and review tool?).

## The review tool — the 10 foundational questions

Renewal is conducted by running each piece of material through ten questions. The set was originally developed as a curriculum *design* tool and is reused here as a *renewal* tool, because the two operations are the same operation run forward versus backward.

1. **What system are we teaching?** (Is it still the relevant system?)
2. **What failures occur when people do not understand that system?** (Are those still the failures?)
3. **What minimum knowledge prevents those failures?** (Has the minimum changed?)
4. **What real-world tasks require that knowledge?** (Are the tasks still the right ones?)
5. **What sequence of skills builds that competence?** (Is the sequence still correct?)
6. **What misconceptions commonly distort understanding?** (Have the misconceptions shifted?)
7. **What tools or mental models simplify the system?** (Are there better ones now?)
8. **What long-term risks arise if this knowledge disappears?** (Still the same risks?)
9. **What examples make the system intuitive?** (Have better examples emerged?)
10. **How can a person verify they actually understand it?** (Is the verification still honest?)

A piece of material that passes the ten questions renews for the term. A piece that fails one or more is annotated as superseded; the new material takes the next available number; the original number is preserved (EDU-02) as a stable citation pointing at the supersession note.

## Lapse is not destruction

A concept whose renewal fails is not deleted from the books. It is annotated — *superseded at [Book].[Age].[Concept]* — and the reader can follow the trail. This is structurally identical to the Stack's general handling of expired authority: continuation requires justification, but the historical record is preserved as part of how the reader can verify the system was operating honestly.

## The renewal cadence

The spec does not fix a calendar. It does require that:

- *some* cadence be named by the implementing author, before the first volume ships;
- the cadence be public and visible to readers;
- and the renewal process produce dated, signed annotations rather than silent edits.

A curriculum that updates silently has failed this module regardless of how good the updates are. The reader's lifelong artifact (EDU-06) requires that they can see what has changed since they bought the book — silent edits violate that promise.

## Nothing is exempt, including this

The renewal principle applies to itself. EDU-08, the 10 questions, the cadence requirement, this paragraph — all subject to renewal under the same rule. A spec that exempts its own renewal machinery from the discipline it imposes on every implementing curriculum has failed the first test it sets.

*Wager named: that curriculum should renew on a public cadence with visible supersession trails, and that the cost of this discipline (slower revisions, more annotation overhead, no clean rewrites) is paid willingly to preserve the reader's lifelong artifact and the citation graph. The opposing view, that frequent clean rewrites better serve learners than annotated supersession chains, is reasonable; this framework treats the citation graph and the historical record as part of the readability EDU is built to protect, and declines the trade.*

---
*Next: EDU-09 — Handoffs.*

---

## EDU-09-Handoffs

*Source: `EDU-09-Handoffs.md`*

# EDU-09 — Handoffs
*Civilization Stack · EDU domain · Core block, module 09.*

EDU specifies what curriculum must do. It does not produce curriculum, enforce learner rights, fund materials, govern records, or guarantee continuity. Those obligations belong to other domains. This module names where the lines are drawn, so an implementing author or a critic can find the right domain to argue with.

The handoffs are listed once here so the spec is bounded — the domain cannot expand by absorption, no matter how naturally adjacent another concern feels.

## Handoffs out — what EDU does not govern

**To BPF.** Diagnosing whether an existing educational institution is captured, drifted, or beyond repair is a BPF question, not an EDU question. EDU describes the spec a healthy curriculum meets; BPF describes how to read a failing one. A school that violates EDU-07 is not corrected by EDU — it is documented by BPF.

**To GOV.** The rights of learners — access, freedom from compelled belief, freedom to exit, protection of children — are governance questions. EDU asserts that the Red Button (EDU-05) is a literacy and must be taught; GOV asserts that the institutional machinery to make refusals enforceable must exist. EDU teaches that the stop is real; GOV is what makes the stop real.

**To ECON.** The material conditions for learning — time, books, access, the teacher's living wage, the learner's freedom from immediate economic pressure — are economic provision questions. EDU specifies the artifact and the standard; ECON is responsible for the conditions under which the artifact reaches the learner. A spec-conforming curriculum that costs more than a population can afford has not failed EDU; it has revealed a failure in ECON's essentials floor.

**To LT.** The *why* of multigenerational continuity — why this generation should bother teaching readability to the next, when it would be easier to optimize for present consumption — is a long-horizon question. LT carries the case for stewardship; EDU is one of stewardship's principal instruments. EDU does not re-argue LT's case; it implements it.

**To DATA.** Records about learners — what is recorded, how long it is kept, who sees it, when it expires — are DATA questions. EDU asserts that a learner's record may not become a permanent identity index (consistent with the Stack's general informational-sovereignty rule); DATA specifies the machinery. Educational records are subject to DATA's expiration and retention limits, not exempt from them.

**To TECH.** Educational technology — platforms, devices, software, AI-assisted learning — is a TECH question with EDU constraints attached. EDU asserts the lifelong-artifact rule (EDU-06), which restricts what technology may be allowed to do to a learner's materials. TECH governs the technology itself; EDU governs which technologies a conforming curriculum may rely on.

**To LEV.** Classroom tone, the role of play, the freedom to find the material absurd when it is, the refusal of solemn instruction as the only legitimate mode — these are levity questions. EDU's design principles forbid moralizing and authority posture (EDU-07); LEV-02 protects the joke as a stop mechanism; the two together produce material that can be both serious and sayable as ridiculous. A spec-conforming curriculum is not required to be funny, but it is required to be *capable* of being laughed at without breaking.

**To NODE / Civic Units.** The application of EDU in a specific built community — actual schools, study circles, libraries, the local instantiation of the books — is a NODE concern, governed by NODE's opt-in and exit rules. EDU does not specify *whose* community runs the curriculum; NODE governs how participation works.

## Handoffs in — what EDU receives from elsewhere

**From BPF.** The structural-diagnostic vocabulary that EDU-04's civic literacy teaches to a general reader at age-appropriate depth.

**From GOV.** The institutional rights framework that EDU-05's Red Button vocabulary is the literacy form of.

**From ECON.** The provision conditions inside which an implementing curriculum can actually reach learners.

**From LT.** The multigenerational stewardship case that justifies the discipline of permanent numbering, non-renumbering, and lifelong artifacts.

**From every other domain.** The actual systems EDU teaches readers to read. EDU is downstream of every domain in the Stack — it teaches *about* the others. A change in any other domain eventually creates renewal work in EDU-08.

## A standing note

EDU is the most absorptive domain in the Stack — almost any topic can be framed as "but also, people should be taught this." The handoffs above are the discipline that keeps the absorption from happening. When in doubt, the question is: *does the implementing author need this spec to be different in order to produce a conforming curriculum?* If yes, it belongs in EDU. If no, it belongs in whichever domain the implementing author would otherwise consult.

*Wager named: that EDU stays small on purpose, and that resisting absorption is more important than feeling complete. The opposing view, that an educational framework should integrate everything it touches, is reasonable; this framework holds that a domain which absorbs everything teaches nothing in particular.*

---
*End of the Core block (EDU-00 → EDU-09). Appendices follow: EDU-A1 (Administrative Literacy) and EDU-A2 (Systems Literacy).*

---

## EDU-A1-Administrative-Literacy

*Source: `EDU-A1-Administrative-Literacy.md`*

# EDU-A1 — Administrative Literacy
*Civilization Stack · EDU domain · Appendix.*

This appendix expands the third of the five literacies named in EDU-04. Administrative literacy is the working knowledge of the institutional systems that attach to a human across a lifetime — identity, finances, taxes, contracts, insurance, healthcare, housing, regulatory exposure — held in advance of needing them. It is the literacy schools rarely teach. It is also the one whose absence costs ordinary people the most, the most quietly, for the longest.

The material below is reference content for implementing authors of Books D, E, F, and G. It is not curriculum — it is the inventory the curriculum is responsible for covering, at developmentally appropriate depth, across the age spine.

---

## The shape of the problem

Adult life is not the management of one system. It is the simultaneous operation of many systems, each with its own paperwork, deadlines, vocabulary, and failure modes. Most people meet these systems serially, through mistakes, in the order the mistakes happen. **The framework's claim is simple: the map should arrive first.**

## The 20 systems that quietly run modern society

1. Identity systems
2. Financial systems
3. Tax systems
4. Legal systems
5. Healthcare systems
6. Housing systems
7. Insurance systems
8. Transportation systems
9. Energy systems
10. Communication systems
11. Education systems
12. Employment systems
13. Retirement systems
14. Regulatory systems
15. Supply systems
16. Information systems
17. Security systems
18. Environmental systems
19. Infrastructure systems
20. Administrative systems

Understanding these systems is what explains *why so many administrative tasks exist*. The task is not arbitrary; it is the surface of an underlying system whose shape can be learned.

## The administrative lifecycle of a human

Administrative systems do not attach all at once. They attach gradually, in phases, and the phases are predictable enough to be taught.

- **Phase 1 — Identity foundation (birth–18).** Identity, education, and medical records are created on the learner's behalf, largely without their participation. Awareness of *what was created and where it lives* is the literacy outcome at this phase.
- **Phase 2 — Entry to adult systems (18–25).** Banking, credit history, employment paperwork, leases. The first contracts the learner enters into directly. The Red Button form at this phase (EDU-05) is: *you do not have to sign immediately.*
- **Phase 3 — Economic participation (25–40).** Loans, housing, insurance, retirement accounts. Long-horizon commitments begin.
- **Phase 4 — Peak administrative load (40–60).** Multiple simultaneous systems — finance, family, healthcare, possibly elder-care for a previous generation. The phase where administrative cost compounds.
- **Phase 5 — Retirement transition (60–70).** Social security, pension systems, public health programs.
- **Phase 6 — Late-life administration (70+).** Healthcare navigation, estate planning, transfer.

A literate adult, at any phase, has at least skimmed the phases that come next.

## The 10 administrative mistakes most adults make

1. Ignoring credit structure
2. Not tracking contracts
3. Underestimating administrative time
4. Misunderstanding insurance systems
5. Losing important documents
6. Signing agreements without understanding penalties
7. Ignoring long-term financial systems
8. Not protecting identity information
9. Assuming institutions automatically correct errors
10. Not realizing systems accumulate

Each of these is the literacy gap that, once present, compounds for years. Most cannot be repaired retroactively; all can be prevented by an age-appropriate orientation delivered in advance.

## The 12 administrative habits that make life easier

1. Maintain a document archive
2. Track contracts
3. Review finances regularly
4. Understand agreement summaries before signing
5. Maintain an administrative calendar
6. Save communication records
7. Monitor credit reports periodically
8. Understand interest and fees
9. Review insurance coverage periodically
10. Protect identity information
11. Maintain a small financial buffer
12. Review administrative systems annually

The habits are the operational expression of the literacy. A curriculum that teaches the systems without teaching the habits has produced an informed person who still gets hit; a curriculum that teaches the habits without the systems has produced a compliant person who cannot adapt.

## The 8 administrative skills schools rarely teach

1. Understanding contract structure
2. Reading financial terms
3. Navigating bureaucratic processes
4. Maintaining organized records
5. Understanding insurance risk structures
6. Monitoring identity and financial systems
7. Managing long-term financial systems
8. Recognizing system accumulation

These eight are named because their absence is observable, repeatable, and harmful. An implementing curriculum that covers them at developmentally appropriate depth has done the substantive work this appendix is asking for.

## The 10 questions every adult should be able to answer

1. What are my current financial obligations?
2. What contracts are active in my life?
3. What administrative deadlines do I have?
4. Where are my important documents stored?
5. What insurance coverage do I have?
6. How much interest am I paying?
7. What taxes affect my income?
8. What systems manage my healthcare?
9. What systems affect my long-term financial security?
10. Who could access my information in an emergency?

A reader who has reached the functionally-literate standard (EDU-04) can answer all ten at any point in adult life. Inability to answer one or more is a literacy gap, not a moral failing — it is what the curriculum is responsible for having closed.

## The 12 points where administrative mistakes cause long-term damage

1. First credit card
2. First student loan
3. First lease
4. First job paperwork
5. First health insurance decision
6. First vehicle financing
7. Ignoring retirement savings early
8. Lack of insurance coverage
9. Poor record keeping
10. Ignoring credit reports
11. Lack of basic legal planning
12. Not recognizing system accumulation

These are the high-leverage moments — the points at which a small literacy gap turns into a large lifetime cost. They are also the moments the curriculum should be most explicit about, because they cluster early in adult life.

## The personal systems map

The core structure of adult administrative life:

```
IDENTITY
   ↓
EMPLOYMENT  →  INCOME
   ↓
FINANCIAL SYSTEMS
   ↓
HOUSING
   ↓
INSURANCE
   ↓
HEALTHCARE
   ↓
RETIREMENT
```

Surrounding systems that attach to every layer: tax, legal, administrative, documentation.

A learner who can draw this map from memory has the structural orientation administrative literacy aims at. The numbers, agencies, and forms change; the shape does not.

## The 5 invisible forces that shape administrative systems

1. Risk reduction
2. Large institutional scale
3. Accountability requirements
4. Professional specialization
5. Historical layering of rules

These five forces explain *why* administrative systems gradually become complex. A learner who understands the forces can recognize new complexity as it appears, rather than experiencing each new requirement as arbitrary.

## The 5 administrative tools every adult should build

1. Personal document archive
2. Contract registry
3. Administrative calendar
4. Financial overview
5. Emergency information file

Together, these five form a *personal administrative dashboard* — the operational layer beneath the literacy. A curriculum that has covered the inventory but not produced learners with these tools has only done half the job.

---

## Outcome at this literacy

A reader who has worked through Book D, E, F, and G material at age-appropriate depth — and who has built the five tools — meets the administrative-literacy bar named in EDU-04. They will still encounter unfamiliar systems; what changes is the posture they encounter them with. **The challenge of adult life is rarely a single system. The challenge is many systems operating simultaneously. Once a person understands the structure of those systems, the complexity becomes navigable.**

*This appendix is reference, not curriculum. The implementing author is responsible for converting it into Books D, E, F, and G at the design quality EDU-03 requires.*

---

## EDU-A2-Systems-Literacy

*Source: `EDU-A2-Systems-Literacy.md`*

# EDU-A2 — Systems Literacy
*Civilization Stack · EDU domain · Appendix.*

This appendix expands the second of the five literacies named in EDU-04. Systems literacy is the working knowledge of *how the systems beneath civilization actually function* — what layers a civilization runs on, what flows must keep moving for those layers to hold, and what responsibilities a durable society must continuously meet. Administrative literacy (EDU-A1) teaches the reader to navigate the institutional systems they live inside; systems literacy teaches them to read the structural systems holding the whole arrangement up.

The material below is reference content for implementing authors of Books B and F. It is not curriculum — it is the inventory the curriculum is responsible for covering, at developmentally appropriate depth, across the age spine.

---

## The shape of the problem

Modern life is built on infrastructure most people never see, organized into systems most people never name, and dependent on continuous flows most people never count. The result is a population that experiences a hot shower, a stocked grocery store, and a working transit system as background facts of reality, rather than as the output of named systems that can fail. Systems literacy is the closing of that gap. A learner who has reached it sees the same world — and reads it as a system, with named parts.

## The 3 layers of civilization

Civilization can be understood as three structural layers.

```
NATURAL SYSTEMS
       ↓
INFRASTRUCTURE SYSTEMS
       ↓
ADMINISTRATIVE & SOCIAL SYSTEMS
```

- **Natural systems** provide the resources: soil, water, atmosphere, climate, the living web. (Maps to the ecological base in the Architecture; the floor.)
- **Infrastructure systems** convert those resources into usable forms: energy, water, transport, communications, settlement. (Maps to INFRA.)
- **Administrative and social systems** coordinate large populations across the converted resources: markets, governments, contracts, records. (Maps to ECON, GOV, DATA.)

Each layer rests on the one beneath. Failure climbs upward more easily than support climbs downward — which is why the Stack's general rule (*if a layer fails, the failure must not be allowed to climb*) is itself a systems-literacy concept the curriculum should teach.

## The 7 flows that keep civilization alive

Civilization is not a static structure; it is a set of *continuous flows* moving through the structure. The flows are:

1. **Energy**
2. **Water**
3. **Food**
4. **Materials**
5. **Information**
6. **Money**
7. **Governance**

Each flow has sources, channels, sinks, failure modes, and recovery times. A learner who can name the seven flows and identify, for their own life, where each one comes from and where it goes, has reached the orientation systems literacy aims at. The seven are not equally well-taught in most curricula; the implementing author is responsible for closing whichever ones are weak.

## The 4 responsibilities of a durable civilization

A society that intends to last must continuously meet four responsibilities. They are not aspirational; they are structural.

1. **Environmental stewardship** — keeping the natural systems intact.
2. **Infrastructure maintenance** — keeping the converted resources flowing.
3. **Social coordination** — keeping the administrative and social systems functioning.
4. **Human development** — keeping the population capable of operating the prior three.

The fourth responsibility is where EDU lives. The first three are the subject of the other Stack domains. Failure in any one of the four eventually destabilizes the others; this is the structural reason the Stack treats all four as load-bearing rather than ranking them.

## What the literacy produces

A learner who has reached working systems literacy can:

- look at a working system and identify which layer of civilization it belongs to;
- trace its dependencies down through the layers (the grocery store depends on transport, which depends on energy, which depends on extraction or generation, which depends on materials and ecological conditions);
- name the flows the system is participating in and predict what happens if any flow is interrupted;
- recognize when a responsibility is going unmet and roughly which domain is failing it;
- read a new system they have never seen before with the same vocabulary used for systems they already know.

This is the structural orientation. It is upstream of more advanced systems thinking (feedback loops, resilience design, anti-fragility) but the foundation must be solid first or the more advanced material has nothing to attach to.

## Relationship to the 20 systems in EDU-A1

The 20 systems listed in EDU-A1 are *individual-facing* systems — the institutional surfaces a single human meets across a lifetime. The three layers, seven flows, and four responsibilities above are *civilization-facing* — the structural systems running underneath the institutions.

The two literacies meet in practice. A reader who has both can answer not just *"what is my health insurance system doing?"* (A1) but *"what flow is this system a piece of, what layer does it sit in, and what civilizational responsibility is it serving or failing?"* (A2). Either literacy alone leaves real understanding short.

## What systems literacy is not

It is not engineering — the curriculum is teaching the reader to *recognize and reason about* systems, not to operate or build them. The engineering literacy (the fourth of the five) covers physical construction and mechanical intuition; systems literacy covers structural reading.

It is not cynicism. A reader trained to see how civilization actually works tends to encounter, early, the question of how much of it is held together by chance. The curriculum's job (per EDU-07's harm bounds — no alarmism) is to teach the reading without instilling the panic. Systems are fragile *and* repairable; both halves are part of the literacy.

---

## Outcome at this literacy

A reader who has worked through Books B and F at age-appropriate depth meets the systems-literacy bar named in EDU-04. They will not necessarily be able to design or operate the systems they have learned to read — that is a further competence. What they will be able to do is hold an accurate mental model of the world they live in: a layered, flowing, continuously maintained civilization, with named parts and visible dependencies, rather than a background fact of reality.

*This appendix is reference, not curriculum. The implementing author is responsible for converting it into Books B and F at the design quality EDU-03 requires.*

---

## EDU-MASTER

*Source: `EDU-MASTER.md`*

# EDU-MASTER — Education Framework Repository Map

This document is the master index and standing-rules reference for the Education domain.

The Education domain defines the structural specification a curriculum must meet so a civilization can be understood by the people who live inside it — across generations, without each generation having to rediscover the basics by trial. Its purpose is not pedagogy theory and not school reform. It is to keep the readability of the Stack itself within reach of ordinary people, so the other domains' correction mechanisms can actually be used.

The domain establishes:

- what education is *for*, and where it inverts into harm
- the age-spine architecture, subject books, and permanent reference numbering
- the design principles that produce understanding rather than performance
- the five literacies the framework treats as load-bearing
- the Red Button Doctrine — stoppability taught as a developmental sequence
- the harm bounds that distinguish orientation from training
- how curriculum renews without renumbering or structural drift
- where EDU hands off to other domains

---

# 1. Core Block

- EDU-00 — Purpose & Scope
- EDU-01 — What Education Is For
- EDU-02 — Architecture — Age Spine and Subject Books
- EDU-03 — Design Principles
- EDU-04 — The Five Literacies and the Functionally Literate Standard
- EDU-05 — The Red Button Doctrine
- EDU-06 — Lifelong Artifact
- EDU-07 — Harm Bounds
- EDU-08 — Renewal Logic
- EDU-09 — Handoffs

# 2. Appendices

- EDU-A1 — Administrative Literacy
- EDU-A2 — Systems Literacy

# 3. Planned Future Modules

- validation methodology (how an implementing curriculum demonstrates conformance without becoming an evaluation regime)
- public-access rights handoff with GOV
- materials-and-time provision handoff with ECON
- two further literacy appendices (Ecological, Civic) at the depth of A1/A2

---

# 4. Standing Rules Across All Modules

Every EDU module operates under these:

1. **Orientation before training.** The first job is a map of the systems a person lives inside, not preparation for an institution.
2. **No compression without grounding.** Page 2 must be real before page 20. Abstraction emerges from demonstrated necessity, not from a schedule.
3. **Demonstrate before naming.** Concepts arrive through experience first and acquire vocabulary second.
4. **No evaluation at exposure.** A person is not graded on what they have just been shown.
5. **Plain language, stable vocabulary, calm tone.** No moralizing, no authority posture, no hero narratives, no alarm.
6. **Stoppability is a literacy.** The Red Button — the right to pause, refuse, delay, and exit — is taught at every age.
7. **The book remains.** Materials function as permanent reference; numbering is never reused.
8. **Applies to itself.** This spec is itself subject to renewal under EDU-08; nothing here is permanent by default.

---

## README

*Source: `README.md`*

# Education

Status: Experimental / High-Instability Research Domain

## Purpose

Defines the learning systems, developmental pathways, literacy structures, institutional education models, cultural transmission systems, and civilization continuity mechanisms required for long-term civilization-scale stability.

The Education domain is not yet structurally stabilized and currently functions as an active research and experimentation environment.

## Structure

```text
09-Education/
  README.md
  ASSESSMENT.md

  00-Reading/
  01-Education/
  98-Lab/
  99-Archive/
```

## Canonical Content

The canonical education framework will eventually reside in:

```text
01-Education/
```

At present, the canonical layer remains intentionally minimal because the domain is still undergoing conceptual stabilization.

## Lab Content

The majority of current educational material resides in:

```text
98-Lab/
```

This includes:

- curriculum experiments
- developmental frameworks
- prompts
- educational tooling
- templates
- literacy systems
- governance education
- pedagogy experiments
- project-management structures
- civilization onboarding concepts
- unresolved educational architectures

Lab materials remain active and intellectually relevant even when structurally incomplete.

## Archive Content

Historical and obsolete materials reside in:

```text
99-Archive/
```

This includes:

- deprecated drafts
- obsolete exports
- abandoned experiments
- superseded structures
- historical fragments

Archived materials should not be treated as active research.

## Relationship to BPF

BPF defines the foundational principles, constraints, and civilization-scale continuity requirements.

Education defines how civilizations transmit understanding, capability, literacy, ethics, operational competence, and continuity across generations.

## Relationship to Other Domains

Education interfaces heavily with:

- Civic Units
- Governance
- Economy
- Landscape Transition
- Technology
- Data

because educational systems influence all civilization-scale operational systems.

## Domain Notes

Education is currently one of the least stabilized domains in the stack.

This is expected.

The domain presently functions more like an active civilizational research laboratory than a finalized institutional framework.

## Current Status

Education is structurally contained for migration but remains an intentionally experimental and evolving domain.

---

## README

*Source: `01-Education/README.md`*

# Education

Status: Early Framework

## Purpose

Defines the learning, literacy, and generational-transmission systems required for a civilization to remain understandable to the people who live inside it — and treats education as orientation to the world, not training for institutions.

The Education domain rests on a plain claim: a civilization whose people cannot understand the systems that govern them has lost the capacity to consent to those systems, correct them, or replace them. Stoppability, renewal, reversibility, and visibility — the throughline of the Stack — require a population that can *read the system it is inside*. EDU is the domain that keeps that readability alive across generations.

It is not pedagogy theory and not school reform. It is the structural specification a curriculum must meet so that knowledge of how civilization actually works does not have to be re-discovered, by each person, through mistakes.

## Scope

- Orientation to the systems people will live inside (administrative, civic, ecological, economic, technological)
- The age-spine architecture and permanent reference numbering
- Design principles that produce understanding rather than performance
- The five literacies the framework treats as load-bearing
- The Red Button Doctrine — stoppability taught developmentally
- Harm bounds on instruction (no moralizing, no authority posture, no compression without grounding)
- Renewal of curriculum without renumbering or structural drift

## Failure Mode

Two directions, both harm.

- **Too little:** functional illiteracy at civilizational scale — people enter adult systems blind, discover them through mistakes, and have no map. Participation becomes symbolic; correction mechanisms go unused because they are invisible.
- **Too much / weaponized:** education as institutional training, evaluation at exposure, performance pressure without grounding, ideological compression sold as literacy. Knowledge of the system replaced by obedience to a curriculum.

## Relationship to BPF

BPF defines the foundational principles, constraints, and civilization-scale boundary conditions.

EDU operationalizes one of them culturally: the capacity for ordinary people to read, navigate, and — when necessary — stop the systems they live inside.

## Canonical Files

- EDU-MASTER
- EDU-00 through EDU-09 modules
- EDU-A1 — Administrative Literacy
- EDU-A2 — Systems Literacy

In `01-Education/`.

## Lab and Archive

`98-Lab/` and `99-Archive/` are preserved from the prior research phase. The canonical EDU framework now lives in `01-Education/`; lab materials remain accessible but are no longer the primary surface.

## Domain Notes

EDU sits structurally late in the Stack. Many domains can be specified before anyone is taught what they are; none of them survive a generation without EDU functioning. The domain is small on purpose — it defines what curriculum *must do* and *must not do*, not the curriculum itself.

The implementation of the EDU spec — actual age-by-age subject books, lessons, examples — is intentionally out of scope here. That work lives separately and is referenced rather than absorbed.

## Open Questions

- How does the spec validate that an implementing curriculum is actually producing functional literacy, without becoming an evaluation regime that contradicts the design principles?
- What is the right handoff with GOV regarding learner rights and public access to materials?
- What rate of curriculum renewal is structurally healthy — fast enough to stay current, slow enough not to invalidate the lifelong-artifact promise?

---

## 98-Lab-SUMMARY

*Source: `98-Lab/98-Lab-SUMMARY.md`*

# 98-Lab

Purpose: Active experimentation and unstable research.

This folder contains:
- exploratory drafts
- prompts
- concept experiments
- generative material
- partially structured systems
- unresolved architectures
- educational or operational experiments

Files in this folder are considered:
- active
- unstable
- evolving
- non-canonical

The Lab exists to preserve experimentation without forcing premature structural stabilization.

---

