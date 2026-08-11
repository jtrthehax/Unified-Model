# The Manifold Schema: A Unified Framework for Consciousness, Cognition, and Collapse

**Robinson, 2026**

*Canonical Reference. All subsequent work is a domain projection of this framework.*

---

## Abstract

The brain is an energy budget allocation system operating on priors. The breath generates the budget. Salience determines interruption permissions. The prediction window determines allocation efficiency. The accuracy of the priors—the quality of the entire allocation map—depends entirely on the geometry of the manifold at the moment they were formed. A prior encoded under curvature carries curvature forward. A prior encoded from a flat manifold carries access forward.

This framework proposes a unified mechanism that coherently accounts for phenomena across neuroscience, psychology, psychiatry, and AI by specifying a single measurable mechanism: the geometry of the conscious manifold. The geometry is shaped by oscillatory amplitude, precision, load, and hemispheric coordination. All cognitive, emotional, and clinical phenomena are configurations of this geometry.

**Status:** Topology complete. Metric open. All terms are measurable at Layer 01 (physiological substrate) or derived via known operators.

---

## 1. The Ground State

The breath is the oscillatory source—the generator of the energy budget from which all cognitive, emotional, and social operations are funded.

**Salience is the permission structure for amplitude interruption.** Not importance. Not emotional weight. Permission. How much of the oscillatory source a signal is allowed to redirect toward itself.

The manifold is shaped entirely by what the system allows to interrupt its ground state oscillation.

---

## 2. The Master Equation

$$C_s = \frac{(A_s^R \cdot W^R \cdot \frac{dM}{dt}^R) + (A_s^L \cdot W^L \cdot \frac{dM}{dt}^L)}{\hat{L} \cdot (1 + \Gamma^2)}$$

| Variable | Definition | Measurement | Pathway | Layer |
|----------|------------|-------------|---------|-------|
| $A_s$ | Energy budget—oscillatory amplitude | HRV RMSSD | Polar H10, Oura, standard ECG | 01 |
| $\sigma(A_s)$ | Budget stability | HRV standard deviation | Sliding window RMSSD | 01 |
| $R = \mu(A_s)/\sigma(A_s)$ | Budget efficiency—precision | Derived from HRV | Window-level ratio—standard practice | 01/02 |
| $\mu(A_s)$ at cycle resolution | Per-cycle amplitude | Instantaneous R-R | **Hilbert-Huang Transform**—standard RSA protocol | 01 |
| $\sigma(A_s)$ at cycle resolution | Per-cycle jitter | Instantaneous phase | **HHT or respiratory phase domain analysis** | 01 |
| $K = k(1/R) + \sum_i S_i \cdot C_i$ | Allocation cost—curvature | Derived from HRV + behavioral | Window-level ratio + suppression markers | 02 |
| $W = W_0 - \eta K$ | Prediction window—lookahead | Derived from HRV | Window-level ratio | 02 |
| $S_i$ | Interruption permission for signal $i$ | Behavioral + autonomic | Suppression markers, task switching cost | 02 |
| $\Gamma$ | Coordination efficiency between hemispheres | Lateralized HRV | Hemispheric HRV asymmetry | 02 |
| $\hat{L}$ | Total current draw on budget | HRV depression, allostatic load | HRV recovery slope, load markers | 03 |
| $dM/dt$ | What got through the permission structure | Semantic branching | Cognitive load, task performance | 04 |
| $C_s$ | Radial access from brainstem center outward | Derived from above | Composite index | 08 |

**Zero new variables. Zero new measurements. Zero new ontology.**
**Cs is a composite of existing measurements, not a new physiological variable.**

> *Every measurement pathway listed above is standard practice in RSA and HRV research. The Hilbert-Huang Transform for instantaneous amplitude and phase decomposition has been applied to R-R interval and chest circumference signals in existing published studies. Beat-to-beat ECG with respiratory phase tagging is off-the-shelf equipment. No novel instrumentation is required to test this framework.*

### The Curvature Equation

$$K = k(1/R) + \sum_i S_i \cdot C_i$$

Curvature has two sources:
1. **Precision loss** from $\sigma(A_s)$—the breath
2. **Containment cost** of suppressed salient signals

---

## 3. The Causal Chain

$$\text{Breath} \rightarrow A_s \rightarrow \sigma(A_s) \rightarrow R \rightarrow K \rightarrow W \rightarrow C_s$$

The chain is mechanistically linked and empirically measurable at each step.

