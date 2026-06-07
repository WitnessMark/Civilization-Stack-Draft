# Data — Draft Domain

> Collapsed from `Stack/04-Data/` — draft-stage content for future development.

---

## DATA-00-Purpose-and-Scope

*Source: `DATA-00-Purpose-and-Scope.md`*

# DATA-00 — Purpose & Scope
*Civilization Stack · DATA domain · Core block, module 00.*

This framework defines the structural rules under which a civilization collects, keeps, and acts on information — designed so that records stay bound, expiring, auditable, and answerable across generations.

**First principle — prevent and repair harm first; then collect and act within that limit.** A data system's first obligation is not to know, record, or predict — it is to avoid the harm that knowing can do, and to repair the harm it causes. Collection, retention, and analysis are activities *permitted inside* that limit, never goals that override it. A record is judged first by the harm it avoids, and only then by what it makes possible.

It is a *constraint system*, not an information ideology — not "open data" or "privacy maximalism" by label. It specifies what an information system **must not be allowed to do**: keep records past their purpose, watch people in ways they cannot see or stop, sort persons into permanent categories they cannot escape, or assemble a view so total that no one left can switch it off. Everything else is left open.

## Stated wagers

This domain rests on value choices. They are named plainly here so they can be argued with, rather than smuggled in as if they were neutral:

- **Autonomy-first** — the person a record describes retains standing over it; data about people is held on their behalf, not owned outright by whoever captured it.
- **Bounded over total** — an information system that stays partial, stoppable, and forgetful is worth more than one that sees everything.
- **Expiry as default** — records expire unless keeping them is justified; permanence is the exception, not the rule.
- **Transparency of systems, privacy of persons** — the larger the information power, the more it must be seen; the smaller and more personal the subject, the more it is shielded.

These are defensible positions, not the only possible ones. They are the foundation, and a reader is meant to be able to see them and contest them.

## What DATA governs

The rules of informational life inside those limits: what data is for (DATA-01), personal data and autonomy (02), collection and purpose limits (03), retention and expiry (04), records and correction (05), and renewal of data authority (06); how it operates — identity, public records, classification, automated decisions, portability, and the information floor (07 → 12); and the safeguards and measurable standards that hold it all in place (13 → 16, A1 → A5).

## What DATA does not govern (handoffs)

- **Who may hold and oversee information authority** → GOV. DATA defines information's rules; GOV defines the authority that enforces them.
- **The tools and algorithms that process data** → TECH. DATA sets what a decision system owes the person; TECH governs the machinery itself.
- **Applying these rules to a specific built community** → NODE.
- **Diagnosing existing information institutions** → BPF, whose records document the surveillance failures DATA is built to prevent.
- **Long-horizon stewardship of archives and knowledge** → LT.

## Standing rules

Every DATA module operates under the domain's structural principles (see `DATA-MASTER`, §5): harm is prevented and repaired before information is collected or acted on; data is collected for a stated purpose and used only for it; records expire by default; the person a record describes retains standing to see, correct, and limit it; data systems stay interruptible, reversible, auditable, and deletable; no actor assembles total visibility into persons; and visibility scales with power while privacy scales with the person.

---
*Next: DATA-01 — What Data Is For.*

---

## DATA-01-What-Data-Is-For

*Source: `DATA-01-What-Data-Is-For.md`*

# DATA-01 — What Data Is For
*Civilization Stack · DATA domain · Core block, module 01.*

Information exists to **record truthfully, coordinate among strangers, and remember what a society needs to function** — memory in service of the people it describes. That is its purpose. Everything else it does is either in service of that, or drift away from it.

**Record.** Data's first useful function is keeping a faithful account — of what happened, what was agreed, what is owed, what exists. A land title, a medical history, a vote count: records let a society act on the past instead of re-deciding it each morning. A record that is false, or that no one may check, fails at the one thing a record is for.

**Coordinate.** Its second function is letting strangers transact and trust without knowing each other — the credential that says you may enter, the ledger that says the payment cleared, the registry that says this is yours. Data here is a coordination *tool*, useful exactly to the degree it lets people cooperate, and no further.

**Remember.** Its third function is institutional memory: holding enough of the past that a society can learn, audit its own conduct, and hold power to account. But memory has a cost the other two do not — it accumulates, and what accumulates can be turned against the person remembered.

**What it is not for.** Data is not for surveillance — watching people in ways they cannot see or stop. It is not for sorting persons into permanent categories that follow them for life, for prediction used to pre-judge and control, or for the quiet conversion of records-about-people into power over them. These are the recurring ways the purpose inverts: the tool of memory becomes an instrument of permanent watch.

**The test.** An information activity is legitimate to the degree that it records, coordinates, or remembers in service of the people involved — and suspect to the degree that it merely watches, profiles, or extracts. This is not a moral mood; it is the working measure the later modules apply: to collection (DATA-03), to retention (04), to automated decisions (10), and to the anti-surveillance safeguards (13–14).

All of this runs inside the harm limit set in DATA-00. Recording, coordinating, and remembering are what data is *for*; not building a watch people cannot escape is what it must respect *while* doing it. Where the two collide, harm-first wins.

*Wager named: that information should be judged by how well it serves the people it describes and the public — not by how much of them it captures. That is a choice, and a contestable one.*

---
*Next: DATA-02 — Personal Data & Autonomy.*

---

## DATA-02-Personal-Data-and-Autonomy

*Source: `DATA-02-Personal-Data-and-Autonomy.md`*

# DATA-02 — Personal Data & Autonomy
*Civilization Stack · DATA domain · Core block, module 02.*

**Personal data** is any record that picks out a person: a name, a face, a location trail, a purchase history, a diagnosis, a pattern of behavior specific enough to be one human and not another. The defining test is identifiability — whether the record, alone or joined to others, points back to someone. That is what sets this category apart from everything else the domain handles.

**Core rule — data about a person is held on their behalf, not owned outright by whoever collects it.** A clinic records your history to treat you; a registry holds your title to protect your claim. The collector holds a *duty*, not a possession. Treating personal data as the collector's property to keep, sell, and repurpose at will inverts the relationship — the person becomes the raw material, and the record becomes someone else's asset extracted from them.

Four standings carry this:

- **To know.** A person may know what is held about them, by whom, and why. A record kept secretly from its own subject is the first move of surveillance.
- **To see.** A person may inspect the records that describe them — not a summary, the substance — because a record you cannot read is a verdict you cannot examine.
- **To correct.** A person may fix what is wrong, and errors are fixable; the machinery lives in DATA-05.
- **To limit.** A person may constrain reuse and demand deletion when the purpose has lapsed; the machinery lives in DATA-03 and DATA-04.

**This is not data as property; it is data as a relationship with duties.** The two misreadings sit on either side. One says data about you is *yours* to own and sell like a thing — which dissolves the moment it is copied, and turns autonomy into a market stall. The other says data is *free for the taker*, the collector's to keep because they gathered it. The framework takes neither: personal data is held in trust for the person it describes, and the holder owes them standing over it.

**Autonomy scales with stakes.** The more a record can harm — health, location, intimate life, the markers that invite discrimination — the stronger the person's standing over it. Trivial records earn light duties; records whose exposure is itself an injury earn the strongest. This mirrors the harm-first ordering of DATA-00: protection rises with the harm that loss of control would cause.

*Wager named: that the person a record describes retains standing over it, and that collecting data does not transfer ownership of the person it describes. The opposing view — that whoever lawfully collects data owns it, and that clear ownership makes data more useful and more tradable — is coherent and widely held; this framework does not take it, on autonomy-first grounds.*

---
*Next: DATA-03 — Collection & Purpose Limits.*

---

## DATA-03-Collection-and-Purpose-Limits

*Source: `DATA-03-Collection-and-Purpose-Limits.md`*

