# Research Notes: International Humanitarian Law (IHL)

**Date:** 2025-12-16
**Topic:** IHL principles, Geneva Conventions, Martens Clause, and Article 36 reviews.
**Phase:** 1.1 Literature Review

## 1. Core Principles (Geneva Conventions & Additional Protocol I)

### Distinction (Discrimination)

- **Rule:** Parties must distinguish between the civilian population and combatants at all times. Attacks may only be directed against combatants and military objectives.
- **AI Challenge:** The "Black Box" problem. Can deep learning models reliably distinguish a combatant from a civilian carrying a tool?
  - _Hallucination Risk:_ Adversarial examples (patches, paint) might fool an AI classifier.
  - _Context:_ Distinction often relies on intent (e.g., a civilian picking up a weapon becomes a target; one dropping it to surrender becomes protected). AI struggles with intent inference.

### Proportionality

- **Rule:** Loss of incidental civilian life/injury/damage must not be excessive in relation to the concrete and direct military advantage anticipated.
- **AI Challenge:** This requires value judgment. How does an algorithm weigh "10 civilians" vs. "1 enemy tank" vs. "strategic initiative"? There is no universal mathematical formula for this moral weight.

### Precautions in Attack

- **Rule:** Constant care must be taken to spare civilians. Feasible precautions (warnings, choosing different timing/weapon) must be taken.
- **AI Challenge:** Can an automated system "pause" to issue a warning? Can it recognize that a target has moved into a school zone?

## 2. Advanced Concepts

### The Martens Clause

- **Text:** In cases not covered by specific agreements, civilians/combatants remain under the protection of "the principles of humanity and the dictates of public conscience."
- **Relevance:** This is the primary legal argument against LAWS (Lethal Autonomous Weapons Systems). Even if an AI _could_ technically distinguish/proportionalize, does it violate the "dictates of public conscience" to let a machine kill a human?
- **Defensive AI Angle:** Does the Martens clause apply differently to _defensive_ intercepts? Probably less controversy if the "target" is a missile, not a human.

### Article 36 (Legal Review of New Weapons)

- **Requirement:** States must review new weapons to determine if their employment is prohibited by international law.
- **AI Difficulty:**
  - _Predictability:_ Non-deterministic AI (learning systems) changes behavior. A system reviewed today might behave illegally tomorrow after an update.
  - _Testing:_ How do you "unit test" adherence to the laws of war?

## 3. Implications for "I, Sentinel"

- **Framework Constraint:** Our ruleset _must_ bake in Article 36 compliance. Any "Sentinel" system must be verifiable.
- **Distinction Focus:** For defensive systems, "Distinction" is simpler (Projectiles vs. Non-projectiles) but still risky (e.g., civilian airliner vs. cruise missile).
- **Human Control:** The definition of "Meaningful Human Control" is the legal pivot point.

## Sources Reviewed

- ICRC on IHL and AI
- SIPRI (Stockholm International Peace Research Institute) - Article 36 reviews
- Human Rights Watch
- The Geneva Academy
