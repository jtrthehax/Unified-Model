---
Contract: "STRESS → TRANSITION"
Expanded_Filename: "contract_STRESS_TRANSITION_stress_to_transition.md"

Manifest:
  file: "unified_model_manifest.yml"
  optional: true
  role: "Global repository index and AI execution rules."

Ontology_Layer: "03_INTEROCEPTION_LOAD_AND_FAILURE"
Upstream_Dependencies:
  - "SOC → AUTO"
  - "MOD → COG"

Downstream_Dependencies:
  - "COG → INTERO"
  - "NOCI → COG"
  - "AUTO → MOD"

Cross_References:
  - "contract_SOC_AUTO_social_to_autonomic.md"
  - "contract_MOD_COG_modulation_to_cognition.md"
  - "contract_COG_INTERO_cognition_to_interoception.md"
  - "contract_NOCI_COG_nociception_to_cognition.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: STRESS → TRANSITION
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_STRESS_TRANSITION_stress_to_transition.md`

**Ontology Layer:**  
INTEROCEPTION_LOAD_AND_FAILURE

**Direction of Influence:**  
STRESS → TRANSITION

**Upstream Dependencies:**  
- SOC → AUTO  
- MOD → COG  

**Downstream Dependencies:**  
- COG → INTERO  
- NOCI → COG  
- AUTO → MOD  

**Cross‑Contract References:**  
- `contract_SOC_AUTO_social_to_autonomic.md`  
- `contract_MOD_COG_modulation_to_cognition.md`  
- `contract_COG_INTERO_cognition_to_interoception.md`  
- `contract_NOCI_COG_nociception_to_cognition.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary


**Input layer:** STRESS — acute sympathetic activation, metabolic mobilization, motor readiness, attentional narrowing, precision-gain shift.

**Output layer:** TRANSITION — resolution through physical discharge and parasympathetic rebound, or failure of resolution leading to chronic sympathetic attractor formation.

**Primary crossover point:** The regulatory fork between a resolved acute stress response and the formation of a chronic sympathetic attractor state. This transition is not described in any existing contract and represents the onset mechanism for chronic stress, trauma, and persistent autonomic rigidity.

**Key risk:** Incomplete discharge of acute sympathetic activation prevents return to baseline priors, maintains elevated precision weighting, and locks autonomic tone into a high-sympathetic configuration. This forms a stable maladaptive attractor state.

**Distinguishing feature:** SOC↔AUTO covers activation states; MOD↔COG covers precision gain; COG↔INTERO and NOCI↔COG cover maintenance loops. None describe the *transition event* from acute to chronic.

---

## Why This Contract Exists

The framework describes:

- chronic sympathetic dominance  
- precision-gain drift  
- interoceptive amplification  
- nociceptive maintenance loops  
- social-autonomic activation  

But it does **not** describe:

- how acute stress normally resolves  
- how physical discharge completes  
- how incomplete discharge becomes chronic  
- how trauma onset occurs  
- what the boundary event looks like mechanistically  

This contract formalizes the **acute → chronic transition**, a missing structural mechanism that determines whether the system returns to baseline or collapses into a persistent attractor.

---

## The Stress Transition Framework

Acute stress is an adaptive, time-limited state characterized by:

- sympathetic surge  
- metabolic mobilization  
- motor readiness  
- attentional narrowing  
- precision-gain increase  

Resolution requires:

- physical discharge  
- parasympathetic rebound  
- prediction-error downshift  
- restoration of baseline priors  

Failure of resolution produces:

- persistent sympathetic tone  
- elevated precision weighting  
- threat-prior reinforcement  
- interoceptive/nociceptive amplification  
- chronic attractor formation  

This contract describes the **boundary conditions** and **mechanistic steps** that determine which path the system takes.

---

## The Complete Chain

