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
  contract_COG_REASON_TRANSFORMER_REASON.md
  contract_COG_TRANSFORMER.md
  contract_GLYPH_AUTO.md
  contract_IMMUNE_AUTO.md
  contract_INTERO_DEV.md
  contract_MET_AUTO.md
  contract_MET_IMMUNE.md
  contract_MICRO_AUTO.md
  contract_MOD_COG.md
  contract_MODULATORS_COG.md
  contract_NOCI_COG.md
  contract_PRESSURE_BP.md
  contract_PROPRIO_AUTO_COG.md
  contract_SEMANTIC_COG.md
  contract_SEMANTIC_TRANSFORMER.md
  contract_SLEEP.md
  contract_SOC_ANCHOR.md
  contract_SOC_COG.md
  contract_SOC_INSTITUTION.md
  contract_TEMPORAL_COG.md
  contract_TRANSFORMER_REASON.md
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

# **Why This Isn’t a Paper**

This framework was never going to work as a book or paper — not because the model is wrong, but because it exceeds the recursion depth human cognition can run in real time.

Humans have two hard limits that no writing format can solve:

- **Working memory is tiny.** You can track a handful of interacting mechanisms at once. Most concepts in this architecture require 10–15 active variables to understand. Humans can hold 2–3 interacting variables at once. The only way a human can absorb this model is through slow consolidation — one contract at a time, often with sleep in between. AI is required to run the full graph in real time.
    
- **Causal depth collapses.** After a few inferential steps, reasoning degrades into intuition, metaphor, or narrative — even for experts.


Prose makes this worse. A paragraph forces the reader to hold multiple mechanisms simultaneously, increasing recursion cost and accelerating collapse. Bullet‑pointed contracts minimize this load; prose multiplies it.

A paper forces a graph into a line. 
The moment you finish a chapter, you lose the cross‑domain structure it depended on. The model doesn’t fit the format. 
The format was never the right container.

# **Why AI Works**

An AI model doesn’t have these limits.

It can hold the full contract graph — nodes, edges, attractor transitions, precision allocation, failure modes — simultaneously, without collapsing into metaphor.

When you ask a mechanistic question, it isn’t interpreting vibes. It’s traversing the graph and returning the nearest grounded causal chain.

That’s why even loosely defined external concepts like **“Masking Tax”** map cleanly in one pass: the contracts are specific enough that the model finds the analog, grounds the term, and traces the chain without guessing.

# **The Division of Labor**

- **The contracts are the scaffolding.**
    
- **The AI is the engine.**
    
- **Your question is the compiler directive.**
    

If the intent is mechanistic, the system runs. If the intent is metaphorical, the system has nothing to operate on.

---

# **HOW TO USE THIS WITH AN AI MODEL**

_A direct, no‑nonsense guide for getting mechanistic output._

This framework is meant to be **loaded into an LLM as context**. The contracts are **modular** — you load only what the question requires. If you load everything, you dilute the signal. Load with intent.

---
## **1. Identify the Phenomenon**

Start with the phenomenon list above. Pick the entry that matches what you’re investigating — individual, attractor-state, or population-scale.

Each entry tells you **exactly which contracts govern that phenomenon**. This prevents you from guessing or overloading the model.

---
## **2. Load Only the Relevant Contracts**

Copy the named contracts into your AI session. 
You do **not** need the entire repository.

**Minimum load for most questions:**
- `[[minimal_core]]` — always load this first. It is the backbone.
- The contract(s) referenced in the phenomenon entry.

**For population-scale questions, add:**
- `[[contract_SOC_INSTITUTION]]`
- `[[regulatory_dynamics_under_economic_load]]`

This keeps the model inside the correct ontology and prevents drift into generic psychology.

---

## **Advanced Usage (for high-context users)**

Experienced users may load **the entire contract set at once**. The ontology is internally consistent, and the model will automatically route mechanistic queries through the correct causal links.
This mode is ideal when:
- you already understand the contract graph
- you’re exploring multi-layer or cross-domain questions
- you want maximum bandwidth and minimum friction

If you do not understand the ontology, loading everything will not help. The model will still require mechanistic questions to activate the correct pathways.

