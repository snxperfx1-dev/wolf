# MEGATRON V71 / V72 / V73 — ENGINE 1A CONSTITUTION

> **Status:** Specification only. No code. This document defines *what the system
> believes about the market*. Implementation follows only after the full
> constitution (Parts 1–16) is ratified.
>
> **Authority rule:** Engine 1A is the single lifecycle authority. Every other
> subsystem is a *consumer*. Nothing outside Engine 1A may classify a phase.
>
> **Reading order:** Part 1 is the foundation. Every later Part inherits its
> definitions verbatim. If a later Part contradicts Part 1, Part 1 wins until
> Part 1 is formally amended.

---

# PART 1 — MARKET ONTOLOGY

*The foundational layer. This Part answers a single question: **what are the
things Engine 1A reasons about?** It does not describe detection, code, or
thresholds. It defines the entities, their nature, and the laws that bind them.
Parts 2–16 are forbidden from introducing any entity not grounded here.*

---

## 1.0 — Purpose and Scope of Part 1

Before the engine can classify anything, the meaning of every word it uses must
be fixed. The audit of the existing implementation revealed the root disease:
**vocabulary was created at the point of detection rather than at the point of
meaning.** Labels such as "Weak Expansion", "M1 Convexity", and "Dominant Phase"
were invented by individual detectors, each with its own private definition.
The result is an engine that *names* the market in many incompatible languages
and therefore *understands* it in none.

Part 1 eliminates this by establishing one ontology — one set of entities, one
definition per entity, one law per relationship. After Part 1, the words
"wave", "phase", "evidence", "structure", "momentum", "physics", "energy",
"capacity", "transfer", "destination", and "regeneration" each have exactly one
meaning, and that meaning is binding on the entire V71/V72/V73 stack.

Scope of Part 1:

- Defines the **market** as a system.
- Defines the **wave** as the fundamental unit of market behaviour.
- Defines the **lifecycle phase** as a *state of being* of a wave.
- Defines **evidence** and separates it permanently from **classification**.
- Defines the three **dimensions** of evidence — Structure, Momentum, Physics.
- Defines the cross-cutting concepts that bind the dimensions: **energy**,
  **capacity**, **participation transfer**, **destination completion**,
  **regeneration**.
- States the **confluence principle** and the **invariants** that all later
  Parts must honour.

Out of scope for Part 1 (assigned to later Parts):

- Persistent structural objects and their lifecycle → Part 2 & Part 5.
- The exact evidence variables for each dimension → Parts 2, 3, 4.
- The phase activation matrix → Part 7.
- Transitions, hysteresis, anti-flicker → Part 8 & Part 15.
- Progress / confidence / integrity math → Part 10, Part 19-equivalent.

---

## 1.1 — The Market as an Energy System

**Axiom 1 — The market is not a price series. It is an energy-resolution
system that *expresses itself* through price.**

Price is the *shadow* of the process, not the process. The process is the
generation, distribution, and resolution of directional energy by participants
competing for control. Engine 1A reasons about the **process**; price is merely
one observable consequence of it.

From this axiom, three properties follow:

1. **Conservation of attention.** Energy spent creating a move is not free. A
   directional expansion consumes participation, liquidity, and conviction.
   What is consumed must later be replenished or surrendered. There is no
   perpetual expansion.

2. **Directionality is temporary control, not permanent truth.** "Bullish" and
   "bearish" describe *who currently holds control of the energy system*, not a
   property of the instrument. Control is always contestable and always
   eventually contested.

3. **Resolution is mandatory.** Every generation of energy (an expansion) must
   resolve — either by *delivery* (reaching a destination and completing) or by
   *transfer* (control passing to the opposing side). A wave cannot remain
   unresolved indefinitely; unresolved energy is a debt the market must pay.

**Axiom 2 — The market moves through three dimensions simultaneously:
Structure, Momentum, and Physics.** These are not three views of one thing; they
are three independent *aspects of the same instant*. A market condition is only
real when all three describe it consistently. This is the seed of the confluence
principle (§1.13) and the entire reason Engine 1A exists.

---

## 1.2 — What a Market Wave Is

**Definition (Wave).** A *wave* is a bounded episode of directional energy
expression that possesses an **origin**, a **direction of control**, a
**lifecycle**, and a **resolution**. It is the fundamental unit Engine 1A
reasons about. The market is, at every instant, *inside exactly one wave per
timeframe degree.*

A wave is **not**:

- a candle,
- a swing leg,
- an impulse,
- a single BOS event.

Those are *evidence about* a wave (Part 2), not the wave itself.

A wave has the following intrinsic properties:

- **Origin.** The price/level from which the wave launched and which defines its
  survival. The origin is the wave's *birth certificate* and its *invalidation
  line* at once. While price respects the origin, the wave lives. When price
  decisively breaches the origin, *that wave is dead and a new, opposite-control
  wave has been born.* This is the formal basis of the direction rule already
  implemented: **price above origin → bullish wave; origin breached → a bearish
  wave now exists** (and symmetrically). Direction is therefore not a guess — it
  is the *identity of the currently living wave* relative to its origin.

- **Direction of control.** Which side (demand/supply) currently owns the
  energy system within this wave. A wave has exactly one direction of control at
  a time; a change of control *is the death of one wave and the birth of
  another*, never a "reversal of the same wave."

- **Objective.** The destination the wave is attempting to deliver price to (a
  prior extreme, a liquidity pool, a structural target). A wave is *purposeful*;
  it is trying to get somewhere. Objective completion is defined in §1.11.

- **Lifecycle.** The ordered sequence of *phases* the wave passes through from
  birth to resolution (§1.3, formalised in Part 6).

- **Resolution.** The terminal condition: either *completion* (objective
  delivered, energy spent, return/regeneration begins) or *transfer* (control
  lost to the opposing side). Every wave resolves.

**Birth, life, death.** A wave is *born* at an origin when control is
established. It *lives* through its lifecycle phases while control persists and
the origin holds. It *dies* when either the origin is breached (control lost) or
its objective completes and energy fully resolves. Death of a wave is always the
birth of the next.

**Recursion.** Waves exist at every timeframe degree (Part 11, Part 12). A
higher-degree wave *contains* lower-degree waves. A lower-degree wave's death may
be merely a *phase* of its parent. Engine 1A's authority resides at one degree
(M5); other degrees are consumers that *inherit* lifecycle meaning and report
their own waves as context, never as competing authorities.

---

## 1.3 — What a Lifecycle Phase Is

**Definition (Phase).** A *lifecycle phase* is a **state of being of a living
wave** — a description of *what the wave is currently doing* in its journey from
origin to resolution. A phase is an *interpretation of the wave's condition*,
established only when Structure, Momentum, and Physics **simultaneously** agree
that the wave is in that condition.

