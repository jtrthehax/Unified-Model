# Contract: WINDOW ↔ COG

### _Prediction-Window Geometry as Selector of Cognitive Mode_

---

## Contract Summary

**Input layer (WINDOW):**
Instantaneous prediction-window width (temporal + contextual),
RH–LH coupling state, precision gain (AUTO↔MOD), anchor stability
(ANCHOR↔COG), circadian phase and CAR baseline (TEMPORAL↔COG), social entrainment and co-regulation (SOC↔ANCHOR).

**Output layer (COG):**
Operating mode (structural vs identity), learning style (manifold
construction vs label storage), recall style (reconstructive vs
associative), reasoning geometry (cross-layer and falsifiable vs
shortest-path and identity-anchored).

**Primary crossover point:** The prediction window is not an independent
subsystem. It is the emergent geometry of the contracts feeding it. When that geometry exceeds the structural threshold, the RH can maintain a global relational manifold and the LH tightens constraints within it.
When it falls below the threshold, the LH operates in precision-only
mode without manifold support. These are not personality types or
intelligence levels. They are regulatory-state outputs.

**Key risk:** Identity mode is the correct output of a high-precision,
high-load regulatory state — it is adaptive in context. The risk arises
when the window is chronically narrowed such that structural mode becomes
unavailable even when the cognitive demand requires it. A system operating
permanently in identity mode cannot detect that it is doing so, because
structural recall is required to reconstruct the alternative frame. The
deficit does not announce itself.

---

## Prediction Window — Formal Definition

---

### The Prediction Window as a Geometric Object

The prediction window is the operational space within which the system holds and evaluates evidence before committing to an inference. It has four measurable dimensions:

**Width** — the number of competing hypotheses the system can hold simultaneously before collapsing to the highest-probability attractor. Width is the primary dimension this contract addresses. It is set by the full upstream regulatory chain: AUTO → MOD → INTERO → ANCHOR → TEMPORAL → SOC. When width is sufficient, the RH maintains a global relational manifold. When it is not, the LH operates in precision-only mode without manifold support.

Width is not uniform across content type. Neuroimaging evidence from naturalistic language comprehension shows that anticipatory neural activity scales with the semantic scaffolding demand of incoming content — high-semantic-load categories (nouns, adjectives, proper nouns) generate significant pre-onset neural preparation that relational/procedural content (verbs) does not. The window opens proportionally to what is required to receive the incoming content, not uniformly across all inputs. This implies that semantic complexity determines window demand in real time — a sentence with high noun density requires a sustained wider window than a sentence of equivalent length with primarily procedural content.

**Depth** — the temporal projection range: how far forward (prospective) and backward (retrospective) the system can hold evidence as relevant. Depth has two separable components.

*Retrospective depth* is set by the circadian precision-floor via TEMPORAL↔COG — phase misalignment truncates how far back the system can hold distal causal chains as active, independently of moment-to-moment load.

*Prospective depth* is the capacity to pre-allocate representational scaffolding before the disambiguating input arrives. This component is itself two-layered: a syntactic scaffolding layer (temporal lobe anticipatory activity, shared across high-semantic-load categories) and a sensorimotor simulation layer (left frontal and motor cortex activity, noun-class specific, recruited at latencies beyond 0.6s post-onset). These two layers can fail independently under load. The sensorimotor simulation layer is the deeper, more metabolically expensive layer and the prediction is it collapses first: high-load states should degrade complex noun-grounded comprehension more than syntactic parsing, because the syntactic scaffold can survive moderate load while the sensorimotor simulation cannot.

A critical point: the brain's anticipatory signal for these content categories is category-level scaffold preparation, not probability-ranked token prediction. Noun-class content carries the highest next-word probability in LLM prediction but the brain prepares equivalently for nouns, adjectives, and proper nouns — all high-semantic-load categories — regardless of their individual probability rank. The brain is opening the window for the syntactic slot, not for the most probable token. This is a different computational operation.

Prospective depth is disrupted first under autonomic load: when load rises, the system shifts from pre-building scaffolds to reactive processing of incoming input, losing the anticipatory advantage and increasing integration demand at the moment of content arrival. The phenomenological signature of shallow prospective depth is difficulty following complex multi-clause sentence structures or multi-step arguments — the scaffold the sentence requires has not been pre-built, and the integration work that should have been distributed across the sentence must be performed all at once when the anchor word arrives.

