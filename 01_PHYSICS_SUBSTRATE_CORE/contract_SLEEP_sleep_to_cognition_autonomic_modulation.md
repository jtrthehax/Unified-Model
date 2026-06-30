---
Contract: "SLEEP ↔ COG / SLEEP ↔ AUTO / SLEEP ↔ MOD"
Expanded_Filename: "contract_SLEEP_sleep_to_cognition_autonomic_modulation.md"

Ontology_Layer: "01_PHYSICS_SUBSTRATE_CORE"
Upstream_Dependencies:
  - "TEMPORAL → SLEEP"

Downstream_Dependencies:
  - "SLEEP → WINDOWS"
  - "SLEEP → MOD"

Cross_References:
  - "contract_TEMPORAL_COG_temporal_to_cognition.md"
  - "contract_WINDOWS_COG_window_geometry_to_cognition.md"
  - "contract_AUTO_MOD_autonomic_to_modulation.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: SLEEP ↔ COG / SLEEP ↔ AUTO / SLEEP ↔ MOD
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_SLEEP_sleep_to_cognition_autonomic_modulation.md`

**Ontology Layer:**  
PHYSICS_SUBSTRATE_CORE

**Direction of Influence:**  
SLEEP ↔ COG / AUTO / MOD

**Upstream Dependencies:**  
- TEMPORAL → SLEEP  

**Downstream Dependencies:**  
- SLEEP → WINDOWS  
- SLEEP → MOD  

**Cross‑Contract References:**  
- `contract_TEMPORAL_COG_temporal_to_cognition.md`  
- `contract_WINDOWS_COG_window_geometry_to_cognition.md`  
- `contract_AUTO_MOD_autonomic_to_modulation.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

**Input layer:** SLEEP — sleep-stage architecture (N1, N2, SWS, REM), ultradian cycling, stage-transition dynamics, REM/SWS proportional balance, spindle density, slow-wave amplitude, REM phasic activity.  
**Output layers:**  
COG — memory consolidation, prior updating, prediction-window recalibration, cognitive stability.  
MOD — neuromodulator cycling (ACh, NE, 5‑HT, NE), precision-gain reset, emotional-salience recalibration.  
AUTO — autonomic recovery, vagal restoration, sympathetic flexibility, metabolic load reduction.  

**Primary crossover point:** Overnight cycling of SWS and REM stages reshapes precision weighting and priors across the stack, with stage proportions and transitions determining how much the system can reset, consolidate, and recalibrate.  

**Key risk:** When sleep architecture is fragmented or biased (e.g., reduced SWS, reduced REM, disrupted transitions), the system loses its overnight reset window. Priors remain rigid, precision-gain calibration drifts, autonomic flexibility collapses, and glymphatic clearance is no longer sufficient to restore regulatory stability.  

**Distinguishing feature:** GLYPH↔AUTO covers clearance; the Temporal Layer covers circadian phase. This contract covers **structure** — the architecture of sleep itself as a regulatory mechanism.

---

## Why This Contract Exists

Sleep is already present in the framework, but only partially:

- GLYPH↔AUTO treats sleep as the **glymphatic clearance window**.  
- The Temporal Layer treats sleep as a **circadian phase event**.

Neither addresses **how the architecture of sleep stages** — the sequence, proportions, and transitions of N1, N2, SWS, and REM — shapes regulatory dynamics. Clinical and experimental literatures repeatedly show that:

- REM proportion predicts memory consolidation and emotional prior updating.  
- SWS amplitude predicts synaptic downscaling and autonomic recovery.  
- Fragmented architecture predicts cognitive instability, mood dysregulation, and autonomic rigidity.

These effects are referenced in fragments across GLYPH↔AUTO, MOD↔COG, and the Temporal Layer, but there is no dedicated home for the **mechanism**. This contract exists to formalize sleep architecture as a **load-bearing regulatory layer**.

---

## The Sleep Architecture Framework

Sleep is not a passive state. It is an **active, staged regulatory process** with:

- **Ultradian cycles** (~90–110 minutes) of NREM → REM.  
- **Stage-specific neuromodulatory environments** (SWS: high delta, low NE; REM: high ACh, low NE).  
- **Stage transitions** that reset precision weighting and prediction windows.  

Across a full night, the system:

- Prunes prediction errors (SWS).  
- Integrates and updates priors (REM).  
- Recalibrates neuromodulator baselines (MOD).  
- Restores autonomic flexibility (AUTO).