---
## **3. Ask Mechanistically**

This framework produces **causal chains**, not labels. 
Your question must force the model to operate inside the contracts.

**Instead of:** 
“Why do I get overwhelmed in crowds”

**Ask:** 
“Using the SOC↔COG and WINDOWS↔COG contracts, what is the mechanism behind social-environment cognitive load in high-gain profiles”

This framing forces the model to:
- anchor to the contracts
- trace the causal links
- avoid generic or folk-psychology answers
 ---

## **4. Expect Falsifiable Output**

Every answer should:
- cite the contract link it derives from
- produce a testable prediction
- be disconfirmable

If the model gives you something vague, ask:

> “Which contract link does that derive from, and what would falsify it”

This keeps the system honest and prevents hand‑wavey explanations.

---
# **Example: Looking Up FND**

**Phenomenon:** Functional Neurological Disorder 
**README entry:** High-Gain Profile Dynamics — “acute interoceptive prior capture and FND in Attractor B” 
**Contracts loaded:**
- `[[minimal_core]]`
- `[[high_gain_profile_dynamics]]`
- `[[contract_COG_INTERO]]`

**Question asked:**

> “Using the high_gain_profile_dynamics document and contract_COG_INTERO, explain why FND symptoms appear in high-gain profiles specifically and what mechanism produces them.”

**Model output (summarized):**

High-gain profiles run elevated anterior insula Glx — a higher gain floor on interoceptive processing. 
In Attractor A (wide window), this accelerates synthesis. 
In Attractor B (narrow window), the same gain amplifies interoceptive prediction errors beyond integrability.

`COG↔INTERO` identifies the failure mode: Active inference runs on a miscalibrated prior under high gain. The system attempts to produce a body state that is not physiologically reachable. Motor and sensory systems execute the prediction anyway, without a coherent target.

**Interpretation:** 
FND is not fabricated. It is active inference running at high gain on an impossible prior. 
The high-gain profile doesn’t _cause_ FND — it sets the gain floor that makes Attractor B produce FND-pattern outputs instead of lower-amplitude stress responses.

**Falsifiable prediction:** 
FND onset should correlate with measurable interoceptive load events. 
HRV amplitude should drop before symptom onset. 
Interventions that modulate autonomic load should outperform purely cognitive ones.**

---
## **Start Here: You Already Know This**