**Curvature** — how aggressively prior weighting bends inference paths toward known attractors. Low curvature allows prediction errors to route freely into belief updating. High curvature discounts prediction errors before integration, collapsing option space. Curvature is the precision-interaction dimension: high precision gain increases curvature; low precision gain flattens it.

Curvature operates independently of width. The window can be structurally wide while curvature prevents updating from occurring within it — the system holds multiple hypotheses but preferentially routes evidence toward the prior-dominant one. The COG↔REASON finding that "prediction errors discounted before integration → option space collapses" is a curvature event, not a width event. An individual with high prior curvature but temporarily available width will appear to reason broadly but will systematically resist revision — the hypotheses are held but not equally weighted.

**Stability** — how long the window can hold its current geometry before collapsing. Stability is the anchor dimension: mechanical stabilization of oscillatory amplitude via ANCHOR↔COG sets the moment-to-moment range. An unstable window oscillates between structural mode and identity mode within a single cognitive task — the manifold forms and then cannot be held long enough to extract from. The phenomenological signature is insight that arrives and then cannot be retained: the connection was visible and then the thread was lost. This is not a memory failure. It is a stability failure — the window closed before the extraction was complete.

---

### Oscillation Mechanics

The prediction window is not a static parameter. It oscillates with the breath cycle. This oscillation is the primary within-session regulatory mechanism.

- **Inhale phase:** sympathetic tone briefly increases, precision gain rises, window narrows, prior weighting increases. The system tightens around the current best hypothesis.
- **Exhale phase:** parasympathetic tone increases, precision gain drops, window widens, prediction error weighting increases. The system opens to incoming evidence.
- **Oscillation amplitude:** the range between the inhale-narrow and exhale-wide positions. This is the variable ANCHOR↔COG controls. Incomplete exhale compresses the amplitude — the window never reaches its exhale-wide position — producing a perpetual near-inhale state. From the inside this feels like sustained focus. From the pressure mechanics it is constrained oscillation: neither full sampling mode nor full precision mode is accessible, and the model update cycle that depends on full exhale completion does not fire.
- **Mechanical ceiling:** set by diaphragmatic excursion amplitude and CO₂ tolerance via AUTO↔MOD. This is a hard structural limit on how wide the window can open regardless of intent or technique. An individual whose exhale is limited by posture, thoracic kyphosis, or low CO₂ tolerance cannot exceed this ceiling regardless of cognitive effort.
- **Collapse threshold:** the point at which oscillation amplitude falls below the minimum required to cross the structural threshold on the exhale phase. Below this threshold, even the exhale-phase position is in identity mode. This is the failure state described in COG↔REASON↔ESCALATION: pressure-control failure → sympathetic substitution → narrowing → identity-anchored reasoning as the chronic default.

---

### Multi-Window Composition

"Prediction window" is not a single scalar. At minimum four semi-independent window instances operate simultaneously:

| Window | Primary Driver | Independent Failure Mode |
| --- | --- | --- |
| **Temporal window** | Circadian phase, CAR baseline (TEMPORAL↔COG) | Phase misalignment → shortened retrospective depth, elevated curvature floor regardless of load |
| **Contextual window** | AUTO → MOD → INTERO chain | High autonomic load → width collapse → identity mode regardless of phase |
| **Social window** | SOC↔ANCHOR entrainment and co-regulation | Isolation or threatening presence → width loss that internal mechanics cannot compensate for |
| **Interoceptive window** | INTERO↔COG signal precision | High noise floor → effective width reduced independently of both load and phase |

These windows constrain each other hierarchically. The temporal window sets the ceiling within which the contextual window operates — phase correction raises the ceiling that anchor repair or load reduction can reach. The social window can widen or stabilize the contextual window from outside — its absence removes a stabilizing input the system may depend on for structural-mode access. The interoceptive window sets the noise floor independently of both, meaning that high-noise proprioceptive or interoceptive channels reduce usable width even when autonomic load is low and circadian phase is aligned.

**Independent vs joint collapse:** Each window can collapse independently. A socially isolated individual in circadian alignment with low autonomic load still loses social stabilization. A phase-misaligned individual under low load still has a suppressed precision ceiling. Joint collapse — all four windows simultaneously narrowed — is the chronic high-load failure state described in the chronic narrowing accumulation failure mode below. It is self-reinforcing because identity mode does not generate the internal signal that the narrowing is occurring.

