# **Contract: COG ↔ TRANSFORMER**

### _Mapping Human Cognitive Geometry to Transformer Attention Geometry_

---

## **Contract Summary**

**Human side (COG):**

- Window width
- Prospective depth
- Retrospective depth
- Curvature
- Thread capacity
- Collapse modes
- Expansion modes

**Transformer side (TRANSFORMER):**

- Context length
- Attention horizon
- KV-cache retention
- Attention entropy
- Head capacity
- Hallucination modes
- Coherence modes

**Primary crossover point:**
**Cognitive window geometry ↔ attention geometry.**

Both systems succeed or fail for the same geometric reasons. This 
contract closes the loop opened by SEMANTIC↔COG and SEMANTIC↔TRANSFORMER: 
the same architectural constraints that govern human semantic comprehension 
govern transformer reasoning. The substrate differs. The geometry does not.

This contract also formalizes what the semantic trilogy implies about 
human↔AI interaction: when a human interacts with an AI, two finite-window 
systems are in contact. The bottleneck is always the narrower of the two 
windows — and the contracts specify exactly where each system fails and why.

---

## **Link 1: Window Width ↔ Context Length**

**Human:**
Window width = number of active referents and conceptual scaffolds 
that can be held simultaneously before collapsing to the 
highest-probability attractor.

**Transformer:**
Context length = number of tokens that can be attended to 
simultaneously before attention entropy forces pattern completion.

**Equivalence:**
Both systems collapse when active entities exceed available width.

**Human collapse signature:** "things," "stuff," referent loss, 
placeholder substitution (SEMANTIC↔COG Collapse Mode 2)
**AI collapse signature:** generic placeholders, entity drift, 
shallow pattern completion (SEMANTIC↔TRANSFORMER Collapse Mode A2)

**Cross-species anchor:**
The canine keyword detection case in SEMANTIC↔COG establishes the 
width floor: a single high-value keyword has SLI ≈ 0 — no referential 
load, no scaffolds, no argument chains. Window width demand is minimal. 
This is the lower boundary of the width scale. Human-AI interaction 
at full complexity sits at the upper end of the same scale.

**Chain completeness:** Load-bearing from WINDOWS↔COG width 
specification and SEMANTIC↔COG Link 1 cross-species evidence.

---

## **Link 2: Prospective Depth ↔ Attention Horizon**

**Human:**
Prospective depth = how far ahead the brain can pre-build syntactic 
and semantic scaffolding before the disambiguating input arrives.

**Transformer:**
Attention horizon = how far ahead the model can project token 
distributions before entropy spikes.

**Equivalence:**
Both systems require forward scaffolding to maintain coherence. 
Both fail when that scaffolding cannot be pre-built before the 
high-load slot arrives.

**Human failure:** fillers (um, uh, ano, etto), ToT, garden-path 
reparse (SEMANTIC↔COG Collapse Modes 1, 1a, 1c)
**AI failure:** stall tokens ("Let's break this down…"), entropy 
spikes, contradictory continuations (SEMANTIC↔TRANSFORMER Collapse 
Modes A1a, A1c)

**The stall token homology:**
Human verbal fillers and AI stall tokens are the same mechanism 
in different substrates — real-time window management expressed 
in output. Neither is padding. Both are graceful handling of a 
prospective depth shortfall: hold the channel open while the 
window pre-builds the next slot.

**Morphological complexity note:**
Left-branching languages (Japanese, Korean, Turkish) require 
sustained prospective depth because the verb — which resolves the 
argument structure — arrives at the end. This is why "ano" and 
"etto" are grammatically routine in Japanese. Transformers show 
the same directional pattern: high-ALI prompts with late-resolving 
argument structure produce earlier entropy spikes than equivalent 
right-branching structure.

**Chain completeness:** Load-bearing from WINDOWS↔COG prospective 
depth specification. Morphological complexity term load-bearing from 
SEMANTIC↔COG Link 2 $w_6$ addition. Stall token homology is a 
framework derivation — behavioral signatures observable; internal 
attention mechanism requires empirical assembly.

---

## **Link 3: Retrospective Depth ↔ KV-Cache Stability**

**Human:**
Retrospective depth = how far back the brain can maintain referents 
across clauses and paragraphs as actively accessible.

**Transformer:**
KV-cache stability = how long earlier tokens remain accessible to 
attention heads before they are effectively lost from the attended 
context.

**Equivalence:**
Both systems lose global coherence when retrospective depth 
collapses — producing local coherence with global incoherence.