A phase is **not**:

- a label printed when one detector fires,
- a score crossing a threshold,
- an event (a BOS is not a phase; it is evidence),
- a momentum reading (a slowing oscillator is not "Absorption"),
- a name owned by any single dimension.

**The cardinal law of phase (the reason this constitution exists):**

> A phase exists **only** when Structure ∧ Momentum ∧ Physics describe the same
> condition. Any one dimension alone is insufficient. Any two dimensions
> together are insufficient. All three must agree.

This is what "3-dimensional" means precisely. The current implementation is
1-dimensional with a momentum tint (structure state machine + momentum overlay);
it is, by this definition, **not classifying phases at all** — it is *labelling
structural events*. Part 7 will encode the exact tri-dimensional requirement for
each canonical phase; Part 1 only fixes the *nature* of a phase: it is a
**consensus condition**, not an event.

**The canonical lifecycle (named here, architected in Part 6):**

```
Point4Origin
  → Expansion
      → ExpansionPreConvexity
          → ExpansionInduction
              → ExpansionLiquidity
                  → NewHigh / NewLow
                      → Absorption
                          → Retracement
                              → RetracementPreConvexity
                                  → RetracementInduction
                                      → RetracementLiquidity
                                          → DemandReturn / SupplyReturn
```

These fourteen names are the **only** lifecycle vocabulary permitted anywhere in
the stack. No detector, panel, or timeframe may invent, abbreviate, or
sub-classify them. (Display abbreviation for on-chart space — e.g. "EXP" — is a
*rendering* concern, not a vocabulary; the underlying state is always one of the
fourteen.)

---

## 1.4 — What Evidence Is

**Definition (Evidence).** *Evidence* is an observation about the wave's
condition produced by one dimension (Structure, Momentum, or Physics). Evidence
is **descriptive**, **dimensional**, and **non-authoritative**. Evidence
*describes*; it never *decides*.

The permanent separation:

- **Evidence** answers: *"What does this dimension observe right now?"*
  (e.g. "Structure observes that BOS1 has occurred and expansion is intact.")
- **Classification** answers: *"What phase is the wave in?"*
  Classification is the exclusive act of Engine 1A, performed **only** by
  combining evidence from all three dimensions.

**The forbidden shortcut.** No evidence item may be wired directly to a phase.
"BOS1 → ExpansionPreConvexity" is forbidden. "absScore > 40 → Absorption" is
forbidden. "induction break → NewHigh" is forbidden. These are *event→label*
shortcuts; they bypass confluence and are the precise defect the constitution
abolishes. An event raises *evidence*; the phase only changes if the other two
dimensions corroborate (Part 7).

**Properties of evidence:**

1. **Owned by one dimension.** Each evidence item belongs to exactly one of
   Structure / Momentum / Physics. It never spans dimensions.
2. **Boolean or graded, but never a phase.** Evidence may be a flag
   ("expansion intact") or a magnitude ("efficiency decaying by X"), but it is
   never itself a lifecycle state.