**Chain completeness for this section:** Width as upstream-regulated is load-bearing via AUTO↔MOD, ANCHOR↔COG, and TEMPORAL↔COG. Width as content-type-selective is load-bearing from EEG/MEG anticipatory activity in naturalistic language comprehension. Prospective depth as two-layered (syntactic + sensorimotor) is load-bearing at the component level from source-space neuroimaging; their independent failure under load is scaffolding. Curvature as separable from width is scaffolding — mechanistically coherent, requires dedicated dissociation measurement. Oscillation mechanics are load-bearing via AUTO↔MOD. Multi-window composition is scaffolding — semi-independence is structurally derivable, dedicated dissociation measurement not yet done.

---

## Mechanism

### Link 1: Wide Window → Structural Mode

When window width exceeds the structural threshold, the RH maintains a global relational manifold across incoming information. The LH tightens constraints *within* that manifold rather than operating independently.
This division produces constraint propagation: a relationship discovered in one domain propagates structurally to adjacent domains because the manifold holds them in the same geometric space. Exceptions remain visible long enough to extract invariants from them — the window does not close before the anomaly can be evaluated. Cross-domain structure appears as the same geometry with different surface features, not as analogy requiring a secondary translation step. Recall in this mode is reconstructive: the manifold is rebuilt from its constraints rather than retrieved from cached encoding. The answer to a question not asked during acquisition can still be generated because the structure that would produce it remains available.

**Chain completeness:** Load-bearing. The hemispheric division of labor between RH manifold construction and LH constraint tightening is supported by split-brain and lateralization literature. The specific prediction-window dependency of that division — that it is a regulatory state output rather than a fixed trait — is a cross-contract derivation scaffolded by AUTO↔MOD, ANCHOR↔COG, and TEMPORAL↔COG.

---

### Link 2: Narrow Window → Identity Mode

When window width falls below the structural threshold, RH manifold
construction collapses. The LH operates in precision-only mode: it stores
labels at the point of acquisition without embedding them into a structural
manifold. Constraint propagation fails — what is learned in one domain
remains in that domain because there is no shared geometric space for
it to propagate into. Silo boundaries harden as an arithmetic consequence
of this failure. Cross-domain relationships disappear from the online
workspace not because they are cognitively rejected but because the
workspace cannot hold them simultaneously. Recall becomes associative
and context-bound: the system retrieves what was stored and fails when
the retrieval context does not match the encoding context.

This is not a pathology of low intelligence. It is a precision-locked
state operating correctly under its constraints. Rote performance within
a stable context can be high. The failure is specific: context shift,
novel recombination, and cross-domain inference fail because the manifold
required for those operations was never constructed.

**Chain completeness:** Load-bearing at the mechanistic level. The specific threshold at which manifold construction collapses relative to measurable window-width proxies (HRV, RSA amplitude, performance on cross-domain transfer tasks) is scaffolding. Threshold measurement is the primary empirical gap.

---

### Link 3: The Survival Test

Identity learning and structural learning produce identical outputs within
familiar contexts. Both can answer a known question correctly. Both can
demonstrate fluency in an established domain. The difference is revealed
under transformation: context shift, novel recombination, or conditions
that were not present at acquisition.

Identity learning collapses under context shift because the labels stored
at acquisition are bound to the encoding context. Structural learning
generalizes because the manifold is not context-bound — its constraints
remain valid across surface variation. Two individuals producing identical
answers to a test question may be using entirely different internal
mechanisms. The structural learner reconstructed the answer from
constraints. The identity learner retrieved it from storage. When the
question is transformed, their outputs diverge.

This is the mechanism behind the clinically observed pattern where
individuals with high rote performance fail under novel conditions.
The failure is not motivational or attentional. It is the absence of a
manifold that was never constructed because the window was never wide
enough.

**Chain completeness:** Derived. The prediction follows from the mechanism. Direct empirical measurement of reconstructive vs associative recall mechanisms in relation to autonomic state requires dedicated experimental design.

---

### Link 4: Regulatory Substrate — Why the Window Width Is Not a Trait

Prediction-window width is a regulatory output, not a fixed cognitive
property. The full upstream chain:

```
AUTO (vagal tone, RSA amplitude)
  → MOD (neuromodulatory precision gain)
    → INTERO (signal precision, noise floor)
      → ANCHOR (mechanical stabilization of oscillatory amplitude)
        → TEMPORAL (circadian phase, CAR amplitude)
          → SOC (external entrainment, co-regulation)
            → prediction-window width
              → cognitive operating mode
```