When architecture is intact, the stack gets a **structured overnight reset**. When architecture is disrupted, the stack carries yesterday’s distortions forward.

---

## The Complete Chain

```text
Circadian phase + homeostatic sleep pressure
→ Sleep onset (N1)
→ N2 (spindles, gating, integration)
→ SWS (delta, pruning, autonomic recovery)
→ REM (ACh-dominant, prior updating, emotional integration)
→ Ultradian cycling of NREM/REM across the night
→ Stage proportions + transitions determine:
   - How much prediction error is pruned (SWS)
   - How much prior content is updated (REM)
   - How neuromodulator baselines are reset (MOD)
   - How autonomic flexibility is restored (AUTO)
→ Next-day precision weighting, prediction-window width,
   cognitive stability, emotional regulation, and autonomic tone
```

---

## Link-by-Link Mechanism

### Link 1: Sleep onset and NREM staging — gating and setup

Sleep onset (N1) and N2 establish the **gating environment**:

- Sensory input is reduced but not eliminated.  
- Spindles in N2 gate external input and support memory integration.  

This sets the stage for deeper SWS and REM processes. N2 is the **transition scaffold**: it prepares the system to move into high-amplitude pruning (SWS) and high-plasticity updating (REM).

**Chain completeness:** Scaffolding. N1/N2 roles are well-characterized in sleep science; their explicit regulatory framing here is an integration step.

---

### Link 2: SWS — prediction-error pruning and autonomic recovery

SWS is characterized by:

- High-amplitude delta activity.  
- Reduced NE and sympathetic output.  
- Strong vagal tone and metabolic downshift.

Mechanistically:

- Synaptic downscaling removes low-value or stale priors.  
- Prediction-error “noise” is pruned, reducing cognitive clutter.  
- Autonomic systems get a **low-arousal, high-vagal recovery window**.

SWS is the **overnight pruning pass**: it reduces the volume of prediction errors the system must carry into the next day.

**Chain completeness:** Load-bearing. SWS as synaptic downscaling and autonomic recovery is well-supported.

---

### Link 3: REM — prior updating and emotional integration

REM is characterized by:

- High ACh, low NE.  
- Vivid internally generated imagery.  
- Emotional memory replay and integration.

Mechanistically:

- Priors are updated using replayed experiences in a low-NE environment, reducing over-weighting of threat signals.  
- Emotional memories are integrated into broader narratives, reducing fragmentation.  
- Prediction windows widen: the system becomes more capable of tolerating variation without catastrophic prediction error.

REM is the **overnight updating pass**: it reshapes priors and emotional models.

**Chain completeness:** Load-bearing. REM’s role in memory consolidation and emotional processing is well-documented.

---

### Link 4: Stage transitions — precision-gain reset

Transitions between SWS and REM:

- Shift neuromodulator baselines.  
- Reconfigure precision weighting across sensory and cognitive channels.  

Each cycle:

- Prunes (SWS) → updates (REM) → recalibrates (transition).  

This repeated cycling is the **precision-gain reset mechanism**: it prevents the system from locking into hyperprecise priors or permanently noisy signals.

**Chain completeness:** Scaffolding. Stage-transition dynamics are empirically described; their precision-gain framing is an architectural integration.

---

### Link 5: Architectural disruption — upward propagation

When architecture is disrupted (e.g., reduced SWS, reduced REM, fragmented cycles):

- Pruning is incomplete → prediction-error noise persists.  
- Updating is incomplete → priors remain rigid or maladaptive.  
- Neuromodulator baselines drift → precision-gain calibration is off.  
- Autonomic recovery is incomplete → HRV flattens, vagal tone remains low.

These effects propagate upward through:

- MOD↔COG — miscalibrated precision gain.  
- COG↔INTERO — impaired interoceptive prior updating.  
- AUTO↔MOD — reduced autonomic flexibility.

**Chain completeness:** Scaffolding approaching load-bearing. Clinical correlations between sleep disruption and psychiatric/autonomic dysregulation are strong; this contract formalizes the mechanism.

---

## Operating States — Predicting Conditions From First Principles