3. **Persistent or instantaneous.** Some evidence is an event (instantaneous —
   a BOS). Some is a standing condition (persistent — "induction extreme
   exists"). Persistence rules are defined in Part 5.
4. **Falsifiable.** Evidence can be withdrawn. If the condition that raised it
   ceases, the evidence ceases. Stale evidence is forbidden (Part 5, Part 15).

---

## 1.5 — What Structure Is

**Definition (Structure).** *Structure* is the dimension of **persistent
geometric objects** the market leaves behind as it expresses energy: origins,
protected swings, breaks of structure, induction objects, extremes. Structure is
the **skeleton** — the durable record of where control was established, defended,
and broken.

Structure answers: *"Where are the levels that define this wave's identity and
survival, and which of them have been respected or violated?"*

Structure provides **evidence only** — e.g. *expansion intact*, *first break of
structure has occurred*, *a counter-structure is developing*, *the induction
extreme exists*, *the origin has been breached*, *the objective is complete*,
*control has been lost*. (The exact object set and their persistence are the
subject of Part 2 and Part 5.)

Structure is necessary but **never sufficient** to assign a phase. A BOS tells
you the skeleton moved; it does not tell you whether momentum and physics agree
that the wave has *changed condition*. Structure alone is a map of bones, not a
description of life.

---

## 1.6 — What Momentum Is

**Definition (Momentum).** *Momentum* is the dimension of **the rate and quality
of energy expression** — how forcefully, efficiently, and sustainably control is
currently being exercised. Where Structure is the skeleton, Momentum is the
**muscle**: the present exertion of the controlling side.

Momentum answers: *"How strong, efficient, and sustainable is the current
exertion of control — and is the opposing side beginning to participate?"*

Momentum is composed of sub-aspects (efficiency, velocity, acceleration,
participation, counter-flow, decay, impulse, exhaustion, transfer, compression —
detailed in Part 3). Each contributes **evidence only** — e.g. *expansion
strong*, *expansion weakening*, *counter-participation growing*, *exhaustion
developing*, *acceleration returning*, *retracement dominant*, *regeneration
developing*.

Momentum is necessary but **never sufficient**. A slowing oscillator is not
Absorption; it is *evidence of decay*. Whether the wave is absorbing depends on
whether Structure says the objective is complete and Physics says capacity is
collapsing. Momentum alone is exertion without context.

---

## 1.7 — What Physics (Orderflow Physics) Is

**Definition (Physics).** *Physics* is the dimension of **the orderflow forces
acting on the wave** — the attraction toward destinations, the exhaustion and
regeneration of energy, the rotation of control between degrees, the integrity
and maturity of the move, the consumption of geometric capacity, and the
probability of return. Where Structure is the skeleton and Momentum is the
muscle, Physics is the **field of forces** the wave moves within.

Physics answers: *"What forces are acting on this wave — is it being pulled to a
destination, is its energy healthy or collapsing, is control rotating, is its
capacity nearly spent, is regeneration forming?"*

Physics is supplied by the V72/V73 engines (all detailed in Part 4):

- **FRZ** — destination distance, zone penetration, attraction, rejection.
- **EAE** — energy exhaustion, acceleration, collapse, regeneration.
- **RE** — rotation state, rotation transfer, rotation completion.
- **EDE** — expansion integrity, dominance, energy distribution, balance.
- **DOM** — participation imbalance, control transfer, liquidity imbalance.
- **Geometric Capacity** — capacity utilisation, capacity collapse, convexity
  maturity.
- **Integrity Engine** — wave / structural / expansion integrity.
- **Maturity Engine** — wave / transfer / liquidity maturity.
- **Future Return Engine** — probability of regeneration, destination
  completion, return potential.

Each yields **evidence only** — e.g. *expansion healthy*, *transfer developing*,
*liquidity present*, *control restored*, *capacity declining*, *retracement
dominant*, *regeneration present*.

**The mandatory-participation law.** Physics is **not optional**. In the current
implementation physics is computed but *never consulted when classifying phase* —
this is a constitutional violation. Under this constitution, **no phase may
activate without the corresponding physics evidence present** (Part 7). Physics
is necessary; like the other two, it is **never sufficient alone**.

> *Implementation consequence (recorded here, executed in Part 4 + Part 7):*
> because the physics engines currently compute downstream of the phase, the
> code must be reordered so that Structure-evidence, Momentum-evidence, and
> Physics-evidence are **all available before** Engine 1A classifies. This is the
> central refactor obligation created by Part 1.

---

## 1.8 — Participation Transfer

**Definition (Participation Transfer).** *Transfer* is the process by which
**control of the energy system passes from the side currently in control to the
opposing side.** It is the single most important cross-dimensional concept,
because the entire back half of the lifecycle (Induction → Liquidity →
Absorption → Retracement → Return) is the *story of a transfer*.

Transfer is observed across all three dimensions at once:

- **Structurally** as counter-structure developing (counter BOS, induction
  objects forming against the controlling side).
- **In momentum** as counter-participation growing while the controlling side's
  efficiency and impulse decay.
- **In physics** as rotation developing (RE), participation imbalance shifting
  (DOM), and integrity weakening (Integrity Engine).

Transfer is **graded and directional**: it *begins*, *grows*, *matures*, and
*completes*. A phase late in the expansion half (e.g. ExpansionInduction)
corresponds to transfer *beginning/growing against* the controlling side; a
phase in the retracement half corresponds to transfer having *matured or
completed*. Transfer is the connective tissue between phases and is never, by
itself, a phase — it is evidence that contributes to phase classification.

---

## 1.9 — Energy

**Definition (Energy).** *Energy* is the **finite directional conviction
available to the controlling side** to extend a wave toward its objective.
Expansion *spends* energy; absorption and retracement reflect energy *depletion*;
demand/supply return reflects energy *regeneration*.

Laws of energy (consequences of Axiom 1):

1. **Energy is created in expansion and consumed by distance.** The farther a
   wave travels from origin, the more energy it has spent.
2. **Energy is finite per wave.** A wave cannot expand forever; spent energy
   must be regenerated (return) or surrendered (transfer).
3. **Energy state is observable through physics**, principally EAE (exhaustion /
   acceleration / collapse / regeneration) and EDE (distribution / balance).
4. **Energy is not direction.** A wave can have low energy and still hold
   control (a tired but unbroken bull wave). Energy describes *capacity to
   continue*, not *who is in control*.

---

## 1.10 — Capacity

**Definition (Capacity).** *Capacity* is the **remaining geometric and
energetic room a wave has to continue its current phase before it must
transition.** Where energy is conviction, capacity is *room to express it*.

- **Geometric capacity** — how much of the structural room toward the objective
  remains versus has been consumed (Geometric Capacity engine, Part 4).
- **Convexity maturity** — how far the wave has progressed along its natural
  curvature from impulsive expansion toward exhaustion.
- **Capacity collapse** — the condition in which little room remains; a strong
  precursor (physics-side) to Absorption and Return.

Capacity is the backbone of **true progress** (Part 10): progress through a phase
is the *consumption of capacity*, not a static percentage. A wave that has
consumed 90% of its geometric capacity toward objective is *near completion*
regardless of how long it has lasted in time.

---

## 1.11 — Destination and Destination Completion

**Definition (Destination).** A *destination* is the **objective level the wave
is being drawn toward** — a prior extreme, a liquidity pool, or a structural
target. Destinations are supplied by physics (principally FRZ attraction and the
destination engine) and are the *purpose* the wave is trying to fulfil.

**Definition (Destination Completion / Objective Completion).** A destination is
*completed* when price **reaches and resolves** it — the objective the wave set
out to deliver has been delivered. Completion is observed when:

- **Structurally** the objective level is reached/exceeded (induction origin
  broken, prior extreme taken).
- **In momentum** acceleration returns to deliver, then participation normalises.
- **In physics** rotation completes, integrity is restored, the liquidity cycle
  closes, and Future Return probability rises.

Completion is the hinge of the lifecycle: it separates the *creation* half
(Expansion → NewHigh/NewLow) from the *resolution* half (Absorption → Return).
NewHigh/NewLow is the moment of delivery; Absorption is the immediate aftermath;
Return is the regeneration that follows. Completion is **never** declared from a
single dimension — reaching a level alone (structure) without physics confirming
the cycle closed is *not* completion, merely a touch.

---

## 1.12 — Regeneration

**Definition (Regeneration).** *Regeneration* is the **rebuilding of directional
energy after a wave has completed its objective and resolved** — the process by
which a new wave is seeded from a return to demand or supply. It is the lifecycle
closing into a new beginning (DemandReturn / SupplyReturn → a new Point4Origin).

Regeneration is observed through physics (EAE regeneration, Future Return
probability rising, Integrity restored) corroborated by structure (price
returning to and respecting an origin/zone) and momentum (acceleration returning
in the original direction). Regeneration is what makes the lifecycle a **cycle**
rather than a line: the death of one wave at its return zone is the conception of
the next.

---

## 1.13 — The Confluence Principle

This is the constitutional core, stated once, binding on every later Part:

> **A lifecycle phase is real if and only if Structure, Momentum, and Physics
> independently produce evidence describing the same condition, simultaneously.**

Formally, for any phase `P`:

```
Phase = P   ⇔   Structure-evidence(P)  ∧  Momentum-evidence(P)  ∧  Physics-evidence(P)
```

Corollaries:

- **C1.** No single dimension may assign `P`. (Structure-only, Momentum-only,
  Physics-only are all invalid.)
- **C2.** No pair may assign `P`. (S∧M, S∧P, M∧P are all invalid.)
- **C3.** Events raise evidence, never phases. (No event→phase shortcut.)
- **C4.** Scores/thresholds may *grade evidence strength*, but a threshold
  crossing may never *be* a phase.
- **C5.** When the three dimensions disagree, the phase **does not change** — the
  wave remains in its prior phase, and the disagreement is surfaced as reduced
  **confidence** (§1.14, Part 19-equivalent), not as a new label. This is the
  seed of anti-flicker (Part 15).

---

## 1.14 — Derived Outputs (defined in nature here, computed later)

Part 1 fixes the *meaning* of Engine 1A's three derived outputs; their formulas
belong to later Parts.

- **phaseConfidence** — the **degree of agreement** among Structure, Momentum,
  and Physics for the currently active phase. Full tri-dimensional agreement →
  high confidence; partial agreement → lower confidence. It is *agreement
  quality*, **never** a score threshold. (Math: Part 19-equivalent / Part 10.)

- **phaseIntegrity** — **how healthy the current phase is** while it is active:
  whether the conditions that justified it remain robust or are decaying. It is a
  *health measure*, not a probability. (Math: Part 4 Integrity + Part 10.)

- **phaseProgress** — **how far the wave has travelled through the current
  phase**, derived from *capacity consumed, energy expended, maturity developed,
  transfer completion, and destination distance* — continuous and live, **never**
  a static 25/50/75 lookup. (Math: Part 10.)

Plus the identity outputs already grounded above: **waveDirection** (§1.2, the
origin-relative identity of the living wave), **currentPhase** (§1.3, one of the
fourteen), **phaseAge** (time/bars since the current phase activated),
**structureState / momentumState / physicsState** (the per-dimension evidence
summaries).

---

## 1.15 — Invariants (binding on Parts 2–16)

1. **One authority.** Only Engine 1A (resident at M5) classifies phase. All
   other timeframes/degrees are consumers (Part 11, Part 12).
2. **One vocabulary.** Only the fourteen canonical phases (§1.3) exist anywhere.
3. **Evidence ≠ phase.** Every detector outputs evidence; none outputs a phase.
4. **Tri-dimensional confluence.** No phase without S ∧ M ∧ P (§1.13).
5. **No event→phase shortcuts.** (C3.)
6. **No threshold→phase shortcuts.** (C4.)
7. **Physics is mandatory**, not decorative (§1.7).
8. **Progress/Confidence/Integrity are dynamic**, never static lookups (§1.14).
9. **Stability over reactivity.** Disagreement holds the prior phase and lowers
   confidence; it never flickers a new label (C5, Part 15).
10. **Death = birth.** A change of control is the death of one wave and the
    birth of an opposite-control wave, not a "reversal of the same wave" (§1.2).

---

## 1.16 — Glossary (terms fixed by Part 1)

- **Market** — an energy-resolution system expressed through price (§1.1).
- **Wave** — a bounded episode of directional energy with origin, control,
  lifecycle, objective, resolution (§1.2).
- **Origin** — the wave's birth level and invalidation line (§1.2).
- **Phase** — a state of being of a living wave, valid only under confluence
  (§1.3).
- **Evidence** — a dimensional observation; descriptive, non-authoritative
  (§1.4).
- **Structure** — persistent geometric objects; the skeleton (§1.5).
- **Momentum** — rate/quality of energy expression; the muscle (§1.6).
- **Physics** — orderflow forces acting on the wave; the field (§1.7).
- **Participation Transfer** — passing of control between sides (§1.8).
- **Energy** — finite directional conviction (§1.9).
- **Capacity** — remaining room to continue the current phase (§1.10).
- **Destination / Completion** — the objective and its delivery (§1.11).
- **Regeneration** — rebuilding of energy into a new wave (§1.12).
- **Confluence Principle** — S ∧ M ∧ P assigns phase; nothing else (§1.13).

---

## End of Part 1

**Part 1 establishes the ontology. Nothing in Parts 2–16 may introduce an entity
or vocabulary not grounded here.**

**Next:** *Part 2 — Structural Ontology* — the persistent structural objects
(Point4Origin, ProtectedSwing1/2, BOS1/BOS2, InductionOrigin, InductionExtreme,
InductionOriginBreak, ExpansionExtreme, CompletionExtreme), their creation
conditions, persistence laws, and the **structure-evidence** outputs they emit —
strictly as evidence, never as phase.

*Awaiting ratification of Part 1 before drafting Part 2.*



---

# PART 2 — STRUCTURAL ONTOLOGY

*The skeleton. This Part defines the **persistent geometric objects** the market
leaves behind as it expresses energy, the laws governing their creation,
persistence, inheritance, and destruction, and the **structure-evidence** they
emit. Every entity here is grounded in Part 1 §1.5 (Structure) and obeys Part 1
§1.4 (evidence is descriptive, never a phase) and §1.15 (the invariants).*

> **Binding restatement.** Structure produces **evidence only**. No object in
> this Part, and no event involving it, may assign a lifecycle phase. A break of
> structure is not "Pre-Convexity"; it is *evidence* that the other two
> dimensions may corroborate (Part 7). This Part is forbidden from naming any of
> the fourteen canonical phases as an output.

---

## 2.0 — Purpose and Scope of Part 2

Part 1 declared *that* structure exists and is the skeleton. Part 2 specifies
*which bones exist*, *how each is created*, *how long it lives*, *what kills it*,
and *what evidence it contributes*. It establishes the structural half of the
input contract that Engine 1A's confluence gate (Part 7) will consume.

Scope of Part 2:

- The **persistent structural objects** and their precise definitions.
- The **creation law** for each object (what brings it into existence).
- The **persistence law** for each object (what keeps it alive; cross-ref Part
  5 for the general persistence machinery).
- The **destruction/replacement law** for each object.
- The **inheritance law** (how lower-degree structure relates to the M5
  authority's structure; cross-ref Part 11).
- The **structure-evidence outputs** — the only things Structure is permitted to
  expose to Engine 1A.

Out of scope (delegated):

- The generic create/persist/destroy/inherit *machinery* → Part 5.
- Momentum and physics evidence → Parts 3, 4.
- How structure-evidence combines with the other dimensions → Part 7.
- Recursive-degree restrictions → Part 11; timeframe span → Part 12.

---

## 2.1 — The Nature of a Structural Object

**Definition (Structural Object).** A *structural object* is a **named,
persistent level or level-pair** that records a specific act of control —
establishment, defence, break, or completion — within a wave. Each object has:

- an **identity** (which of the named objects it is),
- an **anchor** (the price level(s) and the bar at which it was fixed),
- a **lifespan** (from creation to destruction/replacement),
- an **owner wave** (the wave whose lifecycle it belongs to),
- a **directional polarity** (whether it serves the bullish or bearish reading).

Structural objects are **discrete and few**. The skeleton is intentionally
sparse: a small set of high-meaning levels, not a cloud of pivots. Pivots and
swings in the raw sense are *raw material*; a structural object is a pivot that
has been *promoted* by satisfying a creation law.

**Object vs. event.** A structural object is *persistent* (it stands until
destroyed). A structural *event* is *instantaneous* (the moment an object is
created or broken). Both are evidence (Part 1 §1.4), but they differ in
temporality: the *break of BOS1* is an event; the *existence of BOS1* is a
standing object. Part 5 formalises how events become standing evidence and how
standing evidence decays.

---

## 2.2 — The Persistent Structural Objects

The complete and **closed** set. No structural object exists outside this list.

### 2.2.1 — Point4Origin

**Definition.** The **origin of the current wave** — the level/zone from which
control was established and which defines the wave's survival (Part 1 §1.2).
"Point 4" denotes its place in the structural sequence that births a wave (the
origin order block / launch zone).

- **Creation law.** Created at wave birth, when control is established and a new
  wave is spawned. Its anchor is the launch zone (origin high / origin low) and
  the spawn bar. It is the **first** object of every wave.
- **Persistence law.** Persists for the entire life of the wave. It is the
  wave's identity; it does not move during the wave's life.
- **Destruction law.** Destroyed when the wave dies — either by **origin breach**
  (price decisively closes beyond it against the controlling side → control lost
  → §2.2.9) or by **completion-and-resolution** that spawns the next wave. On
  destruction, the next wave's Point4Origin is created (death = birth, Part 1
  §1.2, §1.15 invariant 10).
- **Polarity.** For a bullish wave the surviving edge is the origin **low**; for
  a bearish wave it is the origin **high**. The directional read (Part 1 §1.2)
  is *price vs. this surviving edge*.

> *Implementation note:* this is the object behind the already-implemented
> origin-based direction (`se*_inv` as the surviving edge). Part 2 elevates it
> from an ad-hoc "invalidation" value to the **constitutional origin** of the
> wave.

### 2.2.2 — ProtectedSwing1

**Definition.** The **first swing the controlling side must defend** to keep the
wave alive after birth — the nearest counter-swing whose violation would be the
first sign control is contestable.

- **Creation law.** Created shortly after wave birth, as the first qualifying
  counter-pivot behind the initial expansion leg.
- **Persistence law.** Persists while undefeated. May be *upgraded* (re-anchored
  to a newer protected level) as the wave extends and leaves higher/lower
  defended swings behind.
- **Destruction law.** Destroyed when violated (a counter-break through it) — its
  violation is the **BOS1 event** (§2.2.4). Also destroyed at wave death.
- **Polarity.** Bullish wave: a swing **low** that must hold. Bearish wave: a
  swing **high** that must hold.

### 2.2.3 — ProtectedSwing2

**Definition.** The **second, deeper protected swing** — the level whose
violation signifies a *more serious* erosion of control than ProtectedSwing1.
ProtectedSwing1 and ProtectedSwing2 form a **two-tier defence**: first break is a
warning, second break is a structural counter-trend developing.

- **Creation law.** Created after ProtectedSwing1, as the next-deeper defended
  swing (or promoted from ProtectedSwing1 once a new protected level forms ahead
  of it).
- **Persistence law.** Persists while undefeated; participates in the BOS
  hierarchy (§2.3).
- **Destruction law.** Destroyed when violated — its violation is the **BOS2
  event** (§2.2.5). Also destroyed at wave death.
- **Polarity.** Same convention as ProtectedSwing1, one tier deeper.

### 2.2.4 — BOS1 (First Break of Structure)

**Definition.** The **first violation of a protected swing against the
controlling side** — the first concrete structural sign that the controlling
side's grip is loosening. BOS1 is *both* an event (the moment of break) and a
standing object (the fact that a first break has occurred this wave).

- **Creation law.** Created when ProtectedSwing1 is violated by a decisive close
  (decisiveness rules — buffering against noise — are defined generically in
  Part 5 / Part 8). 
- **Persistence law.** Persists as standing evidence for the remainder of the
  wave (the wave "has had its first break") unless invalidated by the
  controlling side decisively reclaiming and extending (recovery rules, Part 8).
- **Destruction law.** Cleared at wave death or on validated recovery.
- **Evidence contributed.** `structureBOS1` (§2.4).

> **Forbidden:** BOS1 → ExpansionPreConvexity. BOS1 is evidence; Pre-Convexity is
> a phase that requires momentum decay and physics transfer-beginning to also be
> present (Part 1 §1.13; Part 7 §9-equivalent).

### 2.2.5 — BOS2 (Second Break of Structure)

**Definition.** The **violation of ProtectedSwing2** — a deeper break confirming
a counter-structure is genuinely developing, not a single counter-swing.

- **Creation law.** Created when ProtectedSwing2 is violated decisively, after
  BOS1 exists.
- **Persistence law.** Persists for the wave; escalates the structural reading
  from "first warning" (BOS1) to "counter-structure developing."
- **Destruction law.** Cleared at wave death or validated recovery.
- **Evidence contributed.** `structureBOS2` and `structureCounterDeveloping`
  (§2.4).

> **Forbidden:** BOS2 → ExpansionLiquidity. BOS2 is evidence only.

### 2.2.6 — InductionOrigin

**Definition.** The **origin of an inducement move** — the level from which a
counter-directional inducement (a liquidity-engineering leg) launches within the
wave. The InductionOrigin marks where the controlling side (or the transfer
process) sets up the inducement that precedes a liquidity grab.

- **Creation law.** Created when an inducement leg is identified launching from a
  qualifying level after counter-structure begins (typically after BOS1/BOS2).
- **Persistence law.** Persists while the inducement structure is in play.
- **Destruction law.** Destroyed when its **break** occurs (§2.2.8) or at wave
  death.
- **Polarity.** Oriented against the controlling side of the wave.

### 2.2.7 — InductionExtreme

**Definition.** The **extreme reached by the inducement move** — the furthest
counter-extension of the inducement leg, the level around which liquidity pools
and which becomes the target of a subsequent sweep.

- **Creation law.** Created/updated as the inducement leg extends to its extreme.
- **Persistence law.** Persists as the standing inducement extreme; the level
  whose existence is required (as structure-evidence) for the *Liquidity* phases
  (Part 1 §1.3; activation in Part 7).
- **Destruction law.** Destroyed at wave death or when superseded by a new
  inducement structure.
- **Evidence contributed.** `structureInductionExtreme` (§2.4).

> **Forbidden:** InductionExtreme existing → ExpansionLiquidity. The phase
> additionally requires momentum "expansion stalled + liquidity attraction" and
> physics "FRZ destination attraction + DOM imbalance + capacity saturation"
> (Part 7 §11-equivalent).

### 2.2.8 — InductionOriginBreak

**Definition.** The **break of the InductionOrigin** — the event/object marking
that the inducement has been resolved and price has broken back through the
inducement's origin, typically the trigger structure preceding **objective
completion** (NewHigh/NewLow delivery in the controlling direction, or the
confirmation of transfer in the counter direction).

- **Creation law.** Created when price decisively breaks the InductionOrigin.
- **Persistence law.** Persists as standing evidence that the inducement cycle
  has resolved this wave.
- **Destruction law.** Cleared at wave death.
- **Evidence contributed.** Feeds `structureObjectiveComplete` (when in the
  controlling direction, in concert with ExpansionExtreme exceed) (§2.4).

> **Forbidden:** InductionOriginBreak → NewHigh. NewHigh additionally requires
> momentum "acceleration returns + participation restored" and physics "rotation
> complete + integrity restored + liquidity cycle complete" (Part 7
> §12-equivalent).