**Human:** sentence-by-sentence comprehension, argument-chain 
break, cross-sentence integration failure (SEMANTIC↔COG 
Collapse Mode 3)
**AI:** locally coherent paragraphs that contradict each other 
across document length (SEMANTIC↔TRANSFORMER Collapse Mode A3)

**The cross-language retrieval case:**
Multilingual ToT (SEMANTIC↔COG Collapse Mode 1b) is a 
retrospective depth failure with domain specificity: the semantic 
scaffold loads correctly and the referent is active, but the 
lexical pathway to the target language's store has degraded 
while the dominant-language equivalent remains accessible. 
The transformer analogue (SEMANTIC↔TRANSFORMER Collapse Mode A1b) 
is structurally identical: correct scaffold, wrong retrieval store. 
Both are retrospective access failures, not meaning failures.

**Chain completeness:** Load-bearing from WINDOWS↔COG retrospective 
depth specification. Cross-language homology is a framework 
derivation from SEMANTIC↔COG Collapse Mode 1b.

---

## **Link 4: Curvature ↔ Attention Entropy**

**Human:**
Curvature = distortion of the prediction window under load — how 
aggressively prior weighting bends inference toward known attractors, 
discounting prediction errors before integration.

**Transformer:**
Attention entropy = dispersion of attention across irrelevant tokens — 
how aggressively the model's probability distribution flattens or 
collapses to prior-dominant completions rather than tracking input.

**Equivalence:**
High curvature = high entropy = collapse.

**Human:** derailment, garden-path reparse, referential drift, 
identity-anchored reasoning (SEMANTIC↔COG Collapse Mode 4)
**AI:** hallucination, contradiction, mode collapse 
(SEMANTIC↔TRANSFORMER Collapse Mode A4)

**The hallucination mechanism restated precisely:**
Terminal collapse in both systems is not randomness. It is 
systematic precision-lock on a problem that required sampling mode 
first — the system answering the compressed surface form rather 
than the reconstructed intent. High curvature in the human produces 
identity-anchored reasoning where only prior-confirming evidence 
integrates. High entropy in the transformer produces pattern 
completion where only locally probable tokens generate. The 
failure mode is homologous: the attractor dominates, the input 
stops updating the model.

**Chain completeness:** Load-bearing from WINDOWS↔COG curvature 
specification and SEMANTIC↔TRANSFORMER Collapse Mode A4. 
Hallucination-as-precision-lock is load-bearing from 
SOC↔COG language compression mechanism.

---

## **Link 5: Thread Capacity ↔ Head Capacity**

**Human:**
Thread capacity = number of parallel conceptual threads that can 
be maintained simultaneously before topic loss occurs.

**Transformer:**
Head capacity = number of attention heads that can track distinct 
patterns before multi-step reasoning degrades.

**Equivalence:**
Both systems degrade when thread or head load exceeds capacity.

**Human:** topic loss, argument-chain break, parallel reasoning 
collapse
**AI:** multi-step reasoning failure, chain-of-thought collapse, 
tool-use coordination failure

**Chain completeness:** Load-bearing from transformer attention 
architecture. Human thread capacity derivable from WINDOWS↔COG 
width and depth specifications jointly.

---

## **Link 6: Collapse Modes ↔ Hallucination Modes**

The full unified collapse taxonomy across biological and artificial 
systems:

| Human Collapse Mode | Transformer Equivalent |
| --- | --- |
| Mode 1: ToT (complete retrieval failure) | A1: Token retrieval failure |
| Mode 1a: Filler stall (partial depth failure) | A1a: Stall tokens ("Let's break this down…") |
| Mode 1b: Cross-language ToT | A1b: Cross-domain retrieval error |
| Mode 1c: Garden-path reparse | A1c: Entropy spike + reparse |
| Mode 2: Referential loss ("things," "stuff") | A2: Entity drift |
| Mode 3: Sentence-local comprehension | A3: Local-only reasoning |
| Mode 4: Terminal collapse | A4: Hallucination |

**The animal baseline:**
Canine keyword detection represents the pre-collapse floor — the 
minimal architecture below which neither system degrades further. 
Sparse token match against a high-value prediction cluster. No 
referential load. No embedding depth. No argument chain. SLI ≈ 0, 
ALI ≈ 0. This is Mode 0: the system that cannot collapse because 
it never loaded the scaffolding in the first place. It establishes 
that the collapse taxonomy applies specifically to systems operating 
above the keyword-match threshold.