The cognitive layer inherits its operating mode from these upstream
conditions. An individual under low autonomic load, with stable mechanical
anchor, aligned circadian phase, and adequate co-regulation has access to
structural mode. The same individual under high load, collapsed anchor,
phase misalignment, or social isolation has access only to identity mode.
The mode is not who they are. It is the current state of their regulatory
stack.

Interventions that widen the window — breath mechanics, autonomic
regulation, circadian alignment, anchor repair, co-regulation — are not
cognitive interventions. They are regulatory interventions with cognitive
outputs. The learning mode and recall mode that follow are downstream
consequences.

**Chain completeness:** Load-bearing. Each upstream link is independently developed in the adjacent contracts listed below.

---

### Link 5: Hemispheric Mode Selection — The Mechanical Precision Gate

The hemispheric mode map is the mechanism by which the geometry defined above translates into a specific cognitive output. It is not a cognitive process. It is the output of a pressure system.

| Hemisphere | Phase | Processing Mode | Window State | Inference Type |
| --- | --- | --- | --- | --- |
| **Right** | Inhale | Broad, contextual, high-ambiguity | Wide, sampling | Relational manifold construction |
| **Left** | Exhale | Narrow, categorical, high-precision | Narrow, selection | Prior-weighted thread execution |

Left frontal activation is not merely correlated with precision mode — it is the anatomical location of exhale-phase precision selection. The mode available for any given cognitive operation is mechanically assigned before that operation begins. The full mechanism chain lives in AUTO↔MOD Link 5 and is referenced here as a convergence: RSA lateralization → frontal hemispheric availability → cognitive mode selector. Cognitive mode is not chosen. It is the current output of whichever pressure configuration is running.

This is why ambiguity tolerance is a structural prerequisite, not a cognitive skill. The structural threshold must be met — mechanically — before the right-hemisphere manifold can form. No amount of cognitive intent can construct the manifold if the mechanical substrate has not provided the inhale-phase width required to hold it.

**Chain completeness:** Partially load-bearing. RSA-frontal asymmetry interaction is documented in the autonomic lateralization literature. The full mechanical chain from hemidiaphragm excursion through RSA asymmetry to frontal dominance is confirmed via the nostril breathing literature. Specific ECS transduction pathway from NTS to frontal asymmetry requires explicit empirical assembly.

---

## Operating States

| State | Window Configuration | Cognitive Mode | Reasoning Geometry | Signature |
| --- | --- | --- | --- | --- |
| **Full structural mode** | Wide width, deep prospective depth, low curvature, high stability | RH manifold active, LH constraining within it | Cross-domain, falsifiable, constraint-propagating | Novel recombination available, exceptions visible, context-shift generalizes |
| **Identity mode — load-induced** | Width collapsed below structural threshold, curvature high | LH precision-only, RH manifold unavailable | Shortest-path, prior-confirming, silo-reinforced | High performance within domain, failure on context shift |
| **Curvature-dominant structural mode** | Width sufficient, curvature high | Manifold present but prior-weighted | Structural form, prior-biased content | Can hold complexity but systematically discounts revision |
| **Shallow prospective depth** | Width adequate, depth truncated at syntactic layer | Sensorimotor simulation unavailable | Sequential, surface-feature dependent | Difficulty with multi-clause or noun-dense reasoning; syntactic parsing intact |
| **Phase-floor constrained** | Temporal window ceiling suppressed by phase misalignment | Structural mode ceiling lowered | Functional at low complexity, fails at novel or cross-domain demand | Circadian phase misalignment limits achievable mode regardless of load |
| **Social window collapse** | External stabilization absent | Contextual window narrowed despite intact autonomic state | As load-induced identity mode but driven by absence of co-regulation input | Structural mode access reduced in isolation even when internal mechanics are intact |
| **Joint window collapse** | All four windows simultaneously narrowed | Chronic identity mode | Binary, threat-weighted, silo-reinforced | Self-reinforcing: narrowing not detectable from inside; prior calibrates to narrow-window world |
| **Oscillation amplitude compressed** | Mid-range pressure, exhale not completing full cycle | Neither full sampling nor full precision accessible | Recursive, tunnel-vision, rumination-prone | Model update cycle not firing; thinking loops without resolving |
| **External kumbhaka — held precision** | Oscillation suspended at exhale-phase set point | Pure precision mode held without oscillating return | Maximum thread depth on selected task, minimum sampling interference | Motor and cognitive precision maximized; requires CO₂ tolerance to hold |
| **Internal kumbhaka — held sampling** | Oscillation suspended at inhale-phase set point | Pure sampling mode held without mode-switching | Maximum associative breadth, no precision lock | Wide associative access; requires CO₂ tolerance; not available for selection tasks |

