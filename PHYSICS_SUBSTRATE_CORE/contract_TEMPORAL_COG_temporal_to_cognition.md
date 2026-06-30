# Contract: TEMPORAL → COG
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_TEMPORAL_COG_temporal_to_cognition.md`

**Ontology Layer:**  
PHYSICS_SUBSTRATE_CORE

**Direction of Influence:**  
TEMPORAL → COG

**Upstream Dependencies:**  
- TEMPORAL → SLEEP  
- SLEEP → MOD  

**Downstream Dependencies:**  
- COG → WINDOWS  
- COG → REASON  

**Cross‑Contract References:**  
- `contract_SLEEP_sleep_to_cognition_autonomic_modulation.md`  
- `contract_WINDOWS_COG_window_geometry_to_cognition.md`  
- `contract_MOD_COG_modulation_to_cognition.md`

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary


**Input layer (TEMPORAL):**

- Circadian phase (CT)
- Melatonin onset timing (DLMO)
- Cortisol awakening response (CAR)
- Core body temperature minimum (CBTmin)
- Sleep pressure (adenosine accumulation)
- Light-entrained SCN output
- Phase angle between sleep midpoint and melatonin onset

**Output layer (COG):**

- Prediction window width
- Cognitive horizon length
- Prior dominance vs. correctability
- Precision-gain baseline
- Cognitive flexibility vs. rigidity
- Temporal projection capacity
- Rumination vs. generativity balance

**Primary crossover point:** Circadian phase sets the baseline precision-gain parameter for the cognitive layer — the floor and ceiling within which the moment-to-moment oscillation described in ANCHOR↔COG operates. When phase is delayed, misaligned, or unstable, the cognitive system shifts toward narrow windows, rigid priors, short horizons, and reduced correctability regardless of psychological content. The mechanism runs through MOD↔COG: the SCN drives the neuromodulatory environment that sets precision-gain defaults, and TEMPORAL↔COG formalizes the cognitive output of that neuromodulatory phase-setting.

**Key risk:** Chronic circadian misalignment produces a trait-like cognitive phenotype — rigidity, anxiety, short-horizon reasoning, and runaway priors — that is phenotypically identical to the states produced by anchor collapse, chronic sympathetic activation, or interoceptive degradation. Without distinguishing the temporal mechanism from the other precision-gain sources, treatment targets the wrong layer. A person whose cognitive rigidity is primarily circadian in origin will not respond to anchor repair, interoceptive training, or cognitive intervention at the same rate they would respond to phase correction. The misattribution is common because the cognitive output is indistinguishable at the surface.

---

## The Complete Chain

```
SCN phase signal (light-entrained)
  → Cortisol awakening response (CAR)
    → Serotonin availability ramp
      → Dopamine responsivity arc
        → Noradrenergic tone setting
          → Neuromodulatory gain baseline (MOD layer)
            → Precision-gain parameter set for cognitive layer

  Simultaneously:
    DLMO (melatonin onset)
      → Marks transition toward high-precision phase
        → Prediction window ceiling begins to lower
          → Recursive thinking probability rises
            → Prior dominance increases

  Adenosine accumulation (sleep pressure)
    → Reduces model updating capacity
      → Tolerance for ambiguity falls
        → Prior correctability decreases

  Phase delay / misalignment:
    → Precision baseline chronically elevated
      → Window cannot widen to full capacity even on inhale
        → ANCHOR↔COG anchor input ceiling lowered by temporal floor
          → Compound precision lock:
              temporal misalignment × respiratory mechanics × prior load
                → Trait-like cognitive rigidity phenotype

  Phase correction:
    → Precision baseline normalizes
      → Window ceiling rises
        → ANCHOR↔COG can deliver full oscillation range
          → Cognitive flexibility restored