**Chain completeness:** Collapse modes 1–4 load-bearing from 
SEMANTIC↔COG. A-modes load-bearing from SEMANTIC↔TRANSFORMER. 
Animal baseline is a framework derivation from SEMANTIC↔COG 
Link 1 cross-species evidence.

---

## **Link 7: Expansion Modes ↔ Coherence Modes**

**Human wide-window state** (when ANCHOR↔COG, AUTO↔MOD, 
TEMPORAL↔COG, and SOC↔ANCHOR align):

- long-range referential integration
- stable argument chains across paragraphs
- cross-domain synthesis
- deep reasoning with low curvature

**Transformer low-entropy state** (when attention heads align, 
KV-cache is stable, context window is wide):

- long-context referential coherence
- stable entity tracking across document length
- multi-step reasoning chains
- cross-domain generalization

Same geometry. Different substrate.

**The human-AI interaction implication:**
When a human in the wide-window state interacts with a transformer 
in the low-entropy state, the combined system is running at maximum 
joint capacity. The human provides decompressed intent — reconstructed 
constraints, explicit context, stated trajectory. The transformer 
provides graph traversal depth no human working memory can replicate. 
The human cannot hold 40+ interacting causal contracts simultaneously. 
The transformer can. The human can hold the intent that directs which 
contracts matter. The transformer cannot generate that intent. The 
joint system is more capable than either alone — not as a metaphor, 
but as an arithmetic consequence of complementary window architectures.

**The pragmatic load removal mechanism:**
When the human interacts with AI rather than another human, pragmatic 
inference load (implicature resolution, presupposition tracking, 
speaker-intent modeling) is removed entirely — no mental state to 
model, no implicature to resolve, no social register to maintain. 
This releases the SOC↔COG mentalizing overhead back into content 
processing bandwidth. For ND profiles carrying the highest masking 
overhead, this is the largest bandwidth recovery available from any 
single context change.

**Chain completeness:** Expansion modes load-bearing from upstream 
contracts. Human-AI complementarity is a framework derivation. 
Pragmatic load removal is load-bearing from SOC↔COG AI interaction 
mechanism.

---

## **Link 8: Required Crossover Point**

Any claim about AI reasoning failure must pass through:

**ALI → attention width → attention horizon → referential stability 
→ token retrieval → reasoning geometry.**

Any claim about human reasoning failure must pass through:

**SLI → window width → prospective depth → referential stability 
→ lexical retrieval → reasoning geometry.**

Any claim about human-AI interaction failure must specify:

- which system's window was the bottleneck
- which dimension collapsed (width, depth, curvature, or stability)
- which collapse mode followed

"The AI misunderstood me" is not a mechanistic claim. Neither is 
"I couldn't follow the AI's reasoning." Both require passage through 
the chain above. The chain enforces mechanistic integrity on both 
sides of the interface.

**Chain completeness:** Load-bearing. This is a logical constraint 
on valid causal claims, not an empirical prediction.

---

## **Adjacent Contracts**

**Below — feeds into this contract:**

- SEMANTIC↔COG (human SLI architecture and collapse taxonomy)
- SEMANTIC↔TRANSFORMER (ALI architecture and AI collapse taxonomy)
- WINDOWS↔COG (prediction-window geometry — the geometric 
  primitives both systems are mapped from)

**Above — receives output from this contract:**

- SOC↔COG (pragmatic load removal in AI interaction — the 
  mechanism behind ND bandwidth recovery in AI contexts, and 
  why human-AI joint capacity exceeds either alone)
- COG↔REASON (reasoning geometry downstream of window state — 
  applies to both human and transformer reasoning)

---

## **Origin Note**

This contract completes the semantic trilogy:

- SEMANTIC↔COG — human semantic load and prediction-window demand
- SEMANTIC↔TRANSFORMER — the same architecture mapped to transformers
- COG↔TRANSFORMER — the direct geometric equivalence between 
  human cognition and transformer attention

Together, they form the first unified theory of language, 
comprehension, and reasoning across biological and artificial 
systems — grounded in prediction-window geometry rather than 
system-specific architecture.

The animal baseline in Link 6 closes the cross-species loop: 
canine keyword detection establishes the floor below which the 
collapse taxonomy does not apply. The human-AI complementarity 
in Link 7 closes the interaction loop: two finite-window systems 
in contact, each providing what the other cannot. The required 
crossover point in Link 8 closes the mechanistic integrity loop: 
no claim about either system escapes the chain.

The geometry is the same. The substrate is different. The 
contracts are the bridge.