# DATA-03 — Collection & Purpose Limits
*Civilization Stack · DATA domain · Core block, module 03.*

Every record begins with an act of collection — a sensor switched on, a form filled, a transaction logged. That act is where information power is cheapest to bound and most expensive to undo later. What is never collected cannot leak, cannot be repurposed, and cannot outlive its reason.

**Core rule — collect for a stated purpose, and use it only for that.** Data is gathered against a declared reason, and that reason fixes the boundary of its use. Collecting first and finding uses later — the "gather everything, it might be useful" posture — is precisely how ordinary records drift into surveillance: the supermarket loyalty card becomes a behavioral profile, the toll transponder becomes a movement log. Purpose-binding is the wall against that drift.

Two limits carry it:

- **Minimization.** Collect the least that serves the purpose, not the most that is technically available. If the purpose is to confirm you are old enough to enter, the system needs a yes, not your birth date, your address, and a scan of your face. Excess collection is not foresight; it is unspent risk sitting in a database, waiting to be breached or repurposed.
- **Purpose-binding.** Data collected for one reason may not be quietly turned to another. Reuse beyond the declared purpose requires a fresh basis — a new consent, a legal mandate, an oversight finding — not the mere fact that the data is already on hand. "We already have it" is not a reason to use it.

**Stated, not buried.** A purpose hidden in forty pages of terms is not a stated purpose; it is consent manufactured by exhaustion. The standard is whether an ordinary person could know, in plain language and before the fact, what is being collected and what it is for. Opacity at the point of collection poisons everything downstream.

**This is not anti-collection; it is anti-accumulation.** Societies need records — to treat patients, settle claims, run elections. The framework does not forbid collection; it forbids collection without a reason and reuse without a fresh one. The line is between gathering what a purpose requires and hoarding what power might someday want.

*Wager named: that data should be collected against a declared purpose and held to it — not gathered broadly on the chance it proves useful. The opposing view — that maximal collection fuels innovation, research, and efficiency, and that purpose limits forfeit value not yet imagined — is coherent and widely held; this framework does not take it, on the grounds that unbounded collection is the raw material of surveillance.*

---
*Next: DATA-04 — Retention & Expiry.*

---

## DATA-04-Retention-and-Expiry

*Source: `DATA-04-Retention-and-Expiry.md`*

# DATA-04 — Retention & Expiry
*Civilization Stack · DATA domain · Core block, module 04.*

The danger this whole domain is built around is not the record made today; it is the record that never goes away. A debt paid, a charge dropped, an illness recovered from, a place you used to live — left on a permanent file, each becomes a sentence that outlives its cause. Permanent memory is how information turns into the failure mode the architecture names: people defined forever by records that never expire.

**Core rule — records expire by default; keeping is the exception that must be justified.** Every record carries a clock. When its purpose is served, it is deleted — not archived indefinitely, not kept "just in case," but removed. Retention beyond the purpose is the move that has to earn its keep, against a stated reason and a defined limit. This inverts the common default, where storage is cheap so everything is kept forever; here, forgetting is the rule and remembering is the justified exception.

This is the structural form of the right to be forgotten:

- **Expiry is built in, not requested.** The clock runs automatically; a person should not have to petition to have a lapsed record erased. A right that depends on the subject knowing to ask, and the holder choosing to honor it, is a favor, not a guarantee. The measurable schedules live in **DATA-A1 (Retention & Expiry Standard)**.
- **Deletion is real, not cosmetic.** When a record expires it is gone — not flagged hidden while the data persists in backups and derivations. The enforceable machinery of erasure sits in **DATA-16 (Interruption & Deletion)**.

**The carve-outs are narrow, and named.** Some records must outlast their immediate purpose: the historical archive, the public-interest record of how power acted, the data a society needs to audit itself. These exceptions are real — but they are *exceptions*, defined explicitly, held narrow, and aimed at the conduct of power rather than the lives of persons. Permanent memory of what an institution did is accountability; permanent memory of what a person did is surveillance. The line between them is the whole point, and it tracks DATA-08's split between public power and private person.

**This is not amnesia as a policy.** Forgetting by default does not mean a society keeps nothing. It means it keeps what a living purpose requires and lets the rest go — so that memory stays a tool the present uses, not a cage the past builds around people who have changed.

*Wager named: that records should expire by default and permanence should be the justified exception — that a society is healthier for forgetting most of what it could keep. The opposing view — that comprehensive permanent records aid accountability, history, security, and research, and that deletion destroys evidence — is coherent and widely held; this framework does not take it, on the grounds that permanent memory of persons is the engine of permanent surveillance.*

---
*Next: DATA-05 — Records, Access & Correction.*

---

## DATA-05-Records-Access-and-Correction

*Source: `DATA-05-Records-Access-and-Correction.md`*

# DATA-05 — Records, Access & Correction
*Civilization Stack · DATA domain · Core block, module 05.*

A record you cannot see is a verdict you cannot appeal. Decisions get made about people every day on the strength of files they have never read — a credit score, a risk flag, a watchlist entry — and where the file is hidden from its own subject, error becomes permanent and bias becomes invisible. Access is what makes a record answerable.

**Core rule — the person a record describes can see it and correct it.** Standing without sight is empty; the rights named in DATA-02 only bite if the person can actually read what is held and fix what is wrong. So a data system must let its subjects inspect the substance of their records and challenge what is false — not as a courtesy granted on request, but as a built-in property of holding records about people at all.

Three guarantees carry it:

- **Access to the substance.** The subject sees the actual record, in intelligible form — not a summary that omits the damaging part, not an export so technical it conceals what it contains. If a record drives a decision about a person, that person can read what drove it.
- **Correction of error.** A demonstrated error is fixed, promptly, at the source — and the correction propagates to wherever the bad data was already sent. A fix that leaves stale copies circulating has not fixed anything.
- **A trail of changes.** Who recorded, who altered, who accessed — kept so that both error and tampering can be traced. The audit machinery is shared with **DATA-15 (Transparency & Auditability)**.

**Public records, public access.** Where a record is *about* the conduct of power rather than a private person — a court docket, a budget, a permit register — the access right widens from the subject to the public, because the record exists precisely so power can be checked. This is the same principle running the other direction, and it is set out in DATA-08.

**This is not transparency for its own sake; it is appeal.** The point of seeing a record is not curiosity — it is the ability to contest a judgment built on it. A system that decides about people from files they cannot see or fix has placed the record above the person, which is the inversion DATA-01 warns against. Access and correction put the person back in reach of their own account.

*Wager named: that people are owed sight of and correction over the records used to judge them — that no file about a person should be beyond that person's examination. The opposing view — that some records (security, investigative, proprietary scoring) must stay closed to their subjects to remain effective — is coherent and widely held; this framework does not take it as the default, confining closure to the narrow, justified exceptions of DATA-09.*

---
*Next: DATA-06 — Renewal Logic.*

---

## DATA-06-Renewal-Logic

*Source: `DATA-06-Renewal-Logic.md`*

# DATA-06 — Renewal Logic
*Civilization Stack · DATA domain · Core block, module 06.*

No permission to hold data is permanent. Every consent, every access grant, every retention basis, every authority to run a data system is given for a term and must earn its renewal — or it lapses. Continuation is the thing that has to be justified; expiration is the default. This is the Stack's renewal principle (DATA-00) turned directly on information power.

**Why default-to-expiration.** Data permissions drift toward entrenchment the way records drift toward permanence (DATA-04): a consent given once becomes a standing license, an access granted for a project outlives the project, a system authorized for one era keeps running into the next. The usual defense is vigilance after the fact — discovering, years later, that some database still holds what it should have shed. This framework chooses a structural defense instead: grant nothing as standing, and the stale permission never forms, because it was always going to expire unless actively renewed.

**What must renew.** The principle reaches every form of standing information authority:

