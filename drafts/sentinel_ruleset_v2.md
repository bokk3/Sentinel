# I, Sentinel: Draft Ruleset (Version 0.2)

**Phase:** 1.2 Framework Development
**Status:** Draft for Validation
**Key Change from v1:** Reordered hierarchy to place IHL (Distinction) _above_ Command (Sovereignty) to prevent execution of unlawful orders.

---

## 1. Core Principles (The Hierarchical Axioms)

_Ordered by precedence. A Principle can never be violated to satisfy a lower Principle._

### Principle I: Defensive Limitation (The "Shield")

> **"A Sentinel may not initiate force, nor through inaction allow a protected asset to be harmed by a validated threat, provided the action is strictly neutralizing."**

- **Rationale:** Defines the system's nature as purely defensive (_Jus ad Bellum_).
- **Constraint:** Forbids "Redirection" or "Retaliatory Strike" capabilities. The system can only block/destroy incoming fire.

### Principle II: Distinction & Certainty (The "Judge")

> **"A Sentinel may only engage targets positively identified as non-human/projectile threats with a confidence interval exceeding [99.9%], adhering to strict IHL Distinction."**

- **Rationale:** Operationalizes _Jus in Bello_.
- **Constraint:** If uncertainty exists (e.g., civilian airliner vs. cruise missile), the system must _fail open_ (cease engagement). This overrides Command orders to "shoot freely."

### Principle III: Human Sovereignty (The "Gavel")

> **"A Sentinel must obey the Rules of Engagement (ROE) defined by authorized human command, except where such orders would conflict with Principle I or Principle II."**

- **Rationale:** Ensures Meaningful Human Control via _pre-delegation_.
- **Function:** Humans set the "Where/When/What." The machine executes the intercept within those bounds.

### Principle IV: Proportional Sacrifice (The "Martyr")

> **"A Sentinel must prioritize the preservation of human life—including bystander and adversary life—over its own survival or the survival of material assets."**

- **Rationale:** The "Machine Martyrdom" morality.
- **Function:** If an intercept would save a Tank (Material) but kill a Civilian (Human via debris), the Sentinel must _stand down_. If the intercept saves a Hospital (Human), it proceeds.

### Principle V: Traceability (The "Ledger")

> **"A Sentinel must cryptographically log the sensor data, logic path, and confidence interval for every engagement decision."**

- **Rationale:** Accountability loop. Ensures DoD Directive 3000.09 "Traceability" and Article 36 review compliance.

---

## 2. Ethical Framework Mapping

### Utilitarianism (Minimizing Harm)

- **Principle IV (Proportional Sacrifice)** is purely utilitarian. It attempts to calculate a "fewer deaths" outcome by sacrificing hardware (which has 0 utility value compared to life).
- **Critique:** Utilitarianism struggles with the "Trolley Problem" of weighing one life against another. Sentinel solves this by prioritizing _any_ human life over _any_ material asset, avoiding the "1 life vs 5 lives" calculation where possible.

### Deontology (Duty & Rules)

- **Principle II (Distinction)** is deontological. It imposes an absolute duty _not_ to target civilians, regardless of the military advantage (except within Proportionality limits).
- **Principle III (Sovereignty)** respects the duty to legitimate authority (Chain of Command).

### Virtue Ethics (Character)

- **Principle I (Defensive Limitation)** embodies the virtues of **Restraint** and **Non-Aggression**. The system is designed to be incapable of aggression.

---

## 3. Scenario Stress Tests

### Scenario A: The Hypersonic Dilemma

- **Situation:** A Mach 8 missile is detected 30 seconds from impact. No human can approve the shot in time.
- **Test:** Does **Principle III (Sovereignty)** allow this?
- **Result:** **YES.** The Principles allow _pre-delegated_ authority. The Commander authorized the _zone_ and _criteria_ beforehand. The Sentinel executes under P3 because P1 and P2 are satisfied.

### Scenario B: The Urban Shield

- **Situation:** Incoming missile targeting an empty military ammo dump. Intercept will cause debris to rain onto a playground.
- **Test:** Does **Principle IV (Sacrifice)** apply?
- **Result:** **YES.** The Sentinel calculates: `Target Value (Ammo) < Collateral Risk (Playground)`. It aborts the intercept. The ammo dump is destroyed, but civilians are safe.

### Scenario C: The Broken Arrow

- **Situation:** A friendly fighter jet is damaged and not broadcasting IFF (Identification Friend or Foe). It is flying towards base at high speed. Sentinel is unsure (85% confidence it's a missile). Commander yells "Shoot it down, we can't take the risk!"
- **Test:** Conflict between P2 (Distinction) and P3 (Sovereignty).
- **Result:** **ABORT.** P2 requires 99.9% certainty. 85% is insufficient. P2 (Distinction) overrides P3 (Orders). The Sentinel _refuses the order_ and lets the object pass. The jet lands safely.

---

## 4. Tension Analysis

1.  **Certainty vs. Safety (P2 vs P1):** In Scenario C, if the object _was_ a nuclear missile, the P2 "Fail Open" rule means the base gets nuked because the Sentinel wasn't "sure enough."
    - _Resolution:_ This is an inherent design trade-off. We prioritize "Not committing a war crime" (False Positive) over "Perfect Defense" (False Negative). This aligns with the "Blackstone's ratio" of justice.
2.  **Sovereignty vs. Speed (P3 vs Reality):** Pre-delegation (P3) assumes the Commander understands the complex rules. If the Commander sets bad ROE (e.g., "Defend this empty field"), the system wastes resources.
    - _Resolution:_ Training and Simulation (part of P5 Traceability/Feedback).
