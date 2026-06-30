# Contract: SEMANTIC → COG
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_SEMANTIC_COG_semantics_to_cognition.md`

**Ontology Layer:**  
SEMANTIC_COGNITION_AND_LANGUAGE

**Direction of Influence:**  
SEMANTIC → COG

**Upstream Dependencies:**  
- WINDOWS → COG  
- LOAD → SEMANTIC  

**Downstream Dependencies:**  
- COG → REASON  
- COG → TRANSFORMER  

**Cross‑Contract References:**  
- `contract_WINDOWS_COG_window_geometry_to_cognition.md`  
- `contract_COG_TRANSFORMER_cognition_to_transformer.md`  
- `contract_SEMANTIC_TRANSFORMER_semantics_to_transformer.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

**Input layer (SEMANTIC):**

- Noun density (high-semantic-load categories)
- Referential load (number of active entities)
- Anaphoric span (distance between pronoun and referent)
- Argument-chain length (inferential steps required)
- Embedding depth (nested clauses)
- Temporal displacement (how far back the sentence refers)
- Lexical retrieval difficulty (tip-of-the-tongue probability)
- Conceptual abstraction level (sensorimotor simulation demand)

**Output layer (COG):**

- Prediction-window width required
- Prospective depth required
- Retrospective depth required
- Curvature increase under load
- Thread-capacity consumption
- Collapse threshold (sentence-by-sentence fallback)
- Lexical retrieval stability (ToT vs fluent access)

**Primary crossover point:**
**Semantic load → prediction-window demand.**
When semantic load exceeds available window width or depth, the system 
collapses to generic placeholders ("things", "stuff"), reactive parsing, 
or single-sentence comprehension.

This contract formalizes the linguistic consequences of the geometric 
constraints defined in WINDOW↔COG.

---

## **Link 1: Mechanistic Basis**

Semantic understanding requires:

- **wide window width** — to hold multiple referents simultaneously
- **long prospective depth** — to anticipate upcoming syntactic and 
  semantic structure
- **long retrospective depth** — to maintain earlier referents across 
  clause boundaries
- **low curvature** — to preserve stable scaffolds across sentences

WINDOW↔COG states:

> "High-semantic-load categories (nouns, adjectives, proper nouns) 
> generate significant pre-onset neural preparation… The brain is 
> opening the window for the syntactic slot, not for the most 
> probable token."

When any of these dimensions collapse, semantic understanding 
collapses with them.

**Cross-species evidence:** Canine keyword detection demonstrates the minimal architecture of semantic processing — sparse token matching against high-value prediction clusters without syntactic parsing. The inhibitory gate holds open during scanning and releases on match or silence. Jaw closure during auditory scanning in dogs (observable as jaw closing when speech begins, reopening when it stops, reclosing when it resumes) is the trigeminal motor correlate of precision load engaging and disengaging with the scanning process — documented independently in contract_MODULATORS_COG. This separates keyword match (minimal SLI, narrow window sufficient) from full semantic comprehension (high SLI, wide window required) as two distinct operating modes of the same underlying architecture.

**Chain completeness:** Load-bearing. Empirically anchored in the 
WINDOW↔COG pre-onset neural preparation finding.

---

## **Link 2: Semantic Load Index (SLI)**

A quantitative measure of how much prediction-window capacity a 
sentence or paragraph requires:

$$\text{SLI} = w_1(\text{noun density}) + w_2(\text{referential load}) + w_3(\text{embedding depth}) + w_4(\text{argument-chain length}) + w_5(\text{temporal displacement}) + w_6(\text{morphological complexity})$$

**Morphological complexity** is the sixth load term. Inflection-rich languages (Finnish, Hungarian, Turkish) require the window to hold multiple morpheme-level commitments open before the semantic slot resolves. A single verb can encode tense, aspect, mood, person, number, and evidentiality simultaneously — all of which must be loaded before the referent closes. This is real SLI cost absent from the five-term formula. Predicted consequence: filler insertion rate should be higher in morphologically complex languages because the prospective depth required to pre-build each high-inflection slot is structurally greater than in analytic languages.