### 2.2.9 — ExpansionExtreme

**Definition.** The **furthest point the wave has reached in its controlling
direction** — the running high of a bullish wave or running low of a bearish
wave. It is the measure of how far the objective has been pursued.

- **Creation law.** Created at wave birth (initialised at the origin) and
  **updated continuously** as the wave extends in its controlling direction.
- **Persistence law.** Persists and ratchets monotonically in the controlling
  direction for the life of the wave.
- **Destruction law.** Reset at wave death (the next wave starts a new
  ExpansionExtreme).
- **Evidence contributed.** Distance/progress signals; participates in
  `structureObjectiveComplete` (objective exceeded) and feeds capacity (Part 1
  §1.10; physics in Part 4).

### 2.2.10 — CompletionExtreme

**Definition.** The **extreme at the moment objective completion is recognised**
— the level marking delivery (NewHigh/NewLow). It freezes the ExpansionExtreme at
the point the creation half of the lifecycle ends and the resolution half begins
(Part 1 §1.11).

- **Creation law.** Created when objective completion is confirmed (structure
  component of completion; full completion still requires momentum + physics,
  Part 1 §1.11).
- **Persistence law.** Persists through the resolution half (Absorption →
  Retracement → Return) as the reference extreme the resolution is measured
  against.
- **Destruction law.** Cleared at wave death / next wave birth.
- **Evidence contributed.** Anchors `structureObjectiveComplete`; reference for
  `structureDemandReturn` / `structureSupplyReturn` (§2.4).