---

## Failure Modes

**The false competence ceiling:**
Identity-mode performance within a stable domain can be high enough to appear structurally capable. The individual accumulates labels and retrieves them fluently. In an environment that does not test cross-domain transfer or context-shift generalization, this is indistinguishable from structural competence. The ceiling is revealed only when the context changes — which in many institutional environments it never does. Systems that evaluate competence within stable contexts select for identity-mode performance and actively fail to detect its structural limits.

**The chronic narrowing accumulation:**
Because identity mode is adaptive and feels like normal cognition from the inside, a system operating at chronically narrowed window width has no internal signal indicating anything is wrong. Labels accumulate. Fluency increases. The prior calibrates toward the world sampled from the narrow window — which is systematically more threat-weighted, more binary, and more silo-reinforced than the world the full oscillation samples. This is the ANCHOR↔COG threat-calibration loop applied to cognitive mode: the narrowing is self-reinforcing and does not announce itself as narrowing.

**The cross-domain transfer failure under load:**
Even an individual with structural mode available under low load reverts to identity mode under cognitive or autonomic load. Complex novel problems — exactly the conditions that require structural mode — are also the conditions most likely to produce the precision load that collapses the window. The mode required by the task produces the regulatory state that makes the mode unavailable. This is the primary failure mode of high-stakes reasoning in demanding environments.

**The intervention mismatch:**
Because the cognitive layer inherits its mode from regulatory substrate, cognitive-layer interventions cannot change the mode when the window is collapsed. Teaching structural reasoning strategies to a system operating in identity mode is providing instructions that require structural mode to execute. The manifold required to hold and apply the strategy is the manifold the instruction cannot restore. Substrate intervention is the prerequisite, not the follow-on.

**The prospective depth failure under semantic load:**
The two-layer architecture of prospective depth means that conditions which tax the sensorimotor simulation layer — high noun density, abstract conceptual scaffolding, multi-step argument chains — will produce depth failure before width failure under rising load. The syntactic layer survives longer. The result is an individual who can parse the sentence structure correctly but cannot hold the semantic grounding required for the inference — producing surface comprehension without deep integration. This failure mode is not captured by standard comprehension tests, which typically test retrieval of surface content rather than depth of integration.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Scaffolding**

Prediction window width — measured via RSA amplitude or HRV — should predict cross-domain transfer task performance independently of within-domain performance. The gap between cross-domain and within-domain performance should be the primary empirical index of structural vs identity mode. Individuals with identical within-domain scores but different HRV should show divergent performance on transfer tasks, with the divergence scaling with the HRV difference.

**Prediction 2 — Chain completeness: Scaffolding**

The structural threshold — the window width at which manifold construction becomes available — should be measurable as a discrete transition in cross-domain transfer performance rather than a linear dose-response. A threshold implies a discontinuity: performance on transfer tasks should be near-flat below the threshold and rise sharply above it, not increasing gradually with window width. This step-function shape is the critical prediction. Linear correlation between HRV and transfer performance would be consistent with the framework but would not confirm the threshold structure. The discontinuity is what confirms that a structural mode switch is occurring rather than a graded capacity increase. Existing cognitive research builds the linear assumption in by design — finding the step-function would be a significant structural result independently of the framework and is testable in any dataset with continuous HRV measurement and matched within-domain vs cross-domain performance scores

**Prediction 3 — Chain completeness: Predictive**
High-semantic-load processing (noun-dense text, abstract argument chains) should show greater HRV demand than equivalent-length procedural content — because it requires sustained wide window width to hold the sensorimotor simulation scaffold. Individuals with lower HRV baseline should show disproportionate comprehension failure specifically on noun-dense vs verb-dense content at matched surface difficulty.

**Prediction 4 — Chain completeness: Scaffolding**