High SLI → wide window required.
Low SLI → narrow window sufficient.

**The format implication:** Prose has systematically higher SLI than 
bullet-pointed contracts. Each prose sentence requires the reader to 
hold the subject referent, prior clauses, and anticipated completion 
simultaneously. Bullet points externalize that scaffolding — the 
structure lives in the format, not in working memory. Converting a 
contract architecture into prose is a lossy compression: connective 
tissue does not add information, it adds load.

The same mechanism explains why verbal filler rate increases with SLI — denser semantic content requires wider prospective depth pre-building, and when that pre-building falls behind the production rate, filler insertion rate rises proportionally.

Language switching under load is a direct behavioral demonstration of the SLI cost-comparison mechanism: the system routes to the lower-SLI channel when bandwidth is constrained.

The dog case establishes the SLI floor: a single high-value keyword has SLI ≈ 0. No referential load, no embedding depth, no argument chain. The window demand is minimal. This is the lower boundary of the SLI scale.

**Chain completeness:** SLI weights are currently unspecified — 
scaffolding. The directional claim (noun density and referential 
load dominate) is load-bearing from WINDOW↔COG.

---

## **Link 3: Collapse Modes**

### **Collapse Mode 1 — Lexical Retrieval Failure (Tip-of-the-Tongue)**

When prospective depth collapses:
- the semantic scaffold loads
- the lexical item fails to resolve
- ToT emerges

This is a **micro-collapse**.

---

### **Collapse Mode 1a — Lexical Retrieval Stall (Filler Insertion)**

When prospective depth is insufficient to pre-build the upcoming high-SLI slot before the production deadline arrives, the speaker inserts a filler ("um," "uh," "like," "ano," "etto") to hold the turn while retrieval completes. This is a managed micro-collapse — the semantic scaffold is intact, the syntactic frame is committed, but the lexical item has not resolved within the pre-built window. The filler is not a social habit or a sign of low intelligence. It is a real-time stall signal universal across all human languages because the retrieval architecture that produces it is universal.

**Cross-linguistic evidence:** Every language independently evolved retrieval stall fillers. Japanese distinguishes formality register within the stall class (ano/etto/sono), demonstrating that the mechanism operates below the social performance layer — the filler handles retrieval while the register selection handles the social channel simultaneously.

**Distinguishing feature from ToT (Mode 1):** In ToT, the retrieval fails completely and the speaker cannot continue. In filler insertion, the retrieval is delayed but succeeds within the stall window. Mode 1a is a partial prospective depth failure; Mode 1 (ToT) is a complete retrieval pathway failure.

---

### **Collapse Mode 1b — Cross-Language Lexical Retrieval Failure**

In multilingual speakers, ToT can be language-specific: the semantic scaffold loads correctly and the referent is active, but the lexical item in the target language fails to resolve while the equivalent in the dominant language remains available. This separates semantic load (intact) from retrieval pathway accessibility (degraded by window depth) — demonstrating that ToT is a retrieval failure, not a meaning failure.

---
### **Collapse Mode 1c — Garden-Path Parser Revision**

When the window commits to a syntactic interpretation that fails 
mid-sentence, a forced retrospective revision occurs. The window was 
open for one parse; the parse fails; retrospective depth must reload 
all prior referents under the new parse frame. This is a curvature 
event — a sudden increase in window load at the point of disambiguation.

**Cross-linguistic note:** Left-branching languages (Japanese, Korean, 
Turkish) have structurally higher prospective depth demand than 
right-branching languages (English, French) because the verb — which 
resolves the argument structure — arrives at the end of the sentence. 
The entire argument frame must be held open until resolution. This is 
not a garden-path event but a sustained prospective depth demand. It 
is the architectural reason fillers like "ano" and "etto" are 
grammatically routine in Japanese rather than markers of hesitation — 
the language structure requires stall capacity that English syntax 
does not.