```
Acute stressor → sympathetic surge → motor readiness → precision gain ↑
→ physical discharge? (yes/no)

If YES:
    → parasympathetic rebound
    → prediction-error downshift
    → priors return to baseline
    → system exits acute state

If NO:
    → precision remains elevated
    → threat priors remain overweighted
    → autonomic tone fails to return
    → interoceptive/nociceptive amplification begins
    → chronic sympathetic attractor forms
```

---

## Link-by-Link Mechanism

### Link 1: Acute sympathetic activation — adaptive mobilization
Acute stress produces a coordinated autonomic, metabolic, and cognitive shift enabling rapid action. Precision weighting increases to prioritize threat-relevant signals.

**Chain completeness:** Load-bearing.

---

### Link 2: Physical discharge — resolution mechanism
Motor output, metabolic expenditure, and autonomic cycling complete the stress response. Parasympathetic rebound restores baseline priors and autonomic tone.

**Chain completeness:** Scaffolding.

---

### Link 3: Incomplete discharge — failure mode
If discharge is interrupted or suppressed, sympathetic activation remains partially unresolved. Precision weighting stays elevated, and threat priors remain sticky.

**Chain completeness:** Scaffolding approaching load-bearing.

---

### Link 4: Transition boundary — attractor formation
Persistent elevation of precision and sympathetic tone creates a stable configuration. Interoceptive and nociceptive loops (COG↔INTERO, NOCI↔COG) begin reinforcing the state.

**Chain completeness:** Scaffolding.

---

### Link 5: Chronic sympathetic dominance — upward propagation
The chronic attractor propagates through:

- MOD↔COG (precision-gain drift)  
- COG↔INTERO (interoceptive amplification)  
- NOCI↔COG (nociceptive amplification)  
- SOC↔AUTO (rigid activation states)  

**Chain completeness:** Load-bearing.

---

## Operating States — Predicting Conditions From First Principles

| Condition | Transition Failure Mode | Mechanism | Derivable? |
|----------|--------------------------|-----------|------------|
| Trauma onset | Incomplete discharge | Precision remains elevated; threat priors reinforced | Yes |
| Chronic stress | Repeated unresolved acute events | Autonomic tone fails to return | Yes |
| Panic sensitization | Rapid reactivation of unresolved state | Precision-gain instability | Yes |
| Post-surgical FND | Salient event + unresolved activation | Attentional lock + proprioceptive confirmation | Yes |

---

## Predictions

- Incomplete resolution of acute stress should predict higher probability of chronic attractor formation.  
- Physical discharge completion should predict better regulatory recovery than interrupted discharge.  
- The acute → chronic transition should be identifiable as a discrete regulatory event.  
- Precision weighting should remain elevated after unresolved stress events.  
- Chronic sympathetic dominance should correlate with unresolved discharge patterns.

---

## Dependencies

- Longitudinal HRV monitoring around acute stress events.  
- Comparison of resolved vs unresolved discharge patterns.  
- Precision-weighting measurement (behavioral or neuroimaging).  
- Follow-up assessment of chronic attractor formation.

---

## Failure Modes

**Activation-only framing:**  
SOC↔AUTO describes activation but not resolution or transition.

**Precision-only framing:**  
MOD↔COG describes precision gain but not the acute→chronic boundary.

**Maintenance-only framing:**  
COG↔INTERO and NOCI↔COG describe maintenance loops, not onset.

**Event omission:**  
Without this contract, trauma onset has no mechanistic home.

---

## Adjacent Contracts

**Below (inputs):**

- SOC↔AUTO — sympathetic activation  
- MOD↔COG — precision-gain shift  

**Above (outputs):**

- COG↔INTERO — interoceptive amplification  
- NOCI↔COG — nociceptive amplification  
- AUTO↔MOD — autonomic rigidity  

---

## Origin Note

This contract arises from STRUCT-001, identifying the missing mechanism for the acute → chronic transition. Existing contracts describe activation, precision, and maintenance loops, but none describe the resolution mechanism or the failure mode that produces chronic sympathetic attractors.

*Chain status: Links 1 and 5 are load-bearing. Links 2–4 are scaffolding with strong empirical support and clear predictions.*