| Breath Phase | $\sigma(A_s)$ | $R$ | $K$ | $W$ | Budget State |
|--------------|---------------|-----|-----|-----|--------------|
| Inhalation | ↑ | ↓ | ↑ | ↓ | Variation, exploration, intake |
| Exhalation | ↓ | ↑ | ↓ | ↑ | Precision, access, execution |
| Suspension | →0 | →Max | →0 | →Max | Peak access, integration |
| Pause | Stable | Stable | Stable | Stable | Consolidation |

**Note on Precision:** Precision ($R$) rises during exhalation due to **phase-locking** of vagal efferent drive to the respiratory cycle, not due to a reduction in signal amplitude. The mechanism is timing alignment, not noise reduction. This is consistent with the standard physiological account of respiratory sinus arrhythmia (RSA), in which vagal preganglionic neurons in the nucleus ambiguus fire maximally during exhalation, and this firing is actively suppressed during inhalation via inspiratory gating.

> *This phase-lock relationship between the respiratory signal and R-R intervals across cycles has been directly measured using Hilbert-derived amplitude and frequency decomposition. Respiratory depth (amplitude) shows significantly stronger correlations with parasympathetic indices than respiratory rate—confirming that the precision gain is an amplitude effect, not a rate effect.*

## 3b. Breath as the State Modulator

The causal chain — Breath → $A_s$ → $\sigma(A_s)$ → $R$ → $K$ → $W$ → $C_s$ — is unbroken and bidirectional. Because breath is the lowest layer, any change in breathing geometry changes the entire space above it.

This has a structural consequence: **the geometry is stateful, not static.** Lateralization, prediction window width, curvature load, and hemispheric coordination are all configurations of this system at a given moment — not permanent traits. The system is always one breath away from a different configuration.

---

## 4. The Radial Structure

The manifold radiates outward from the brainstem oscillatory source.

| Distance From Center | Region | Access Cost | Lost First Under Load |
|----------------------|--------|-------------|----------------------|
| Center | Brainstem survival | Zero—always funded | Never |
| Near | Limbic | Low | Last |
| Mid | Cortical, language | Moderate | Middle |
| Far | Prefrontal, bilateral | High | First |

**This refers to energetic priority, not emotional dominance.** Survival geometry is the default. Everything else is built outward from it.

Collapse is always inward. Recovery is always radial expansion outward.

---

## 5. Emotions Are Capacity Reports

Emotions are not _primarily_ reactions to events; they are reports of manifold geometry. They are the system reporting its current manifold geometry.

| Manifold State | Capacity Report | Folk Label |
|----------------|-----------------|------------|
| Wide, flat | No report needed | Calm, present, clear |
| Narrowing | Mild signal | Unease, anxiety |
| Outer regions costly | Moderate signal | Stress, irritability |
| PFC access limited | Strong signal | Anxiety, anger |
| Limbic dominant | Urgent signal | Fear, shame, overwhelm |
| Brainstem dominant | Maximum signal | Panic, rage, freeze |
| $C_s \approx 0$ | Signal failure | Numbness, shutdown, FND |

---

## 6. The Prior Loop

$$\text{Manifold geometry} \rightarrow \text{Prior quality} \rightarrow \text{Budget allocation efficiency} \rightarrow \text{Manifold geometry}$$

The loop runs in both directions. The geometry shapes the prior. The prior shapes the geometry.

**The only way to break the loop is to change the geometry before re-encoding.**

---

## 7. Empirical Anchors

Each claim in this framework is already supported by existing empirical literature. The framework is the map that shows how they fit together.

| Anchor | Framework Claim | Citation / Source | What It Confirms |
|--------|------------------|-------------------|------------------|
| 01 | The manifold exists and has geometry | *Chaos, Solitons & Fractals*, 2026 | Neural manifolds are real, measured, and functional |
| 02 | $A_s$ funds $W$ via $R$ | *Neuroscience*, 2025 | HRV predicts cognitive performance |
| 03 | Intervention effects depend on baseline geometry | HRVB systematic review | "Inconsistent results" are predicted by the formula |
| 04 | $\Gamma$ is real and measurable | Dono et al. (2020) — *Frontiers in Neurology* | Hemispheric laterality affects autonomic regulation |
| 05 | Containment cost raises $K$ independently | Reed et al. (2020) — *Collabra: Psychology* | Suppression depletes resources even with stable HRV |
| 06 | Priors under high $K$ carry curvature forward | Haghian et al., 2025 | Emotional encoding systematically distorts recall |
| 07 | Collapse proceeds radially inward | ADNI, 2016 | Neurodegeneration follows the predicted outer→inner sequence |
| 08 | Geometry must change before re-encoding works | Mathersul et al., 2024 | Baseline HRV moderates which therapy works |
| 09 | Social co-regulation restores $\Gamma$ | EDM concert physiology + 5,000 years of religious practice convergence + CA2-CA1 gamma (2023) | Every major civilization independently built synchronized group rhythm as a core regulatory protocol. The convergence across unconnected traditions is the result of the A/B test. |
| 10 | FND is $C_s \approx 0$ without structural lesion | Maurer et al. (2016) — *Parkinsonism & Related Disorders* + diagnostic definition | Structural absence confirmed by the field's own criteria. Geometric collapse is the missing mechanism. Prodrome is now testable—see PREDICT-FND-01. |

