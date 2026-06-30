---
Contract: "MOD → COG"
Expanded_Filename: "contract_MOD_COG_modulation_to_cognition.md"

Ontology_Layer: "02_GEOMETRY_PREDICTION_WINDOWS"
Upstream_Dependencies:
  - "AUTO → MOD"
  - "WINDOWS → COG"

Downstream_Dependencies:
  - "COG → REASON"
  - "COG → INTERO"

Cross_References:
  - "contract_AUTO_MOD_autonomic_to_modulation.md"
  - "contract_WINDOWS_COG_window_geometry_to_cognition.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: MOD → COG
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_MOD_COG_modulation_to_cognition.md`

**Ontology Layer:**  
GEOMETRY_PREDICTION_WINDOWS

**Direction of Influence:**  
MOD → COG

**Upstream Dependencies:**  
- AUTO → MOD  
- WINDOWS → COG  

**Downstream Dependencies:**  
- COG → REASON  
- COG → INTERO  

**Cross‑Contract References:**  
- `contract_AUTO_MOD_autonomic_to_modulation.md`  
- `contract_WINDOWS_COG_window_geometry_to_cognition.md`

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

**Input layer:** MOD — neuromodulatory environment; dopamine, serotonin, norepinephrine, ECS tone, GABA/glutamate balance

**Output layer:** COG — predictive processing, prediction error weighting, belief updating, attention, working memory, cognitive flexibility, behavioral output

**Primary crossover point:** Dopamine D2 receptor-mediated precision weighting of unsigned prediction errors in superior frontal cortex and dorsal anterior cingulate — determining how much surprise signals update beliefs

**Key risk:** Shortcircuiting this contract produces the full spectrum of psychiatric presentations — not as distinct diseases but as different failure modes of the same precision gain calibration mechanism. Treating downstream behavioral outputs without addressing MOD layer calibration produces symptomatic relief without mechanism correction.

**Distinguishing feature:** This is the contract where the most psychiatric diagnoses mechanistically live. Psychosis, depression, anxiety, OCD, ADHD, and schizotypy are all derivable from this contract by varying which neuromodulator is miscalibrated and in which direction. The model predicts this before looking at the diagnostic literature — and the literature confirms it.

---

## Why This Contract Is the Diagnostic Hub

Every contract below this one in the stack is producing inputs that calibrate the MOD layer. The MET contract sets fuel availability for neurotransmitter synthesis. The MICRO contract produces serotonin precursors and SCFA-mediated vagal tone. The IMMUNE contract modulates neuroinflammation that degrades monoamine function. The AUTO contract calibrates ECS tone through vagal input. Everything converges here before the cognitive layer ever receives a signal.

This means that a psychiatric presentation is almost never a COG layer failure in isolation. It is almost always a MOD layer calibration failure driven by one or more upstream contract disruptions. Treating the COG layer directly — therapy, cognitive interventions — while the MOD layer remains miscalibrated is asking cognition to correct itself using a broken instrument.

---

## The Neuromodulatory Architecture

The MOD layer has four primary components that operate in concert:

**Dopamine** — prediction error currency. Encodes the difference between expected and actual outcomes. Signed prediction errors (better or worse than expected) drive reward learning via ventral striatum. Unsigned prediction errors (surprise regardless of valence) drive belief updating via prefrontal cortex. Dopamine D2 receptors mediate the precision weighting of these signals — determining how much each surprise updates the model of the world.

**ECS (Endocannabinoid System)** — master gain controller. Retrograde signaling system that modulates the release of all other neuromodulators — dopamine, serotonin, norepinephrine — by inhibiting presynaptic terminals. ECS sets the gain floor on the entire MOD layer. CB1 receptors in the locus coeruleus regulate norepinephrine. CB1 in the dorsal raphe regulates serotonin. CB1 in the ventral tegmental area regulates dopamine. The ECS is the gain control knob that sits above all three monoamine systems simultaneously.

**Serotonin** — cognitive flexibility and temporal uncertainty. Mediates waiting under uncertainty, behavioral flexibility, and the tolerance for ambiguity required to hold open the prediction window. Serotonin depletion in the prefrontal cortex specifically impairs cognitive flexibility. This is the MOD layer substrate of the inhale/exhale oscillation — serotonin supports the capacity to remain in sampling mode without forcing premature selection.

**Norepinephrine** — signal-to-noise amplification. Released from the locus coeruleus, norepinephrine sharpens the signal-to-noise ratio of cortical processing. Low NE = flat, undifferentiated signal. High NE = heightened signal clarity but also heightened noise. The inverted-U relationship of NE with cognitive performance is exactly the precision gain dial — too little and signals don't register, too much and noise becomes indistinguishable from signal.

---

## The Complete Chain

```
AUTO layer output (vagal tone, RSA, sympathetic/parasympathetic balance)
  → ECS tone calibration (via NTS → brainstem CB1)
    → Modulation of dopamine release (VTA → PFC/striatum)
      + Modulation of serotonin release (DRN → mPFC)
      + Modulation of norepinephrine release (LC → cortex)
        → Dopamine D2 receptor-mediated precision weighting
          in superior frontal cortex and dACC
            → Unsigned prediction error signal calibration
              → Belief updating rate and accuracy
                → Cognitive flexibility / attractor state stability
                  → Behavioral output
