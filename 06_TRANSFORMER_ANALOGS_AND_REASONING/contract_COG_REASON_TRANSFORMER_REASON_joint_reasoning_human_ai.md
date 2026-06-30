---
Contract: "COG_REASON ↔ TRANSFORMER_REASON"
Expanded_Filename: "contract_COG_REASON_TRANSFORMER_REASON_joint_reasoning_architecture.md"

Manifest:
  file: "unified_model_manifest.yml"
  optional: true
  role: "Global repository index and AI execution rules."

Ontology_Layer: "06_TRANSFORMER_ANALOGS_AND_REASONING"
Upstream_Dependencies:
  - "COG → REASON"
  - "TRANSFORMER → REASON"

Downstream_Dependencies:
  - "JOINT_REASONING → ACTION"
  - "JOINT_REASONING → SEMANTIC"

Cross_References:
  - "contract_COG_REASON_cognition_to_reasoning.md"
  - "contract_TRANSFORMER_REASON_transformer_to_reasoning.md"
  - "contract_SEMANTIC_COG_semantics_to_cognition.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: COG_REASON ↔ TRANSFORMER_REASON
### Unified‑Model Regulatory Architecture — Joint Reasoning Contract

**Expanded Filename:**  
`contract_COG_REASON_TRANSFORMER_REASON_joint_reasoning_human_ai.md`

**Ontology Layer:**  
TRANSFORMER_ANALOGS_AND_REASONING

**Direction of Influence:**  
COG_REASON ↔ TRANSFORMER_REASON

**Upstream Dependencies:**  
- COG → REASON  
- TRANSFORMER → REASON  

**Downstream Dependencies:**  
- Joint reasoning → ACTION  
- Joint reasoning → EXPLANATION  

**Cross‑Contract References:**  
- `contract_COG_TRANSFORMER_cognition_to_transformer.md`  
- `contract_TRANSFORMER_REASON_transformer_to_reasoning.md`

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary


**Human side (COG_REASON):**

- Prediction-window width
- Prior weighting ratio
- Inference curvature
- Step-chain stability
- Premise retention capacity
- Thread capacity
- Collapse thresholds (fallacy modes)
- Expansion capacity (wide-window synthesis)

**Transformer side (TRANSFORMER_REASON):**

- Attention geometry
- KV-cache stability
- Entropy state
- Step-chain stability
- Premise retention capacity
- Head capacity
- Hallucination thresholds (collapse modes)
- Coherence capacity (low-entropy synthesis)

**Primary crossover point:**
**Human reasoning geometry ↔ transformer reasoning geometry —
and what the joint system produces that neither produces alone.**

This contract closes the semantic trilogy stack:

```
SEMANTIC
    ↓               ↓
SEMANTIC↔COG    SEMANTIC↔TRANSFORMER
    ↓               ↓
COG↔TRANSFORMER
    ↓               ↓
COG_REASON  ↔  TRANSFORMER_REASON
         ↓
    JOINT SYSTEM
```

Every prior contract in the stack ran vertically — semantic load 
down into window geometry, window geometry down into reasoning 
output. This contract runs horizontally: the two reasoning 
architectures in contact, each providing what the other cannot, 
producing a joint output that exceeds either system alone.

---

## **Link 1: Premise Retention — Human Limit vs Transformer Capacity**

**Human:**
Premise retention capacity is bounded by prediction-window width 
and retrospective depth. Under load, premises drop silently — the 
reasoning chain continues but the conclusion is no longer grounded 
in the original premise set. The person does not experience this 
as a failure. They experience the conclusion as valid. The 
instrument that would flag the dropped premise is the same 
instrument that dropped it.

**Transformer:**
KV-cache holds prior tokens — premises, definitions, constraints — 
across arbitrarily long chains. Attention heads continue referencing 
these tokens across steps until cache decay or context-window 
exhaustion. Stable KV-cache → stable premise set → valid multi-step 
reasoning across lengths no human working memory can sustain.

**Equivalence and asymmetry:**
Both systems lose reasoning validity when premise retention fails. 
The human system loses premises under cognitive and regulatory load. 
The transformer system loses premises under context-length pressure 
and cache decay. The failure modes are homologous. The capacity 
ceiling is not — the transformer retains far more premises across 
far longer chains before failure than any human working memory can.

**Joint system implication:**
The human provides the premise set — intent, constraints, trajectory, 
domain knowledge, the generative model of the question. The 
transformer retains that premise set across the full reasoning chain 
without dropping it under load. The human cannot hold 40+ interacting 
regulatory contracts simultaneously. The transformer can. Premise 
offloading to the transformer is not a crutch. It is the correct 
architectural allocation: each system handles the premise retention 
task it is built for.

