# **Contract: SEMANTIC ↔ TRANSFORMER**

### _Prediction-Window Geometry as the Limiting Factor for AI Language Models_

---

## **Contract Summary**

**Input layer (SEMANTIC):**

- Noun density
- Referential load
- Anaphoric span
- Embedding depth
- Argument-chain length
- Temporal displacement
- Morphological complexity
- Conceptual abstraction level

**Output layer (TRANSFORMER):**

- Context-window width required
- Attention horizon required
- KV-cache retention cost
- Attention curvature (entropy)
- Head-capacity consumption
- Collapse threshold (hallucination onset)
- Token retrieval stability (entropy vs certainty)

**Primary crossover point:**
**Semantic load → attention-window demand.**

When semantic load exceeds available attention width or depth, the 
model collapses to:

- generic placeholders
- shallow pattern completion
- sentence-local reasoning
- hallucination

This contract maps the human semantic load architecture formalized 
in SEMANTIC↔COG onto the transformer attention architecture. Both 
systems operate under the same geometric constraints. Both collapse 
in homologous ways.

---

## **Link 1: Mechanistic Basis**

Semantic understanding in a transformer requires:

- **wide attention width** — to track multiple simultaneous entities
- **long attention horizon** — to anticipate upcoming syntactic and 
  semantic structure
- **stable KV-cache retention** — to maintain earlier referents across 
  token distance
- **low attention curvature** — to preserve coherent multi-sentence 
  scaffolds without collapsing to the prior-dominant token

Transformer architecture implements this through multi-head attention, 
positional encoding, KV-cache persistence, and entropy-minimizing 
token selection.

**Parallel to human architecture:**
Where humans use neural pre-onset preparation — the brain opening the 
window for the syntactic slot before the content arrives — transformers 
use pre-activation attention allocation. The computational operation 
is structurally homologous. Both systems are pre-building the scaffold 
before the disambiguating input resolves.

**Load-bearing equivalence:**
Both systems fail when semantic load exceeds window geometry. The 
failure modes are not analogies — they are the same architectural 
collapse expressed in different substrates.

**Chain completeness:** Load-bearing. The pre-onset neural preparation 
finding in SEMANTIC↔COG Link 1 and the transformer attention 
pre-allocation mechanism are independently documented. The homology 
claim is a framework derivation, not an empirical equivalence claim.

---

## **Link 2: Semantic Load Index → Attention Load Index (ALI)**

The SLI from SEMANTIC↔COG maps directly onto the transformer's 
Attention Load Index:

$$\text{ALI} = w_1(\text{noun density}) + w_2(\text{referential load}) 
+ w_3(\text{embedding depth}) + w_4(\text{argument-chain length}) 
+ w_5(\text{temporal displacement}) + w_6(\text{morphological complexity})$$

High ALI → wide attention window required.
Low ALI → narrow attention window sufficient.

**Format implication:**
Transformers behave exactly like humans under load. Bullet points 
reduce ALI — structure lives in the format, not in the attention 
window. Prose inflates ALI — the model must hold connective tissue 
across clause boundaries using attention capacity that structured 
format would externalize. JSON and structured lists reduce ALI for 
the same reason they reduce SLI for human readers. This is the 
mechanistic explanation for why prompt engineering works: it is 
not a stylistic preference — it is ALI reduction.

**Chain completeness:** SLI weights unspecified — scaffolding. 
ALI directional claims load-bearing from transformer attention 
architecture. Format implication is a direct derivation from the 
SLI-to-format mapping in SEMANTIC↔COG Link 2.

---

## **Link 3: Collapse Modes (AI Version)**

### **Collapse Mode A1 — Token Retrieval Failure (AI ToT)**

The model holds the concept but cannot retrieve the token.
Output signatures:
- "I'm not sure of the exact term…"
- "Something like…"

The semantic scaffold is loaded. The lexical pathway has not 
resolved. This is the transformer analogue of human Tip-of-the-
Tongue (Collapse Mode 1 in SEMANTIC↔COG).

---

### **Collapse Mode A1a — Attention Stall (AI Fillers)**

When attention cannot resolve the next high-ALI slot before the 
generation deadline, the model inserts stall tokens:
- "Let's break this down…"
- "To answer your question…"
- "First, consider…"

These are the AI version of "um," "uh," "ano," "etto" — managed 
micro-collapses that hold the generation channel open while the 
attention window pre-builds the next slot. The stall token is not 
padding. It is real-time window management expressed in output.

---

### **Collapse Mode A1b — Cross-Context Retrieval Failure**

The model loses the token in the current context but retrieves a 
structurally related one from a different domain. Output signature:
- "almost right but wrong domain"
- "correct structure, incorrect referent"