---

## 2.3 — The BOS Hierarchy

Structure escalates in **ordered tiers**, never out of sequence:

```
ProtectedSwing1 violated  → BOS1  → "first warning"
ProtectedSwing2 violated  → BOS2  → "counter-structure developing"
InductionOrigin formed    → inducement engineering underway
InductionExtreme set      → liquidity pooled (sweep target exists)
InductionOriginBreak      → inducement resolved (objective trigger / transfer confirm)
```

**Hierarchy laws:**

1. **Ordering.** BOS2 cannot exist before BOS1. Induction objects form in the
   transfer region (after counter-structure begins). The skeleton tells a story
   in order; out-of-order promotion is forbidden.
2. **Monotonic escalation within a wave.** Structural severity only increases
   within a living wave until either recovery (controlling side reclaims, Part 8)
   or wave death.
3. **Directional symmetry.** The entire hierarchy mirrors for bullish and
   bearish waves; "protected" means the level the *controlling* side defends, and
   "counter" means *against* the controlling side. The retracement-half phases
   reuse the same object types (BOS1/BOS2/Induction*) but read in the
   now-dominant counter direction (Part 7 §15–17-equivalent).

---

## 2.4 — Structure-Evidence Outputs (the only permitted exposure)

These are the **complete and closed** set of signals Structure exposes to Engine
1A. Each is **evidence** (boolean or graded), owned solely by Structure, and
**never** a phase. Engine 1A consumes them only in confluence with Momentum
(Part 3) and Physics (Part 4).