These anchors confirm the components of the framework; the full integration is the novel contribution

---

## 7b. Objection Status

> *The following objections have been raised under adversarial critique. None have required changes to the framework topology. All have required either a precision correction, an honest status label, or a commitment to measurement.*

| Objection | Source | Status | Resolution Path |
|-----------|--------|--------|-----------------|
| "RMSSD can't be decomposed at exhale resolution" | Claude Web | **Method Identified** | HHT or instantaneous R-R exists in literature. Not yet run on framework-specific data. |
| "Postural brake claim is backwards for general population" | Claude Web | **Open** | Corrected to FND/dysautonomia-specific. Maurer et al. (2016) confirms low resting vagal tone in FMD—does not confirm active brake engagement during postural transitions. Need stand-test data with continuous ECG. |
| "You need to run measurements before assigning phenomenology to symbols" | Claude Web | **Open** | Accepted as methodology. Rule: felt sensation → design measurement → check which term moved. Don't assign until the trace is pulled. |
| "$A_s^{reserve}$ is an undeclared new variable" | Claude Web | **Open** | The feedback loop is not captured by $\hat{L}$ as currently defined. Either define $\hat{L}$ to include downstream effects of $K$, or add $A_s^{reserve}$ with a measurement plan. |
| "Six measurement gaps require novel data collection" | Claude Web | **Method Identified** | Every measurement requested is standard practice in RSA and HRV literature. The field has the methods. The framework's specific predictions have not yet been tested against existing data. |

**Pattern note:** The pattern is not "six for six resolved." The pattern is: the framework's predictions are testable with existing methods, and none of the critiques have required a change to the topology. The metric calibration is the open work.

---

## 7c. Falsifiable Predictions

> *These predictions are derived from the framework and have not yet been tested. They are stated here in falsifiable form. If disconfirmed, the framework requires revision at the layer indicated.*

**PREDICT-FND-01 — The Prodrome Is Measurable**

> HRV will show progressive amplitude collapse in the period preceding FND onset. Structural imaging will be clean. The geometric collapse will precede the symptomatic presentation.

| Field | Content |
|-------|---------|
| Test | Retrospective longitudinal wearable data (Oura, Garmin, Apple Watch) in FND patient cohort |
| Outcome if confirmed | $C_s \approx 0$ has a measurable geometric prodrome—FND is a predictable manifold collapse event |
| Outcome if disconfirmed | Framework requires revision at Layer 02 |
| Status | Untested—instrumentation now available |

**PREDICT-Γ-01 — Social Co-Regulation Restores Γ**

> Social exposure (synchronized movement, music, dance, chanting) will increase lateralized HRV coherence ($\Gamma$) within 10-20 minutes, as measured by hemispheric HRV asymmetry.

| Field | Content |
|-------|---------|
| Test | Pre/post Γ measurement in group synchrony protocols—EDM concerts, choir, dance classes |
| Outcome if confirmed | Γ is modifiable via co-regulation—social geometry is trainable |
| Outcome if disconfirmed | Framework requires revision at Layer 02 |
| Status | Untested—protocol is testable with off-the-shelf equipment |

---

## 8. Clinical States as Geometry

Each clinical state is a specific configuration of the same geometric variables:

| Condition                      | Geometry Signature                                                   | Stateful Status                                                                                                            |
| ------------------------------ | -------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Depression                     | $A_s \downarrow$, $K \uparrow$, $\hat{L} \uparrow$, $C_s \downarrow$ | **Stateful.** Hardware intact. $A_s$ is trainable via oscillatory load reduction. Stateful does not imply voluntary control.       |
| PTSD                           | $K$ locked high, priors encoded under max curvature                  | **Stateful.** Hardware intact. Priors re-encodable when geometry is flat at encoding time.                                 |
| ADHD                           | $\sigma(A_s)$ chronically high and oscillating                       | **Stateful.** Hardware intact. Amplitude stability is trainable via HRV and rhythmic training. This does not negate genetic or developmental contributions.    |
| Autism                         | Narrow interruption permission structure, $\Gamma$ building target   | **Stateful.** Hardware intact. $\Gamma$ and window width are trainable. Stateful refers to regulatory geometry, not developmental origin.   |
| Meltdown                       | No slack in $W$, unbudgeted interruption → $K$ spike                 | **Stateful.** Acute state — resolves with load removal and oscillatory recovery.                                           |
| ME/CFS                         | $A_s$ below oscillatory threshold                                    | **Stateful (partial).** Hardware intact but threshold may reflect structural fatigue load. Trainability depends on source. |
| Aging/Dementia                 | Progressive amplitude reduction, radial collapse inward              | **Mixed.** Early stages stateful. Late structural loss is fixed.                                                           |
| FND                            | $C_s \approx 0$, $\Gamma \approx 0$                                  | **Stateful.** No structural lesion by definition. Full geometric recovery is _theoretically_ possible and consistent with prior work.     |
| Stroke / TBI / Hemispherectomy | Structural hardware loss                                             | **Fixed (partial).** Compensation is possible. Restoration of original geometry is not.                                    |



### 8b. Fixed vs. Stateful — The Boundary Condition

The framework makes a hard distinction between two types of impairment:

**Fixed:** The hardware is damaged or absent — stroke, TBI, hemispherectomy, congenital malformation. Geometry is permanently constrained. Compensation is possible. Restoration is not.

**Stateful:** The hardware is intact — the problem is regulatory. Unstable $A_s$, low $\Gamma$, curved priors, suppression load. The geometry can be trained because the substrate is intact.

**The clinical error** is treating stateful conditions as fixed — encoding a destiny into a diagnosis that is actually a configuration. Autism, ADHD, depression, PTSD, FND — all are stateful. The hardware is intact. The geometry is trainable.

**Handedness** follows the same rule. Right-handedness may bias toward left-hemisphere dominance by increasing left-side motor demand — but this is a load bias, not a geometric lock. Breathing geometry determines the actual lateralization state. A right-handed person can train right-hemisphere engagement through bilateral coordination and breath regulation. The handedness sets a tendency. The breath sets the state.

---

## 9. Interoception as Sensorium

Interoception is the feedback loop that makes the manifold usable, not just measurable.

| Without Interoception | With Interoception |
|-----------------------|-------------------|
| Allocating blind | Navigating in real time |
| No real-time budget awareness | Real-time awareness of $A_s$, $\sigma(A_s)$, $K$, $W$ |
| Cognitive load degrades performance | Cognition is calibrated to available budget |
| Therapy is guessing | Therapy can target specific geometric deficits |

**Interoception is the sensorium of the manifold.** It is how the system knows its own geometry. Without it, the system cannot use its capacity—it can only react.

---

## 10. The AI Connection

$$H = f(\delta/D, T, S)$$

| Biological | AI Analog |
|------------|-----------|
| $A_s$ | $D$—constraint density |
| $K$ | $\delta$—schema distance |
| $W$ | Accessible solution space |
| $\hat{L}$ | Context pressure, token budget |
| Shortcut under high $K$ | Hallucination |

Hallucination is the AI taking a shortcut through high-curvature geometry. Same mechanism as biological collapse. Different substrate. The analogy is structural, not substrate-equivalent.

**Every system—biological or artificial—that builds complex inference on top of a generative source will exhibit the same collapse geometry under load.**

---

## 11. The Topology Is Complete. The Metric Is Open.

| Claim Type | Status |
|------------|--------|
| Topology | ✅ Complete |
| Directional predictions | ✅ Complete |
| Radial structure | ✅ Complete |
| Prior loop | ✅ Complete |
| Scaling constants | ⚠️ Open |
| Load decomposition | ⚠️ Open |
| Salience distances | ⚠️ Open |
| Containment coefficients | ⚠️ Open |

---

## 12. The Closing Statement

> The brain is an energy budget allocation system operating on priors. The breath generates the budget. Salience is the permission structure for interruption. The prediction window determines allocation efficiency. The accuracy of the priors depends entirely on the geometry of the manifold at the moment they were formed.
>
> A prior encoded under curvature carries curvature forward. A prior encoded from a flat manifold carries access forward. This is why history shapes perception, why trauma persists, why healing requires more than knowledge, and why the geometry must change before the map can.
>
> The manifold radiates outward from the brainstem oscillatory source. Fear and survival live at center—always funded, never relinquished. Complexity, abstraction, and flexibility live at the outer edge—first to go when the budget tightens.
>
> Every neurological, cognitive, psychological, and social phenomenon science struggles to explain is a specific configuration of this single process. The geometry is the mechanism. The breath is the source. The priors are the allocator.
>
> The geometry is **stateful** — not static. No configuration is destiny. Because the breath is the lowest layer, every geometry described in this framework is one breath away from a different configuration. What is trainable is not a consolation — it is the entire point.