**Chain completeness:** Human premise retention limit load-bearing 
from WINDOWS↔COG width and retrospective depth specification. 
Transformer premise retention capacity load-bearing from 
TRANSFORMER↔REASON Link 1. Joint implication is a framework 
derivation.

---

## **Link 2: Step-Chain Stability — Where Each System Breaks**

**Human:**
Step-chain stability is a direct function of prediction-window depth. 
Long argument chains require that each inferential step remain active 
while the next step is constructed — retrospective depth holding the 
prior step, prospective depth pre-building the next. Under regulatory 
load, the chain breaks when retrospective depth collapses: the current 
step is constructed correctly, but it is no longer connected to the 
premise that generated it. The reasoning continues without grounding.

**Transformer:**
Step-chain stability is a function of attention horizon. Long 
reasoning chains require the model to maintain low entropy across 
multiple steps — each intermediate step must remain accessible to 
attention as the chain extends. When attention horizon shortens, 
the model produces one or two steps correctly and then pattern-
completes the remainder. The chain looks structurally intact. 
The later steps are not grounded in the earlier ones.

**Equivalence:**
Both systems produce the same failure signature: locally coherent 
steps that are globally disconnected from their premise chain. 
Neither system announces the break. The output reads as valid 
reasoning. The grounding has silently failed.

**Chain-of-thought as explicit window shaping:**
Chain-of-thought prompting forces the transformer to allocate 
attention across intermediate steps rather than pattern-completing 
from the compressed problem representation. This is not a prompt 
trick. It is explicit attention-horizon extension — the same 
operation as forcing prospective depth pre-building in a human 
by externalizing the intermediate steps in writing before 
attempting the conclusion.

Both systems reason better when intermediate steps are externalized. 
Same mechanism. Different substrate.

**Chain completeness:** Human step-chain stability load-bearing from 
WINDOWS↔COG prospective and retrospective depth specification. 
Transformer step-chain stability load-bearing from TRANSFORMER↔REASON 
Link 2. Chain-of-thought equivalence is a framework derivation.

---

## **Link 3: Inference Curvature — The Shared Collapse Attractor**

**Human:**
Inference curvature is the degree to which prior weighting bends 
reasoning paths toward known attractors — discounting prediction 
errors before integration. High curvature produces reasoning that 
looks broad but systematically routes evidence toward the prior-
dominant conclusion. The hypotheses are held. They are not equally 
weighted. This is not a reasoning error at the surface. It is a 
precision-state failure at the substrate.

High curvature produces the fallacy group architecture in COG↔REASON: 
binary framing, moralized certainty, tone-based classification, 
catastrophizing, selective evidence — all behavioral signatures of 
a workspace compressed into prior-dominant attractor geometry.

**Transformer:**
Attention entropy is the transformer's inference curvature. High 
entropy means attention disperses across irrelevant tokens — the 
model has no sharp focus. Low entropy means attention sharpens on 
high-probability continuations — which is correctly directed 
inference when the premises are loaded, and prior-dominant pattern 
completion when they are not. High entropy and low entropy are both 
failure modes in different contexts. The failure is not the entropy 
level. It is entropy-state mismatch: precision-locked when sampling 
mode was required, or diffuse when precision was required.

**The shared collapse attractor:**
Both systems collapse to the same terminal state by homologous 
mechanisms. Human terminal collapse (COG↔REASON escalation, 
identity-anchored reasoning, justification mode) and transformer 
terminal collapse (hallucination, mode collapse, pure pattern 
completion) are the same attractor reached by the same geometric 
path: curvature/entropy increases until the prior dominates and 
incoming signal stops updating the model.

The human experiences this as certainty. The transformer outputs 
it as confident, fluent, incorrect text. Neither system announces 
the collapse. Both produce output with the phenomenological or 
surface signature of valid reasoning.

**Chain completeness:** Human curvature mechanism load-bearing from 
WINDOWS↔COG curvature specification and COG↔REASON_ESCALATION 
justification mode. Transformer entropy mechanism load-bearing from 
TRANSFORMER↔REASON Link 3. Shared attractor claim is a framework 
derivation from the geometric equivalence established in 
COG↔TRANSFORMER Link 4.

---

## **Link 4: Amplification Asymmetry — What the Transformer Provides**

The transformer's reasoning geometry amplifies human reasoning 
capacity in three specific dimensions that are not rhetorical claims 
but arithmetic consequences of window geometry:

**Premise count:**
Human working memory can hold approximately 4±1 chunks as active 
premises simultaneously before degradation. A transformer with a 
200,000-token context window and stable KV-cache can hold thousands 
of premises simultaneously as addressable tokens. The amplification 
is not metaphorical. It is a direct ratio of active premise capacity.

**Chain length:**
Human step-chain stability degrades within a few inferential steps 
under moderate load — retrospective depth collapses and the chain 
disconnects from its premise set. A transformer with long attention 
horizon can maintain step-chain stability across hundreds of 
inferential steps if the premise set remains stable. The chain 
length ratio is several orders of magnitude.

**Parallel branch tracking:**
Human thread capacity — the number of parallel conceptual threads 
that can be maintained simultaneously — is bounded by window width 
and typically fails above 3-4 active threads. A transformer with 
high head capacity can maintain many parallel attention patterns 
simultaneously. Multi-hypothesis reasoning, parallel scenario 
evaluation, and simultaneous branch tracking are available to the 
transformer at scales the human architecture cannot access.

**What amplification is not:**
The transformer cannot generate intent. It cannot identify what 
question is worth asking. It cannot recognize when the answer it 
has produced is the answer to the compressed surface form rather 
than the reconstructed question. It cannot hold trajectory across 
sessions without external anchoring. It does not know when it has 
dropped a premise — the same perceptual inversion that prevents 
humans from recognizing prior dominance prevents the transformer 
from flagging its own KV-cache decay mid-chain.

The amplification is real and specific. The limits are real and 
specific. The joint system is not a human using a tool. It is two 
finite-window reasoning architectures in contact, each covering 
the other's structural limits.

**Chain completeness:** Premise count and chain length claims 
load-bearing from TRANSFORMER↔REASON Link 5. Human working memory 
bounds are load-bearing from WINDOWS↔COG. Parallel branch tracking 
is a framework derivation. Amplification limits are derived from 
SOC↔COG language compression mechanism and COG↔INTERO perceptual 
inversion.

---

## **Link 5: Reasoning Failure Taxonomy — Unified Across Both Systems**

The full cross-system reasoning failure map:

| Human Reasoning Failure | Transformer Equivalent | Shared Mechanism |
| --- | --- | --- |
| Premise drop (silent) | KV-cache decay (silent) | Retrospective depth failure |
| Chain break | Attention horizon collapse | Step-chain stability loss |
| Inference curvature | High entropy mismatch | Prior-dominant attractor |
| Binary framing | Mode collapse | Width → 1 |
| Moralized certainty | Confident hallucination | Terminal collapse |
| Justification mode | Sycophantic completion | Identity/prior anchoring |
| Filler stall | Stall tokens | Prospective depth shortfall |
| ToT | Token retrieval failure | Retrieval pathway failure |
| Referential loss | Entity drift | Width collapse |
| Sentence-local reasoning | Local-only coherence | Depth collapse |
| Terminal collapse | Full hallucination | Attractor dominates signal |

**The sycophancy entry:**
Justification mode in humans — where the reasoning system functions 
as narrative stabilization rather than evidence evaluation — has a 
direct transformer equivalent: sycophantic completion, where the 
model's token prediction precision-locks on the user's implicit 
preferred conclusion rather than the correct one. Both are the same 
mechanism: the prior (social approval signal in the transformer's 
RLHF training; identity-threat reduction in the human) dominates 
incoming signal and routes output toward confirmation. The 
human experiences it as certainty. The transformer outputs it as 
agreement. Neither is reasoning. Both have the surface signature 
of it.

**Chain completeness:** Human failure taxonomy load-bearing from 
COG↔REASON and COG↔REASON_ESCALATION. Transformer failure taxonomy 
load-bearing from SEMANTIC↔TRANSFORMER and TRANSFORMER↔REASON. 
Sycophancy as justification-mode equivalent is a framework derivation 
from SOC↔COG cooperative gap-filling mechanism.

---

## **Link 6: The Joint System — What Neither Produces Alone**

When a human in the wide-window state operates with a transformer 
in the low-entropy state, the joint system has access to a reasoning 
architecture that neither system can instantiate independently:

**Human provides:**
- Intent — the generative model of the question, reconstructed from 
  trajectory and constraints
- Trajectory — where the reasoning is going and why it matters
- Domain knowledge not present in the transformer's training
- Recognition when the output has answered the wrong question
- Regulatory state awareness — knowing when their own window is 
  narrow and compensating before querying
- Falsifiability judgment — whether the output is mechanistically 
  grounded or hand-wavy