- consents and the permissions built on them;
- access grants to records, especially to personal and sensitive data;
- retention bases — the justification for keeping a record past its purpose (DATA-04);
- the operating authority of data systems that hold information at scale;
- and the mandates of the oversight bodies themselves. The watchers renew too; there is no permanent data regulator any more than a permanent registry.

**The renewal test.** To renew, an authority must show its purpose still holds (DATA-03), that it collects and keeps no more than that purpose requires, that it sits inside the harm limits (DATA-00), and that it remains auditable, stoppable, and answerable to the people it describes. Meeting the test renews the term; failing it lets the term end. The review machinery is **DATA-A5 (Structural Renewal Review Protocol)**.

**Lapse is not punishment.** A permission ending for lack of renewal is the ordinary, scheduled default — not a penalty, not a finding of wrongdoing. Keeping it neutral is what stops renewal from becoming a fight: nothing has to be proven *against* a data holder to let its access expire; it simply has to fail to prove the access is still needed. Removal *for cause* — emergency shutdown, forced deletion — is a separate path, and lives in **DATA-16**.

**Nothing is exempt, including this.** The renewal principle applies to itself. These rules, and the protocol that enforces them, are themselves subject to review and renewal. A framework that exempts its own machinery from the limits it imposes on everyone else has already failed the first test it sets.

*Wager named: that authority to hold and use data should default to expiration and earn renewal again and again — standing assumed by nothing. The opposing view, that durable data permissions create the stability long-running systems and research depend on, and that constant renewal is friction, is coherent and widely held; this framework does not take it, holding that stale, unrenewed access is the quiet path to permanent surveillance.*

---
*End of the Core block (DATA-00 → DATA-06). Next group: Operational Structure, beginning with DATA-07 — Identity & Credentials.*

---

## DATA-07-Identity-and-Credentials

*Source: `DATA-07-Identity-and-Credentials.md`*

# DATA-07 — Identity & Credentials
*Civilization Stack · DATA domain · Operational block, module 07.*

Most of what a society needs to verify about a person is narrow: are you old enough, are you licensed, did you pay, do you live here. Yet the usual way to answer is to hand over a full identity — a single number or document that confirms the one fact and, in passing, links the person to everything else under the same key. A credential should answer the question asked, and no more.

**Core rule — prove what is needed without revealing all you are.** Identity systems are built for minimal disclosure: the claim required by the situation, established without exposing the rest. The contrast is the whole design choice. *Not one master key that unlocks every record; partitioned proofs that each open one door.* A bar needs to know you may drink, not who you are. A landlord needs to know you can pay, not your medical history.

Two structures carry it:

- **Minimal disclosure.** Each transaction gets the least identifying information that settles it — a yes, a token, a verified attribute — rather than a full identity dossier handed over by reflex. The standards for what "least" means live in **DATA-A2 (Minimization & Purpose Standard)**.
- **Partition over unification.** Identities are plural and compartmented, not consolidated under one index that ties a person's whole life together. The single national identifier is convenient precisely because it links everything — which is exactly why it is dangerous: it is one query away from total visibility, and one breach away from total exposure.

**The convenience is real, and it is the trap.** A single universal ID is easier for everyone who wants to find you — the service, the merchant, the state, the attacker. That ease is not a side benefit; it is the hazard. Linkage that makes life frictionless for the holder is the same linkage that makes surveillance frictionless for whoever assembles it (DATA-13). Partitioning trades a little convenience for the structural impossibility of one actor seeing the whole person.

**This is not anonymity as a goal.** People must be accountable — for debts, crimes, contracts; the framework does not dissolve identity into untraceable fog. It separates *verifying a claim* from *exposing a person*, so that accountability does not require building the master key that makes everyone permanently visible.

*Wager named: that identity should be partitioned and disclosure minimal — that proving one thing should not reveal everything. The opposing view — that a single trusted identity is simpler, safer against fraud, and easier to administer — is coherent and widely held; this framework does not take it, on the grounds that the unified key is also the single point of total surveillance and total failure.*

---
*Next: DATA-08 — Public Records & Open Information.*

---

## DATA-08-Public-Records-and-Open-Information

*Source: `DATA-08-Public-Records-and-Open-Information.md`*

# DATA-08 — Public Records & Open Information
*Civilization Stack · DATA domain · Operational block, module 08.*

Some information must be open *because* it concerns power. A budget, a court docket, a permit register, a record of how an official voted — these exist so that the people subject to authority can see what it is doing. Where DATA-04 makes private records expire and DATA-09 lets some be closed, this module runs the other way: it names what must stay open, and why.

**Core rule — visibility scales with power; privacy scales with the person.** The larger the authority a record describes, the more it must be seeable by those it affects; the smaller and more personal the subject, the more it is shielded. This is the mirror image of the personal-data rule (DATA-02), and the two are one principle read from both ends: daylight on power, shade on persons. A household's affairs are private; a government's are not.

Two categories follow from it:

- **Open by default — the conduct of power.** Public business, public spending, public decisions, and the records of how institutions exercise authority are open as a standing condition, not on request. These are the records that let power be checked, and the ones whose permanent retention is accountability rather than surveillance (DATA-04). Closing them requires the narrow, justified exception of DATA-09 — never mere inconvenience.
- **Shielded by default — the private person.** Records that pick out a private individual are not opened by labeling them "public interest." The fact that a person interacted with a public system does not make that person public business.

**Openness must be usable, not nominal.** A record technically public but buried, unsearchable, or released too late to act on is open in name only. The standard is whether an ordinary member of the public can actually find and read it in time to use it — the same legibility bar DATA-15 sets for auditability. Access that exists only on paper does not check anything.

**This is where DATA and ECON meet, and divide.** ECON-15 requires economic power at scale to be visible; this module requires public power to be. They share the rule — the larger the power, the more it owes daylight — and they share the guardrail: neither permits a transparency regime to curdle into a surveillance regime aimed at persons. Watching power is the job; watching people is the failure.

*Wager named: that information about the conduct of power should be open by default, while information about private persons should not — and that the two are governed by one rule read in opposite directions. The opposing view — that broad official secrecy protects effective government, and that wide openness chills candor and aids bad actors — is coherent and widely held; this framework does not take it, on the grounds that power unseen cannot be bounded.*

---
*Next: DATA-09 — Classification & Access Control.*

---

## DATA-09-Classification-and-Access-Control

*Source: `DATA-09-Classification-and-Access-Control.md`*

# DATA-09 — Classification & Access Control
*Civilization Stack · DATA domain · Operational block, module 09.*

Some information genuinely should be closed for a time: an investigation in progress, a security detail, a person's medical file, a negotiation not yet settled. The need is real. But secrecy is also the oldest cover for power that does not want to be seen — and the line between a justified seal and a convenient one is where this module does its work.

**Core rule — secrecy is a cost, justified narrowly, and made to expire.** Classification is not a property a record simply has; it is a restriction someone must justify, against a stated harm that disclosure would cause, for a defined period. The default is open (DATA-08); closure is the exception that carries a burden of proof — and a clock. The contrast that governs it: *not secret because the information is inconvenient or embarrassing; secret only because openness would cause a specific, nameable harm.*

Three limits carry it:

- **Bounded.** A seal covers the specific record and harm that justify it, not a whole subject area swept shut for convenience. Over-classification — sealing far more than the harm requires — is itself a failure, because it hides the accountable along with the genuinely sensitive.
- **Expiring.** Every classification carries a review date and a default to declassification; secrecy that never lapses is how the conduct of power escapes the openness DATA-08 requires. The schedules track the retention logic of DATA-04.
- **Reviewable.** Whether a seal is still justified is checked by someone other than the party that benefits from it. Self-certified secrecy is not a safeguard; it is a blank check.