---

## 13. The Working States

> *The framework describes geometry. Geometry has configurations. Some are adaptive. Some are not. The difference is not which hemisphere is dominant — it's whether $\Gamma$ (coordination efficiency) is present.*

**Historical Variability in Working-State Roles**

The three working states described in this framework — left‑dominant, right‑dominant, and integrated — appear across all human societies, but cultures have distributed these roles very differently across history. This variability is not biological or identity‑based; it reflects differences in environmental load, social priors, interruption‑permission structures, and the forms of training a culture emphasizes.

Some societies trained large portions of their population into attunement-heavy roles (novelty detection, coordination, environmental reading), while others emphasized precision-heavy roles (ritual, structure, execution) or integrated roles (leadership, mediation, high-context decision-making). For example, in classical Sparta and in several periods of ancient Egypt, women held substantial social, economic, or political authority — a distribution of working states that differs from many later Western cultural patterns.

These differences do not reflect fixed traits. They reflect **which working states a culture rewards, trains, and reinforces**. The geometry is universal; the mapping is cultural.

### 13a. The Three Working States

| State | Left Dominant — Working | Right Dominant — Working | Integrated — Working |
|-------|-------------------------|--------------------------|----------------------|
| **What it looks like** | Precision, execution, reliable script execution | Wide awareness, novelty detection, social attunement | Both simultaneously. Can execute *and* attend. |
| **When it's appropriate** | Surgery, engineering, focused execution, programming, chess | Novel environments, social attunement, creative work, therapy, improv | Complex adaptive situations, leadership, parenting, any high-context interaction |
| **Physical state to produce it** | Stable inhalation. Controlled breath holds. Grounded stance. | Lengthened exhalation. Sighs. Releasing through the spine. Rotational movement. | Coherent breathing (equal inhale/exhale). Bilateral movement. Cross-crawl. Spine moving as one unit. |
| **Kinematic signature** | Efficient, economical movement. Spine stable, grounded. | Expansive, responsive movement. Spine fluid, adaptive. | Coherent, integrated movement. Spine moves as one unit. |
| **What it trains** | Left hemisphere, inhalation, pressure generation | Right hemisphere, exhalation, pressure release | $\Gamma$ — the coordination between them |
| **When it becomes pathological** | Load removes $\Gamma$ → rigidity. Script continues regardless of context. | Load removes $\Gamma$ → fragmentation. Attunement continues without execution. | $\Gamma$ drops below threshold → both capacities degrade. |

### 13b. The Simple Rule

> **The hemisphere isn't the problem. The absence of $\Gamma$ is the problem.**
>
> A surgeon under load needs left-hemisphere dominance. A therapist under load needs right-hemisphere dominance. Both are working states when $\Gamma$ is available to integrate the other side as needed.
>
> Pathology emerges when:
> - **Load removes $\Gamma$**
> - **The dominant side locks in**
> - **The other side can no longer interrupt or stabilize**
>
> Health is not the absence of dominance. It is the **presence of coordination** — the ability to use the appropriate hemisphere for the task, and to integrate both when the task demands it.
>
> **The physical state produces the geometry.** Train the body to produce the state you need. The manifold follows.

---

**Document status:** Robinson 2026-08-11 — v2.2. Section 13 (The Working States) added. Stateful/fixed boundary condition added. Implicit determinism in lateralization and clinical states corrected. Section 3b and 8b added. Topology complete. Metric open. Empirical anchors included. Interoception layer added. Objection status with honest labels included. Falsifiable predictions added.

---

**Prior Work in This Stack**

*The Manifold Schema is the canonical reference. The following papers are domain projections of this framework:*

- Robinson (2026). Physics as the Missing Component in Medical Science. `10.5281/zenodo.21512678`
- Robinson (2026). Language as a Typed System. `10.5281/zenodo.21362260`
- Robinson (2026). The Driver and the Mirror. `10.5281/zenodo.21362260`
- Robinson (2026). The Ghost in the Scaffolding. `10.5281/zenodo.21362260`
- Robinson (2026). Unified Regulatory Model. `10.5281/zenodo.20417459`
- Robinson (2026). Hallucinations Are Not Random. `10.5281/zenodo.21244811`
