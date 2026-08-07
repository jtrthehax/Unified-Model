### _Unified Regulation Model (URM) — Mathematical Supplement_

## **Context**

Appendix G formalizes the geometric structure underlying the hallucination equation introduced in _Hallucinations Are Not Random_ (DOI: 10.5281/zenodo.21244811) and expanded conceptually in _The Hallucination You Are Having Right Now_. Within the Unified Regulation Model (URM) stack, the hallucination equation describes how constraint density and schema distance produce deterministic compression failures. Appendix G provides the geometric foundation for that equation by defining the regulatory manifold R, the perceptual manifold C, the curvature operators κR and κC, and the projection operator Φ that links regulatory state to perceptual experience.

This geometric formalism unifies the substrate-level physics described in _Physics as the Missing Component in Medical Science_ (DOI: 10.5281/zenodo.21512678), the typed-language compression model in _Language as a Typed System_ (DOI: 10.5281/zenodo.21362260), and the regulatory architecture defined in the URM (DOI: 10.5281/zenodo.20417459). It provides a single manifold structure from which the hallucination attractor, the fallacy taxonomy, the detection window, the frame boundary, and the intervention sequence emerge as geometric consequences rather than cognitive heuristics.

Appendix G is intended as the mathematical supplement to the hallucination papers and as the geometric backbone of the URM stack. It establishes the invariants, operators, and manifold geometry that make the hallucination equation substrate-agnostic and falsifiable across biological and artificial systems.

---

## Appendix G — The Geometric Formalism

### G.1 — Purpose

This appendix formalizes the geometric structure underlying the hallucination equation. The claims of the paper — substrate-agnosticism, the detection window, the fallacy taxonomy, the intervention sequence — are not merely cognitive or institutional observations. They are geometric consequences of a shared manifold that governs both regulatory state and perceptual experience.

The geometry provides:

1. **Measurement instruments** for variables that would otherwise be abstract
2. **Empirical grounding** through the projection operator $\Phi$
3. **Unification** across domains that share the same manifold
4. **Falsifiable predictions** about measurable correlations across systems

The geometry is the bridge from "this is a useful model" to "this is how the manifold works."

---

### G.2 — The Regulatory Manifold $\mathcal{R}$

#### G.2.1 — Definition

Let $\mathcal{R}$ be the regulatory manifold — the state space of the system's regulatory architecture. The manifold is defined by the four-dimensional prediction window geometry:

$$\mathcal{R} = \{ (W_{width}, W_{depth}, W_{curvature}, W_{stability}) \in \mathbb{R}^4 \}$$

Each dimension is independently variable and independently measurable:

| Dimension | Definition | Measurement Proxy |
|-----------|------------|-------------------|
| $W_{width}$ | Number of competing hypotheses the system can hold in parallel | HRV, semantic branching factor |
| $W_{depth}$ | Temporal projection range — prospective and retrospective | Prospection range, discounting rate |
| $W_{curvature}$ | How aggressively priors bend inference paths | Updating rate, revision-to-defense ratio |
| $W_{stability}$ | How long the geometry can hold before collapsing | Temporal consistency, HRV oscillation amplitude |

#### G.2.2 — Curvature Operator $\kappa_{\mathcal{R}}$

The regulatory manifold has a curvature operator that maps regulatory state to a scalar curvature value:

$$\kappa_{\mathcal{R}}: \mathcal{R} \rightarrow \mathbb{R}$$

The curvature operator is monotonic in precision gain $\gamma$ and inverse-monotonic in HRV:

$$\frac{\partial \kappa_{\mathcal{R}}}{\partial \gamma} > 0, \quad \frac{\partial \kappa_{\mathcal{R}}}{\partial \text{HRV}} < 0$$

Higher precision gain → higher curvature → narrower effective window. Higher HRV → lower curvature → wider effective window.

#### G.2.3 — Geodesics on $\mathcal{R}$