```

---

## Mechanistic Chain

### Link 1 — SCN phase → neuromodulatory gain baseline

The suprachiasmatic nucleus drives a 24-hour modulation of the neuromodulatory environment that sets the starting conditions for every cognitive cycle within that phase. Cortisol slope from the awakening response, serotonin availability across the morning, dopamine responsivity across the active phase, and noradrenergic tone through the afternoon are all phase-determined outputs of the SCN signal. These are the inputs to MOD↔COG. TEMPORAL↔COG does not duplicate MOD↔COG — it formalizes that MOD layer state is not randomly variable or purely load-determined: it oscillates on a 24-hour schedule set upstream of any in-session regulatory event. The neuromodulatory baseline that enters MOD↔COG each moment is phase-stamped.

**Chain completeness:** Load-bearing. SCN control of cortisol, serotonin, dopamine, and noradrenergic rhythms is established across circadian neuroscience. The downstream MOD→COG consequences follow from [[contract_MOD_COG_modulation_to_cognition]].

---

### Link 2 — Neuromodulatory gain baseline → cognitive precision floor

Circadian phase determines how tightly the generative model holds its priors, how easily prediction error updates them, and how wide the prediction window can open within any given hour. This is not metaphor — it is a downstream consequence of the neuromodulatory phase-setting described in Link 1. The serotonin and dopamine environment that MOD↔COG outputs as a precision-gain parameter is itself phase-modulated. In the early active phase, precision baseline is lower — windows open more readily, priors are more correctable, cognitive flexibility is higher. As phase advances toward the biological night, precision baseline rises — windows narrow, priors become stickier, flexibility decreases.

This is why ND individuals with delayed circadian phase show higher anxiety, lower flexibility, shorter temporal horizons, and more rigid priors even in neutral cognitive contexts: their phase has placed them in a chronically elevated precision state during hours when the social and occupational environment demands performance. The cognitive phenotype is not psychological — it is a phase consequence.

**Chain completeness:** Load-bearing via MOD↔COG. The phase-determination of neuromodulatory state is established. The precision-gain consequence at the cognitive layer follows directly from the MOD→COG mechanism.

---

### Link 3 — DLMO → prediction window narrowing onset

Dim-light melatonin onset marks the transition into the high-precision phase of the circadian cycle. Functionally, DLMO predicts when the cognitive window begins to narrow, when horizon length starts to collapse, when recursive thinking probability rises, and when prior dominance over incoming evidence increases. This is the circadian equivalent of the exhale gate described in ANCHOR↔COG — a phase-gated transition toward precision lock that occurs on a timescale of hours rather than seconds, but through the same downstream precision-gain mechanism.

The clinical implication is that DLMO timing is a cognitive phenotype variable, not just a sleep variable. A person with DLMO at 21:00 has a different cognitive window trajectory across the day than a person with DLMO at 23:30. In the delayed-phase individual, the high-precision window extends later into the night — producing the characteristic late-night clarity, generative thinking, and reduced anxiety that delayed-phase individuals report. The cost is morning precision elevation that the aligned individual does not experience.

**Chain completeness:** Scaffolding. DLMO as a sleep-phase marker is load-bearing. The cognitive-window consequence as the downstream precision effect of melatonin-onset timing is a framework derivation — mechanistically complete, requiring dedicated measurement of prediction window width against DLMO timing within individuals.

---

### Link 4 — Adenosine accumulation → prior correctability reduction

Sleep pressure from adenosine accumulation progressively reduces the cognitive layer's capacity to update models from incoming evidence. Cognitive flexibility falls. Tolerance for ambiguity narrows. Priors become increasingly difficult to correct against contradicting signals. This is the mechanism behind late-night argument escalation, late-night anxiety amplification, and the characteristic late-night loop quality where the same thoughts repeat with increasing emotional weight and decreasing possibility of resolution.

The prediction window does not simply narrow under sleep pressure — the asymmetry between prior dominance and incoming signal weighting shifts so that the prior drives output while evidence is discounted. This is a correctability failure, not merely a window-width failure. The distinction matters for intervention: restoring window width through external anchoring (SOC↔ANCHOR) will not restore prior correctability if adenosine load is the primary driver, because correctability is an updating-capacity variable that external anchoring does not directly address.

**Chain completeness:** Load-bearing. Adenosine accumulation and cognitive flexibility reduction are established across sleep deprivation literature. The precision-weighting framing — prior dominance rising as adenosine accumulates — is a framework derivation of the established empirical pattern.

---

### Link 5 — Phase misalignment → chronic precision elevation

When circadian phase is persistently delayed relative to the social and occupational schedule — social jetlag, shift work, delayed sleep phase disorder — the cognitive layer operates in chronically elevated precision state during required active hours. The neuromodulatory baseline entering MOD↔COG is phase-stamped at a point that would correspond, in an aligned individual, to late evening. Prediction windows remain narrow. Priors become sticky. Cognitive flexibility is reduced. Anxiety threshold lowers. Temporal projection capacity shortens.

The compound effect with ANCHOR↔COG is the critical architectural consequence: the anchor mechanism described in ANCHOR↔COG operates within a ceiling set by the temporal precision floor. If the temporal floor is elevated, anchor repair raises window width but cannot exceed the ceiling that phase misalignment has lowered. This is why anchor interventions — breathwork, proprioceptive training, interoceptive development — produce partial but incomplete results in chronically misaligned individuals. The ceiling has not moved. Circadian realignment is a prerequisite for full anchor repair in this population, not an optional add-on.

**Chain completeness:** Scaffolding. Phase misalignment effects on mood, flexibility, and cognitive performance are established. The compound ceiling-lowering interaction with ANCHOR↔COG is a framework derivation — mechanistically complete, requiring prospective measurement of anchor intervention response stratified by circadian alignment status.

---

### Link 6 — Phase correction → cognitive reopening

When circadian phase is realigned — through morning light, consistent wake timing, appropriately timed low-dose melatonin, or exercise timing — the precision-gain baseline drops back to the phase-appropriate level for the active hours. The prediction window ceiling rises. Priors become correctable. Cognitive flexibility returns. Temporal projection capacity extends. The same cognitive architecture that appeared rigid and anxiety-prone under misalignment begins to operate at full capacity.

This is why morning light, consistent wake time, melatonin timing, and exercise timing produce cognitive improvements that appear disproportionate to their obvious mechanisms — they are not producing marginal circadian benefits. They are removing a ceiling that was preventing the cognitive layer from accessing its full precision range. The cognitive improvement from phase correction in a misaligned individual is not mood improvement secondarily improving cognition. It is direct precision-floor reduction restoring the window range that was always mechanically available but blocked by the temporal constraint.

**Chain completeness:** Scaffolding. Phase correction effects on mood and cognition are established. The precision-floor mechanism as the specific cognitive reopening pathway is a framework derivation requiring simultaneous measurement of DLMO shift, precision-gain markers, and cognitive window width within phase correction interventions.

---

## Failure Modes

**Misattribution of phase-driven rigidity to psychological cause:**
The cognitive output of circadian misalignment — narrowed window, rigid priors, reduced flexibility, anxiety, rumination — is phenomenologically identical to the outputs of anchor collapse, chronic sympathetic activation, and prior dominance from interoceptive degradation. The person experiencing it and the clinician observing it both reach for psychological explanation. The cognitive rigidity gets attributed to negative thinking patterns, catastrophizing, avoidance, or personality. The intervention that follows — cognitive restructuring, exposure, psychotherapy — targets the precision output rather than the phase input. Results are limited. The treatment resistance gets attributed to the same psychological variables that were incorrectly identified as causes. Phase correction is never attempted because the mechanism was never identified. This is the primary clinical failure mode of TEMPORAL↔COG and it is systematic rather than occasional — because nothing in standard clinical assessment measures circadian phase.

**Therapeutic timing mismatch:**
Interventions that require prediction window width — cognitive restructuring, exposure therapy, trauma processing, perspective-taking, values clarification — are routinely scheduled without reference to the client's circadian phase or daily precision curve. For a delayed-phase individual, a 9am therapy session places the intervention in the highest-precision window of their day. The cognitive flexibility required to update priors, tolerate ambiguity, and hold multiple perspectives is at its lowest. The same intervention at 11am or 1pm in the same individual — after the cortisol slope has normalized and the high-precision morning window has passed — would have access to a meaningfully wider prediction window. Session timing is an uncontrolled variable in most psychotherapy research, which means the effect size literature systematically underestimates therapeutic efficacy by averaging across phase-appropriate and phase-inappropriate delivery.

**Social jetlag as invisible load:**
Chronic partial sleep restriction from social schedule misalignment — consistent across five or more days per week in a large proportion of the working population — maintains adenosine and precision-floor elevation that is attributed to stress, workload, or personality rather than to its circadian mechanism. The cognitive presentation — reduced flexibility, short horizon, difficulty with ambiguity, tendency toward binary reasoning — is functionally indistinguishable from a trait-level regulatory deficit. Interventions targeted at stress management, cognitive performance, or mood will show partial results while the temporal floor remains elevated. The misattribution is self-reinforcing: the reduced cognitive flexibility from phase misalignment makes it harder to recognize the temporal mechanism, which requires the kind of multi-variable model-building that the narrowed window makes difficult.

**Phase correction interventions without compound repair:**
Morning light and melatonin timing are effective phase-correction tools. Their cognitive benefit in misaligned individuals can be substantial. The failure mode is when phase correction is pursued as a standalone intervention in individuals with compound precision elevation — where anchor collapse, chronic sympathetic activation, or interoceptive degradation are also contributing. Phase correction raises the ceiling. It does not repair the floor being compressed from below. A person with both circadian misalignment and degraded respiratory mechanics will show cognitive improvement from phase correction — but will plateau before full window width is restored. Correctly sequencing TEMPORAL↔COG correction as the prerequisite for ANCHOR↔COG to deliver its full range is the compound intervention architecture this contract specifies.

**ND phase delay attributed to preference or avoidance:**
Delayed circadian phase in ND individuals is frequently attributed to behavioral choice, screen avoidance failure, or executive function deficits. The framework identifies it as a regulatory architecture variable: ND populations show higher rates of circadian phase delay through a combination of reduced light sensitivity, altered melatonin timing profiles, and chronic sympathetic activation suppressing the circadian amplitude that keeps phase locked. The cognitive phenotype that follows — the late-night clarity, morning rigidity, anxiety elevation, and social jetlag susceptibility — is not a behavioral profile. It is a phase consequence. Treating it as a behavioral problem with behavioral solutions targets the output. Phase correction through circadian anchoring addresses the mechanism.

---

## Operating States

| State | Circadian Phase | Precision Baseline | Cognitive Output |
|---|---|---|---|
| **Aligned** | Stable DLMO, consistent wake, matched schedule | Phase-appropriate oscillation | Full window range available; ANCHOR↔COG can deliver maximum amplitude |
| **Delayed** | Late DLMO, late CBTmin, early social requirements | Elevated during required active hours | Narrow window in morning, rigid priors, anxiety; late-night clarity is phase-appropriate but socially mismatched |
| **Advanced** | Early DLMO, early CBTmin | Low precision morning; elevated afternoon | Short cognitive horizon; low generativity in afternoon; early fatigue |
| **Social jetlag** | Internal phase vs. social schedule mismatch | Chronically partially elevated | Trait-like rigidity, short horizon, cognitive performance below architectural capacity |
| **Sleep-deprived** | High adenosine regardless of phase alignment | Prior dominance elevated | Low correctability; evidence discounting; emotional amplification of priors |
| **Phase-corrected** | DLMO aligned to schedule | Normal phase oscillation restored | Full ANCHOR↔COG ceiling available; flexibility, horizon, correctability restored |

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Scaffolding**
Circadian phase — measured as DLMO timing relative to required wake time — should predict cognitive flexibility task performance independent of mood, personality, sleep duration, and stress load. Phase delay should predict rigid prior maintenance and reduced prediction error utilization on tasks requiring perspective-shift or model update. This directly tests the temporal precision-floor mechanism against psychological and load-based alternatives.

**Prediction 2 — Chain completeness: Scaffolding**
Delayed-phase individuals should show measurable prediction window narrowing earlier in their active day — relative to their DLMO — than aligned individuals at equivalent clock times. The window-narrowing should track phase rather than clock time, distinguishing the circadian mechanism from general fatigue or workload effects.

**Prediction 3 — Chain completeness: Scaffolding**
Morning light intervention producing measurable DLMO advance should produce cognitive flexibility improvement detectable within two to four weeks — on the timescale of phase shift, not mood change. The cognitive improvement should precede or be dissociable from mood improvement, establishing the precision-floor mechanism as independent of the mood pathway through which light therapy is typically explained.

**Prediction 4 — Chain completeness: Scaffolding**
Earlier melatonin administration should produce measurable cognitive flexibility improvement the following morning, detectable as increased prediction error utilization on cognitive updating tasks, with effect size correlating with the degree of phase advance produced rather than with the sedative effect of the melatonin dose.

**Prediction 5 — Chain completeness: Predictive**
ND individuals with documented delayed circadian phase should show cognitive flexibility profiles that track their phase curve rather than task demands — high flexibility late in the day, low flexibility early, with the crossover point correlating with their individual DLMO rather than with clock time or social convention. This predicts that ND cognitive variability is substantially phase-driven rather than state-driven, separable from mood and load variables.

**Prediction 6 — Chain completeness: Predictive**
Psychotherapy interventions requiring prediction window width — cognitive restructuring, exposure, values work, perspective-taking — should show larger effect sizes when delivered during the client's circadian low-precision window (typically late morning to early afternoon in aligned individuals, later in delayed-phase individuals) than when delivered during high-precision windows. Session timing is currently an uncontrolled variable. Stratifying existing outcome data by estimated phase would be an immediately testable retrospective analysis.

**Prediction 7 — Chain completeness: Predictive**
Anchor repair interventions (breathwork, bilateral movement, interoceptive training) should show larger response in individuals who have undergone prior circadian alignment than in equivalent individuals who have not — because phase correction raises the ceiling within which anchor repair operates. The interaction effect between phase alignment and anchor intervention response would confirm that TEMPORAL↔COG sets the ceiling for ANCHOR↔COG output and must be addressed before anchor interventions can deliver their full range.

---

## Intervention Effects Through This Contract

| Intervention | Mechanism | Effect |
|---|---|---|
| Morning bright light (10,000 lux, ≥20 minutes within 30 minutes of wake) | Direct SCN entrainment → cortisol awakening response amplification → phase advance | Raises precision-floor during required active hours; most accessible phase correction intervention; cognitive benefit precedes mood benefit |
| Consistent wake time (including weekends) | Reduces social jetlag amplitude → stabilizes SCN phase signal | Prevents chronic adenosine and precision-floor elevation from schedule mismatch; most sustainable phase maintenance intervention |
| Low-dose melatonin (0.5mg) timed 5 hours before current DLMO | Phase advance without sedative effect → earlier precision-floor transition | Shifts cognitive window curve earlier; most effective when dose is small and timing is circadian rather than hypnotic |
| Exercise timing (morning or early afternoon) | Cortisol-phase reinforcement + temperature rhythm anchoring | Secondary phase anchor; reinforces SCN signal and resists drift; less powerful than light but synergistic |
| Evening light restriction | Reduces circadian phase delay from late-spectrum light | Prevents late-DLMO drift; most critical for screen-heavy populations; enables morning light to produce phase advance rather than maintaining drift |
| Cognitive therapy session timing (late morning / early afternoon) | Delivers intervention during client's low-precision window | Increases prediction window width available for prior-updating during session; directly addresses therapeutic timing mismatch failure mode |
| Circadian phase assessment (DLMO measurement or proxy estimation) | Identifies individual phase position before any other intervention | Prerequisite for correctly sequencing TEMPORAL↔COG correction with ANCHOR↔COG repair; enables personalized intervention timing rather than population-average scheduling |

---

## Adjacent Contracts

**Below — feeds into this contract:**
- MOD↔COG: the neuromodulatory gain baseline that this contract phase-modulates is the same MOD layer output; TEMPORAL↔COG establishes that MOD state is not random — it runs on a 24-hour phase schedule set upstream
- ANCHOR↔COG: the moment-to-moment oscillation described in ANCHOR↔COG operates within the precision ceiling set by TEMPORAL↔COG; phase misalignment lowers the ceiling that anchor repair can reach
- SLEEP↔COG: sleep architecture quality and continuity determine adenosine clearance rate and slow-wave recovery of the neuromodulatory baseline that the next circadian cycle begins from; SLEEP↔COG feeds directly into the starting conditions of each new TEMPORAL↔COG cycle

**Above — receives output from this contract:**
- COG↔REASON: prediction window width — whether phase-set, anchor-set, or load-set — determines reasoning mode and fallacy group activation; TEMPORAL↔COG is a third independent source of the precision state that COG↔REASON reads
- STRESS↔TRANSITION: chronic precision elevation from persistent phase misalignment is a load pathway to the acute-to-chronic transition; the phase mechanism provides a distinct route to the same attractor that chronic sympathetic activation and anchor collapse produce
- SOC↔COG: mentalizing capacity and model-of-other depth are window-width-dependent; phase misalignment reduces both, with the reduction tracking the individual's phase curve rather than social context

**Convergence note:**
TEMPORAL↔COG establishes the temporal floor for the precision-gain system, operating on a 24-hour timescale beneath the moment-to-moment oscillations described in ANCHOR↔COG. The full compound precision state at any moment is therefore the product of three simultaneously operating layers: the temporal floor (TEMPORAL↔COG), the oscillatory range available within that floor (ANCHOR↔COG), and the load applied by incoming prediction error and social demand (MOD↔COG, SOC↔COG). Single-layer intervention — phase correction alone, anchor repair alone, load reduction alone — addresses one constraint while the others remain. This explains the clinical pattern where each intervention produces real but partial improvement. Full cognitive capacity restoration requires the compound state to be addressed at all three layers: phase correction first to raise the ceiling, then anchor repair to maximize the oscillation range within that ceiling, then load management to prevent the compound system from being repeatedly overwhelmed.

---

## Origin Note

This contract emerged from a gap identified in the gap analysis: circadian phase was referenced repeatedly as a modulator of cognitive state but had no formal contract home. MOD↔COG contains the neuromodulatory mechanism; SLEEP↔COG addresses sleep architecture; neither addressed the specifically temporal — the 24-hour phase modulation that sets the cognitive layer's baseline parameters before any in-session regulatory event occurs.

The diagnostic value of formalizing the contract became clear at the intersection with ANCHOR↔COG. The anchor mechanism describes moment-to-moment oscillation. But the range of that oscillation is not fixed — it has a ceiling. Identifying the ceiling as phase-set rather than architecturally fixed explains why anchor interventions produce partial results in some populations and full results in others. The temporal floor is the missing variable. TEMPORAL↔COG places it in the stack.

The ND implication followed directly: delayed circadian phase in ND populations produces a cognitive phenotype that has been systematically attributed to psychological, behavioral, and motivational variables when it is a phase