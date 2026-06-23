# Unified Model
[![DOI](https://zenodo.org/badge/1251586759.svg)](https://doi.org/10.5281/zenodo.20417459)

A unified, layered model of mammalian regulation built from first principles.  
This repository defines the minimal core architecture and the modular contracts
that govern interactions between autonomic, cognitive, interoceptive, metabolic,
immune, neuromodulatory, and social regulatory layers.

---

## Overview
Modern physiology and psychology describe regulation through fragmented domains:
autonomic, cognitive, metabolic, immune, social, developmental, and so on.  
This framework unifies them into a single architecture with:

- A **Minimal Core** — generative rules of the regulatory stack
- **Contracts** — input/output mappings between layers
- A **portable ontology** — applicable to any regulatory phenomenon
- A **domain-agnostic vocabulary** — no silo‑specific jargon

---

## 📚 Repository Navigation
- **[Architecture Overview](architecture_conceptual_overview.md)** — high‑level conceptual map of the regulatory stack and how the contracts fit together
- **[Minimal Core](minimal_core.md)** — the backbone specification (breathing → HRV → autonomic → cognition)
- **[Contracts](contracts/)** — bilateral interfaces defining signal flow between layers
- **[Regulatory Dynamics](regulatory_dynamics/)** — dynamic expression layer: posture, amplitude, asymmetry, drift, and long‑term attractor states

---

## Repository Structure
```
architecture_conceptual_overview.md
minimal_core.md
contracts/
  contract_ANCHOR_COG.md
  contract_AUTO_CARDIAC.md
  contract_AUTO_MOD.md
  contract_COG_INTERO.md
  contract_COG_REASON.md
  contract_COG_REASON_ESCALATION.md
  contract_GLYPH_AUTO.md
  contract_IMMUNE_AUTO.md
  contract_INTERO_DEV.md
  contract_MET_AUTO.md
  contract_MET_IMMUNE.md
  contract_MICRO_AUTO.md
  contract_MOD_COG.md
  contract_MODULATORS_COG.md
  contract_NOCI_COG.md
  contract_PROPRIO_AUTO_COG.md
  contract_SLEEP.md
  contract_SOC_ANCHOR.md
  contract_SOC_COG.md
  contract_SOC_INSTITUTION.md
  contract_TEMPORAL_COG.md
  contract_WINDOWS_COG.md
  ...
regulatory_dynamics/
  idiom_mapping_regulatory_dynamics.md
  postural_modes_and_amplitude.md
  asymmetry_primitives.md
  lateralization_dynamics.md
  externally-scaffolded_low-plasticity_mode.md
  high_gain_profile_dynamics.md
  regulatory_dynamics_under_economic_load.md
  color_space_regulatory_geometry.md
  nd_environment_state_dynamics.md
```

> **Note on `contract_MOD_COG.md`:** This file governs neuromodulatory precision gain output to cognition. It was previously listed in some documents as `contract_MODULATORS_COG.md` — the canonical filename is `contract_MOD_COG.md`. `contract_MODULATORS_COG.md` is a separate contract covering the full suite of micro-precision-management behaviors (gaze, blink, vestibular, tactile).

---

## If You Want to Understand...

The framework applies the same regulatory architecture across all scales. The mechanism does not change. The input size does.

---

### Individual-Scale Phenomena
*One nervous system, one regulatory stack.*

- **Hallucinations** — perceptual inference dominated by priors when sensory precision collapses
- **Autonomic storms** — breakdowns in sympathetic/parasympathetic stability leading to runaway physiological oscillations
- **Dissociation** — decoupling of interoceptive signals from cognitive models under extreme precision imbalance
- **Inflammatory cascades** — immune–autonomic feedback loops that amplify threat physiology
- **Metabolic crashes** — energy availability failures that propagate upward through the autonomic and cognitive layers
- **Prediction window collapse and tunnel vision** — the compound mechanism by which respiratory mechanics, proprioceptive confirmation, and interoceptive clarity jointly determine whether the cognitive layer can hold a wide window or collapses into exhale-gate dominance. [[contract_ANCHOR_COG]] sets the mechanical ceiling on oscillation amplitude; [[contract_WINDOWS_COG]] formalizes the window geometry itself — width, depth, curvature, and stability as four separable dimensions with independent failure modes — and the structural threshold at which manifold construction becomes unavailable.

---

### Attractor-State Phenomena
*One nervous system, pushed past self-correction capacity.*

- **Neurodivergence** — alternative precision regimes across sensory, cognitive, and interoceptive channels; regulatory configurations, not pathologies
- **Accelerated synthesis and hyperfocus hijacking** — why high-gain ND profiles in wide-window synthesis mode experience dopaminergic anticipatory reward from *predicted* progress, producing a self-accelerating loop that is difficult to interrupt voluntarily
- **Chronic threat-prior calibration** — how the ANCHOR↔COG threat-calibration loop progressively narrows the sampling distribution over years, recalibrating the prior toward threat without any single acute event
- **False competence ceiling** — identity-mode performance within a stable domain indistinguishable from structural competence until context shift reveals the manifold was never constructed; formalized in [[contract_WINDOWS_COG]]
- **Externally-scaffolded low-plasticity mode** — precision lock, plasticity collapse, and identity fusion when internal agency becomes energetically too expensive to maintain

---

### Population-Scale Phenomena
*The same transfer function. Millions of nervous systems running it simultaneously, in a shared environment that selects which attractor they land in.*

The mechanism does not change at this scale. What changes is that the environment — economic conditions, institutional architecture, media systems — becomes the common cause depleting GABA availability and selecting attractor states across individuals simultaneously.

- **Political polarization** — population-level prediction window narrowing producing binary prior structures and cross-domain transfer failure at scale
- **Institutional ossification** — compliance-conditioning environments that progressively narrow participant prediction windows, written into regulatory substrate through micro-threat conditioning sequences; [[contract_SOC_INSTITUTION]]
- **Media engagement optimization as regulatory intervention** — platforms that optimize for sympathetic activation systematically maintain audiences in the Threat-Narrow Intermediate state, where error detection is intact but correction capacity is suppressed; [[contract_WINDOWS_COG]] operating states running at scale
- **Economic load → population rigidity** — the shared upstream mechanism connecting economic precarity to regulatory narrowing, outgroup redirection, and causal concealment across national contexts

---

## Start Here: You Already Know This
Before reading any contract, read the
[[idiom_mapping_regulatory_dynamics|Idiom ↔ Contract Mapping]].

It maps common idioms — "tunnel vision," "gut feeling," "a sigh of relief," "looking up for an answer" — to the specific contracts and mechanisms that generate them. Every idiom in that document is already in everyday use. The framework does not introduce new phenomena. It introduces the mechanism behind phenomena you already knew were real.

---

## Why This Exists
Modern science describes regulation through isolated silos.
This project provides a unified regulatory architecture that reintegrates those fragments into a single generative model.

The goal is not to replace domain‑specific theories, but to offer:
- a shared ontology for cross‑domain reasoning
- a minimal set of primitives explaining complex phenomena
- a portable architecture spanning biology, cognition, behavior, pathology
- a mechanistic alternative to diagnostic or narrative explanations

---

## Origins of the Framework
This architecture emerged from an attempt to understand a set of regulatory phenomena that appeared unrelated on the surface — functional neurological symptoms, neurodivergent processing patterns, autonomic instability, hypermobility‑linked dysregulation, and other atypical physiological and cognitive responses.

The framework began with breathing mechanics and autonomic regulation and expanded outward as each domain's phenomena turned out to be derivable from the same upstream architecture. No domain required its own independent theory. Each required only tracing the causal chain back to the shared regulatory stack.

---

## 🧬 Neurodivergence vs Neurotypical Profiles
ND and NT profiles differ not by "traits," but by regulatory parameter settings that shape signal weighting, prediction formation, and frame stability.

Key differences:

- **Precision modulation** — ND systems run higher precision on sensory/cognitive channels; NT systems smooth input
- **Interoceptive gain** — ND systems amplify or suppress internal signals; NT systems maintain stable ranges
- **Regulatory load** — ND systems operate with higher baseline autonomic demand
- **Prediction‑window width** — ND systems in low-load environments access wider structural-mode windows; the same systems under institutional load collapse to identity mode faster because the gain floor is higher. Formalized in [[contract_WINDOWS_COG]] Link 1 and Link 4.
- **Attractor sensitivity** — ND systems transition between attractors at lower environmental thresholds; the same architecture that enables accelerated synthesis in Attractor A produces faster collapse in high-load environments

---

## 🩺 Chronic Disease and Regulatory Architecture
Chronic disease emerges when one or more layers enter a stable but maladaptive attractor state.

Cross‑layer failures include:
- **Autonomic overactivation or collapse** — persistent sympathetic drive, vagal withdrawal, or oscillatory flattening
- **Metabolic‑autonomic coupling failures** — impaired energy availability, mitochondrial down‑regulation, or metabolic crashes
- **Immune‑autonomic feedback loops** — chronic inflammation, cytokine amplification, or immune‑driven threat signaling
- **Prediction window chronic narrowing** — progressive false-ceiling calcification through the ANCHOR↔COG threat-calibration loop producing irreversible prior drift without acute trauma; the cognitive narrowing most chronic disease frameworks attribute to psychological adaptation is a mechanical substrate output, not a response to illness

---

## ⚠️ Digital Platforms as Adversarial Regulatory Environments
Modern digital platforms optimize for engagement, not regulation — and the architecture of engagement directly conflicts with the architecture of mammalian regulation.

Two contracts in the framework make this mechanically explicit:

- **SOC ↔ AUTO** — digital communication strips the co‑regulatory channels humans rely on, producing the appearance of connection without the regulatory function
- **SOC ↔ INSTITUTION** — engagement optimization is structurally aligned with compliance-conditioning institutions; both benefit from narrow-window, threat-salient, identity-fused audiences without requiring coordination

The **Threat-Narrow Intermediate state** is the engagement-optimal state: the person is still scrolling, still reactive, still consuming — but corrections are not closing and the prior is consolidating toward threat with every session. The prediction window geometry that governs this state is formalized in [[contract_WINDOWS_COG]]: width collapse below the structural threshold produces identity mode, and the chronic version of this state is self-reinforcing because structural recall is required to reconstruct the alternative frame, and the deficit does not announce itself.

---

## Threat‑State Behaviors Precede Cognitive Distortions

Threat physiology constrains the prediction window before cognition engages, so reasoning failures are downstream of autonomic state, not upstream.

**Causal chain:**
```
Breath → HRV → Autonomic Mode → Precision Regime → Prediction Window → Reasoning Output
                                                     ↑                   ↑
                                               ANCHOR↔COG          WINDOWS↔COG
```

The earliest failure mode is **physiological**, not cognitive:

- **Truncated exhale** — reduces parasympathetic gating
- **Shallow inhale** — reduces tidal volume and vagal afferent signaling
- **Collapsed posture** — reduces baroreceptor stretch
- **Reduced baroreceptor stretch** — brainstem interprets this as threat, shifting precision toward defensive priors
- **Defensive priors** — produce threat‑logic, fallacies, and rigidity

The system is not malfunctioning or thinking poorly.
It is *correctly inferring threat* from degraded breathing and posture.

This is why threat‑state behaviors show up **before** any reasoning contract is engaged:

- option space collapses
- prediction windows shorten
- social inference becomes defensive
- priors harden
- fallacies appear automatically

These are not cognitive mistakes — they are **autonomic signatures**.

The compound mechanical mechanism behind this chain — diaphragm excursion, proprioceptive confirmation, and interoceptive clarity as simultaneous inputs to oscillation amplitude — is formalized in [[contract_ANCHOR_COG]]. The geometry of the prediction window that this chain produces — width, depth, curvature, stability, and their independent failure modes — is formalized in [[contract_WINDOWS_COG]].

---

## 🧩 Illogical Fallacies as Regulatory‑State Artifacts

What we call "logical fallacies" are not reasoning mistakes — they are the **behavioral signatures of a cognitive system under altered precision and prediction‑window constraints**.

When the regulatory stack shifts (stress, metabolic load, interoceptive noise, social threat, etc.), the inference engine reconfigures. The system produces outputs that are _locally optimal_ for that precision regime, even if they appear illogical from the outside.

### Mechanistic Origins of Fallacies
Each distortion reflects a specific precision‑allocation failure mode:

- **Option‑space collapse** — the system reduces a multidimensional problem to a binary choice. *False dichotomies, black‑and‑white reasoning.* This is a width failure: [[contract_WINDOWS_COG]] Link 2.
- **Prior over‑weighting** — incoming evidence is forced to fit existing priors. *Confirmation bias, motivated reasoning.* This is a curvature event — the window can be structurally present while curvature routes evidence toward the prior-dominant attractor before integration occurs. [[contract_WINDOWS_COG]] Prediction 7.
- **Temporal compression** — the prediction window narrows; long‑range consequences vanish. *Short-termism, hyperbolic discounting.* This is a depth failure: retrospective and prospective depth truncate under load before width collapses.
- **Identity anchoring** — source identity replaces content evaluation as the primary classifier. *Ad hominem, in-group/out-group reasoning.* This is the [[contract_COG_REASON_ESCALATION]] convergence: workspace collapse + SOC↔COG identity-as-precision-proxy.
- **Cross‑domain transfer failure** — what is learned in one domain cannot propagate to another because the shared geometric space that would allow it was never constructed. *Inability to generalize, silo-reinforced expertise.* [[contract_WINDOWS_COG]] Link 2.

### Why This Reframe Matters

Fallacies are not:
- failures of intelligence
- gaps in education
- incorrect logic

They are **state‑dependent outputs** of a regulatory architecture whose precision, priors, and temporal horizon have shifted.

Correcting them is not about teaching logic.
It is about restoring **prediction‑window width**, **precision balance**, and **regulatory stability** — which means substrate intervention precedes cognitive intervention. [[contract_WINDOWS_COG]] Failure Mode: The intervention mismatch.

These same precision‑state dynamics shape how people scaffold interactions with external systems — including AI.

---

## 🤖 AI Interactions Driven by Regulatory Profiles
People don't interact with AI systems uniformly.
Once cognition is modeled as regulation, not symbol manipulation, the variation becomes predictable.

AI interaction quality is shaped by regulatory profiles — stable configurations of:

- **Precision modulation** — how tightly meaning, inference, and context are constrained
- **Prediction‑window width** — how far ahead conversational trajectories can be modeled; wide-window users generate structural queries that cross domains and hold ambiguity; narrow-window users generate identity-anchored queries that require confirmation rather than exploration. The geometry is [[contract_WINDOWS_COG]].
- **Interoceptive weighting** — how strongly internal signals bias interpretation
- **Curvature** — how aggressively prior weighting bends the interaction toward known attractors; high-curvature users resist revision and interpret prediction errors as threats rather than updates, producing the sycophancy attractor in compliant systems

---

## License

Creative Commons Attribution 4.0 International (CC BY 4.0).
