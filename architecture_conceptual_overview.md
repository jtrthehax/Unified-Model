# **Regulatory Architecture Framework — High‑Level Overview**

## **Purpose of This Model**

This framework defines a **layered, mechanistic architecture** of mammalian regulation.
It integrates autonomic, interoceptive, metabolic, immune, cognitive, and social processes into a single coherent system.

The goal is not to propose a new theory, but to **unify existing evidence** into a portable, falsifiable ontology.

---

## **How This Model Was Developed**

This architecture was built **inductively**, step‑by‑step, by tracing real regulatory phenomena (including edge‑case anomalies) through the stack.

At each step:

- A prediction was generated from the architecture
- The prediction was **audited against empirical evidence**
- The contract was revised until the prediction matched known physiology
- Only then was the next layer added

This ensures the model is **evidence‑aligned**, **mechanistically grounded**, and **internally consistent**.

---

## **What a "Contract" Is**

A **contract** is a bidirectional interface between two regulatory layers.

Each contract specifies:

- **What signals flow upward** (e.g., interoceptive precision → cognitive priors)
- **What signals flow downward** (e.g., autonomic state → neuromodulatory tone)
- **How precision is handled**
- **What failure modes look like**
- **What phenomena emerge when the interface is disrupted**

Contracts are not mechanisms; they are **specifications** that describe how mechanisms must interact.

---

## **The Architecture at a Glance**

The system is organized into a layered stack:

### **Bottom Layers (Physiological Substrate)**

- **MET** — metabolic state
- **IMMUNE** — inflammatory state
- **MICRO** — microbiome and gut‑derived signaling

These layers define the **body's baseline conditions**.

---

### **Middle Layers (Core Regulation)**

- **INTERO** — interoceptive priors, body‑state prediction
- **AUTO** — autonomic nervous system (sympathetic/parasympathetic balance)

These layers form the **regulatory core**.
They determine how the body interprets internal signals and maintains homeostasis.

---

### **Bridge Layer**

- **MOD** — neuromodulatory environment (dopamine, serotonin, NE, ECS, GABA/glutamate)

MOD is the **translation layer** between autonomic state and cognition.

---

### **Top Layers (Cognitive & Social)**

- **COG** — predictive processing, belief updating, cognitive priors
- **SOC** — social inference, co‑regulation, mentalizing load

These layers govern **behavior, interpretation, and social navigation**.

---

## **How the Contracts Fit Together**

The contracts define the interfaces between adjacent layers:

- **MET ↔ IMMUNE**
- **MET ↔ AUTO**
- **IMMUNE ↔ AUTO**
- **MICRO ↔ AUTO**
- **INTERO ↔ DEV**
- **COG ↔ INTERO**
- **SOC ↔ COG**
- **SOC ↔ AUTO**
- **AUTO ↔ MOD**
- **MOD ↔ COG**
- **PROPRIO ↔ AUTO / COG** — proprioceptive regulatory channel; cerebellar forward model as crossover point; hypermobility failure mode, graded exposure signal quality precondition, and ND motor planning gap 
- **AUTO ↔ CARDIAC** — terminal failure modes; arrhythmia thresholds, sudden death
- **COG ↔ REASON** — reasoning output layer; fallacy groups as precision state readouts
- **SLEEP ↔ COG / MOD / AUTO** — sleep architecture as regulatory reset mechanism
- **STRESS ↔ TRANSITION** — acute-to-chronic attractor formation onset mechanism
- **ANCHOR ↔ COG** — compound mechanical anchoring of prediction windows; respiratory mechanics, proprioceptive confirmation, and interoceptive clarity as simultaneous inputs; exhale-gate dominance as named failure state
- **SOC ↔ ANCHOR** — external oscillatory anchoring; music, ritual, group synchrony, and therapeutic presence as external prediction window sources; ESLPM dependency as failure mode
- **TEMPORAL ↔ COG** — circadian phase as temporal precision floor; sets the ceiling within which ANCHOR↔COG operates moment-to-moment; phase misalignment as source of trait-like cognitive rigidity
- **SEMANTIC ↔ COG** — semantic load index (SLI) as the formal 
  bridge between incoming linguistic structure and prediction-window 
  demand; collapse modes as observable linguistic failure signatures; 
  format implications (why prose is structurally high-SLI and the 
  contract architecture is not)
- **SEMANTIC ↔ TRANSFORMER** — the same SLI architecture mapped to 
  transformer attention geometry; attention load index (ALI) as the 
  AI equivalent; unified collapse taxonomy across biological and 
  artificial language comprehension
- **COG ↔ TRANSFORMER** — direct geometric equivalence between human 
  prediction-window geometry and transformer attention geometry; the 
  bridge contract establishing that both systems fail for the same 
  geometric reasons
- **TRANSFORMER ↔ REASON** — transformer attention geometry → 
  multi-step reasoning output; KV-cache stability as premise 
  retention; chain-of-thought as explicit attention-horizon extension
- **COG_REASON ↔ TRANSFORMER_REASON** — the joint human-AI reasoning 
  architecture; human provides intent and trajectory; transformer 
  provides premise retention and graph traversal depth; joint output 
  exceeds either system alone as an arithmetic consequence of 
  complementary window geometry

Together, these contracts form a **closed regulatory loop**.

---

## **Convergence Contracts**