**Access control is the same logic at smaller scale.** Inside a system, who may read which record follows the same rule: access granted against a need, scoped to that need, logged, and expiring. "Available to everyone with a login" is not access control; it is the absence of it. The audit trail that makes access answerable is shared with **DATA-15**.

**This is not a license for opacity; it is its containment.** Naming when secrecy is allowed is what keeps it from spreading everywhere. A regime with no legitimate secrets is naive; a regime whose secrets never expire and never face review is the surveillance state's other half — the watchers who cannot themselves be watched. This module permits the first and forbids the second.

*Wager named: that secrecy must be justified, bounded, and time-limited rather than presumed — that the burden falls on closing a record, not on opening it. The opposing view — that effective security and candid deliberation need broad, durable confidentiality, and that frequent review leaks what it examines — is coherent and widely held; this framework does not take it, on the grounds that unbounded secrecy is where unaccountable power lives.*

---
*Next: DATA-10 — Algorithmic & Automated Decisions.*

---

## DATA-10-Algorithmic-and-Automated-Decisions

*Source: `DATA-10-Algorithmic-and-Automated-Decisions.md`*

# DATA-10 — Algorithmic & Automated Decisions
*Civilization Stack · DATA domain · Operational block, module 10.*

Increasingly the decision about a person is made by a system, not a clerk: who gets the loan, the interview, the bail, the benefit, the flag. Data does not just sit in records anymore; it is fed into models that sort, score, and decide. When that decision lands on a person, the question this module answers is simple — can the person reach the thing that judged them?

**Core rule — a decision about a person must be answerable to that person.** An automated decision that affects someone's life must be explainable in terms they can understand, contestable through a real channel, and overridable by a human with the authority to reverse it. The contrast is exact: *not a black box whose output is final because no one can see inside it; a decision a person can question and a human can undo.* A system that decides and cannot be asked why has made the record the authority — the inversion DATA-01 names.

Three requirements carry it:

- **Explainable.** The person can learn the basis of a decision about them — the factors that drove it — in intelligible terms, not a shrug toward proprietary math. A reason you cannot be told is a reason you cannot challenge.
- **Contestable.** There is a real path to dispute the outcome, reaching someone empowered to look again — not an appeal that loops back to the same machine that decided.
- **Human-overridable.** A person retains the authority to set the automated output aside. Automation may advise and may scale; it may not become an authority no one chose, deciding lives with no one able to say no.

**The handoff to TECH, and the line DATA holds.** The model itself — how it is built, trained, and kept controllable — is TECH's domain; the governing mandate is GOV's. DATA's part is narrower and specific: what the *decision* owes the *person*. It does not matter to this module how clever the system is. What matters is that its judgments about people remain seeable, disputable, and reversible.

**This is not a ban on automation; it is a bound on automated authority.** Automated decisions are often faster and more consistent than human ones, and the framework does not forbid them. It forbids the unanswerable version — the decision that is final because it is opaque. Speed and scale are permitted; unaccountability is not.

*Wager named: that automated decisions about people must stay explainable, contestable, and overridable — that efficiency does not buy exemption from answerability. The opposing view — that human review forfeits the consistency and scale automation offers, and that some models cannot be made legible without losing accuracy — is coherent and widely held; this framework does not take it, on the grounds that an authority no one can question is exactly what the Stack exists to prevent.*

---
*Next: DATA-11 — Interoperability & Portability.*

---

## DATA-11-Interoperability-and-Portability

*Source: `DATA-11-Interoperability-and-Portability.md`*

# DATA-11 — Interoperability & Portability
*Civilization Stack · DATA domain · Operational block, module 11.*

A record that only one system can read becomes a record that holds you hostage. Your history, your contacts, your work, your account — if the only copy lives in a format no one else speaks, leaving the service means losing the data, and so you do not leave. Lock-in is rarely announced; it is built quietly, one proprietary format at a time, until the exit is theoretical.

**Core rule — you can leave with your data, and systems can talk without a gatekeeper.** Information is portable in usable form, and the interfaces between systems are open enough that no single holder controls who may connect. The contrast is the design fork: *not a walled garden that keeps your records by making them impossible to take elsewhere; open formats and interfaces that keep the door out real.* This is the Stack's reversibility property (README) applied to data — the same anti-lock-in logic INFRA brings to physical systems (INFRA-09).

Two structures carry it:

- **Portability.** A person or community can export their data in a form another system can actually use, and take it with them. An export that arrives as an unreadable dump, or omits the part that matters, is portability in name only — the standard is whether the data is genuinely usable elsewhere.
- **Interoperability.** Systems exchange information through open, documented interfaces rather than closed ones that let an incumbent decide who connects. Where the interface is the chokepoint, whoever controls it controls the market and the people in it — the concentration DATA-13 and ECON-13 both guard against.

**Lock-in is how a tool becomes an authority.** A service you cannot leave stops being a service you chose and becomes one you are subject to — free to change its terms, raise its price, or alter what it does with your data, because the cost of leaving is losing your record. Portability keeps the relationship voluntary: the exit that stays open is what keeps the holder honest. This is the data form of "nothing too big to leave."

**This is not a demand that everything be public.** Interoperability is about *access by the data's owner and chosen connectors*, not exposure to all comers; portability moves your record to where you direct it, under the same autonomy rules as DATA-02. Open interfaces and open data are different things — this module requires the first without requiring the second.

*Wager named: that data should be portable and interfaces open, so that leaving a system stays possible. The opposing view — that proprietary formats and closed ecosystems fund investment, ensure quality, and protect security, and that mandated openness erodes the incentive to build — is coherent and widely held; this framework does not take it, on the grounds that a system you cannot leave is a system that no longer answers to you.*

---
*Next: DATA-12 — Information Floor.*

---

## DATA-12-Information-Floor

*Source: `DATA-12-Information-Floor.md`*

# DATA-12 — Information Floor
*Civilization Stack · DATA domain · Operational block, module 12.*

To take part in a society, a person needs to know things: what their rights are, how to reach a service, what a record says about them, where a decision came from. When that knowledge is locked behind cost, complexity, or a connection a person does not have, they are shut out — not by a rule that bars them, but by an information gap that does the same work quietly. This module sets the baseline below which no one should fall.

**Core rule — everyone has baseline access to the information needed to participate, and the means to use it.** There is a floor of essential information — and of the access and literacy to read it — beneath the open market in information, never beneath the person. This is the DATA parallel to the provision floor (ECON-12): some things are guaranteed because their absence is an injury, not a preference. To be cut off from the information a society runs on is to be excluded from the society itself.

Two parts carry it:

- **Access to essential information.** The public records, rights, and service information a person needs to function are reachable without a paywall or a privileged connection — findable, free at the point of need, and in plain language. The measurable content lives in **DATA-A3 (Information Floor Standard)**.
- **The means to use it.** Access without the literacy or the connection to act on it is a floor in name only. The floor includes a baseline ability to reach and read essential information — because a right you cannot find and could not understand if you found it is not a right you hold.

**Information poverty is exclusion, not misfortune.** When the people with the least access are the ones who cannot learn their rights, contest a record, or reach a service, the harm lands exactly where DATA-00's first principle forbids it. An information gap is not a neutral fact about who happens to be online; it is a distribution of exclusion, and the floor exists to close it.

**The category is bounded, and stays bounded.** "Essential information" is held narrow — the rights, records, and service knowledge whose absence is an injury — not every fact a person might find useful. As with the essentials rule it parallels (ECON-04), inflating the category would hollow out the guarantee. The floor secures what participation requires, and leaves the open market in information above it.

*Wager named: that baseline access to essential information, and the means to use it, is a floor beneath the market rather than a market outcome — that participation should not be rationed by ability to pay or connect. The opposing view — that information is a good like any other, best provided and priced by the market, and that guaranteed floors are costly and paternalistic — is coherent and widely held; this framework does not take it, on the grounds that exclusion from essential information is exclusion from civic life.*