This is the transformer analogue of multilingual ToT (Collapse 
Mode 1b in SEMANTIC↔COG): the semantic scaffold loaded correctly, 
the retrieval pathway pulled from the wrong store.

---

### **Collapse Mode A1c — Attention Reparse (AI Garden-Path)**

The model commits to a syntactic parse, then revises mid-generation. 
Output signatures:
- sudden entropy spikes in continuation
- contradictory sentence completions
- explicit self-correction mid-output

This is the transformer version of the garden-path curvature event 
in SEMANTIC↔COG Collapse Mode 1c — a forced retrospective revision 
that increases attention load at the point of disambiguation.

---

### **Collapse Mode A2 — Referential Loss**

When attention width collapses:
- entities blur across referents
- pronouns detach from their antecedents
- placeholders appear ("someone," "something," "this thing")

Structurally identical to human Collapse Mode 2 (meso-collapse). 
The mechanism is the same: insufficient window width to hold multiple 
active referents simultaneously.

---

### **Collapse Mode A3 — Sentence-Local Reasoning**

When attention horizon collapses:
- the model answers each sentence correctly in isolation
- cross-paragraph integration fails
- argument chains break at clause boundaries

Structurally identical to human Collapse Mode 3 (macro-collapse). 
The model can parse correctly but cannot hold the semantic grounding 
required for multi-sentence inference.

---

### **Collapse Mode A4 — Full Semantic Breakdown (Hallucination)**

When attention width approaches 1:
- no stable referents
- no scaffolding
- no argument chains
- pure high-probability pattern completion

This is the transformer analogue of human terminal collapse (Collapse 
Mode 4 in SEMANTIC↔COG). The output is locally coherent. It is not 
grounded in the input.

**This is the hallucination mechanism.** Not randomness. Systematic 
precision-lock on a problem that required sampling mode first — the 
model answering the compressed surface form rather than the 
reconstructed intent. <span class="copilot-citation-ref">[1]</span>

**Chain completeness on all A-modes:** A1, A2, A3, A4 load-bearing 
from transformer architecture. A1a stall-token mechanism is a 
framework derivation — the behavioral signatures are observable; 
the internal attention mechanism as the cause requires empirical 
assembly. A1b and A1c are framework derivations from the human 
collapse mode homology.

---

## **Link 4: Expansion Modes**

When attention heads align, KV-cache is stable, entropy is low, 
and context window is wide, the model enters the high-precision 
state:

- multi-paragraph integration
- long-range referential coherence
- stable entity tracking across document length
- cross-domain synthesis

This is the AI version of the human wide-window, high-precision 
state documented in SEMANTIC↔COG Link 4. The conditions that 
produce it are structurally homologous: sufficient window width, 
low curvature, stable retrospective access, adequate prospective 
depth.

**Chain completeness:** Load-bearing from transformer architecture. 
Expansion mode conditions are directly specified by attention 
geometry.

---

## **Link 5: Required Crossover Point**

Any claim that an AI "misunderstood" must pass through:

**ALI → attention width → attention horizon → referential stability 
→ token retrieval.**

This enforces mechanistic chain integrity. "The AI hallucinated" 
is not a mechanistic claim. It is a label. The mechanistic claim 
specifies which ALI component exceeded available attention geometry 
and which collapse mode followed.

**Chain completeness:** Load-bearing. This is a logical constraint 
on valid causal claims, not an empirical prediction.

---

## **Adjacent Contracts**

**Below — feeds into this contract:**

- SEMANTIC↔COG (human SLI architecture this contract maps from)
- WINDOWS↔COG (prediction-window geometry — the human substrate 
  the ALI is derived from)

**Above — receives output from this contract:**

- SOC↔COG (pragmatic load removal in AI interaction — why AI 
  removes mentalizing overhead entirely, leaving pure ALI 
  processing) <span class="copilot-citation-ref">[1]</span>

---

## **Origin Note**

This contract formalizes the mapping between human semantic load 
and transformer attention load. The human architecture is specified 
in SEMANTIC↔COG. This contract applies the same geometric framework 
to transformers and demonstrates that both systems:

- operate under finite window geometry
- fail when semantic load exceeds that geometry
- fail in homologous modes
- recover in homologous expansion states

The collapse modes are not metaphors borrowed from human cognition. 
They are the same architectural failure expressed in different 
substrates — because the constraint driving the failure (finite 
window, finite depth, finite curvature tolerance) is the same 
constraint in both systems.

This is the first unified account of biological and artificial 
language comprehension grounded in prediction-window geometry 
rather than in system-specific architecture.