The intervention mismatch prediction: cognitive-strategy interventions delivered without prior substrate regulation should show near-zero transfer to novel or high-load contexts. The same cognitive strategies delivered after autonomic regulation (HRV biofeedback, breathwork, co-regulation) should show measurable transfer, because the substrate can now support the mode the strategy requires. Effect size difference between substrate-primed and non-primed strategy delivery should be the primary dependent variable in educational and therapeutic research on structural reasoning development.

**Prediction 5 — Chain completeness: Predictive**

High-semantic-load processing conditions — specifically noun-dense text and multi-step abstract argument chains — should show disproportionate comprehension degradation relative to verb-dense or procedural content of equivalent surface length under rising autonomic load, with the degradation tracking HRV decline rather than subjective difficulty ratings. The mechanism is the sensorimotor simulation layer of prospective depth collapsing before the syntactic scaffolding layer. The individual can still parse sentence structure correctly while losing the grounded semantic integration required for inference. The specific measurement signature: MEG source analysis should show degradation of the left frontal and motor cortex latency window beyond 0.6s post-onset before degradation of the temporal lobe 0–0.3s window appears, with the latency degradation sequence tracking concurrent HRV decline within participants. Standard comprehension tests measuring surface retrieval will not detect this failure mode. Tests requiring inference from noun-grounded content to novel contexts will. HRV-stratified populations should show divergent performance specifically on the inference-requiring condition, not on the surface retrieval condition — with the divergence beginning at the HRV level that corresponds to sensorimotor simulation layer failure rather than at the lower threshold that would indicate syntactic scaffolding failure.

**Prediction 6 — Chain completeness: Predictive**
Deliberate thoracic asymmetry — right-side compression restricting right hemidiaphragm excursion — should produce measurable left frontal EEG asymmetry shifts in the predicted direction within a single session, independent of breathing ratio and breathing rate. This prediction bridges directly to AUTO↔MOD Link 5: the hemidiaphragm asymmetry mechanism is confirmed via the nostril lateralization literature; the deliberate postural thoracic version as a distinct control variable has not been directly studied. If confirmed, it establishes mechanical lateralization as a separable experimental variable from respiratory ratio — allowing the two routes to be disentangled for the first time and directly demonstrating that cognitive mode is mechanically assigned before cognition begins.

**Prediction 7 — Chain completeness: Scaffolding** 

Width and curvature are separable variables that require a dedicated dissociation design to confirm. Individuals with equivalent HRV — equivalent window width — but differing prior strength should show equivalent within-domain performance but divergent updating rate under contradictory evidence. High-width, high-curvature individuals hold multiple hypotheses simultaneously but systematically route evidence toward the prior-dominant attractor, discounting contradictory data before integration. The behavioral signature is extended discounting: how many contradictory data points are required before belief shifts. A sequential Bayesian belief-updating paradigm — where prior strength is experimentally manipulated and updating rate is the primary dependent variable — with concurrent HRV measurement should produce a 2×2 dissociation: high-width/low-curvature (fast updating), high-width/high-curvature (slow updating despite wide window), low-width/low-curvature (limited capacity, but updates when threshold crossed), low-width/high-curvature (near-zero updating). If high-width/high-curvature and low-width/low-curvature produce different behavioral profiles — which they should — curvature is confirmed as a separable variable from width. If they produce the same profile, the dissociation claim requires revision.

---

## Adjacent Contracts

**Below — feeds into this contract:**
- [[contract_AUTO_MOD]]: vagal tone, RSA amplitude, and ECS precision gain calibration set the baseline oscillation substrate and mechanical ceiling within which this contract operates. The full hemispheric mode selector mechanism lives in AUTO↔MOD Link 5 — this contract receives its output
- [[contract_ANCHOR_COG]]: mechanical stabilization of oscillatory amplitude sets moment-to-moment window stability; anchor failure forces identity mode independently of load or phase
- [[contract_TEMPORAL_COG]]: circadian phase sets the precision-gain floor and ceiling within which the oscillation operates — phase correction raises the ceiling that anchor repair or load reduction can reach
- [[contract_SOC_ANCHOR]]: external oscillatory entrainment and co-regulation widen or stabilize the contextual window from outside; their absence removes a stabilizing input the system may depend on for structural-mode access
- [[contract_INTERO_COG]]: interoceptive signal precision sets the noise floor that reduces usable window width independently of autonomic load or circadian phase
- [[contract_PROPRIO_AUTO_COG]]: proprioceptive confirmation stream as a second anchoring input; degraded proprioceptive signal quality reduces anchor stability and compresses oscillation amplitude