---
*End of the Operational block (DATA-07 → DATA-12). Next group: Structural Safeguards, beginning with DATA-13 — Anti-Surveillance Firewall.*

---

## DATA-13-Anti-Surveillance-Firewall

*Source: `DATA-13-Anti-Surveillance-Firewall.md`*

# DATA-13 — Anti-Surveillance Firewall
*Civilization Stack · DATA domain · Safeguards block, module 13.*

This is the limit the rest of the domain keeps pointing at. Records drift toward permanence (DATA-04), identities toward unification (DATA-07), classification toward opacity (DATA-09) — and every one of those modules names a firewall that holds the line. This is that firewall: the structural cap on how much any single actor may see, link, and remember about persons.

**Core rule — no actor, public or private, may assemble total visibility into people.** The bar is not "is this watcher behaving well." It is "could this actor, by virtue of how much it can link and retain, build a complete and lasting view of persons" — because by the time that view is abused, the power to prevent it is already assembled. Surveillance is treated as a hazard in itself, before any misuse, the same way ECON-13 treats concentration. The measurable lines — how much may be linked, aggregated, and kept across sources — live in **DATA-A4 (Surveillance & Linkage Thresholds)**.

**Structural, not behavioral.** The standard move is to permit collection without limit and police misuse — let the watching grow, then punish the abuses. This framework refuses that order. Policing misuse fights the symptom and leaves the cause; a system that *can* see everything is one policy change, one breach, or one new owner away from doing so, regardless of today's restraint. The firewall caps the *capacity to watch*, not merely the *conduct*, because structure is what holds when vigilance lapses.

The firewall works by breaking the links surveillance is built from:

- **Aggregation limits.** No single actor combines enough separate streams — location, purchases, communications, health, identity — to reconstruct the whole person. The danger is rarely any one record; it is the join, where harmless fragments become a dossier.
- **Linkage limits.** The partitioned identities of DATA-07 may not be quietly re-linked into one. A society that forbids the master key in name but permits its reassembly by data brokers has kept the form and lost the substance.
- **Persistence limits.** What is watched does not accumulate forever; the retention defaults of DATA-04 are part of the wall, because permanence is what turns observation into a permanent record.

**The state and the market are both inside the wall.** Surveillance does not become safe because a government does it for security, or because a company does it for convenience and profit. The firewall binds both, and binds its own enforcers: an anti-surveillance authority that itself becomes an unaccountable watcher (DATA-14, DATA-15) has reproduced the disease it was built to prevent.

*Wager named: that no actor should be able to assemble total visibility into persons, even where the watching is useful for security, efficiency, or profit. The opposing view — that comprehensive data linkage catches fraud and crime, personalizes services, and powers research, and that the gains outweigh the risk — is coherent and widely held; this framework does not take it, because permanent, pervasive watch is the exact failure the domain exists to prevent.*

---
*Next: DATA-14 — Systemic Oversight.*

---

## DATA-14-Systemic-Oversight

*Source: `DATA-14-Systemic-Oversight.md`*

# DATA-14 — Systemic Oversight
*Civilization Stack · DATA domain · Safeguards block, module 14.*

The firewall (DATA-13) sets the lines; someone has to watch whether the largest data systems stay inside them. A registry holding the records of millions, a platform tracking a population's behavior, a model deciding who gets credit at scale — these are systemic actors, and a limit no one is checking is a limit in name only. This module is the standing watch over data power at scale.

**Core rule — the larger a data system's reach, the more it must show its workings to an outside overseer.** Oversight scales with reach: a small holder owes little, a system that touches a whole population owes continuous, examinable account of what it collects, links, retains, and decides. The threshold for "systemic" — how much reach triggers the duty — tracks the linkage and aggregation lines of **DATA-A4**. Below it, the lighter rules of the core block suffice; above it, the system operates under watch.

**Show the real position, not a summary.** The overseer must be able to see what a systemic system actually holds and does — the scope of its collection, the links it maintains, its retention in practice, the basis of its automated decisions — not a self-flattering report. The standard mirrors ECON-14's demand that systemic economic actors show their true position: disclosure that conceals the part that matters is not oversight, it is its appearance.

**Nothing too big to stop.** A data system can become so embedded that halting it would break the services depending on it — and at that point it has stopped being a tool and become an authority no one can remove. Oversight watches for exactly this: a system that *cannot* be interrupted or unwound (DATA-16) is, for that reason alone, already too entangled, the data form of "too big to fail." Resolvability is a condition of operating at scale, not an afterthought.

**The watchers are watched, and the authority is GOV's.** The oversight bodies renew like everything else (DATA-06) and operate transparently (DATA-15); an overseer that becomes a permanent, unaccountable holder of everyone's data has become the surveillance engine it was meant to bound. And as with ECON, DATA defines *that* systemic data power must be overseen and on *what* terms; *who* holds the enforcing authority — the bodies, the powers, the process — is GOV's to define. DATA builds the requirement; GOV supplies the office.

*Wager named: that data power at scale owes continuous, examinable oversight to those it affects — that size brings scrutiny. The opposing view — that oversight burdens the systems people rely on, slows them, and concentrates sensitive data in the overseer — is coherent and widely held; this framework does not take it, on the grounds that an unwatched system at population scale is unbounded power by default.*

---
*Next: DATA-15 — Transparency & Auditability.*

---

## DATA-15-Transparency-and-Auditability

*Source: `DATA-15-Transparency-and-Auditability.md`*

# DATA-15 — Transparency & Auditability
*Civilization Stack · DATA domain · Safeguards block, module 15.*

A data system you cannot audit is a power operating in the dark. Every safeguard in this domain — the firewall, the oversight, the renewal test — assumes someone can actually check what a system holds and does, and none of them work if the system's own operations are invisible. Visibility is one of the Stack's four load-bearing properties (README), and this module is where data systems are required to provide it.

**Core rule — a data system's operation must be examinable from outside.** It must be possible for an authorized party to see what is collected, why it is held, who has accessed it, how long it is kept, and on what basis it decides. The contrast is the design choice: *not a system whose handling of data is unknowable even to its overseers; a system that keeps a true, inspectable account of what it does.* A system that cannot show its own workings cannot be checked, and a power that cannot be checked is the one the Stack exists to bound.

Two mechanisms carry it:

- **Audit trails.** Who accessed a record, who changed it, who disclosed it, and when — kept so that both error (DATA-05) and abuse can be traced after the fact. An access no one logged is an access no one can question; the trail is what makes the firewall's linkage limits (DATA-13) enforceable rather than aspirational.
- **Legibility of holdings.** What a system holds and why is recorded in a form an overseer can actually read — not buried in undocumented schemas that conceal the substance. Auditability that requires decoding the system's private language is not auditability.

**Auditability is a precondition, not a report.** Disclosure that arrives too late, too vague, or only after a breach is not visibility. The standard is whether an overseer (DATA-14), an affected person (DATA-05), or the public where power is concerned (DATA-08) can see enough, in time, to check the system in question. The measurable forms of that sufficiency are carried by the standards the safeguards reference (DATA-A4); this module sets the requirement they must meet.

**This watches the system, not the person.** The line matters enough to state plainly: auditability targets the *operations of the data system* — what it collects, links, and decides — not the lives of the people inside it. A transparency regime that became a record of every person's every move would have failed the firewall (DATA-13) and the domain's first principle alike. Watching the watcher is the job; the audit log exists to bound power, not to extend it.

*Wager named: that data systems at scale owe an examinable account of their own operation to those who oversee and are affected by them. The opposing view — that audit requirements expose security-relevant internals, burden operators, and create logs that are themselves a surveillance risk — is coherent and widely held; this framework does not take it, on the grounds that a system whose handling of data cannot be seen cannot be bounded.*

---
*Next: DATA-16 — Interruption & Deletion.*

