# Unified Model
[![DOI](https://zenodo.org/badge/1251586759.svg)](https://doi.org/10.5281/zenodo.20417459)


A unified, layered model of mammalian regulation built from first principles.  
This repository defines the minimal core architecture and the modular contracts
that govern interactions between autonomic, cognitive, interoceptive, metabolic,
immune, neuromodulatory, and social regulatory layers.

The goal of this project is simple:  
**provide a coherent, portable ontology that explains cross-domain regulatory
phenomena without relying on siloed biomedical terminology.**

This is a specification, not a narrative.  
It is meant to be read, queried, extended, and mapped into.

---

## Overview

Modern physiology and psychology describe regulation through fragmented domains:
autonomic, cognitive, metabolic, immune, social, developmental, and so on.  
This framework unifies them into a single architecture with:

- A **Minimal Core** — generative rules of the regulatory stack
- **Contracts** — input/output mappings between layers
- A **portable ontology** — applicable to any regulatory phenomenon
- A **domain-agnostic vocabulary** — no silo‑specific jargon 

The architecture is designed to be:

- **Modular** — contracts are independent but interoperable
- **Predictive** — explains and anticipates cross-domain effects
- **Portable** — spans physiology, cognition, behavior, pathology
- **Extensible** — new domains map cleanly into existing primitives  

---
## 📚 Repository Navigation


- **[Architecture Overview](architecture_conceptual_overview.md)** — high‑level conceptual map of the regulatory stack and how the contracts fit together
- **[Minimal Core](minimal_core.md)** — the backbone specification (breathing → HRV → autonomic → cognition)
- **[Contracts](contracts/)** — bilateral interfaces defining signal flow between layers
- **[Gap Analysis](gap_analysis/)** — development history, resolved contradictions, and evidence audits (v1 → v6)
- **[README](readme.md)** — repository purpose, structure, and usage guidance

---

## Repository Structure
```
architecture_conceptual_overview.md
minimal_core.md
contracts/
  contract_AUTO_MOD.md
  contract_COG_INTERO.md
  contract_COG_REASON.md
  contract_GLYPH_AUTO.md
  contract_IMMUNE_AUTO.md
  contract_INTERO_DEV.md
  contract_MICRO_AUTO.md
  contract_MET_AUTO.md
  contract_MET_IMMUNE.md
  contract_NOCI_COG.md
  contract_SOC_COG.md
  contract_SOC_AUTO.md
gap_analysis/
  framework_gap_analysis...md   
```
  
Each contract defines:

- **Input layer**  
- **Output layer**  
- **Regulatory transformation**  
- **Failure modes**  
- **Cross-domain implications**  

Together, these files form a complete regulatory architecture.

---

## How to Use This Framework

This repository is a **reference architecture**. You can:

- Map domain-specific mechanisms into the contracts  
- Use the ontology to explain complex regulatory phenomena  
- Query the architecture to understand multi-layer interactions  
- Extend the model with new contracts or domains  
- Apply the framework to research, modeling, or conceptual analysis  

If you want to understand phenomena like:

- **Autonomic storms** — breakdowns in sympathetic/parasympathetic stability leading to runaway physiological oscillations.
- **Hallucinations** — perceptual inference dominated by priors when sensory precision collapses.
- **Dissociation** — decoupling of interoceptive signals from cognitive models under extreme precision imbalance.
- **Inflammatory cascades** — immune–autonomic feedback loops that amplify threat physiology.
- **Metabolic crashes** — failures in fuel prediction and autonomic regulation leading to sudden energy collapse.
- **Trauma responses** — developmental shaping of priors that bias threat detection and autonomic reactivity.
- **Cognitive distortions** — maladaptive belief‑updating patterns driven by skewed precision weighting.
- **Social threat amplification** — hypersensitive SOC ↔ AUTO coupling that magnifies perceived interpersonal danger.
- **Neurodivergence** — alternative precision regimes across sensory, cognitive, and interoceptive channels.
- **Consciousness** — coherence across regulatory contracts forming a unified global workspace.
- **Gender identity** — a developmentally anchored interoceptive prior that becomes “fixed” only when polarized social roles impose high‑precision demands; in low‑pressure environments, the underlying generative model shows its natural flexibility.
- **Chronic disease** — long‑term multisystem dysregulation across metabolic, immune, and autonomic layers.
- **AI Interactions driven by Regulatory Profiles** — regulatory responses to non‑human agents with atypical social signal patterns.
- **Sleep and dreaming** — offline generative model consolidation and autonomic recalibration.
- **Learning and memory** — cross‑layer plasticity shaping future prediction and regulation.
- **Plasticity** — adaptive changes in synaptic, autonomic, interoceptive, and social inference pathways.
- **Addiction** — hijacking of dopaminergic precision and habit loops within MOD ↔ COG dynamics.
- **Digital platforms** — algorithms optimize for sympathetic activation which drops HRV and creates a feedback loop by collapsing prediction windows
- **Near‑death experiences** — catastrophic precision collapse across metabolic, autonomic, interoceptive, and cognitive layers forcing the generative model to fallback on its deepest, lowest‑entropy priors to maintain coherence.
- **Flow** — a high‑coherence state where prediction errors are minimized through tight sensorimotor loops, stabilized neuromodulation, and suppressed self‑modeling, producing effortless action with maximal precision.
- **Placebo** — cognitive priors modulating autonomic, interoceptive, and immune precision weighting, allowing belief‑driven predictions to produce real physiological change.

…load the relevant contracts and trace the regulatory pathways.

This architecture is **domain‑agnostic** — if a phenomenon emerges from regulation, it can be mapped into this model.

---

## Why This Exists

Modern science describes regulation through isolated silos.
This project provides a unified regulatory architecture that reintegrates those fragments into a single generative model.

The goal is not to replace domain‑specific theories, but to offer:
- a shared ontology for cross‑domain reasoning
- a minimal set of primitives explaining complex phenomena
- a portable architecture spanning biology, cognition, behavior, pathology
- a mechanistic alternative to diagnostic or narrative explanations

It exists so researchers, engineers, clinicians, and theorists can map diverse phenomena — from consciousness to chronic disease to neurodivergence — into a single coherent system.

---

## Origins of the Framework

This architecture emerged from an attempt to understand a set of regulatory phenomena that appeared unrelated on the surface — functional neurological symptoms, neurodivergent processing patterns, autonomic instability, hypermobility‑linked dysregulation, and other atypical physiological and cognitive responses.

As each domain was examined, the same underlying mechanisms kept reappearing:
- **precision modulation**
- **prediction‑window dynamics**
- **interoceptive weighting**
- **autonomic load**
- **cross‑layer coupling**  

What began as an effort to explain one condition revealed a deeper pattern:
- the regulatory stack behaves according to a small set of generative rules that manifest across multiple systems.

The framework was not designed top‑down.
It was **discovered iteratively**, as overlapping mechanisms surfaced across domains that are normally treated as independent. Each new phenomenon — metabolic crashes, dissociation, sensory volatility, immune‑autonomic loops, social threat amplification — mapped cleanly onto the same primitives. The architecture expanded only when necessary, and contracted whenever two mechanisms proved to be expressions of the same underlying process.

The result is a **minimal, unified regulatory model**:
a set of contracts and primitives capable of explaining diverse physiological, cognitive, and behavioral phenomena without relying on siloed terminology.
This framework exists because the patterns were too consistent to ignore — and because a single architecture could account for complexity that previously required multiple disconnected theories.

---

## 🧬 Neurodivergence vs Neurotypical Profiles

ND and NT profiles differ not by “traits,” but by regulatory parameter settings that shape signal weighting, prediction formation, and frame stability.

Key differences:

- **Precision modulation** — ND systems run higher precision on sensory/cognitive channels; NT systems smooth input
- **Interoceptive gain** — ND systems amplify or suppress internal signals; NT systems maintain stable ranges
- **Regulatory load** — ND systems operate with higher baseline autonomic demand
- **Prediction‑window width** — ND windows extend further or collapse under load
- **Behavioral inertia** — ND systems have stronger attractor states
- **Developmental stabilization** — ND patterns consolidate earlier or more intensely

This frames neurodivergence as a regulatory architecture variant, not a deficit.

---

## 🩺 Chronic Disease and Regulatory Architecture

Chronic disease emerges when one or more layers enter a stable but maladaptive attractor state.

Cross‑layer failures include:
- **Autonomic overactivation or collapse** — persistent sympathetic drive, vagal withdrawal, or oscillatory flattening
- **Metabolic‑autonomic coupling failures** — impaired energy availability, mitochondrial down‑regulation, or metabolic crashes
- **Immune‑autonomic feedback loops** — chronic inflammation, cytokine amplification, or immune‑driven threat signaling
- **Interoceptive distortion** — misweighted internal signals leading to fatigue, pain, or dyshomeostasis
- **Regulatory load saturation** — baseline load exceeding system capacity, reducing adaptability
- **Developmental consolidation of maladaptive patterns** — long‑term stabilization of dysregulated states

This reframes chronic disease as a regulatory‑architecture problem, not a collection of unrelated symptoms.
It provides a unified way to trace how autonomic, metabolic, immune, and cognitive layers interact to produce persistent dysregulation.

---

## ⚠️ Digital Platforms as Adversarial Regulatory Environments

Modern digital platforms optimize for engagement, not regulation — and the architecture of engagement directly conflicts with the architecture of mammalian regulation.

Two contracts in the framework make this mechanically explicit:

- SOC ↔ AUTO — digital communication strips the co‑regulatory channels humans rely on  
  > “Digital communication strips most of the channel bandwidth through which social co‑regulation operates… producing the appearance of connection without the regulatory transfer that connection is supposed to accomplish.”  
  

- SOC ↔ COG — platforms overload the cognitive social‑prediction channel  
  > “Social media may actually impose higher COG‑channel social load than in‑person interaction while providing less AUTO‑channel co‑regulation — the worst combination for regulatory health.”  
  

The result:  
Platforms systematically push users toward high‑load, low‑regulation states because those states produce more predictable, reactive, high‑engagement behavior.

What platforms optimize for
- **Unpredictability** → narrows prediction windows  
- **Ambiguity** → increases cognitive load  
- **Threat cues** → suppresses VVC activation  
- **Asynchronous text** → removes co‑regulation  
- **Infinite agent exposure** → overloads social generative models  

What humans need
- Prosody, synchrony, facial cues  
- Predictable social context  
- Co‑regulatory HRV transfer  
- Stable precision gain  
- Low‑noise interoceptive feedback  

Digital platforms remove the stabilizing channels and amplify the destabilizing ones.  
This is not a moral failure — it is architectural incompatibility between:

- the mammalian regulatory stack, and  
- engagement optimized digital systems.

---

## Threat‑State Behaviors Precede Cognitive Distortions

Threat physiology constrains the prediction window before cognition engages, so reasoning failures are downstream of autonomic state, not upstream.

**Causal chain:**
```
Breath → HRV → Autonomic Mode → Precision Regime → Prediction Window → Reasoning Output
```

The earliest failure mode is **physiological**, not cognitive:

- **Truncated exhale** — reduces parasympathetic gating
- **Shallow inhale** — reduces tidal volume and vagal afferent signaling
- **Collapsed posture** — reduces baroreceptor stretch
- **Reduced baroreceptor stretch** — brainstem interprets this as threat, shifting precision toward defensive priors
- **Defensive priors** — produce threat‑logic, fallacies, and rigidity

The system is not malfunctioning or thinking poorly.
It is _correctly inferring threat_ from degraded breathing and posture.

This is why threat‑state behaviors show up **before** any reasoning contract is engaged:

- option space collapses
- prediction windows shorten
- social inference becomes defensive
- priors harden
- fallacies appear automatically

These are not cognitive mistakes — they are **autonomic signatures**.

---

## 🧩 Illogical Fallacies as Regulatory‑State Artifacts

What we call “logical fallacies” are not reasoning mistakes — they are the **behavioral signatures of a cognitive system under altered precision and prediction‑window constraints**.

When the regulatory stack shifts (stress, metabolic load, interoceptive noise, social threat, etc.), the inference engine reconfigures. The system produces outputs that are _locally optimal_ for that precision regime, even if they appear illogical from the outside.

### Mechanistic Origins of Fallacies

Each distortion reflects a specific precision‑allocation failure mode:

- **Option‑space collapse**  
    The system reduces a multidimensional problem to a binary choice.  
    _False dichotomies, black‑and‑white reasoning._
    
- **Prior over‑weighting**  
    Incoming evidence is forced to fit existing priors.  
    _Confirmation bias, motivated reasoning._
    
- **Temporal compression**  
    The prediction window narrows; long‑range consequences vanish.  
    _Sunk‑cost fallacy, short‑termism._
    
- **Precision hijack by social signals**  
    Identity‑relevant cues dominate evidence weighting.  
    _Appeal to authority, ad hominem, group‑loyalty reasoning._
    
- **Model‑of‑other simplification**  
    The system reduces other agents to low‑resolution caricatures.  
    _Straw man, intent attribution errors._
    
- **Runaway prior chains**  
    Priors propagate unchecked due to missing correction points.  
    _Slippery slope, catastrophizing, paranoid escalation._
    

### Why This Reframe Matters

Fallacies are not:

- failures of intelligence
- gaps in education
- incorrect logic

They are **state‑dependent outputs** of a regulatory architecture whose precision, priors, and temporal horizon have shifted.

Correcting them is not about teaching logic.  
It’s about restoring **prediction‑window width**, **precision balance**, and **regulatory stability**.

These same precision‑state dynamics shape how people scaffold interactions with external systems — including AI.

---

## 🤖 AI Interactions Driven by Regulatory Profiles


People don’t interact with AI systems uniformly.
Once cognition is modeled as regulation, not symbol manipulation, the variation becomes predictable.

AI interaction quality is shaped by regulatory profiles — stable configurations of:

- **Precision modulation** — how tightly meaning, inference, and context are constrained
- **Prediction‑window width** — how far ahead conversational trajectories can be modeled
- **Interoceptive weighting** — how strongly internal signals bias interpretation
- **Regulatory load** — available bandwidth for maintaining context and coherence
- **Behavioral inertia** — how easily conversational frames can shift
- **Social‑cognitive contracts** — how individuals negotiate shared meaning and intent

Many “AI hallucinations” are not model failures but frame mismatches — the AI is following the user’s degraded scaffolding.
“Good prompting” is just stable regulatory scaffolding.

This reframes AI interaction differences as expressions of regulatory architecture, not user skill.

---

## License

Creative Commons Attribution 4.0 International (CC BY 4.0).

---

## Citation

**Regulatory Architecture Framework (2026).  
https://github.com/jtrhehax/Unified-Model**

---

## Contributing

Pull requests that extend the architecture, add mappings, or propose new contracts are welcome.  
This is a living specification.

