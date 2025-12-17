# Research Notes: Comparative Analysis of Defensive Systems

## 1. Iron Dome (Israel)

- **Status:** Operational, widely used.
- **Autonomy Level:** "Human-on-the-loop" (Supervisory).
- **Workflow:** Radar detects launch -> BMC calculates trajectory -> Determines if threat to populated area -> If Yes, recommends intercept.
- **Human Role:** Operators have a few seconds to veto. Default is usually to engage if the system recommends.
- **Sentinel Comparison:** Iron Dome is closest to Sentinel in "mission" (intercepting projectiles), but lacks the "Machine Martyrdom" constraint (it will intercept even if debris falls on empty land, though it tries to avoid it). It prioritizes Defense over strict Certitude in some high-saturation attacks.

## 2. Aegis Combat System (US Navy)

- **Incident:** USS Vincennes (1988), shootdown of Iran Air 655.
- **Myth:** "The computer did it."
- **Reality:** System was NOT in "Auto-Special" mode. The system correctly identified the plane as ascending (Mode III). The _human crew_, under stress ("Scenario Fulfillment"), misread the data as descending (F-14 attack profile).
- **Sentinel Comparison:** This proves the danger of "Human-in-the-loop" under stress. A "Sentinel" ruleset (Principle II: Certainty) would have aborted the shot because the sensor data (Ascending + Mode III) would not reach the 99.9% threat threshold. The Sentinel would have "Failed Open" and saved the plane.
- **Key Lesson:** Humans are often the weak link in the OODA loop due to cognitive bias.

## 3. Patriot Missile System (US Army)

- **Incident:** 2003 Iraq War Fratricide (RAF Tornado GR4 & US Navy F/A-18).
- **Cause:** IFF (Identification Friend or Foe) failure. The Patriot radar classified the friendly jets as Anti-Radiation Missiles (ARM).
- **Automation Bias:** Operators trusted the system's classification implicitly. "Trust but verify" failed because verification was impossible in the time window.
- **Sentinel Comparison:** Principle II (Certainty) imposes a "Fail Open" state. If IFF is missing (Tornado), does it equal "Threat"?
  - Standard Rules: If no IFF -> Hostile.
  - Sentinel Rules: If no IFF -> Unknown -> Do Not Fire (unless visual/thermal confirmation).
  - The Sentinel would likely have _not_ fired at the Tornado, accepting the risk that it _might_ be an ARM, because the "Positive ID" was not absolute. This highlights the "Suicide Pact" critique (Realist Critique) but satisfies the "Lawful" requirement.