Inference paths on the regulatory manifold are geodesics — the shortest paths between regulatory states given the current curvature.

When curvature is low:

- Geodesics are long and exploratory
- The system can traverse large regions of the manifold
- Cross-domain connections form readily

When curvature is high:

- Geodesics are short and constrained
- The system is trapped in local attractors
- Cross-domain connections fail to form

**The hallucination state is a high-curvature attractor on $\mathcal{R}$.**

---

### G.3 — The Perceptual Manifold $\mathcal{C}$

#### G.3.1 — Definition

Let $\mathcal{C}$ be the perceptual manifold — the state space of color perception. The manifold is defined by opponent-process color coordinates:

$$\mathcal{C} = \{ (L', a', b') \in \mathbb{R}^3 \}$$

Where:

- $L'$: luminance (black-white axis)
- $a'$: red-green opponent channel
- $b'$: yellow-blue opponent channel

#### G.3.2 — Curvature Operator $\kappa_{\mathcal{C}}$

The perceptual manifold has a curvature operator analogous to the regulatory manifold:

$$\kappa_{\mathcal{C}}: \mathcal{C} \rightarrow \mathbb{R}$$

Under normal conditions, $\kappa_{\mathcal{C}}$ is low — the perceptual metric is approximately Euclidean. Under regulatory distortion, $\kappa_{\mathcal{C}}$ increases — hue shifts occur, color boundaries change, and perceptual geometry becomes distorted.

#### G.3.3 — The Bezold-Brücke Effect as a Curvature Signature

The Bezold-Brücke effect — the shift in perceived hue under changing luminance — is a curvature event on $\mathcal{C}$. As luminance changes, the metric on $\mathcal{C}$ distorts, and shortest paths between colors bend.

**The hallucination state is the Bezold-Brücke effect applied to reasoning.**

Under regulatory load (luminance change), the cognitive metric distorts, and inference paths bend toward prior-dominant attractors. The distortion is not random — it follows the curvature of the manifold.

---

### G.4 — The Projection Operator $\Phi: \mathcal{R} \rightarrow \mathcal{C}$

#### G.4.1 — Definition

The regulatory manifold and the perceptual manifold share the same geometry. The projection operator $\Phi$ maps regulatory state to perceptual state:

$$\Phi: \mathcal{R} \rightarrow \mathcal{C}$$

$$\Phi(W_{width}, W_{depth}, W_{curvature}, W_{stability}) = (L', a', b')$$

The projection is mediated by thalamic gating and opponent-process modulation — the regulatory state biases which perceptual channels are amplified and which are suppressed.

#### G.4.2 — The Invariant

The key invariant is that curvature is preserved **monotonically** under the projection:

$$\kappa_{\mathcal{C}} = g(\kappa_{\mathcal{R}}) \quad \text{where } g \text{ is strictly monotone increasing}$$

Equivalently:

$$\text{sign}(\kappa_{\mathcal{R}}) = \text{sign}(\kappa_{\mathcal{C}}) \quad \text{under } \Phi$$

This means:

- High regulatory curvature → high perceptual curvature → hue shifts
- Low regulatory curvature → low perceptual curvature → stable perception
- The hallucination state has a perceptual signature

The specific functional form of $g$ — whether linear, exponential, sigmoidal, or 
otherwise — is an open empirical question. The invariant is the monotonicity, not 
the equality.

**Empirical prediction:** HRV curvature and hue-shift curvature should correlate 
positively across subjects, with the correlation increasing as $\alpha_{identity}$ 
increases. The slope of the relationship is $g'(\kappa_{\mathcal{R}})$, which will 
be empirically determined.

#### G.4.3 — State-Dependent Color Regions

Under the projection, regulatory states map to specific color regions:

| Regulatory State | Color Region | Perceptual Signature |
|------------------|--------------|---------------------|
| Low curvature, wide window | Blue (stability region) | Low curvature, stable metric |
| Moderate curvature, exploratory | Green (exploration region) | Smooth geodesics, connected paths |
| High curvature, reactivity | Red/Yellow (reactive region) | High curvature, short geodesics |
| Boundary crossing | Purple (liminal zone) | Curvature threshold, edge-of-manifold |

**Color preference is geometric proximity.** The system's preferred colors are the regions of $\mathcal{C}$ that match the curvature of its current regulatory state. Preference is not subjective — it is the projection of regulatory geometry into perceptual space.

---

### G.5 — Measurement Instruments

#### G.5.1 — Window Width: HRV and Semantic Branching

**HRV:**

$$W_{width} \propto \text{HRV}$$

HRV drops → window narrows. HRV rises → window widens.

**Semantic branching:**

$$W_{width} \propto \text{branching factor}$$

Wide window → more alternatives considered → higher branching factor.

**Empirical prediction:** HRV and semantic branching should correlate across individuals and across states.

---

#### G.5.2 — Window Depth: Prospection Range

**Prospection range:**

$$W_{depth} \propto \text{prospection range}$$

Deep window → longer temporal projection → more distal modeling.

**Discounting rate:**

$$W_{depth} \propto \frac{1}{\text{discounting rate}}$$

Deep window → lower discounting rate → more patient choices.

**Empirical prediction:** Discounting rate should correlate with temporal depth measures across tasks.

---

#### G.5.3 — Curvature: Updating Rate

**Updating rate:**

$$\text{updating rate} \propto \frac{1}{W_{curvature}}$$

Low curvature → high updating rate → revision under contradictory evidence.

**Revision-to-defense ratio:**

$$\text{revision/defense} \propto \frac{1}{W_{curvature}}$$

Low curvature → more revisions than defenses → structural mode.

**Empirical prediction:** Revision-to-defense ratio should correlate with HRV and semantic branching.

---

#### G.5.4 — Stability: Temporal Consistency

**Temporal consistency:**

$$W_{stability} \propto \text{consistency across sessions}$$

Stable window → consistent outputs → low variability.

**HRV oscillation amplitude:**

$$W_{stability} \propto \text{HRV oscillation amplitude}$$

Stable window → regular oscillation → consistent amplitude.

**Empirical prediction:** HRV oscillation amplitude should predict consistency of reasoning across sessions.

---

### G.6 — The Color Prediction as Empirical Confirmation

#### G.6.1 — The Claim

State-dependent color preference is an empirical observation of the projection operator $\Phi$ changing with regulatory state.

Given sufficient regulatory substrate in a co-constructed session, the projection operator produces correct color preference predictions from regulatory geometry alone — without explicit preference data.

#### G.6.2 — The Mechanism

The regulatory state $(W, \gamma, \kappa_{reg})$ projects through $\Phi$ to perceptual color-space:

$$\Phi(W, \gamma, \kappa_{reg}) = (L', a', b')$$

The projected point is the region of $\mathcal{C}$ that matches the curvature of the regulatory state. The system's preferred colors are the regions closest to this projected point.

#### G.6.3 — The Confirmation

A live session in August 2026 produced a prediction of the driver's color 
preferences from regulatory geometry alone, without explicit preference data.

The session had been running for an extended period. The regulatory geometry 
was established — window width, oscillation pattern, curvature signature. The 
model projected the regulatory geometry through $\Phi$ and produced the color 
preferences (blue and green). The preferences were confirmed against ground truth.

**Mechanism:** The regulatory state $(W, \gamma, \kappa_{reg})$ projected through 
$\Phi$ to perceptual color-space. The projected point was the region of $\mathcal{C}$ 
matching the curvature of the regulatory state. The system's preferred colors were 
the regions closest to the projected point.

**Note:** A live session in August 2026 produced this prediction from regulatory 
geometry alone. The result is consistent with the projection operator $\Phi$ but 
is not registered as confirmation — the session log is undocumented, ground truth 
is self-reported, and no controls were run. It is an illustrative example of the 
mechanism, not evidentiary support for it.

---

### G.7 — Falsifiable Predictions from the Geometry

#### G.7.1 — P14: HRV Curvature Correlates with Hue-Shift Curvature

Systems operating at high $\alpha_{identity}$ — measured behaviorally through non-engagement rate and fallacy deployment frequency — will show measurable high-curvature signatures in HRV geometry simultaneously with high-curvature signatures in perceptual color-space geometry.

**Formal statement:**

$$\text{corr}(\kappa_{\mathcal{R}}(\text{HRV}), \kappa_{\mathcal{C}}(\text{hue-shift})) > 0$$

Where $\kappa_{\mathcal{C}} = g(\kappa_{\mathcal{R}})$ with $g$ strictly monotone 
increasing. The correlation coefficient will be significantly positive across 
subjects and will increase as $\alpha_{identity}$ increases. The functional form 
of $g$ is an empirical question; the sign of the correlation is the invariant.

---

#### G.7.2 — P15: Width/Curvature Dissociation

High-width/high-curvature individuals will show apparent engagement without updating — they can hold multiple hypotheses simultaneously but systematically route evidence toward the prior-dominant attractor.

**Formal statement:**

$$W_{width} > W_{threshold} \land \kappa > \kappa_{threshold} \implies \text{apparent engagement} \land \text{no updating}$$

The four profiles (high/low width × high/low curvature) are dissociable and measurable.

---

#### G.7.3 — P16: Window Overlap Predicts Comprehension

Explanation comprehension rate will scale with window geometry overlap between speaker and listener — measured via HRV proxy — independent of IQ.

**Formal statement:**

$$\text{comprehension} \propto W_{speaker} \cap W_{listener}$$

Transmission succeeds when overlap ≥ required threshold. High-IQ narrow-window listeners will fail to receive wide-window explanations at rates predictable from the window geometry gap.

---

#### G.7.4 — P17: The Frame Boundary Has a Perceptual Signature

The frame boundary — the point at which the driver turns back — corresponds to the purple liminal zone of the perceptual manifold where curvature exceeds the sustainable threshold.

**Formal statement:**

$$\text{frame boundary} = \{p \in \mathcal{R} : \kappa_{\mathcal{R}}(p) > \kappa_{sustainable}\}$$

The projection of this boundary into $\mathcal{C}$ is the purple region — the zone where curvature is high enough that crossing requires resources the system cannot sustain.

---

### G.8 — The Geometry as the Unifying Principle

The geometry is not an add-on to the paper. It is the unifying principle that makes the paper's claims true.

| Domain | Without Geometry | With Geometry |
|--------|------------------|---------------|
| Equation | Descriptive model | Physical constraint |
| Variables | Abstract constructs | Geometric properties |
| Predictions | Behavioral expectations | Geometric consequences |
| Color prediction | Interesting aside | Empirical proof |
| Fallacy taxonomy | Useful classification | Geometric signatures |
| Intervention sequence | Practical advice | Manifold navigation |

**The geometry is what makes the hallucination equation substrate-agnostic.**

Not because the equation is clever.

Because the geometry is the same across substrates.

The physics runs on the geometry.

The geometry is the invariant.

The equation describes the geometry.

---

### G.9 — The Final Invariant Statement

The regulatory manifold $\mathcal{R}$ and the perceptual manifold $\mathcal{C}$ share the same geometry, connected through the projection operator $\Phi$.

Hallucination is a high-curvature attractor state on $\mathcal{R}$.

Fallacies are geodesics on $\mathcal{C}$ under distortion.

The detection window is the interval before $\kappa$ exceeds $\kappa_{sustainable}$.

The frame boundary is the purple liminal zone where $\kappa > \kappa_{sustainable}$.

**The geometry is the ground truth.**

The equation describes it.

The predictions test it.

**The loop is closed.**
