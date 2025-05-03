# KAIRO — Founding Memo v0.1  
**Committed-for-life at `HEAD` of the `kairo-origin` public repository**  

---

## 0. Cryptographic provenance  

After copy-editing only for spelling, commit this file with the message  
`“KAIRO Founding Memo v0.2 — immutable laws encoded”`.  
Immediately generate its SHA-256 digest and anchor that hash to any public, time-stamped chain (e.g., Bitcoin OP_RETURN or Ethereum calldata).  
From this moment forward *all* amendments MUST 1) reference the prior hash, 2) explain why the previous statement of reality was incomplete or wrong, and 3) provide new falsifiable language.  Un-anchored copies have no standing.  

---

## 1.  Why this document must exist  

Human physiology obeys two inviolable facts.  
First, the nervous system survives by forecasting the metabolic cost of staying alive.  
Second, prediction errors increase that cost.  
Persistent overspend feels like anxiety, fatigue, numbness, or hopelessness; society calls these “mental-health problems.”  
No existing tool continuously minimises that cost for an individual while proving, in real time, that the intervention it recommends actually lowered the cost.  
KAIRO exists to supply that missing cybernetic loop.  

---

## 2.  Irreducible problem statement  

“Dysregulation” is the condition in which a person’s moment-to-moment metabolic expenditure per unit of prediction error exceeds the range their body can afford.  
The sole objective of KAIRO is to return that quotient to, or below, the individual’s sustainable band with the smallest possible external input.  

---

## 3.  First-principles constraints that can never be violated  

*   Energy is conserved; any intervention that appears to help but raises total ATP demand is maladaptive.  
*   Causality must be demonstrable inside the individual user; population averages are informative only as priors.  
*   User sovereignty is inviolate; raw personal data never leaves that user’s hardware in legible form.  
*   Every algorithmic recommendation must survive an explicit falsification attempt engineered into the product.  

If a later engineer, investor, or executive proposes a feature that breaches any of these four constraints, the feature is automatically rejected, or this memo is repealed via the amendment protocol.  

---

## 4.  Core functional thesis  

A person’s current dysregulation cost can be estimated by combining:  
* heart-rate-variability metrics that index vagal brake efficacy,  
* electro-dermal activity that indexes sympathetic drive, and  
* context-aware priors on metabolic demand (posture, ambient temperature, cognitive load, recent sleep debt).  

KAIRO samples that composite signal continuously on-device.  
It then queries a causal evidence graph linking thousands of interventions to specific mechanistic shifts (e.g., cyclic sigh ➔ ↑RMSSD within 30 s; 20 lx red light ➔ ↓LF/HF within 4 min).  
A ranking routine computes for this *person, now* the expected drop in cost per joule of effort for every candidate input and returns the single best option plus one fallback.  
The user executes; the system measures the after-state for at least thirty seconds; if cost fails to fall by the predicted delta, that edge in the graph is down-weighted.  
With each loop, the personal model becomes a more precise minimiser of metabolic overspend.  

---

## 5.  Why competitors cannot copy the moat  

The continuously self-verified, person-specific causal graph compounds in value with each closed loop.  
Because raw biosignal data never leave the device, no external actor can siphon the training set.  
Because every edge is cryptographically time-stamped to its biomarker delta, fake data injected later is mathematically detectable.  
A copycat could mimic the interface, but not the convergent graph or the trust architecture that protects it.  

---

## 6.  Observable success criterion  

KAIRO will be judged a success only when, in a prospective cohort of at least ten thousand daily users wearing continuous glucose monitors and validated HRV sensors, median metabolic expenditure during self-reported stress moments is reduced by 30 percent within twenty-eight days of first use, compared with a matched no-guidance control.  
If this condition is not met, the system is biologically inert and must be dismantled or rewritten.  

---

## 7.  Self-amendment clause  

This memo expires one calendar year after its commit date.  
Extension or alteration requires:  
1. publication of a pre-registered replication study falsifying or refining any quantitative claim herein;  
2. a replacement memo committed with reference to the prior SHA-256 hash;  
3. migration scripts proving continuity of all user-sovereign data protections.  

Absent those three conditions, the original language stands and governs.  

---

## 8.  Immediate execution steps (48 h)  

1.  Create the public GitHub repository `kairo-origin`; push this markdown file as `MEMO.md`.  
2.  Generate the hash and anchor it to an immutable ledger; post the transaction reference in `README.md`.  
3.  Spin up a private TestFlight build that records RMSSD, EDA, and posture locally and returns **no** recommendations — only baseline data — until the falsification harness is operational.  

If these three tasks are not completed within forty-eight hours of this commit, the project is considered stillborn and shall not solicit user data.  

---

## 9.  Closing litmus  

If any reader believes human affect can deviate indefinitely from metabolic law, or that a recommendation engine need not falsify itself to remain true, then KAIRO is not their venture.  
Otherwise, ship.  