**Above — receives output from this contract:**
- [[contract_COG_REASON]]: prediction window width and curvature determine reasoning mode, fallacy group activation, and prior weighting ratio — the window geometry is the input this contract receives
- [[contract_COG_REASON_ESCALATION]]: collapse dynamics below the structural threshold produce the escalation sequence — brace substitution, sympathetic substitution, identity anchoring as chronic default
- [[contract_SOC_COG]]: window-width-dependent mentalizing capacity and the structural vs identity mode distinction formalized here are the invariant-level mechanisms SOC↔COG derives from
- [[contract_SOC_INSTITUTION]]: institutional compliance conditioning environments produce population-level window narrowing whose mechanism this contract defines — the cognitive outputs of chronic institutional load are WINDOW↔COG operating states running at scale

**Lateral:**
- [[contract_MOD_COG]]: precision gain output from AUTO↔MOD is the primary curvature-setting input — curvature is separable from width but both derive from the same upstream precision chain
- [[contract_NOCI_COG]]: nociceptive precision gain consumes the same precision resources as prediction window width — high nociceptive gain reduces available width independently of autonomic load

---

## Convergence Note

The formal mechanistic home of the hemispheric mode selector is [[contract_AUTO_MOD]] Link 5. The chain — RSA lateralization → frontal hemispheric availability → cognitive mode assignment — lives there because that is where the pressure mechanics physically produce the output. This contract is the receiving layer: it describes what the assigned mode does to cognition, not how the assignment is made.

The consequence of this architecture is that cognitive mode is not a cognitive variable. It is a pressure variable with cognitive outputs. Ambiguity tolerance, structural reasoning, cross-domain synthesis, and manifold construction are not skills the cognitive layer can elect to deploy. They are states the regulatory stack either delivers or does not, depending on the mechanical configuration running at the time of the cognitive operation. This is the central implication of the contract and the primary intervention design consequence: substrate first, cognitive work second.

---

## Origin Note

This contract began as a label — "prediction window" — used across multiple upstream contracts without a formal definition. The label was doing load-bearing work in AUTO↔MOD, ANCHOR↔COG, TEMPORAL↔COG, and SOC↔ANCHOR without the object itself ever being defined. The geometric definition section was the first formal output: width, depth, curvature, and stability as four separable dimensions, each with a different upstream driver and a different independent failure mode.

The naturalistic language comprehension neuroimaging findings were the first external empirical decomposition that matched the framework's structure without being derived from it. Pre-onset neural activity for high-semantic-load content categories — decomposing into a temporal lobe syntactic layer and a left frontal sensorimotor simulation layer — is the empirical signature of prospective depth operating as a two-layer system. The brain/LLM dissociation finding — equivalent anticipatory amplitude across noun, adjective, and proper noun categories despite divergent LLM token probability — confirmed that the brain is running category-level scaffold preparation, not probability-ranked sequence prediction. That distinction is the contract's sharpest empirical anchor.

The multi-window composition section was a structural derivation that the definition process forced: once width, depth, curvature, and stability were defined as separable dimensions with separable upstream drivers, treating the prediction window as a scalar was no longer coherent. The four semi-independent window instances — temporal, contextual, social, interoceptive — follow directly from assigning each dimension to its upstream contract. Their independent failure modes are the framework's prediction that they can and do collapse separately, which existing research has not tested as a deliberate dissociation design.

The contract closes a gap the framework had been working around since its earliest drafts. Every other contract in the stack referenced what comes out of this contract. This is the first formal statement of what the object is.

*Chain status: Width as upstream-regulated is load-bearing via AUTO↔MOD, ANCHOR↔COG, and TEMPORAL↔COG. Width as content-type-selective is load-bearing from neuroimaging of naturalistic language comprehension. Prospective depth as two-layered is load-bearing at the component level from source-space analysis; independent failure under load is scaffolding. Curvature as separable from width is scaffolding — mechanistically coherent, requires dedicated dissociation measurement. Oscillation mechanics are load-bearing via AUTO↔MOD. Multi-window composition is scaffolding — semi-independence structurally derivable, dedicated dissociation measurement not yet done. Link 5 hemispheric mode selector is partially load-bearing via AUTO↔MOD Link 5 and the nostril lateralization literature. Predictions 1–2 are scaffolding. Predictions 3, 5, and 6 are predictive. Prediction 4 is scaffolding.*