| Condition                         | Contract Failure Mode                         | Mechanism                                                                 | Derivable? |
|----------------------------------|-----------------------------------------------|---------------------------------------------------------------------------|-----------|
| Insomnia with intact clearance   | Architectural fragmentation                   | SWS/REM cycles disrupted → pruning/updating incomplete                    | Yes       |
| PTSD with REM suppression        | REM-specific architectural bias               | Threat priors not updated → emotional memories remain rigid               | Yes       |
| Depression with reduced SWS      | Pruning deficit                               | Synaptic downscaling impaired → cognitive noise, rumination               | Yes       |
| Anxiety with fragmented REM      | Updating deficit                              | Emotional priors partially updated → persistent hypervigilance            | Yes       |
| OSA (sleep apnea)                | Repeated architectural interruption           | Stage transitions repeatedly broken → neuromodulator and autonomic drift  | Yes       |
| Narcolepsy                       | Stage-boundary instability                    | REM intrusions into wake → prediction-window and precision-gain instability | Yes     |

Every entry is derivable from the architecture logic; most are already supported by sleep and psychiatric literature.

---

## Drug and Intervention Effects Through This Contract

| Intervention             | Mechanism via SLEEP                               | Effect                                                  |
|--------------------------|---------------------------------------------------|---------------------------------------------------------|
| SSRIs / SNRIs            | Alter REM proportion and architecture             | Change emotional prior updating and threat integration  |
| Sedative-hypnotics       | Increase total sleep, distort architecture        | Clearance preserved, pruning/updating distorted         |
| CBT-I (insomnia therapy) | Restore architecture and timing                   | Re-establish pruning/updating cycles                    |
| CPAP (for OSA)           | Prevent stage interruption                        | Restore continuous SWS/REM cycling                      |
| Exercise (timed)         | Shift SWS amplitude and architecture              | Enhance pruning and autonomic recovery                  |
| Psychedelics (acute)     | Interact with REM-like states and replay          | Amplify prior updating windows                          |

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing**  
REM proportion should predict **memory consolidation** and **prior-updating** outcomes across diagnoses, independent of total sleep time.

**Prediction 2 — Chain completeness: Scaffolding**  
SWS amplitude and continuity should predict **autonomic recovery** (HRV, vagal tone) and next-day precision-gain stability.

**Prediction 3 — Chain completeness: Scaffolding**  
Architectural disruption (e.g., OSA, fragmented REM) should show **systematic upward propagation** into MOD↔COG and COG↔INTERO failure modes.

**Prediction 4 — Chain completeness: Predictive**  
REM and SWS proportions should show **compensatory coupling**: perturbation of one stage produces predictable adjustments in the other, with distinct regulatory signatures.

**Prediction 5 — Chain completeness: Predictive**  
Interventions that restore architecture (CBT-I, CPAP) should improve regulatory outcomes across multiple diagnoses, not just sleep complaints.

---

## Failure Modes

**Clearance-only framing:**  
Treating sleep purely as glymphatic clearance (GLYPH↔AUTO) misses architectural failure modes. Clearance can be intact while architecture is fragmented, leaving priors and precision-gain miscalibrated.

**Total-sleep-time bias:**  
Clinical focus on “hours slept” ignores stage proportions and transitions. Eight hours of fragmented, REM-suppressed sleep is not equivalent to eight hours of intact architecture.

**Phase-only interventions:**  
Circadian-phase corrections (Temporal Layer) without architectural repair improve timing but not pruning/updating. The system falls asleep at the right time but does the wrong work.

**Sedation vs architecture:**  
Sedative drugs can increase sleep duration while degrading architecture. Symptoms improve transiently (less wakefulness) but regulatory drift continues.

---

## Adjacent Contracts

**Below (feeds into SLEEP):**

- GLYPH↔AUTO — clearance capacity sets the background for architectural work.  
- Temporal Layer — circadian phase and sleep timing determine when architecture can run.

**Above (fed by SLEEP):**

- MOD↔COG — precision-gain calibration depends on overnight neuromodulator cycling.  
- COG↔INTERO — interoceptive prior updating depends on REM-mediated integration.  
- AUTO↔MOD — autonomic flexibility depends on SWS-mediated recovery.

---

## Origin Note

This contract arises from repeated fragments across GLYPH↔AUTO, MOD↔COG, and the Temporal Layer that all point to the same missing variable: **sleep architecture as a regulatory layer**. Clinical patterns — insomnia, OSA, REM suppression, fragmented sleep — consistently show cross-diagnostic regulatory consequences that cannot be explained by clearance or timing alone.

SLEEP formalizes the idea that:

- The stack gets one structured overnight opportunity to prune, update, and recalibrate.  
- The quality of that opportunity is determined by **architecture**, not just duration.  

*Chain status: Links 2–3 are load-bearing. Links 1, 4–5 are scaffolding approaching load-bearing. Operating states and intervention mappings are derivable and partially confirmed. Predictions are ready for systematic empirical assembly.*