| Evidence | Meaning | Derived from |
|---|---|---|
| `structureExpansionIntact` | Controlling side still in control; no BOS against it; ExpansionExtreme advancing | Point4Origin holding, no BOS1, ExpansionExtreme ratcheting |
| `structureBOS1` | First protected swing broken | BOS1 object (§2.2.4) |
| `structureBOS2` | Second protected swing broken | BOS2 object (§2.2.5) |
| `structureCounterDeveloping` | A genuine counter-structure is forming | BOS1 ∧ BOS2 / counter-pivot sequence |
| `structureInductionExtreme` | An inducement extreme (liquidity pool / sweep target) exists | InductionExtreme object (§2.2.7) |
| `structureOriginBreak` | The wave's origin has been breached (control invalidated) | Point4Origin destruction by breach (§2.2.1) |
| `structureObjectiveComplete` | Objective exceeded / induction origin broken in controlling direction | InductionOriginBreak ∧ ExpansionExtreme exceed ∧ CompletionExtreme set |
| `structureControlLost` | Controlling side has lost structural control | OriginBreak ∨ (BOS2 ∧ counter-extension beyond defence) |
| `structureDemandReturn` | Price has structurally returned to a demand origin/zone (bull regeneration setup) | Return to Point4Origin-class zone after completion |
| `structureSupplyReturn` | Price has structurally returned to a supply origin/zone (bear regeneration setup) | Return to Point4Origin-class zone after completion |

**Output laws:**

1. **Evidence only.** None of the above is, or maps to, a phase (Part 1 §1.4,
   §1.15 invariant 3).
2. **Falsifiable.** Each is withdrawn the instant its underlying object is
   destroyed or its condition ceases (Part 1 §1.4; persistence in Part 5).
3. **No private vocabulary.** Structure may not emit any string outside this
   table; it must never emit "Weak Expansion", "M1 Convexity", "Dominant Phase",
   etc. (Part 1 §1.15 invariant 2).
4. **Direction-aware, polarity-symmetric.** Each evidence item is computed for
   the controlling direction of the current wave and mirrors for the opposite
   wave (§2.3 law 3).

---

## 2.5 — Inheritance (lower degrees inherit, never classify)

Per Part 1 §1.2 (recursion) and §1.15 (one authority), only the M5 degree's
structural objects feed Engine 1A's classification. Other degrees (M1, M3, M15,
H1, H4, and higher per Part 12) maintain their **own** structural objects for
**context**, but:

1. They expose their structure-evidence **as context to consumers** (Story,
   Fusion, Dashboard), never to the phase gate.
2. They **inherit** the lifecycle meaning from Engine 1A; a lower-degree BOS does
   not change the M5 phase.
3. A lower-degree wave's death may register at M5 only as **evidence**
   (e.g. contributing to `structureCounterDeveloping`), never as a phase change.

The detailed restrictions on what each degree may and may not do are deferred to
**Part 11 — Recursive Layer Constitution**. Part 2 only fixes the principle:
**one skeleton classifies; the others describe.**

---

## 2.6 — Part 2 Invariants (added to the §1.15 set)

11. **Closed object set.** Only the ten objects of §2.2 exist. No new structural
    object may be invented by any detector or timeframe.
12. **Ordered escalation.** The BOS hierarchy (§2.3) is strictly ordered; no
    out-of-sequence promotion.
13. **Structure emits only the §2.4 evidence table.** Nothing else crosses the
    boundary from Structure to Engine 1A.
14. **One skeleton classifies.** Only M5-degree structure feeds the phase gate;
    all other degrees are context (§2.5).