---

## DATA-16-Interruption-and-Deletion

*Source: `DATA-16-Interruption-and-Deletion.md`*

# DATA-16 — Interruption & Deletion
*Civilization Stack · DATA domain · Safeguards block, module 16.*

Renewal handles the ordinary case: a permission's term ends, and it must earn another (DATA-06). This module handles the other case — when something has gone wrong enough that you cannot wait for the term to lapse. It is the domain's stop button: the power to halt a data system or erase its records *for cause*, when the harm is real and waiting is not an option.

**Core rule — every data system must be stoppable, and every record erasable, without the system collapsing around it.** Stoppability is one of the Stack's four load-bearing properties (README), and a data regime honors it only if its systems can actually be halted and its data actually deleted. The corollary is hard: a system whose records *cannot* be deleted, or that cannot be stopped without catastrophe, is for that reason already too entrenched — the over-entanglement DATA-14 forbids. Deletability is not a feature added at the end; it is a condition of being allowed to hold data at scale.

**Deletion must be real, not cosmetic.** This is where DATA-04's expiry becomes enforceable. When a record is to be erased — on expiry, on a lapsed purpose, on a person's valid demand, or for cause — it is genuinely gone: removed from live systems, backups, and the derivations made from it, not merely flagged hidden while the data persists. A "deletion" that leaves the record recoverable in a backup or baked into a trained model has deleted nothing; the standards for what counts as real erasure track **DATA-A1**.

**Interruption is distinct from lapse, and kept distinct on purpose.** Lapse (DATA-06) is neutral and scheduled and proves nothing against anyone. Interruption is active and for-cause: a finding that a system is surveilling past the firewall (DATA-13), holding records it must not, or causing harm it cannot repair, and must be stopped now. Keeping the two paths separate is what stops the emergency power from becoming a routine one — for-cause action must clear a real bar, precisely because it is the sharper tool.

**A stop is itself a power, and bounded like one — and the authority is GOV's.** The power to halt a system or order deletion sits under the same limits as the rest of the domain: due process, transparency (DATA-15), and disrupting no more than the harm requires. A regime that could erase any record or shut any system at will, unchecked, would have relocated the unaccountable power, not removed it. And as throughout, DATA defines *that* systems must be stoppable and records erasable, and on *what* trigger; *who* holds and exercises that authority is GOV's. DATA builds the off-switch into the design; GOV decides whose hand is on it.

*Wager named: that every data system must remain stoppable and its records truly deletable, even at the cost of the convenience and continuity permanence offers. The opposing view — that durable, hard-to-delete records protect against tampering, loss, and evasion, and that easy deletion destroys evidence and accountability — is coherent and widely held; this framework does not take it, on the grounds that data that cannot be deleted is the permanent record the domain exists to prevent.*

---
*End of the Structural Safeguards block (DATA-13 → DATA-16). Next: the External block, DATA-17 — Data Exchange Between Communities.*

---

## DATA-17-Data-Exchange-Between-Communities

*Source: `DATA-17-Data-Exchange-Between-Communities.md`*

# DATA-17 — Data Exchange Between Communities
*Civilization Stack · DATA domain · External block, module 17.*

Everything so far governs information looking inward. This module turns it outward — to data moving between one community and another, across the border where one community's rules stop and another's begin. The border changes who holds the data, how far it travels, and who can reach it. It does not change the rule.

**Core rule — a record's limits travel with it across the border.** Data sent to another community carries its purpose-binding, its retention clock, and its deletion guarantee with it; exchange may not become the channel for doing across a line what would be forbidden within it. The contrast names the evasion exactly: *not a border that launders away the limits — collect under loose foreign rules, retain forever where the clock does not run, link where the firewall does not reach; but limits that bind the data wherever it goes.* A community that keeps its own records bounded while exporting persons' data to where it can be watched freely has not honored the framework — it has offshored the surveillance.

Three limits bind hardest across borders:

- **Purpose survives transfer.** Data shared for one reason may not be repurposed because it crossed into a jurisdiction with weaker rules. The purpose-binding of DATA-03 attaches to the record, not to the territory.
- **Expiry survives transfer.** A retention clock (DATA-04) does not reset to "forever" on export. Sending data somewhere it can be kept permanently is how the permanent record gets built out of sight.
- **The firewall survives transfer.** Personal data may not be exported so that an outside actor can assemble the total view the anti-surveillance firewall (DATA-13) forbids at home. Linkage banned within is not permitted by routing it through a partner.

**Exchange is coordination between communities, judged the same way.** The test for cross-border data flow is the test for all data (DATA-01): legitimate to the degree it lets communities record, coordinate, and serve each other — a shared registry, a public-health signal, an interoperable standard (DATA-11) — and suspect to the degree it merely extends one party's watch over the other's people. The asymmetry of power between communities is exactly where that inversion hides, and the weaker partner's persons are where the harm lands.

**Sovereignty and the long horizon sit elsewhere.** DATA defines the informational conduct of cross-border exchange. The *authority* to make data treaties and bind a community to them is GOV's; the *long-term stewardship* of shared archives and knowledge is held with LT. DATA's claim is narrow and firm: whatever the agreement says, data may not be used to do across a border the surveillance the framework forbids at home.

*Wager named: that data crossing a border carries its purpose, expiry, and firewall limits with it — that you may not export what you may not do. The opposing view — that free data flows power trade, research, and cooperation, and that binding data to its origin's rules fragments the global information commons — is coherent and widely held; this framework does not take it, on the grounds that surveillance offshored is surveillance still.*

---
*End of the External block. Next: the Appendix & Reference block, beginning with DATA-A0 — Appendix & Reference Strategy.*

---

## DATA-A0-Appendix-Reference-Strategy

*Source: `DATA-A0-Appendix-Reference-Strategy.md`*

# DATA-A0 — Appendix & Reference Strategy
*Civilization Stack · DATA domain · Appendix & Reference block, module A0.*

Status: Active scaffold

> Lineage note: the original placeholder framework note for this domain (informational autonomy, purpose-binding, time-limited retention, auditability) has been superseded by the core modules and retained at `99-Archive/DATA-Framework-LEGACY.md`. Its principles are now carried canonically by DATA-00 through DATA-06; this A-series carries the measurable standards behind them.

## Purpose

Defines the appendix, reference, glossary, registry, and standards strategy for the Data domain. It exists to prevent uncontrolled growth and structural fragmentation as the domain expands, and to keep the measurable standards that back the core modules in one predictable place.

## The A-series

The core modules state principles in prose; the A-series carries the measurable standards those principles reference. Each standard backs a specific constraint:

- **DATA-A1 — Retention & Expiry Standard** — behind the retention defaults and real deletion (DATA-04, DATA-16).
- **DATA-A2 — Minimization & Purpose Standard** — behind collection limits and minimal disclosure (DATA-03, DATA-07).
- **DATA-A3 — Information Floor Standard** — behind the information floor (DATA-12).
- **DATA-A4 — Surveillance & Linkage Thresholds** — the measurable lines behind the anti-surveillance firewall and systemic oversight (DATA-13, DATA-14).
- **DATA-A5 — Structural Renewal Review Protocol** — behind renewal logic (DATA-06).

## Naming scheme

- **DATA-A1+** → appendices and measurable standards
- **DATA-R1+** → references and external source material
- **DATA-X1+** → experimental or provisional modules

## Structural questions (open)

- What belongs in a core module versus an A-series standard?
- What stays domain-local versus shared globally across the Stack (especially where DATA-A4 meets ECON-A1 on concentration)?
- How are thresholds versioned as they are revised?
- Which registries — of retention schedules, of systemic-system designations — become authoritative?

## Notes

The A-series is written in a standards register — terse, criteria- and threshold-driven — distinct from the prose voice of the core modules. Where a standard sets numbers, those numbers are provisional until reviewed; the structure is canonical, the specific values are not.