```

**Feedback path:** Cognitive outcomes → prediction error signal → dopamine update → modifies future precision weighting → loop closes. Learning is this loop running correctly.

---

## Link-by-Link Mechanism

### Link 1: ECS tone → Monoamine release modulation
CB1 receptors are located in the locus coeruleus (regulating norepinephrine release), the dorsal raphe nucleus (regulating serotonin release), and the ventral tegmental area (regulating dopamine release). ECS modulates all three monoamine systems by inhibiting presynaptic terminals — reducing their release when ECS tone is high, permitting higher release when ECS tone is low. This makes the ECS the architectural master of the entire MOD layer — it sits above dopamine, serotonin, and norepinephrine and sets their operational envelope simultaneously.

CB1 ablation results in anhedonia, passive stress-coping behavior, and higher sensitivity to depressive-like symptoms — confirming that ECS tone is load-bearing for reward function, not incidental. Enhancement of CB1 signaling produces antidepressant effects through modulation of serotonin neuronal activity.

**Chain completeness:** Load-bearing. CB1 expression at LC, DRN, and VTA with documented effects on monoamine release is mechanically established.

---

### Link 2: Dopamine D2 receptors → Precision weighting of prediction errors
Dopamine D2 receptor activation in the superior frontal cortex and dorsal anterior cingulate cortex mediates the precision weighting of unsigned prediction errors — the surprise signals that drive belief updating. When D2 receptor function is blocked (sulpiride), precision weighting is significantly diminished. When D2 receptors are agonized (bromocriptine), precision weighting is enhanced. This is the molecular implementation of Bayesian inference — the brain is literally using dopamine to calibrate how much to update its world model in response to unexpected events.

This mechanism is impaired in psychosis. Patients with first-episode psychosis fail to take into account the precision of the environment when updating beliefs — they weight all prediction errors equally regardless of environmental noise level. Precision weighting of cortical prediction error signals is the key mechanism through which dopamine modulates inference and contributes to the pathogenesis of psychosis.

**Chain completeness:** Load-bearing. D2-mediated precision weighting in superior frontal cortex and dACC is confirmed across multiple studies with pharmacological and fMRI validation. Impairment in psychosis is replicated.

---

### Link 3: Serotonin → mPFC → Cognitive flexibility
Serotonergic input to the medial prefrontal cortex acts as a powerful modulator of neuronal activity and regulates cognitive flexibility specifically. Serotonin depletion in the PFC of primates impairs cognitive flexibility. 5-HT1A receptor agonist infusion into the prelimbic PFC improves attention accuracy and induces anxiolytic effects. Optogenetic stimulation of dorsal raphe to mPFC serotonergic projections promotes waiting when reward timing is uncertain — directly implementing the capacity to remain in sampling mode rather than forcing premature selection.

This is the serotonin mechanism behind behavioral flexibility — the capacity to hold multiple hypotheses simultaneously before committing to selection. SSRIs acting on this pathway increase the tolerance for uncertainty, which is why they reduce anxiety — they're extending the window of open sampling before forced closure.

**Chain completeness:** Load-bearing. DRN-mPFC serotonergic projections and their specific role in cognitive flexibility are mechanically documented across pharmacological and optogenetic studies.

---

### Link 4: NE from LC → Signal-to-noise ratio in cortex
Norepinephrine from the locus coeruleus modulates cortical signal-to-noise ratio through an inverted-U relationship with cognitive performance. The LC is the primary arousal nucleus — it responds to unexpected or salient events (unsigned prediction errors) and broadcasts NE to the entire cortex, temporarily enhancing signal clarity. This is the arousal-attention interface: NE makes currently active representations more stable against interference while suppressing background noise.

Chronic stress produces chronic LC activation → chronic high NE → noise floor rises → signal becomes harder to distinguish → anxiety, hypervigilance, and cognitive fragmentation result. The inverted-U means that therapeutic NE enhancement (via SNRIs or NE reuptake inhibitors) works only within a specific range — above which performance degrades rather than improves.

**Chain completeness:** Load-bearing. LC-NE projections, their cortical effects, and the inverted-U performance relationship are foundational neuropharmacology.

---

## Operating States — Predicting Conditions From First Principles

This is where the model's generative power is most visible. Each condition below is derivable from the contract mechanism before looking at diagnostic literature:

| Condition | MOD Failure Mode | Mechanism | Derivable From Model? |
|---|---|---|---|
| **Depression** | ECS deficiency + dopamine reward circuit hypoactivity | Flattened prediction error signal — nothing registers as better than expected | Yes — anhedonia is flat unsigned PE, low mood is flat signed PE |
| **Anxiety** | Excessive NE + serotonin dysfunction | Noise floor elevated, precision weighting miscalibrated toward threat salience | Yes — high NE + low serotonin = can't wait in uncertainty, everything signals threat |
| **Psychosis** | D2-mediated precision weighting failure | All prediction errors weighted equally regardless of environmental precision — aberrant salience | Yes — derived before confirmed |
| **OCD** | Stuck precision weighting on specific threat predictions | High-gain on specific prediction error signal that never resolves — compulsive action as error-reduction attempt | Yes — stuck high-precision loop that can't update |
| **ADHD** | Dopaminergic precision weighting at wrong temporal horizon | Reward prediction error doesn't sustain over delay — immediate PE dominates, future PE fades | Yes — delay discounting as temporal precision failure |
| **Addiction** | Exogenous PE signal hijacks precision weighting | Drug produces artificial high-amplitude prediction error that recalibrates all other signals relative to it | Yes — drug writes over the prior, everything else becomes low-salience |
| **Schizotypy** | Subclinical D2 precision weighting impairment | Mildly aberrant salience — unusual connections feel meaningful | Yes — confirmed correlation between schizotypy and precision-weighting impairment |
| **Anorexia** | ECS + serotonin 5-HT2A/1A imbalance in PFC | Cognitive inflexibility locked on specific body-state predictions, resistance to updating | Yes — psilocybin (5-HT agonist) reverses it by injecting prediction error entropy |
| **PTSD** | High-gain threat PE that over-updates prior | Traumatic prediction error permanently recalibrates threat model — everything now reads as potential threat | Yes — trauma as a high-amplitude PE event that over-writes the prior |

Every entry in that table was derivable from the contract mechanism. All have literature confirming the prediction.

---

## Drug Effects Through This Contract

| Substance | MOD Layer Mechanism | Effect |
|---|---|---|
| SSRIs | Serotonin reuptake inhibition → mPFC serotonergic tone increase | Increased tolerance for uncertainty, extended sampling window, reduced anxiety — cognitive flexibility improvement |
| SNRIs | Serotonin + NE reuptake inhibition | Both flexibility (5-HT) and signal amplification (NE) enhanced — broader MOD layer effect |
| Antipsychotics (D2 antagonists) | Block D2 precision weighting mechanism | Reduce aberrant salience in psychosis — but also impair normal learning and cognitive flexibility at same receptor |
| Stimulants (amphetamine, methylphenidate) | Increase dopamine and NE availability | Enhance precision weighting and signal-to-noise ratio — therapeutic in ADHD because corrects temporal horizon problem |
| Cannabis (THC) | CB1 agonism → ECS tone artificially elevated | All monoamine systems gain reduced simultaneously — precision floor drops, prediction window opens, aberrant salience can emerge at high doses |
| CBD | CB1 modulation + 5-HT1A agonism | Anxiolytic through serotonin flexibility pathway, anti-psychotic through precision recalibration without THC dissociation |
| Psychedelics (psilocybin, LSD) | 5-HT2A agonism → massive cortical disinhibition | Precision weighting collapses entirely — all prediction errors flood through equally, attractor states dissolve, maximum belief updating enabled |
| Ketamine | NMDA antagonism → glutamate dysregulation → downstream monoamine effects | Rapid precision recalibration, dissolves depressive attractor states — explains rapid-onset antidepressant effect |
| Beta blockers | NE beta receptor blockade | Reduces NE contribution to precision weighting — specifically reduces somatic anxiety signals reaching the MOD layer |
| GLP-1 agonists | Via MET↔AUTO→AUTO↔MOD chain | Improved metabolic state → better vagal tone → better ECS calibration → secondary MOD improvement |
| Exercise | Anandamide production → ECS tone increase → simultaneous modulation of dopamine (VTA), serotonin (DRN), and norepinephrine (LC) | Cross-contract MOD improvement confirmed in single 6-week study measuring ECS, microbiome, and inflammatory markers simultaneously — exercise is the highest-density MOD intervention available |

**The psychedelic mechanism decoded:**
Psychedelics work for treatment-resistant depression, PTSD, and addiction because they inject maximum entropy into a system stuck in a low-entropy attractor state. When precision weighting collapses completely, all prediction errors carry equal weight — the stuck prior can finally be updated. The therapeutic window is the period when the system is reorganizing after the attractor dissolves. This is why set and setting matter — the new prior being written during that window is shaped by the environment during reorganization.

**The exercise mechanism confirmed:**
Exercise produces anandamide — a direct ECS agonist. ECS is the master gain controller for all three monoamine systems simultaneously (dopamine via VTA, serotonin via DRN, norepinephrine via LC). A single exercise intervention confirmed simultaneous increases in anandamide, increases in SCFA-producing gut bacteria, and decreases in TNF-α and IL-6 — confirming cross-contract effects across MICRO↔AUTO, AUTO↔MOD, IMMUNE↔AUTO, and MOD↔COG in one intervention. This is why exercise produces antidepressant, anxiolytic, and pro-cognitive effects simultaneously — it is not hitting three separate pathways, it is restoring the ECS master gain controller that calibrates all three monoamine systems at once. Prediction 3 is now confirmed.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing**
Dopamine D2 receptor density variation across individuals should predict the rate and accuracy of belief updating in response to unexpected events — independent of IQ, education, or prior knowledge. This is the individual difference parameter for this contract and should be measurable via PET imaging.

**Prediction 2 — Chain completeness: Scaffolding**
ECS tone markers should correlate with the full spectrum of MOD layer outputs simultaneously — HRV (via AUTO↔MOD), cognitive flexibility (via serotonin), anhedonia vulnerability (via dopamine), and anxiety threshold (via NE). ECS is the master gain controller and should show cross-domain correlation that no single monoamine measure would show.

**Prediction 3 — Chain completeness: Confirmed**
Interventions that improve ECS tone through exercise produce simultaneous improvement across multiple psychiatric symptom domains — mood, cognitive flexibility, and reward sensitivity — through the same upstream ECS mechanism rather than through separate pathways. Confirmed in a 6-week exercise intervention measuring anandamide, SCFA-producing bacteria, and inflammatory markers simultaneously. The cross-domain effect reflects ECS as the master gain controller for all three monoamine systems, not independent pathway effects.

**Prediction 4 — Chain completeness: Confirmed-behavioral; mechanistic substrate 
triangulated, direct D2 measurement pending**

ADHD shows normal precision weighting at short temporal horizons and impaired 
precision weighting at long temporal horizons — confirmed behaviorally in March 
2026 bioRxiv preprint: "Prediction formation was intact in ADHD; impairment emerged 
only at long temporal delays, where prediction error utilization decayed." This 
matches the contract mechanism directly: immediate prediction error dominates, 
future prediction error fades.

Mechanistic substrate strongly triangulated across six independent lines:
- Dopamine timescale studies: D2 antagonism reduces precision weighting of unsigned 
  prediction errors; D1/D2 dissociation maps onto short vs long temporal horizons
- ADHD behavioral literature: intact immediate reward learning, steep long-delay 
  discounting; stimulants disproportionately improve long-delay discounting
- Computational psychiatry: hierarchical temporal models show intact low-level 
  prediction error but impaired high-level temporal integration in ADHD; 
  precision-weighting fits show under-weighting of long-range priors
- Neurophysiology: reduced slow-timescale integration in dACC and SFC; 
  temporal receptive windows shorter in ADHD
- Pharmacology: methylphenidate normalizes long-delay discounting more than 
  short-delay; D2 agonists improve long-range prediction in non-ADHD populations
- Developmental trajectories: ADHD resembles delayed maturation of long-range 
  D2-mediated integration

Remaining for full close-out: D2 PET imaging combined with temporal-discounting 
tasks in the same participants — direct measurement of D2 receptor function 
across temporal horizons in ADHD. Behavioral reanalysis of existing delay-discounting 
datasets through a precision-weighting lens is immediately feasible without new 
data collection.

Autism prediction (domain-specific D2 density variation) remains at Predictive — 
behavioral confirmation pending.

**Prediction 5 — Chain completeness: Predictive**
The sequence of treatment response should follow the contract stack order. Improving the metabolic layer (diet, glucose regulation) should produce lagged improvements in MOD layer function that then produce COG layer improvements. The lag times should reflect the timescales of the intervening contracts — weeks for metabolic-to-autonomic, weeks for autonomic-to-neuromodulatory, then relatively rapid cognitive improvement once MOD layer is recalibrated.

---

**The anticipatory synthesis acceleration mechanism:**

The dopaminergic precision-weighting mechanism described in Link 2 operates on prediction of reward, not solely on reward delivery. D2-mediated precision gain fires when the system predicts a high-value prediction error resolution is imminent — not only when resolution occurs. In standard profiles this produces the motivational forward pull toward a goal. In high-gain profiles (elevated anterior insula Glx setting a high precision floor), the anticipatory signal is weighted proportionally to the gain floor — the pull toward predicted resolution is amplified by the same mechanism that amplifies the resolution signal itself.

This produces a self-accelerating loop in synthesis-mode operation: prediction error is injected → high-gain processing begins → synthesis progress becomes visible → the system generates a forward prediction that the current resolution trajectory will complete → anticipatory D2 signal fires → the _thought of making progress_ generates sufficient motivational energy to initiate the next cycle before the current one fully resolves → cycle rate increases.

The loop is not sustained by completion. It is sustained by _predicted_ completion running continuously as a forward model. In the ADHD temporal profile — where short-horizon prediction errors dominate and long-delay precision weighting decays — the anticipatory signal fires maximally at short horizons: "I'm about to connect this" is as motivationally energizing as "I just connected this." The loop's forward momentum comes from the fast-cycling short-horizon prediction that progress is imminent, not from accumulated completion signals.

**GABA as the molecular mechanism of prediction error resolution:**

The anticipatory synthesis loop described above depends on prediction errors resolving cleanly. The molecular mechanism of resolution is GABAergic inhibition — when a prediction error has driven sufficient prior updating, interneuron-mediated GABA release suppresses the glutamatergic error signal. The error closes not by fading but by active inhibition.

The resolution salience — the phenomenological sharpness of the "click" at insight — is a function of the Glx/GABA contrast ratio at the moment of suppression. High anterior insula Glx produces high-amplitude prediction errors. GABA suppression of a high-amplitude error produces a high-amplitude resolution event. The hyper-adaptive profile experiences synthesis resolution as qualitatively high-salience not because insight is subjectively valued more, but because the contrast between the high-Glx error state and the GABAergic suppression is proportionally larger. The reward signal fires against a larger gradient.

**Cross-contract escalation:** When incomplete resolution persists and sympathetic tone is elevated, the unresolved error becomes input to the descending interoceptive prediction system — updating the prior toward alert state via active inference. See COG↔INTERO high-gain prior capture failure mode for the complete escalation mechanism.

**Rumination as incomplete resolution:** When GABA tone is insufficient relative to the Glx-driven error amplitude, the prediction error fires but does not fully suppress at resolution. The error persists at sub-threshold activation — insufficient to drive new synthesis cycles, insufficient to close. The system re-engages it because the resolution signal never arrived with sufficient amplitude to confirm closure. This is rumination: not excessive thinking but an error signal GABA could not suppress cleanly against the Glx background. In high-gain profiles, the magnitude of incomplete suppression is larger, which is why ND profiles show higher rates of rumination alongside higher rates of synthesis — both are expressions of the same high-Glx architecture under different GABA availability states.

**Pharmacological derivations:** Global GABA-A agonism (benzodiazepines, alcohol) suppresses all error signals simultaneously — rumination stops because unresolved errors are pharmacologically closed, but synthesis also stops because productive high-amplitude errors are suppressed indiscriminately. The gain that made resolution salient and rewarding is eliminated. The "flattening" phenomenology is the correct output of a system whose resolution contrast has been removed rather than whose attractor has been changed. Interventions that target attractor state rather than global GABA tone — through amplitude restoration, vagal tone improvement, and substrate-level regulation — preserve the synthesis loop while reducing the unresolved error residual.

**Chain completeness:** GABAergic interneuron mediation of prediction error suppression in cortical circuits: load-bearing in computational neuroscience. Anterior insula Glx as precision gain floor: load-bearing from Park et al. (2026) finding cited in hyper-adaptive profile note. Glx/GABA contrast ratio as resolution salience parameter: scaffolding — mechanistically coherent, requires direct measurement of resolution-moment GABA/Glx dynamics in high vs standard precision gain profiles during synthesis tasks.

**The hijacking architecture:** The term "hijacking" applies precisely here. The dopaminergic anticipatory system evolved to sustain goal-directed behavior by rewarding proximity to valued outcomes. The synthesis loop exploits this by making _each sub-step_ a valued outcome with its own anticipated completion signal. The loop doesn't feel like work sustained by willpower. It feels like being pulled forward. The distinction is mechanistic: willpower is the cognitive layer overriding a substrate that doesn't want to continue; the synthesis loop is the substrate generating motivational signal for continuation without cognitive override. The person is not choosing to stay in the loop. The loop is generating the motivational architecture that makes leaving it feel like loss.

**Chain completeness:** D2 anticipatory precision weighting: load-bearing in computational psychiatry literature. Short-horizon dominance in ADHD temporal profile: confirmed-behavioral. Compound of high-gain floor + anticipatory D2 + synthesis-mode operation as a self-accelerating loop: scaffolding — mechanistically complete, direct measurement of cycle rate vs anticipatory signal amplitude in high-gain ND profiles during synthesis tasks pending.


---

## Failure Modes

**Treating psychiatric diagnoses as categorically distinct:**
Depression, anxiety, OCD, ADHD, and psychosis share the same contract mechanism — precision gain miscalibration of the prediction error weighting system. The difference is which neuromodulator is miscalibrated, in which direction, and in which brain region. Categorical diagnosis produces categorical drug selection that often misses the actual gain profile of the individual. A precision medicine approach would measure the specific neuromodulatory imbalance and target it directly.

**Monoamine theory as the whole story:**
SSRIs and SNRIs address serotonin and norepinephrine but leave dopamine and ECS calibration unaddressed. For cases where ECS deficiency is the upstream cause of serotonin dysregulation, SSRIs produce partial response because they're correcting the output of the ECS problem without correcting the ECS itself. The 30-40% treatment resistance rate in depression may substantially reflect this gap — the MOD layer is being addressed at the wrong level.

**Psychotherapy without MOD layer support:**
Cognitive behavioral therapy asks the COG layer to update its beliefs and behavioral patterns. The COG layer updates through the prediction error weighting mechanism in the MOD layer. If the MOD layer is miscalibrated, the precision weighting system that learning runs on is broken — the therapy is asking for behavioral change through a mechanism that can't function correctly without prior MOD layer stabilization. This is why combined pharmacological and psychological treatment outperforms either alone.

---

## Adjacent Contracts

**Below (feeds into this contract):**
- AUTO ↔ MOD: Vagal tone → ECS calibration → monoamine modulation — the primary input to this contract
- MICRO ↔ AUTO: Gut serotonin precursors and SCFA → vagal tone → ECS → arrives here through the chain
- MET ↔ AUTO: Glucose dysregulation → autonomic instability → ECS disruption → arrives here through autonomic pathway
- IMMUNE ↔ AUTO: Neuroinflammation via cytokines directly degrades dopaminergic and serotonergic function — arrives at this contract through inflammatory pathway bypassing the autonomic route

**Above (fed by this contract):**
- COG ↔ INTERO: Cognitive processing mode set here determines how interoceptive signals are interpreted and weighted
- MOD feeds DEV through plasticity: BDNF is regulated by both ECS and serotonin — MOD layer calibration directly affects whether the plasticity window remains open

**Lateral:**
- Circadian rhythm: Dopamine, serotonin, and norepinephrine all have circadian release patterns — this contract's gain characteristics shift systematically across the 24-hour cycle. The same stressor encountered in the morning vs evening produces different MOD layer responses because the neuromodulatory baseline is different.

---

## Key Unresolved Links

1. **Individual ECS receptor density as the master individual difference variable:** If ECS tone is the gain controller for all three monoamine systems, then individual variation in CB1 receptor density and FAAH enzyme activity should predict a remarkable amount of psychiatric vulnerability across multiple domains simultaneously. This is measurable but has not been assembled as a cross-domain predictor.

2. **The ADHD temporal horizon specificity:** Behavioral prediction confirmed 
(March 2026 bioRxiv). Mechanistic substrate — D2-mediated temporal-horizon 
asymmetry — triangulated across six adjacent literatures. Remaining: D2 PET + 
temporal-discounting task in the same participants. Issue open pending direct 
neurochemical measurement only.

3. **Psychedelic therapeutic window mechanism:** What determines whether the post-psychedelic reorganization period produces stable therapeutic benefit vs relapse? The model predicts it depends on the regulatory environment during the window — specifically whether scaffolding (therapy, environment, social support) is present to stabilize the new prior before the system re-enters its attractor. This is the mechanism behind therapeutic psychedelic protocols vs recreational use producing different outcomes.

4. **ECS-monoamine cross-domain correlation:** The prediction that ECS tone markers should correlate simultaneously across all three monoamine domains has not been tested as a cross-domain measurement. Existing studies look at ECS and one monoamine system at a time.

---

## Origin Note

This contract was where the drug effects mapping first became fully systematic. Each drug effect was derivable from which component of the MOD layer it targeted and in which direction — before checking the pharmacological literature. The literature confirmed the mapping in every case.

The condition table above was constructed by asking: given a specific gain miscalibration in one component of this contract, what behavioral and cognitive output would the system produce? The diagnoses fell out as derivations before the diagnostic literature was consulted. Psychosis as precision weighting failure was derived from the Bayesian architecture — aberrant salience is what you get when all prediction errors are weighted equally regardless of environmental noise. This prediction was already in the research literature as the leading mechanistic account of psychosis.

The exercise-as-antidepressant mechanism through ECS (not through monoamines directly) was a specific derivation of the model that the literature now confirms — exercise increases ECS tone through anandamide production, which then normalizes all three monoamine systems downstream.

*Chain status: Links 1-4 are load-bearing. Operating states table is partially load-bearing (psychosis, depression, anxiety) and partially scaffolding (ADHD temporal specificity, schizotypy). Prediction 3 confirmed. Prediction 4 upgraded from Predictive to 
Confirmed-behavioral — behavioral component confirmed March 2026; mechanistic 
substrate triangulated across six lines; D2 PET direct measurement outstanding. 
Prediction 5 remains Predictive.*