15. **Objects are falsifiable.** Destruction of an object immediately withdraws
    its evidence (no stale skeleton).

---

## End of Part 2

**Part 2 establishes the skeleton: the closed set of persistent structural
objects, their creation/persistence/destruction laws, the ordered BOS hierarchy,
and the closed set of structure-evidence outputs — strictly evidence, never
phase.**

**Next:** *Part 3 — Momentum Ontology* — the muscle: the Efficiency, Velocity,
Acceleration, Participation, CounterFlow, Decay, Impulse, Exhaustion, Transfer,
and Compression engines, defined as **evidence producers** (momExpansionStrong,
momExpansionWeakening, momCounterParticipationGrowing, momExhaustionDeveloping,
momAccelerationReturning, momRetracementDominant, momRegenerationDeveloping) —
strictly evidence, never phase — and how momentum evidence aligns in time with
the structural objects of Part 2.

*Awaiting ratification of Part 2 before drafting Part 3.*



---

# ENGINE 1A.7 — PRE-OBJECTIVE LIQUIDATION WAVE ARCHITECTURE

> **Purely additive. Nothing in Engine 1A is removed.** The canonical 14-phase
> lifecycle (Part 1 §1.3, Part 6) is unchanged. This engine raises the
> *resolution* of the single most important section of the lifecycle: objective
> completion and the genuine transfer of control.
>
> **Status:** Implemented in `Spartica.txt` inside `f_v72_run` as the
> `liq_*` overlay (see "Implementation Mapping" below).

## Architectural Purpose

The current architecture treats objective completion as **instantaneous**:

```
Expansion Liquidity → New High → Absorption
Retracement Liquidity → Demand/Supply Return
```

This is physically incorrect. **The movement toward the objective is itself a
wave** — with its own birth, acceleration, displacement, induction, exhaustion,
and destination arrival. Without modelling that wave, the system cannot
distinguish *temporary counterflow* from *genuine objective completion*, and
therefore cannot reliably determine true supply/demand activation, genuine
reversals, true absorption, or real transfer of control.

## Core Principle

Price does not jump from Induction to New High / Return. After Induction, price
builds a **dedicated objective-completion wave** whose purpose is to *finish the
previous objective*. That wave is where liquidity is swept, destinations fill,
supply/demand activates, reversals begin, absorption begins, and true CHoCH
forms. It must be modelled.

## Architectural Change (additive sub-states only)

```
Expansion Induction
   → PRE-NEW HIGH (or PRE-NEW LOW) LIQUIDATION WAVE
        → Objective Arrival → New High / New Low → Absorption

Retracement Induction
   → PRE-DEMAND RETURN (bull) / PRE-SUPPLY RETURN (bear) LIQUIDATION WAVE
        → Objective Arrival → Demand Return / Supply Return
```

**Only these two phases receive sub-states. Everything else is unchanged.**

## Internal Liquidation-Wave Lifecycle (informational sub-states)

```
Initialization → Expansion → Displacement → Induction → Terminal Liquidation → Objective Arrival
```

- **Stage 0 — Initialization.** Birth of the objective-completion wave.
  Structure: induction completed. Momentum: transfer beginning. Physics:
  destination attraction beginning. Store: `liqOrigin`, `liqDirection`,
  `liqTarget`, `liqDistance`, birth references. No phase active.
- **Stage 1 — Expansion.** The wave establishes itself and moves away from
  origin (nothing can be displaced before it exists). Small impulse; no BOS /
  convexity / displacement required yet; distance still large; energy available.
- **Stage 2 — Displacement.** Pre-convexity of the liquidation wave. Directional
  sequence established, protected structure intact; velocity/efficiency
  expanding; participation transfer beginning; distance compression begins;
  objective attraction strengthening.
- **Stage 3 — Induction.** Secondary development (internal BOS2 may appear);
  impulse weakening; counter-participation increasing; convexity develops;
  transfer increases; destination attraction intensifies.
- **Stage 4 — Terminal Liquidation.** Induction complete; velocity compressing,
  efficiency collapsing; movement changes from **push-driven to pull-driven**;
  price magnetised — FRZ destination attraction dominates, DOM transfer
  dominates, geometric capacity exhaustion develops, integrity deteriorates,
  rotation completion approaches, future-return compression extreme.
- **Stage 5 — Objective Arrival.** Requires **simultaneous** agreement:
  - *Structure:* destination touched / protected-swing violation / objective
    completed.
  - *Momentum:* velocity collapse, efficiency collapse, directional exhaustion.
  - *Physics:* FRZ destination complete, rotation complete, geometric capacity
    exhausted, energy depleted, DOM transfer complete, integrity/maturity
    exhausted, future-return compression maximal.
  - Only then `objectiveArrival = TRUE`.

## True Change-of-Character Engine

CHoCH must **never** trigger merely because a BOS occurred. `trueCHoCH = TRUE`
only when, simultaneously: *Structure* (protected-swing failure) ∧ *Momentum*
(directional collapse + participation transfer) ∧ *Physics* (supply/demand
arrival confirmed, energy exhaustion, rotation + capacity + destination
completion, future-return collapse).

## Absorption Activation Gate

**Absorption cannot begin until `objectiveArrival = TRUE` AND `trueCHoCH =
TRUE`.** Until then price remains inside the Pre-Objective Liquidation Wave
*regardless of any single BOS*.

## Distance Engine (NEVER time-based)

Liquidation maturity must never use time, bars elapsed, timers, percentages of
duration, maturity counters, or static progress. It must use
**distanceToDestination, relativeDistanceCompression, arrivalVelocity,
energyDecay, geometricCapacity, destinationAttraction, rotationCompletion,
integrityExhaustion, futureReturnCompression, domTransfer** — all sourced from
the V72/V73 physics engines (FRZ, EAE, RE, EDE, Rotation, DOM, Geometric
Capacity, Integrity, Maturity, Future Return).

## Panel Display

```
M5
PRE-NEW HIGH LIQUIDATION WAVE
Subphase: Expansion        Distance: 61%   Arrival: No
   → Displacement          Distance: 42%
   → Induction             Distance: 23%
   → Terminal Liquidation  Distance: 8%    Arrival: Imminent
OBJECTIVE ARRIVAL → New High Completed → Absorption Beginning
```

## Critical Architectural Rule

The six stages (Initialization, Expansion, Displacement, Induction, Terminal
Liquidation, Objective Arrival) **MUST NOT become independent canonical phases.**
They exist only *inside* the Pre-Objective Liquidation Wave as informational
states. The canonical Engine 1A lifecycle remains unchanged.

## Philosophical Foundation

