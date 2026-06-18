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