---
*Next: DATA-A1 — Retention & Expiry Standard.*

---

## DATA-A1-Retention-and-Expiry-Standard

*Source: `DATA-A1-Retention-and-Expiry-Standard.md`*

# DATA-A1 — Retention & Expiry Standard
*Civilization Stack · DATA domain · Appendix & Reference block, module A1.*

Status: Standard (provisional values)

## Purpose

Defines what "expires by default" and "really deleted" must mean in operation — the measurable content of the retention rule (DATA-04) and the deletion guarantee (DATA-16). The core modules establish that records expire and deletion is real; this standard sets how a clock is assigned and what counts as erasure, so a guarantee cannot be satisfied in name while failing in fact.

Structure is canonical. The specific retention periods are provisional and set to context (record type, purpose, legal mandate) by the overseeing authority; this document defines how a period is justified and what deletion must achieve, not the final durations.

## I. Assigning a clock

Every record class is assigned, before collection:

1. **A purpose** — the stated reason it exists (DATA-03).
2. **A retention period** — tied to that purpose, not open-ended; the default is the shortest period that serves the purpose.
3. **An expiry action** — deletion, or for narrow named exceptions (DATA-04, DATA-08), transfer to a justified archive.

A record class with no assigned period is non-compliant by default; absence of a clock is not permission to keep forever.

## II. Justifying retention past purpose

Keeping a record beyond its purpose requires an explicit, reviewable basis — legal mandate, active dispute, or named public-interest archive. The basis is recorded, scoped to the specific records, and itself given a review date. "Operationally convenient" and "storage is cheap" are not bases.

## III. What real deletion requires

On expiry or valid demand, erasure reaches:

1. **Live systems** — the working record is removed, not flagged hidden.
2. **Backups** — covered on a defined cycle, so a deleted record does not survive in restore sets.
3. **Derivations** — copies, exports, and downstream shares are propagated to (DATA-05), and material used to train models is addressed rather than ignored.

A deletion that leaves the record recoverable has not occurred.

## IV. Failure conditions

- Record classes with no assigned clock (de facto permanent retention).
- "Deletion" that only hides or de-indexes while the data persists.
- Retention bases that never expire or never face review (DATA-09).
- Backups or model derivations used as a quiet permanent store after live deletion.

## V. Review

Retention periods and the carve-out list are reviewed and renewed (DATA-A5) on a defined cycle. The periods are revisable; the default-to-expiry is not.

---
*Next: DATA-A2 — Minimization & Purpose Standard.*

---

## DATA-A2-Minimization-and-Purpose-Standard

*Source: `DATA-A2-Minimization-and-Purpose-Standard.md`*

# DATA-A2 — Minimization & Purpose Standard
*Civilization Stack · DATA domain · Appendix & Reference block, module A2.*

Status: Standard (provisional values)

## Purpose

Defines how "collect the least that serves the purpose" and "prove what is needed without revealing all you are" are judged in operation — the measurable content of collection limits (DATA-03) and minimal disclosure (DATA-07). The core modules establish that collection is purpose-bound and disclosure minimal; this standard sets the tests that decide whether a given collection or credential meets that bar.

Structure is canonical. What counts as the minimum for a given purpose is set to context by the overseeing authority; this document defines the tests, not the per-case answers.

## I. Necessity test (collection)

For each field collected, the holder can state:

1. **The purpose it serves** — the specific declared reason (DATA-03).
2. **Why the purpose fails without it** — necessity, not usefulness; "might help later" fails.
3. **Why a less identifying form will not do** — a token, a yes/no, or an aggregate in place of a raw identifier where one suffices.

A field that cannot pass all three is excess collection and is not collected.

## II. Minimal-disclosure test (credentials)

A credential or verification satisfies the standard when it returns:

1. **Only the attribute in question** — "is permitted," not the full identity behind it (DATA-07).
2. **Without creating a durable link** — verification that does not, by itself, tie the transaction into a cross-context profile.
3. **Without retention by the verifier** beyond what the check requires (DATA-A1).

## III. Stated-purpose test (notice)

A purpose qualifies as *stated* (DATA-03) only if an ordinary person could, before the fact and in plain language, know what is collected and why. Purpose buried in length, jargon, or bundled consent fails; consent extracted by exhaustion is not consent.

## IV. Failure conditions

- Collection justified by "may be useful" rather than necessity.
- Full-identity disclosure where an attribute would settle the matter.
- Verifiers retaining or linking data beyond the check (DATA-13).
- Purposes too broad, too vague, or too buried to bound reuse.

## V. Review

The per-purpose minimums and notice standards are reviewed and renewed (DATA-A5). The tests are canonical; the case-by-case minimums are provisional.

---
*Next: DATA-A3 — Information Floor Standard.*

---

## DATA-A3-Information-Floor-Standard

*Source: `DATA-A3-Information-Floor-Standard.md`*

# DATA-A3 — Information Floor Standard
*Civilization Stack · DATA domain · Appendix & Reference block, module A3.*

Status: Standard (provisional values)

## Purpose

Defines what counts as adequate baseline access to essential information — the measurable content of the information floor (DATA-12). The core module establishes that a floor of access and the means to use it exists and is unconditional; this standard sets what the floor must actually deliver, so a guarantee cannot be satisfied in name while failing in fact.

Structure is canonical. The specific adequacy levels are provisional and set to context (geography, language, infrastructure) by the overseeing authority; this document defines what must be guaranteed and how adequacy is judged, not the final levels.

## I. Covered information

The floor covers the finite, harm-defined set of DATA-12: a person's rights and the means to exercise them; essential public records and how to reach them; the information needed to access essential services (ECON-12); and the records held about the person themselves (DATA-05). The set is held narrow on purpose; additions require justification on exclusion-harm grounds, not convenience.

## II. Adequacy test

For each covered item, the floor must define and meet:

1. **Reachability** — findable and free at the point of need, without a paywall or a privileged connection.
2. **Intelligibility** — in plain language and accessible formats; information a person cannot understand is not access.
3. **Reach** — actually reaching everyone, including those hardest to serve (low-connectivity, low-literacy, marginalized); coverage gaps are failures, not edge cases.
4. **Usability** — paired with the baseline means and literacy to act on it (DATA-12), not delivered into a vacuum.
5. **Timeliness** — available when the person needs it to act, not after the window has closed.

## III. Failure conditions

- Essential information gated behind cost, login, or connection the worst-off lack.
- Information technically published but unfindable, unreadable, or too late to use (DATA-08).
- Coverage that reaches most but strands those the floor exists for.
- Access provided without the means or literacy to use it — a floor in name only.

## IV. Review

Adequacy levels are reviewed and renewed (DATA-A5) on a defined cycle and adjusted to real conditions. The floor's content is revisable; its unconditional character is not.

---
*Next: DATA-A4 — Surveillance & Linkage Thresholds.*

---

## DATA-A4-Surveillance-and-Linkage-Thresholds

*Source: `DATA-A4-Surveillance-and-Linkage-Thresholds.md`*

# DATA-A4 — Surveillance & Linkage Thresholds
*Civilization Stack · DATA domain · Appendix & Reference block, module A4.*

Status: Standard (provisional values)

## Purpose

Defines the measurable lines behind the anti-surveillance firewall (DATA-13) and systemic oversight (DATA-14): how much an actor may collect, link, aggregate, and retain about persons before it crosses from bounded record-keeping into the assembly of total visibility. The core modules establish that no actor may build a complete, lasting view of people; this standard sets where that line falls and what triggers oversight.

Structure is canonical. The specific thresholds are provisional and set to context by the overseeing authority; this document defines the dimensions measured and the failure conditions, not the final numbers.

## I. Dimensions measured

An actor's surveillance weight is assessed across, at minimum:

1. **Aggregation** — how many distinct, sensitive streams about the same persons it combines (location, communications, purchases, health, identity).
2. **Linkage** — its ability to re-tie partitioned identities (DATA-07) into a single profile, directly or via brokered joins.
3. **Persistence** — how long it retains person-level data and history (DATA-04, DATA-A1).
4. **Reach** — the share of a population it can observe.

These are assessed together: harmless streams individually can constitute total visibility once joined.

## II. The firewall lines (DATA-13)

Hard caps — not for crossing at any utility:

- No actor combines streams past the aggregation cap such that a near-complete profile of persons becomes reconstructable.
- Re-linkage of partitioned identities beyond the linkage cap is prohibited, including via third-party brokers.
- Person-level data retained past its expiry (DATA-A1) counts against persistence regardless of where it is held (live, backup, model).

## III. The oversight threshold (DATA-14)

An actor crossing the *systemic* line on reach or aggregation enters standing oversight: it must show its true collection, linkage, retention, and automated-decision basis to an external overseer (DATA-15), and must demonstrate it remains interruptible and its records deletable (DATA-16). Below the line, the core-block rules suffice.

## IV. Failure conditions

- Linkage limits met internally but defeated by routing through brokers or partners (DATA-17).
- Aggregation assessed stream-by-stream, ignoring the profile the join creates.
- Systemic actors below nominal caps but un-interruptible in practice ("too big to stop").
- Thresholds applied to private actors but not to state systems, or vice versa.

## V. Review

The thresholds are reviewed and renewed (DATA-A5) on a defined cycle. The dimensions and failure conditions are canonical; the specific lines are provisional and coordinated, where relevant, with ECON-A1 on concentration.

---
*Next: DATA-A5 — Structural Renewal Review Protocol.*

---

## DATA-A5-Structural-Renewal-Review-Protocol

*Source: `DATA-A5-Structural-Renewal-Review-Protocol.md`*

# DATA-A5 — Structural Renewal Review Protocol
*Civilization Stack · DATA domain · Appendix & Reference block, module A5.*

Status: Standard (provisional values)

## Purpose

Defines the procedure by which standing data authority is reviewed for renewal — the machinery behind renewal logic (DATA-06). DATA-06 establishes that authority to hold and use data defaults to expiration and must earn continuation; this protocol sets what a holder must demonstrate, how the review runs, and what happens when evidence is absent.

The protocol mirrors the Stack's wider renewal-evidence approach: continuation requires affirmative demonstration, and absence of evidence defaults to non-renewal.

## I. What is subject to review

Per DATA-06: consents and the permissions built on them; access grants to records, especially personal and sensitive data; retention bases (DATA-04); the operating authority of data systems at scale; and the mandates of the oversight bodies themselves. Nothing is exempt, including this protocol.

## II. Renewal evidence (the test from DATA-06)

To renew, an authority must demonstrate, with documented evidence, that it:

1. **Still serves its stated purpose** (DATA-01, DATA-03) — not merely persists.
2. **Collects and keeps no more than that purpose requires** (DATA-A1, DATA-A2).
3. **Has not crossed the surveillance and linkage lines** (DATA-13, DATA-A4).
4. **Remains auditable, stoppable, deletable, and answerable** to the people it describes (DATA-05, DATA-15, DATA-16).

Absence of documented evidence in any one of these defaults to non-renewal. The burden is on the authority to prove *for* continuation, never on others to prove *against* it.

## III. Lapse versus for-cause removal

- **Lapse** — a permission ending for failed or absent renewal. Neutral, scheduled, no finding of wrongdoing (DATA-06). The ordinary default.
- **For-cause removal** — active interruption or forced deletion mid-term on a finding of harm (DATA-16). A separate, sharper path with a higher bar.

This protocol governs lapse. It hands the for-cause path to DATA-16, and the authority to act in either case to GOV.

## IV. Failure conditions

- Renewal granted by inertia, without affirmative evidence ("the system is too embedded to stop").
- Burden inverted — requiring proof against a holder rather than proof from it.
- Oversight bodies exempting their own mandates from review.
- Cumulative scope creep — collection or linkage expanding step by step, each move passed over as minor.

## V. Review

The protocol is itself reviewed and renewed on a defined cycle. A renewal procedure that exempted itself from renewal would fail the first test it sets (DATA-06).

---
*End of the DATA Appendix & Reference block (DATA-A0 → DATA-A5).*

---

## DATA-Framework

*Source: `DATA-Framework.md`*

# DATA --- Information Governance Framework (SCBP Implementation)

Purpose: Protect informational autonomy and ensure responsible data
governance.

Principles: - Individuals retain fundamental rights over personal
data. - Data collection must be purpose-bound. - Data retention must be
time-limited. - Data systems must remain auditable.

Safeguards: - algorithm transparency requirements - public records
accessibility - protection from indefinite data indexing

---

## DATA-MASTER

*Source: `DATA-MASTER.md`*

# 1. Purpose

The Data domain defines the operational rules governing how information is collected, retained, accessed, disclosed, and acted on across civilization-scale systems.

Its purpose is not to study information technology as a discipline, but to define the actual constraints on information power required for long-term civilizational continuity within the limits established by BPF.

The domain establishes:

- what information systems are for
- how data stays bound to the purpose it was collected for
- how records expire instead of persisting forever
- how the people described by data retain standing over it
- how automated decisions remain answerable to the people they affect
- how surveillance is walled off before it concentrates into permanent watch

The Data domain exists to ensure that a civilization can remember and coordinate without converting memory into a cage — without letting records outlive their purpose, escape correction, or assemble into a view of people so total that it can no longer be switched off.

---

# 5. Structural Principles

Every DATA module operates under these principles:

- Harm is prevented and repaired before information is collected or acted on.
- Data is collected for a stated purpose and used only for it.
- Records expire by default; permanence is the exception that must be justified.
- The person a record describes retains standing to see, correct, and limit it.
- Data systems stay interruptible, reversible, auditable, and deletable.
- No actor assembles total visibility into persons.
- Visibility scales with power; privacy scales with the person.

---

# 7. Current Module Structure

DATA-00 is the canonical spine; this list reconciles to it. Module titles and cross-references are fixed by the modules themselves.

## Core block (00–06)

- DATA-00 — Purpose and Scope
- DATA-01 — What Data Is For
- DATA-02 — Personal Data and Autonomy
- DATA-03 — Collection and Purpose Limits
- DATA-04 — Retention and Expiry
- DATA-05 — Records, Access and Correction
- DATA-06 — Renewal Logic

## Operational block (07–12)

- DATA-07 — Identity and Credentials
- DATA-08 — Public Records and Open Information
- DATA-09 — Classification and Access Control
- DATA-10 — Algorithmic and Automated Decisions
- DATA-11 — Interoperability and Portability
- DATA-12 — Information Floor

## Structural Safeguards block (13–16)

- DATA-13 — Anti-Surveillance Firewall
- DATA-14 — Systemic Oversight
- DATA-15 — Transparency and Auditability
- DATA-16 — Interruption and Deletion

## External block (17)

- DATA-17 — Data Exchange Between Communities

## Appendix & Reference block (A0–A5)

- DATA-A0 — Appendix and Reference Strategy
- DATA-A1 — Retention and Expiry Standard
- DATA-A2 — Minimization and Purpose Standard
- DATA-A3 — Information Floor Standard
- DATA-A4 — Surveillance and Linkage Thresholds
- DATA-A5 — Structural Renewal Review Protocol

## Planned Future Modules

Further modules may be added as the stack matures, including: data commons and shared-knowledge governance, breach and shock response, provenance and authenticity of records, and inter-domain data coordination. Additional references (DATA-R series) and experimental modules (DATA-X series) may be added per the strategy in DATA-A0.

---

## README

*Source: `README.md`*

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