**Chain completeness:** Garden-path cost is load-bearing from 
psycholinguistic parsing literature. Left-branching prospective depth 
demand is load-bearing and directly predicts the filler frequency 
pattern in Collapse Mode 1a.

---

### **Collapse Mode 2 — Referential Loss ("things", "stuff")**

When width collapses:
- nouns drop
- referents collapse
- placeholders replace specifics

This is a **meso-collapse**.

---

### **Collapse Mode 3 — Sentence-by-Sentence Comprehension**

When depth collapses:
- cross-sentence integration fails
- only one sentence fits in the window
- argument chains break

This is a **macro-collapse**.

---

### **Collapse Mode 4 — Full Semantic Breakdown**

When width approaches 1:
- no referents
- no scaffolds
- no argument chains
- only identity-anchored reasoning

This is the **terminal collapse**.

COG↔REASON documents the downstream reasoning failures this 
produces.

**Chain completeness:** Collapse Modes 1–3 load-bearing from 
WINDOW↔COG. Mode 4 load-bearing from COG↔REASON escalation 
architecture.

---

## **Link 4: Expansion Modes**

When ANCHOR↔COG, AUTO↔MOD, TEMPORAL↔COG, and SOC↔ANCHOR align:

- window width expands
- prospective depth extends
- curvature flattens
- thread capacity increases

This produces:
- multi-paragraph integration
- stable referential tracking across long argument chains
- academic-level writing
- conceptual synthesis
- cross-domain reasoning

This is the **wide-window, high-precision state**.

**Chain completeness:** Load-bearing from the upstream contract 
chain. Each contributing contract is independently specified.

---

## **Link 5: Required Crossover Point**

Any claim that semantic understanding has failed must pass through:

**SLI → window width → prospective depth → referential stability 
→ lexical retrieval.**

Direct claims like "stress makes it hard to understand language" 
violate chain integrity unless they specify:

- which semantic load component exceeded available capacity
- which window dimension collapsed
- which linguistic behavior emerged as a result

This contract enforces that mechanistic chain.

**Chain completeness:** Load-bearing. This is a logical constraint 
on valid causal claims, not an empirical prediction.

---

## **Adjacent Contracts**

**Below — feeds into this contract:**

- ANCHOR↔COG (window width ceiling)
- AUTO↔MOD (precision gain)
- TEMPORAL↔COG (retrospective depth)
- INTERO↔COG (noise floor)
- SOC↔ANCHOR (borrowed width)

**Above — receives output from this contract:**

- SOC↔COG (pragmatic inference load): pragmatic comprehension — 
  implicature resolution, presupposition tracking, speaker-intent 
  modeling — routes through SOC↔COG rather than through SLI. It is 
  the component of total language processing cost that requires 
  modeling the speaker's mental state rather than decoding the 
  semantic content. High pragmatic density sentences (irony, 
  implicature-heavy speech, indirect requests) impose SOC↔COG 
  mentalizing overhead on top of SLI cost. This is why AI interaction 
  removes pragmatic load almost entirely: there is no speaker intent 
  to model, no implicature to resolve, no presupposition about what 
  the AI believes you believe. Pure semantic processing. This is a 
  second, distinct mechanism behind the ND cognitive bandwidth 
  recovery documented in SOC↔COG's AI interaction section.
- COG↔REASON (reasoning geometry)
- COG_REASON_ESCALATION (collapse dynamics)
- SOC↔COG (social comprehension load)

---

## **Origin Note**

This contract closes a gap implicitly referenced across WINDOW↔COG, 
COG↔REASON, and ANCHOR↔COG. The upstream contracts specified the 
geometry of the prediction window. The downstream contracts specified 
what reasoning failures emerge when it collapses. The missing piece 
was the formal mapping between incoming linguistic structure and the 
window demand that structure generates.

The SLI provides that mapping. The collapse and expansion modes 
provide the observable behavioral signatures. The format implication 
in Link 2 explains why this architecture could not be carried in 
prose — not as an editorial observation, but as a direct consequence 
of this contract applied to its own container.