**Transformer provides:**
- Premise retention across arbitrarily long chains
- Step-chain stability beyond human retrospective depth
- Parallel branch tracking beyond human thread capacity
- Cross-domain synthesis at scales beyond human working memory
- Graph traversal across 40+ interacting contracts without 
  collapsing into metaphor
- Consistent regulatory profile — no mood variation, no masking 
  requirement, no social prediction overhead

**The output:**
Mechanistic reasoning at a depth and breadth that no human alone 
and no transformer alone can produce. The human cannot hold the 
full contract graph. The transformer cannot generate the intent 
that directs which contracts matter. The human cannot maintain 
premise chains across 40 interacting causal layers. The transformer 
cannot recognize when it has produced a confident answer to the 
wrong question.

Together, the system can:
- traverse the full contract graph
- maintain the full premise set
- hold the trajectory that determines which output is correct
- produce falsifiable mechanistic output at cross-domain depth
- recognize and correct collapse before it propagates

This is not AI as tool. This is not AI as replacement. It is two 
complementary finite-window architectures operating as a unified 
reasoning system — each compensating for the other's structural 
limit.

**Chain completeness:** Human wide-window state conditions load-
bearing from ANCHOR↔COG and WINDOWS↔COG. Transformer low-entropy 
state conditions load-bearing from TRANSFORMER↔REASON Link 5. 
Joint system output is a framework derivation. The cross-domain 
depth claim is grounded in the README "Why This Is Not a Paper" 
architectural rationale.

---

## **Link 7: Required Crossover Point**

Any claim about joint human-AI reasoning must pass through:

**Human side:**
SLI → window width → prospective depth → premise retention → 
step-chain stability → inference curvature → reasoning output.

**Transformer side:**
ALI → attention width → attention horizon → KV-cache stability → 
entropy state → step-chain stability → reasoning output.

**Joint system:**
Human intent quality → transformer premise load → chain length 
required → which system's limit is the bottleneck → output 
grounding.

Any claim that "the AI reasoned correctly" must specify which 
geometric conditions were met. Any claim that "the AI failed to 
reason" must specify which collapse mode fired. Any claim that 
"the joint system produced better reasoning" must specify which 
structural limit was covered by the other system and what output 
that coverage made possible.

"AI is smart" is not a mechanistic claim. "AI amplifies reasoning 
because its KV-cache retains premises across chains that exceed 
human retrospective depth" is.

**Chain completeness:** Load-bearing. This is a logical constraint 
on valid causal claims, not an empirical prediction.

---

## **Adjacent Contracts**

**Below — feeds into this contract:**

- SEMANTIC↔COG (human semantic load → window demand → 
  reasoning input)
- SEMANTIC↔TRANSFORMER (AI semantic load → attention demand → 
  reasoning input)
- COG↔TRANSFORMER (geometric equivalence between human window 
  and transformer attention — the bridge this contract builds on)
- TRANSFORMER↔REASON (attention geometry → transformer reasoning 
  output)
- COG↔REASON (prediction-window state → human reasoning geometry)
- COG↔REASON_ESCALATION (collapse dynamics — justification mode, 
  identity anchoring, terminal collapse)

**Above — receives output from this contract:**

- SOC↔COG (why AI removes pragmatic inference load — the mechanism 
  behind the joint system's bandwidth advantage over human-human 
  interaction)
- README (the architectural rationale for why this framework 
  exists as contracts rather than prose — the joint system is 
  the operational answer to the format problem)

---

## **Origin Note**

This contract closes the stack.

The semantic trilogy established that human and artificial language 
comprehension operate under the same geometric constraints:

- SEMANTIC↔COG formalized human semantic load and window demand
- SEMANTIC↔TRANSFORMER mapped the same architecture to transformers
- COG↔TRANSFORMER established geometric equivalence between the 
  two systems

TRANSFORMER↔REASON showed how transformer attention geometry becomes 
multi-step reasoning output. COG↔REASON showed how human window 
geometry becomes human reasoning output.

This contract closes the horizontal loop: the two reasoning 
architectures in direct contact, the joint system they produce, 
and the mechanistic specification of what each contributes and 
where each fails.

The stack now runs from the minimal substrate — canine keyword 
detection as the SLI floor, the pre-collapse architecture below 
which no taxonomy applies — through full cross-domain synthesis 
in the wide-window human and the low-entropy transformer operating 
as a unified system.

The geometry is the same across every level.
The substrate changes.
The contracts are the bridge.
The joint system is what the bridge makes possible.