There is not truly an "Expansion Liquidity" phase — there is a *wave whose
purpose is to finish expansion*, and a *wave whose purpose is to finish
retracement*. Those waves are where liquidity is swept, destinations fill,
energy exhausts, participation transfers, supply/demand activate, capacity
collapses, rotations complete, change of character forms, and reversals begin.
Engine 1A.7 models them at high enough resolution that V71/V72/V73 can
distinguish *"liquidation has started"* from *"the objective has actually been
reached and the real reversal has begun."*

---

## Implementation Mapping (as built in `Spartica.txt` → `f_v72_run`)

| Spec concept | Implementation |
|---|---|
| Wave armed | `_liqArm` = `ie1a_currentPhase ∈ {Expansion Induction, Retracement Induction}` |
| Objective / destination | `liq_target` = ranked destination `dc_bestPrice` → `eae_primaryAttractorPrice` → `frz_bestZoneMid` |
| Origin / initial distance | `liq_origin`, `liq_initDist` captured at birth (close, |target−close|) |
| Distance compression (no time) | `liq_distancePct` = remaining / initial × 100 |
| Magnet / pull-driven | `_liqMagnet` from `frz_inProximity` / `frz_distanceToZone < frzProximityATR` |
| Capacity exhaustion | `_liqCapExh` from `ede_dissipationProgress` / `convexityMaturity` |
| Rotation/resolution complete | `_liqRotDone` from `rot_transferProbability` / `re_resolutionState` |
| Momentum collapse | `_liqEnergyLo` from `efficiency < effThresh·0.7` |
| Sub-phase | `liq_subPhase` (Initialization→Objective Arrival) from distance + physics |
| Objective Arrival (S∧M∧P) | `liq_objArrival` = `_liqArrStruct ∧ _liqEnergyLo ∧ _liqArrPhys` |
| True CHoCH (not BOS alone) | `liq_trueCHoCH` = `liq_objArrival ∧ counter-BOS ∧ collapse ∧ RESOLVED` |
| Absorption gate | overlay holds until `liq_objArrival ∧ liq_trueCHoCH`, then retires |
| Panel | Market Story headline + dedicated readout (Subphase / Target / Distance / Arrival) |

**Known limitation (honest):** because the canonical Absorption phase is assigned
*upstream* of the physics engines (source-order constraint documented in Part
1/§1.7), the Absorption gate is enforced at the **overlay/consumer layer** (the
liquidation wave dominates the displayed narrative and DOE-facing story until
arrival + true CHoCH), not by rewriting the upstream `f_se` phase assignment. A
full upstream gate requires the source reorder described in Part 1 and is
deferred to the implementation phase of the constitution.



---

# CHART LABEL PHASE AUTHORITY — IMPLEMENTATION NOTE

**Implemented** in `Spartica.txt` as a single global authority (after
`convexityMaturity` is finalised, ~line 1661) so that **both** the on-chart
labels (drawn mid-file) and the late MOS panels (in `f_v72_run`) consume **one**
string. Nothing canonical was removed.

**Single owner of the visible phase string:** `currentDisplayPhase`.
- When the liquidation overlay is active: `liqg_title • liqg_subPhase`
  (e.g. `Pre-New High Liquidation Wave • Displacement`).
- Otherwise: `ie1a_currentPhase` (canonical M5).
- **Absorption gate:** the overlay stays in control through the two Induction
  phases until `liqg_objArrival ∧ liqg_trueCHoCH`, so the visible string cannot
  read "Absorption" while the objective wave is still in progress.

**Consumers re-pointed to the single authority:**
- On-chart M5 trace label (`_l0txt = "M5 · " + liqg_readout`) — now shows
  Direction · Phase [· Substate] · Target · Distance · Arrival.
- P3 Wave Narrative M5 row (`narr_primary`).
- MOS Market Story headline + readout row.
- MOS Copilot "CURRENT".

**Authority physics (early-available consensus):** EDE dissipation, RE
resolution, geometric/convexity capacity, momentum efficiency, and the M5
structural objective (`se5_tgt`) for distance compression. The late
FRZ/DOM/rotation engines still refine the DOE/destination panels downstream but
do **not** reclassify this authority.

### Honest scope boundary (what is NOT yet done)
- **Per-timeframe rows (M1/M3/M15/H1/H4)** still display their own engine's
  phase (consistent with the Multi-Timeframe Label rule that each TF shows its
  own state). They are not yet routed through a per-TF liquidation overlay.
- **Execution Probability / waveAgreement / Fusion** still use the legacy
  stack-score model (audit Phases 8–9). They are not yet re-pointed to
  `currentDisplayPhase`.
- The **upstream `f_se` phase latch and its event/score shortcuts still exist**
  underneath as structural evidence; `currentDisplayPhase` overlays the 3-D /
  liquidation-aware projection on top. A true removal of the upstream shortcuts
  requires the physics-before-phase source reorder described in Part 1, which is
  deferred (cannot be validated without compilation).
- Cannot compile here — verified statically (identifier scope, no orphaned refs,
  function integrity). If a token-limit error (CE10117) appears, a dead-code
  trim pass is required before further additions.



---

# AUTHORITY WIRING — BATCH 2 (consumers + 1A.7 → decisions)

Additive, on the compiling baseline. No canonical logic removed.

- **On-chart DIE narrative marker** now consumes `currentDisplayPhase`
  (`die_narrativeDir`), and `f_phaseAbbr` tags any liquidation-wave state as
  `LQW` so the floating marker matches the authority (full substate remains on
  the M5 trace label + Market Story).
- **Multi-Level Progress — M5 row** is now **dynamic**: during a liquidation
  wave it shows distance-traveled (`100 − liqg_distPct`) instead of the static
  `_wp` lookup, and labels the row with `currentDisplayPhase`. (M1/M3/M15/H1/H4
  rows remain static `_wp` — they have no per-TF liquidation engine yet.)
- **DOE decision gate (Engine 1A.7 → decisions):** `doe_action` now returns
  `Wait` while `liqg_active and not (liqg_objArrival and liqg_trueCHoCH)` — i.e.
  no entry is issued while the objective-completion wave is still in progress.
  This is the first decision-layer consumption of Engine 1A.7 (previously
  display-only).

### Still deferred (requires compile-checked iteration, not safe blind)
- Physics-before-phase **source reorder** (move FRZ/DOM/EAE/Rotation above the
  phase) — the only way to make the *canonical* phase truly 3-D and flip
  criteria 8–13/27. Must be done in small, individually-compiled steps.
- **Per-TF liquidation overlays** (M1/M3/M15/H1/H4) — need per-TF EDE/RE which
  are currently M5-only.
- **ExecProb / Fusion / waveAgreement** still legacy stack-score; not yet routed
  to `currentDisplayPhase`.
- Non-liquidation **progress** for M1/M3/M15/H1/H4 still static `_wp`.