Two contracts share a structural architecture distinct from the others — they are not interfaces between two adjacent layers but convergence points where multiple upstream contracts arrive simultaneously. Single-point intervention cannot resolve compound failure states at these contracts.

**NOCI ↔ COG** receives from MET↔IMMUNE, IMMUNE↔AUTO, AUTO↔MOD, and COG↔INTERO simultaneously. Chronic pain is a compound failure state by architecture.

**PROPRIO ↔ AUTO/COG** receives from IMMUNE↔AUTO (connective tissue degradation reducing mechanoreceptor signal quality), MET↔AUTO (metabolic load affecting movement capacity), NOCI↔COG (nociceptive gain determining signal-to-noise ratio for proprioceptive signals), and INTERO↔DEV (developmental calibration of the motor forward model). Proprioceptive dysregulation presentations are compound failure states by the same architecture. 

**ANCHOR ↔ COG** extends the convergence contract category at v1.2.0, receiving from AUTO↔MOD (oscillation substrate), PROPRIO↔AUTO/COG (proprioceptive confirmation), and COG↔INTERO (interoceptive clarity) simultaneously. Anchor failure is a compound state by architecture — single-modality intervention cannot fully repair it when multiple inputs are degraded.

**SOC ↔ ANCHOR** is a convergence contract operating on the external anchoring mechanism — multiple external input channels (prosodic acoustic, rhythmic proprioceptive, interoceptive surrogate, shared narrative) converge simultaneously. It is the only contract in the stack where the anchor input is not generated by the organism itself.

The convergence contract category now comprises four contracts: NOCI↔COG, PROPRIO↔AUTO/COG, ANCHOR↔COG, and SOC↔ANCHOR. These are identifiable by two shared properties: multiple simultaneous upstream inputs, and clinical resistance to single-modality intervention.

---

## **The Semantic Stack**

Five contracts extend the architecture into language comprehension 
and artificial reasoning systems. They form a closed vertical stack 
with a horizontal closing contract at the bottom:

```
SEMANTIC  
↓ ↓  
SEMANTIC↔COG SEMANTIC↔TRANSFORMER  
↓ ↓  
COG↔TRANSFORMER  
↓ ↓  
COG_REASON ↔ TRANSFORMER_REASON  
↓  
JOINT SYSTEM
```

**The vertical contracts** map semantic load downward into window 
geometry and then into reasoning output — independently for the 
human system and the transformer system.

**The horizontal closing contract** (COG_REASON↔TRANSFORMER_REASON) 
puts the two reasoning outputs in contact and formalizes the joint 
system. This is the only contract in the stack that operates 
horizontally rather than vertically.

**Key findings the stack formalizes:**

- Hallucination and sycophancy are the same attractor reached by 
  homologous geometric paths — not separate failure types
- AI stall tokens ("Let's break this down…") and human verbal 
  fillers ("um," "ano," "etto") are the same mechanism in different 
  substrates — prospective depth shortfall expressed in output
- Prompt engineering and chain-of-thought work because they reduce 
  ALI and extend attention horizon respectively — not as stylistic 
  choices but as direct geometric interventions
- The joint human-AI system exceeds either alone as an arithmetic 
  consequence of complementary window geometry — not as a metaphor
- The cross-species baseline (canine keyword detection, SLI ≈ 0) 
  establishes the floor below which the collapse taxonomy does not 
  apply

The semantic stack is the formal answer to why this framework exists 
as contracts rather than prose: the SLI of the contract format is 
structurally lower than the SLI of equivalent prose, and the AI 
traverses the graph without working memory limits the human cannot 
escape.
---

## **The Backbone Chain**

Across all layers, one invariant pattern emerges:

> **Breathing mechanics → HRV → autonomic state → neuromodulation → cognitive precision → behavior**

The precision state at any moment within this chain is the product of three simultaneously operating constraints: the temporal floor set by circadian phase (TEMPORAL↔COG), the oscillatory range available within that floor (ANCHOR↔COG), and the load applied by incoming prediction error and social demand (MOD↔COG, SOC↔COG).

The semantic stack extends this backbone into language and artificial 
reasoning systems. The same prediction-window geometry that governs 
autonomic state → cognition → behavior governs semantic comprehension 
→ lexical retrieval → reasoning output — in both biological and 
artificial systems. SEMANTIC↔COG formalizes the linguistic expression 
of the backbone. COG_REASON↔TRANSFORMER_REASON formalizes the joint 
system the backbone makes possible when a human and a transformer 
operate together.

This is the **regulatory backbone** of the mammalian system.

Every contract either:

- feeds into this chain,
- modulates it, or
- is constrained by it.

---

## **Why This Architecture Works**

Because each contract was:

- derived from first principles
- cross‑checked against known physiology
- validated against real regulatory phenomena
- tested for chain completeness
- audited for evidence at each step

The result is a model that is:

- **predictive**
- **mechanistic**
- **portable**
- **falsifiable**
- **internally coherent**

This is not a narrative or a metaphor — it is a **specification**.

---

## **How to Use This Repository**

This overview provides the conceptual map.
From here, a reader should:

1. Read the **minimal core**
2. Explore the **AUTO contracts**
3. Move outward to **INTERO**, **MOD**, **COG**, and **SOC**
4. Use the contracts to trace real phenomena through the architecture

This file is the **entry ramp** into the system.