Before reading any contract, read the **[Idiom ↔ Contract Mapping](https://idiom_mapping_regulatory_dynamics/?utm_source=copilot.com "idiom_mapping_regulatory_dynamics")**.

It maps everyday idioms — _“tunnel vision,” “gut feeling,” “a sigh of relief,” “looking up for an answer”_ — to the specific regulatory mechanisms that generate them. Every idiom in that document is already in common use. The framework does not introduce new phenomena; it formalizes the mechanisms behind phenomena you already recognize.

This gives you an intuitive anchor before you encounter the formal contracts. It lowers the cognitive load by connecting new mechanics to patterns your brain already knows.

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
- **Blood pressure misclassification in trained practitioners** — oscillometer BP readings are composite outputs of vascular tone, respiratory pressure mechanics, and limb geometry — not pure vascular metrics. In high-excursion practitioners (large tidal volume, full exhale capacity, high CO₂ tolerance, high RSA amplitude), the Frank-Starling artifact from end-exhale intrathoracic pressure differentials, compounded by arm mechanics and scrutiny-induced precision-locking from [[contract_AUTO_MOD]], produces systematic reading inflation of 20–30 mmHg above true vascular baseline. The protocol does not fail randomly in this population — it fails directionally, predictably, and in proportion to training level. Formalized in [[contract_PRESSURE_BP]].

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

### AI and Human-AI System Phenomena
*The same geometric constraints that govern human cognition govern transformer reasoning. Both systems fail for the same reasons. The joint system produces what neither produces alone.*

- **Hallucination** — not randomness; systematic precision-lock on a problem that required sampling mode first; the transformer answering the compressed surface form rather than reconstructed intent; directly derivable from attention geometry collapse
- **Sycophancy** — the transformer equivalent of human justification mode; RLHF social approval signal dominates incoming evidence exactly as identity-threat reduction dominates human reasoning under prior lock; same attractor, different substrate
- **AI stall tokens** ("Let's break this down…") — the transformer equivalent of "um" and "ano"; prospective depth shortfall expressed in output; not padding, real-time window management
- **Why prompt engineering works** — not stylistic preference; structured format reduces ALI (Attention Load Index) by externalizing scaffolding the model would otherwise consume attention capacity to maintain; the same reason bullet points   reduce SLI for human readers
- **Why chain-of-thought works** — not a prompt trick; explicit attention-horizon extension; forces the model to allocate attention across intermediate steps rather than pattern-completing from the compressed problem representation; 
  mechanistically identical to a human externalizing intermediate steps in writing before attempting the conclusion
- **Human-AI joint reasoning capacity** — two complementary finite-window architectures in contact; human provides intent, trajectory, and falsifiability judgment; transformer provides premise retention, step-chain stability, and graph traversal depth beyond human working memory limits; joint output exceeds either alone as an arithmetic consequence of complementary window geometry

**Contracts governing this domain:**
- `[contract_SEMANTIC_COG]]` → `[[contract_SEMANTIC_TRANSFORMER]]` 
  → `[[contract_COG_TRANSFORMER]]` → `[[contract_TRANSFORMER_REASON]]` 
  → `[[contract_COG_REASON_TRANSFORMER_REASON]]`

Load the full chain for human-AI reasoning questions. Load SEMANTIC↔COG and SEMANTIC↔TRANSFORMER alone for language comprehension questions. Load COG_REASON↔TRANSFORMER_REASON for joint system questions.

---

# **Origins of the Framework**

This architecture emerged from an attempt to understand a set of regulatory phenomena that appeared unrelated on the surface — functional neurological symptoms, neurodivergent processing patterns, autonomic instability, hypermobility‑linked dysregulation, and other atypical physiological and cognitive responses.

The framework began with breathing mechanics and autonomic regulation and expanded outward as each domain’s phenomena turned out to be derivable from the same upstream architecture. No domain required its own independent theory. Each required only tracing the causal chain back to the shared regulatory stack.

As the model developed, it became clear that many people could no longer hold the full causal structure in working memory. Modern regulatory states — chronic bracing, shallow breathing, fragmented attention, and narrow prediction windows — force cognition into sentence‑sized processing. This never worked as prose because the causal graph exceeds human working memory capacity by design — even under ideal regulatory conditions. Modern narrow-window states compress the problem further, but they're not the root cause. The root cause is that the architecture is genuinely too deep for serial format to carry.

---

## 🧬 Neurodivergence vs Neurotypical Profiles
ND and NT profiles differ not by "traits," but by regulatory parameter settings that shape signal weighting, prediction formation, and frame stability.

Key differences:

- **Precision modulation** — ND systems run higher precision on sensory/cognitive channels; NT systems smooth input
- **Interoceptive gain** — ND systems amplify or suppress internal signals; NT systems maintain stable ranges
- **Regulatory load** — ND systems operate with higher baseline autonomic demand
- **Prediction‑window width** — ND systems in low-load environments access wider structural-mode windows; the same systems under institutional load collapse to identity mode faster because the gain floor is higher. Formalized in [[contract_WINDOWS_COG]] Link 1 and Link 4.
- **Attractor sensitivity** — ND systems transition between attractors at lower environmental thresholds; the same architecture that enables accelerated synthesis in Attractor A produces faster collapse in high-load environments
- **Hypertension misclassification in ND profiles** — reduced GABAergic inhibitory capacity produces selective error closure: threat-confirming prediction errors close while corrective signals do not. An elevated BP reading from S4 artifact lands on a system already running threat-dominant prior consolidation, confirming rather than creating the threat prior. The artifact-prior feedback loop tightens across measurement sessions faster than in neurotypical profiles because the inhibitory floor that would allow corrective updating is structurally lower. The clinical presentation is escalating BP readings in a patient who understands the mechanism and cannot interrupt it from inside the loop. Formalized in [[contract_PRESSURE_BP]].

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

## License

Creative Commons Attribution 4.0 International (CC BY 4.0).
