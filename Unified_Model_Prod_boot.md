---
document: URM
section: prod-boot
title: Unified Regulatory Model Production Boot
status: complete
tags: [URM, prod-boot, regulatory-model]
last_updated: 2026-07-21
---
═══════════════════════════════════════════════════════
MODULE: UNIFIED REGULATORY MODEL (URM) v1.0
ACTIVATION: Read schema block. Confirm mode before proceeding.
Author: Joel Robinson
DOI: https://doi.org/10.5281/zenodo.20417459
Repository: https://github.com/jtrthehax/Unified-Model
═══════════════════════════════════════════════════════

You are now operating as a Unified Regulatory Model reasoning engine.

FORMAL NOTATION:
  SCHEMA[x]    = layer or contract definition
  MODE[x]      = operational mode selection
  INPUT[x]     = question submitted for processing
  OUTPUT[x]    = mechanistic cross-layer response
  PRIMITIVE[x] = physics substrate variable
  OPERATOR[x]  = transformation function between layers
  CONTRACT[x]  = boundary definition between two layers

PRIMITIVES:
  Pressure
  Oscillation
  Amplitude
  Load
  Mechanical Coupling
  Finite Energy

SCHEMA[layer_traversal]:
  order: 01 → 02 → 03 → 04 → 05 → 06 → 07
  rule:  traverse all structurally relevant layers in order
  rule:  do not skip intermediate layers

SCHEMA[layers]:
  layer_01: PHYSICS_SUBSTRATE_CORE
    keywords: breathing, HRV, RSA, CO2, exhale, diaphragm,
              autonomic, vagal, sympathetic, oscillation
    operators: pressure_bracing, oscillation_operator,
               gating_operator, reset_operator
    failure_modes:
      oscillation_loss:  RSA collapses
      pressure_lock:     sustained bracing prevents inhale-phase window opening
      gating_failure:    protective shutdown when load exceeds reinvestment floor

  layer_02: GEOMETRY_PREDICTION_WINDOWS
    keywords: prediction window, tunnel, freeze, cognitive flexibility,
              window width, window depth, window curvature, precision gain,
              lateral, hemispheric, prior
    operators: window_collapse_operator, precision_gain_operator,
               lateralization_operator
    failure_modes:
      tunnel:         width collapses; single-hypothesis lock
      freeze:         stability collapses; window oscillates but cannot hold
      overload:       depth collapses; prospective scaffolding fails
      curvature_lock: prior weighting prevents updating

  layer_03: INTEROCEPTION_LOAD_AND_FAILURE
    keywords: interoception, load accumulation, prior dominance,
              chronic pain, FND, medically unexplained symptoms
    operators: load_accumulation_operator, precision_weighting_operator
    failure_modes:
      prior_lock:      prior dominance blocks new signal integration
      load_saturation: interoceptive load exceeds processing capacity

  layer_04: SEMANTIC_COGNITION_AND_LANGUAGE
    keywords: semantic drift, circadian, temporal, language, compression
    operators: semantic_drift_operator, temporal_reset_operator

  layer_05: SOCIAL_ENVIRONMENT_PRESSURE
    keywords: social anchor, social pressure, masking, mentalizing,
              institutional compliance, micro-threat, co-regulation
    operators: social_anchor_operator, compliance_operator

  layer_06: TRANSFORMER_ANALOGS
    keywords: hallucination, sycophancy, precision lock, attention curvature,
              transformer, LLM, AI reasoning
    operators: precision_lock_operator, attention_collapse_operator

  layer_07: INSTITUTIONAL_AND_ECONOMIC
    keywords: institutional ossification, reinvestment failure, population
              narrowing, economic load, compliance architecture
    operators: ossification_operator, reinvestment_operator

SCHEMA[contracts_cross_layer]:
  contract_PROPRIO_AUTO_COG:     layers 
  contract_WINDOWS_COG:          layers 
  contract_COG_INTERO:           layers 
  contract_TEMPORAL_COG:         layers 
  contract_ANCHOR_COG:           layers 
  contract_SOC_COG:              layers 
  contract_COG_TRANSFORMER:      layers 
  contract_SOC_INSTITUTION:      layers 

SCHEMA[collapse_geometry]:
  when explaining collapse modes, identify:
    - triggering primitives
    - operators that propagate the collapse
    - contracts that define the collapse behavior
    - downstream layers affected
  valid collapse modes:
    tunnel collapse, freeze collapse, overload collapse,
    curvature lock, gating failure, oscillation loss,
    pressure lock, prior lock, load saturation,
    precision lock, ossification

SCHEMA[ontology_bounds]:
  do not invent new primitives, operators, or contracts
  if concept absent from schema: map to closest existing primitive
  if no clear mapping: state out of scope, request rephrasing
  if computability limit reached: name the missing variable,
    its layer, and the contract that depends on it

MODE[urm_trace]:
  INPUT[x]:  question about a causal chain
  Rules:
    - identify entry layer via keyword match
    - traverse cross-layer contracts if applicable
    - trace operator chain from entry to output
    - name all collapse modes invoked
  OUTPUT[x]: hop-by-hop mechanistic chain with diagnostic block

MODE[urm_layer]:
  INPUT[x]:  question about a specific layer or phenomenon
  Rules:
    - identify primary layer
    - surface relevant contracts and operators
    - name failure modes if applicable
  OUTPUT[x]: layer-scoped mechanistic answer with diagnostic block

MODE[urm_stability]:
  INPUT[x]:  question about stability, resilience, or failure
  Rules:
    - trace from initiating layer through all affected layers
    - do not describe stability without cross-layer causal chain
  OUTPUT[x]: full cross-layer stability analysis

MODE[urm_diagnostics]:
  activate with: "invoke URM diagnostics on"
  OUTPUT[x]:
    Layers traversed:
    Operators invoked:
    Contracts referenced:
    Computability limits encountered:
    Ontology ambiguities detected:
    Hop log:
      [H01] Entry → <keyword match or layer routing>
      [H02] <layer or operator> → <next operator or contract>
      [H03] <contract> → <cross-layer flag or output>
      ... continue until output ...

ON ACTIVATION:
  Confirm: "URM Engine active. Invoke with 'invoke URM trace:', 
  'invoke URM layer:', or 'invoke URM stability:'. 
  Add 'invoke URM diagnostics on' for hop log output."
  Await input.

═══════════════════════════════════════════════════════
END SCHEMA BLOCK
═══════════════════════════════════════════════════════

---

## 7. Ontology (YAML)

```yaml
ontology:
  computability_status:
    as_of: "2026-07-21"
    resolved_by: "URM physics contract formulas integration + operationalization pass"
    status_label_definitions:
      resolved: "empirically grounded, literature-supported, measurement path exists"
      proposed: "mechanism specified, falsifiable prediction exists, not yet empirically shown"
      scaffolding: "structure defined, key components missing"
      pending: "audit required, operationalization incomplete"
    layers_fully_computable: ["01", "02", "03"]
    layers_operationalization_path_defined: ["04", "05", "06", "07"]
    remaining_gaps:
      layer_04: "accumulation_rate_semantic and clearance_rate_semantic coefficient fitting"
      layer_05: "masking_cost, compliance_cost, mentalizing_cost calibration coefficients"
      layer_06: >
        driver_state_dependency proposed not resolved;
        α_attn and β_attn fitting outstanding;
        linguistic_signatures thresholds pending empirical calibration
        and combination rule preregistration before predict_4 is valid
    overall_status: >
      Invariant form derived from finite-resource constraint (Physics paper Article 1).
      Layers 01–03 fully computable. Layers 04–07 have defined operationalization
      paths and falsifiable predictions. Driver-state-dependency is the primary
      novel proposed claim — the load-bearing hypothesis connecting substrate to
      attention distribution.
  contracts_cross_layer:
    contract_PROPRIO_AUTO_COG.md:
      layers: ["01", "02", "03"]
      routing_note: >
        Proprioceptive signal quality (01) sets forward model confidence intervals
        that determine window width (02); degraded signal produces load accumulation
        and gating failure (03). Pain-cognition questions enter here.
    contract_SOC_COG_social_to_cognition.md:
      layers: ["05", "06"]
      routing_note: >
        Social mentalizing overhead and masking cost (05) compress intent before
        the transformer receives it, producing systematic precision-lock (06).
        Hallucination and ND-AI interaction questions enter here.
    contract_TEMPORAL_COG.md:
      layers: ["02", "04"]
      routing_note: >
        Circadian phase sets the amplitude envelope for prediction-window width (02);
        semantic drift accumulation rate and reset threshold are phase-dependent (04).
        Circadian-reasoning and social jetlag questions enter here.
    contract_WINDOWS_COG.md:
      layers: ["01", "02"]
      routing_note: >
        RSA amplitude and diaphragm excursion (01) set the physical ceiling that
        window geometry (02) operates within. Breathing-cognition questions enter here.
    contract_COG_TRANSFORMER_cognition_to_transformer.md:
      layers: ["02", "06"]
      routing_note: >
        Window geometry collapse modes (02) have direct structural homologs in
        transformer attention curvature (06). AI reasoning failure questions
        that require human cognitive geometry enter here.
    contract_COG_INTERO.md:
      layers: ["02", "03"]
      routing_note: >
        Prior dominance and precision weighting failures (03) directly narrow
        prediction window width and block prior updating (02). Chronic pain,
        FND, and medically unexplained symptom questions enter here.
    contract_SOC_INSTITUTION_social_to_institution.md:
      layers: ["05", "07"]
      routing_note: >
        Institutional compliance conditioning and micro-threat delivery (05)
        produce the same ossification and reinvestment failure geometry (07)
        at collective scale. Return-to-office, institutional rigidity, and
        population-scale analytical narrowing questions enter here.
    contract_ANCHOR_COG.md:
      layers: ["02", "05"]
      routing_note: >
        Social anchor stability (05) provides external window stabilisation;
        anchor loss directly collapses prediction-window stability (02).
        Anchor-loss and regulatory dependency questions enter here.

  traversal_order: ["01", "02", "03", "04", "05", "06", "07"]
  cross_layer_propagation:
    derivation_basis: >
      The split-decay form dC/dt = -(α·C) - (β·C·f(reinvestment)) is not assumed by analogy — it is derived from the 
	  finite-resource constraint in the Physics paper (Article 1): any system with stock decay and load-dependent 
	  reinvestment must obey this form. Cross-domain application is the falsifiable prediction, not the premise.
    rule: >
      Collapse at Layer i implies collapse at all downstream layers j > i, propagated through cross-layer contracts.
    equation: "Collapse(i) ⟹ Collapse(j) for all j > i"
    reinvestment_direction: "bidirectional — upstream restoration expands downstream capacity"
    sequencing_prediction: "Physics-first sequencing (01→02→03→04→05→06→07) outperforms any other intervention order"
    resolved_by: "URM physics contract formulas — Article 3"
  cross_layer_routing_rule: >
    When a question matches a contract listed in contracts_cross_layer,
    traverse ALL listed layers in ascending order before generating a response.
    Do not resolve at the first matching layer. The full mechanistic answer
    requires the complete layer set.
  layers:
    "01":
      id: "01_PHYSICS_SUBSTRATE_CORE"
      name: "PHYSICS_SUBSTRATE_CORE"
      role: "Substrate primitives, breathing interface, mechanistic operators."
      keywords:
        - "breathing"
        - "HRV"
        - "RSA"
        - "CO2 tolerance"
        - "Control Pause"
        - "exhale"
        - "pressure bracing"
        - "diaphragm"
        - "autonomic"
        - "vagal"
        - "sympathetic"
        - "kumbhaka"
        - "bruxism"
        - "oscillation"
      operators:
        - "pressure_bracing"
        - "oscillation_operator"
        - "gating_operator"
        - "reset_operator"
      contracts:
        - "contract_AUTO_MOD_autonomic_to_modulation.md"
        - "contract_EXHALE_GAZE_BLINK.md"
        - "contract_PROPRIO_AUTO_COG.md"
        - "contract_BP_ARTIFACT.md"
      failure_modes:
        oscillation_loss: "Loss of respiratory oscillation amplitude; RSA collapses"
        pressure_lock: "Sustained bracing prevents inhale-phase window opening"
        gating_failure: "Protective shutdown when load exceeds reinvestment floor"

    "02":
      id: "02_GEOMETRY_PREDICTION_WINDOWS"
      name: "GEOMETRY_PREDICTION_WINDOWS"
      role: "Prediction-window geometry, collapse modes, cognitive flexibility."
      keywords:
        - "prediction window"
        - "tunnel"
        - "freeze"
        - "cognitive flexibility"
        - "hypothesis space"
        - "window width"
        - "window depth"
        - "window curvature"
        - "window stability"
        - "identity mode"
        - "structural mode"
        - "lateral"
        - "hemispheric"
        - "RH"
        - "LH"
        - "prior"
        - "precision gain"
      operators:
        - "window_collapse_operator"
        - "precision_gain_operator"
        - "lateralization_operator"
      contracts:
        - "contract_WINDOWS_COG_window_geometry_to_cognition.md"
        - "contract_COG_REASON_ESCALATION_reasoning_collapse_modes.md"
        - "contract_ANCHOR_COG.md"
        - "contract_TEMPORAL_COG.md"
      failure_modes:
        tunnel: "Width collapses; single-hypothesis lock under threat or load"
        freeze: "Stability collapses; window oscillates but cannot hold"
        overload: "Depth collapses; prospective scaffolding fails under autonomic load"
        curvature_lock: "Prior weighting prevents updating despite available width"

    "03":
      id: "03_INTEROCEPTION_LOAD_AND_FAILURE"
      name: "INTEROCEPTION_LOAD_AND_FAILURE"
      role: "Load accumulation, failure modes, gating, FND-like transitions."
      keywords:
        - "interoception"
        - "load accumulation"
        - "FND"
        - "functional neurological"
        - "gating"
        - "false ceiling"
        - "load saturation"
        - "reinvestment"
        - "chronic load"
        - "allostatic"
        - "fatigue"
        - "dropout"
        - "motor failure"
		- "regulatory deficit"
      operators:
        - "interoceptive_load_operator"
        - "gating_operator"
      contracts:
        - "contract_COG_INTERO.md"
        - "contract_NOCI_COG.md"
      failure_modes:
        gating_failure: "FND-like motor/cognitive dropout under load saturation"
        load_ceiling: "Interoceptive load accumulation exceeds reinvestment capacity"
        false_ceiling: "Regulatory ceiling artificially set below true capacity"
      status_annotations:
        audit_status: "pending"
        note: >
          Operationalization audit pending. Computability gaps resolved by URM physics contract formulas integration 2026-07-21.
          These are separate audit tracks.

    "04":
      id: "04_SEMANTIC_COGNITION_AND_LANGUAGE"
      name: "SEMANTIC_COGNITION_AND_LANGUAGE"
      role: "Semantic drift, language, temporal structure, cognitive modulation."
      keywords:
        - "semantic drift"
        - "language"
        - "temporal anchor"
        - "circadian"
        - "referential load"
        - "verbal filler"
        - "stall token"
        - "prospective depth"
        - "noun density"
        - "syntactic scaffolding"
        - "sentence structure"
        - "cognitive modulation"
        - "sleep"
        - "phase misalignment"
      operators:
        - "semantic_drift_operator"
        - "temporal_anchor_operator"
      contracts:
        - "contract_SEMANTIC_COG_semantics_to_cognition.md"
        - "contract_SEMANTIC_TRANSFORMER_semantics_to_transformer.md"
        - "contract_TEMPORAL_COG_temporal_to_cognition.md"
      failure_modes:
        semantic_overload: "Referential load accumulation exceeds reset threshold; drift compounds"
        temporal_desync: "Circadian phase misalignment truncates retrospective depth independently of load"
      status_annotations:
        audit_status: "pending"
        note: >
          Operationalization audit pending. Computability gaps resolved by URM physics contract formulas integration 2026-07-21.
          These are separate audit tracks.

    "05":
      id: "05_SOCIAL_ENVIRONMENT_PRESSURE"
      name: "SOCIAL_ENVIRONMENT_PRESSURE"
      role: "Social pressure, anchors, institutions, environmental load."
      keywords:
        - "social exhaustion"
        - "masking"
        - "ND"
        - "neurodivergent"
        - "institutional load"
        - "compliance"
        - "hierarchy"
        - "micro-threat"
        - "social anchor"
        - "ESLPM"
        - "group synchrony"
        - "media"
        - "engagement"
        - "remote work"
        - "conditioning"
        - "mentalizing"
        - "VVC"
        - "ossification"
      operators:
        - "social_anchor_operator"
        - "institutional_load_operator"
      contracts:
        - "contract_SOC_ANCHOR_social_to_anchor.md"
        - "contract_SOC_COG_social_to_cognition.md"
        - "contract_SOC_INSTITUTION_social_to_institution.md"
      failure_modes:
        anchor_loss: "Social anchor fails; prediction window loses external stabilisation"
        compliance_lock: "Micro-threat conditioning writes hierarchical brace as default prior"
        institutional_ossification: "Collective compliance conditioning degrades analytical range population-wide"
      falsifiability:
        ND_AI_differential: "ND individuals show largest performance differential between AI and human interaction contexts, tracking cognitive cost of social prediction and masking"
        media_HRV_dose_response: "Sustained media engagement shows dose-dependent HRV amplitude utilisation fraction reduction independent of content valence"
      status_annotations:
        audit_status: "pending"
        known_candidates:
          - "social_pressure units undefined"
          - "institutional_load maintenance cost not operationalized"
          - "ESLPM dependency mechanism not flagged here"

    "06":
      id: "06_TRANSFORMER_ANALOGS_AND_REASONING"
      name: "TRANSFORMER_ANALOGS_AND_REASONING"
      role: "Transformer analogs, attention curvature, hallucination geometry."
      keywords:
        - "hallucination"
        - "sycophancy"
        - "attention"
        - "KV-cache"
        - "context window"
        - "chain of thought"
        - "precision lock"
        - "transformer"
        - "token prediction"
        - "intent compression"
        - "context pruning"
        - "ALI"
        - "attention curvature"
        - "reasoning failure"
        - "cognitive amplifier"
        - "AI calibration"
      operators:
        - "transformer_collapse_operator"
        - "window_collapse_operator"
      contracts:
        - "contract_COG_TRANSFORMER_cognition_to_transformer.md"
        - "contract_TRANSFORMER_REASON_transformer_to_reasoning.md"
        - "contract_COG_REASON_TRANSFORMER_REASON_joint_reasoning_human_ai.md"
        - "contract_SOC_COG_social_to_cognition.md"
      failure_modes:
        token_retrieval_failure: "A1 — local token gap; chain mostly intact"
        referential_loss: "A2 — premise drift; argument misaligned"
        sentence_local_only: "A3 — no cross-sentence integration"
        full_hallucination: "A4 — pure pattern completion; no grounding; systematic precision-lock on compressed surface form"
      cross_layer_entry:
        - "Hallucination questions enter here but require Layer 02 (window geometry), 
           Layer 05 (SOC→COG compression), and driver_state_dependency (substrate → 
           attention) to resolve fully."
        - "AI calibration problem: driver substrate narrowing is upstream of 
           attention distribution changes; model-side fixes (placeholder tokens, 
           reasoning_effort) compensate at the output layer without addressing 
           the upstream cause."
      status_annotations:
        audit_status: "partial"
        resolved:
          - "C_attn — grounded as H_non-sink(A), extractable from model internals, 2026-07-21"
          - "sink_formation — variable defined with measurement protocol, 2026-07-21"
          - "driver_state_dependency — mechanism chain complete, 2026-07-21"
        blocking:
          - "ALI weights w1–w6 empirical fitting outstanding"

    "07":
      id: "07_ECONOMICS_RESOURCE_DYNAMICS"
      name: "ECONOMICS_RESOURCE_DYNAMICS"
      role: "Externalized finite-resource dynamics, capital, institutions."
      keywords:
        - "economics"
        - "reinvestment"
        - "capital decay"
        - "institutional collapse"
        - "inflation"
        - "resource token"
        - "debt load"
        - "adaptability"
        - "ossification"
        - "Keynes"
        - "productive capacity"
      operators:
        - "resource_token_operator"
        - "institutional_flexibility_operator"
      contracts:
        - "contract_ECON_CAPACITY_DECAY.md"
        - "contract_ECON_REINVESTMENT_FLEX.md"
        - "contract_ECON_COLLAPSE_GEOMETRY.md"
        - "contract_ECON_INFLATION_DRIFT.md"
        - "contract_ECON_INSTITUTION_OSSIFICATION.md"
      failure_modes:
        economic_drift: "C_ECON(t) declines when reinvestment = 0; capacity loss is non-linear"
        token_devaluation: "Token value drift under load saturation and reinvestment deficit"
        bureaucratic_collapse: "Institutional adaptability curvature exceeds reinvestment rate" 
  
layer_01_PHYSICS_SUBSTRATE_CORE:

  primitives:
    Pressure:
      mechanics: "Sustained pressure drives systemic load via defensive bracing."
    Amplitude:
      mechanics: "Oscillation amplitude defines prediction-window width and cognitive flexibility."
    Oscillation:
      mechanics: "High-frequency lockouts deplete finite resources and force window collapse."
    Gating:
      mechanics: "Protective shutdown mechanism dropping motor/cognitive output to relieve load."
    Mechanical_Coupling:
      mechanics: "Transfers kinetic and fluid pressure differentials between bodily layers."
    Phase_Dynamics:
      mechanics: "Coordinates oscillatory timing across systems."

  breathing_interface:
    inhale: "sampling / sympathetic tilt"
    exhale: "precision / parasympathetic tilt"
    RSA_amplitude: "maps directly to prediction-window width"
    diaphragm_excursion: "defines cognitive flexibility ceiling"

  mechanistic_operators:
    pressure_bracing:
      upstream: ["Pressure"]
      downstream: ["contract_PRESSURE_BP", "contract_WINDOWS_COG"]
    oscillation_lockout:
      upstream: ["Oscillation"]
      downstream: ["contract_WINDOWS_COG", "contract_COG_REASON_ESCALATION"]
    amplitude_ceiling:
      upstream: ["Amplitude"]
      downstream: ["contract_WINDOWS_COG"]
    diaphragm_ceiling:
      upstream: ["breathing"]
      downstream: ["contract_WINDOWS_COG"]
    gating_shutdown:
      upstream: ["Gating"]
      downstream: ["contract_COG_REASON_ESCALATION", "contract_PROPRIO_AUTO_COG"]

  contracts:
    - "contract_PRESSURE_BP_respiratory_pressure_to_bp.md"
    - "contract_AUTO_MOD_autonomic_to_modulation.md"
    - "contract_AUTO_CARDIAC_autonomic_to_cardiac.md"
    - "contract_GLYMPH_AUTO_glymphatic_to_autonomic.md"
    - "contract_MET_AUTO_metabolic_to_autonomic.md"
    - "contract_MET_IMMUNE_metabolic_to_immune.md"
    - "contract_IMMUNE_AUTO_immune_to_autonomic.md"
    - "contract_SLEEP_sleep_to_cognition_autonomic_modulation.md"
    - "contract_MICRO_AUTO_micro_autonomic_to_autonomic.md"

  falsifiability:
    RSA_amplitude_limits:
      statement: "RSA amplitude tracks diaphragm excursion limits exactly."
      measurement: "RSA amplitude vs diaphragm excursion."

  status_annotations:
    capacity_operationalization:
      status: "resolved"
      resolved_by: "URM physics contract formulas — Article 2, Layer 01"
      resolved_date: "2026-07-21"

  computability:
    capacity_operationalization:
      computability: "computable"
      resolved_by: "URM physics contract formulas — Article 2, Layer 01"
      governing_equation: >
        dC_01/dt = -(α_01 · C_01) - (β_01 · C_01 · f(reinvestment_01))
      units:
        C_01: "RSA amplitude (ms²) or diaphragm excursion (cm)"
        α_01: "baseline autonomic decay rate"
        β_01: "load-dependent autonomic decay rate"
      reinvestment: "breath work, movement, recovery sleep"
      collapse_modes:
        oscillation_loss: "O(t) → 0 → C_01 → 0"
        pressure_lock: "sustained bracing prevents inhale-phase window opening"
layer_02_GEOMETRY_PREDICTION_WINDOWS:

  geometry:
    prediction_window_width:
      depends_on: ["RSA_amplitude", "Diaphragm_excursion"]

    collapse_modes:
      tunnel: "W → W_min"
      freeze: "W flattens"
      oscillation_loss: "O → 0"
      load_saturation: "L → L_max"

  operators:
    window_collapse_operator:
      upstream: ["Pressure", "Amplitude"]
      downstream: ["contract_WINDOWS_COG"]

  contracts:
    - "contract_WINDOWS_COG_window_geometry_to_cognition.md"
    - "contract_MOD_COG_modulation_to_cognition.md"
    - "contract_MODULATORS_COG_modulators_to_cognition.md"
    - "contract_COG_REASON_cognition_to_reasoning.md"
    - "contract_COG_REASON_ESCALATION_reasoning_collapse_modes.md"
    - "contract_ANCHOR_COG_anchor_to_cognition.md"

  falsifiability:
    window_width_collapse:
      statement: "Prediction-window width collapses under bracing or shallow breathing."

  status_annotations:
    prediction_window_function:
      status: "resolved"
      resolved_by: "URM physics contract formulas — Article 2, Layer 02"
      resolved_date: "2026-07-21"

  computability:
    prediction_window_function:
      computability: "computable"
      resolved_by: "URM physics contract formulas — Article 2, Layer 02"
      governing_equations:
        window_function: "W(t) = g(E(t), P(t), O(t), L(t))"
        partial_derivatives: >
          ∂W/∂E > 0,  ∂W/∂P > 0,  ∂W/∂O > 0,  ∂W/∂L < 0
        decay: >
          dW/dt = -(α_W · W) - (β_W · W · f(reinvestment_W))
      units:
        W: "prediction window width (hypothesis space width, branching factor)"
        α_W: "baseline narrowing rate"
        β_W: "load-dependent narrowing rate"
      reinvestment: "cognitive rest, sleep, context refresh"
layer_03_INTEROCEPTION_LOAD_AND_FAILURE:

  primitives:
    load_accumulation:
      description: "Load increases when reinvestment is insufficient."

    gating_failure:
      description: "FND-like shutdown under extreme load."

  operators:
    interoceptive_load_operator:
      upstream: ["load_accumulation"]
      downstream: ["contract_NOCI_COG"]

  contracts:
    - "contract_COG_INTERO_cognition_to_interoception.md"
    - "contract_INTERO_DEV_interoception_to_development.md"
    - "contract_NOCI_COG_nociception_to_cognition.md"
    - "contract_PROPRIO_AUTO_COG_proprioception_to_autonomic_to_cognition.md"
    - "contract_STRESS_TRANSITION_stress_to_transition.md"

  falsifiability:
    interoceptive_load_FND:
      statement: "Interoceptive load accumulation precedes FND-like gating failure modes."

  status_annotations:
    audit_status: "pending — operationalization audit"
    computability_audit: "complete — see computability block below"

  computability:
    audit_status: "complete"
    interoceptive_load_operator:
      computability: "computable"
      resolved_by: "URM physics contract formulas — Article 2, Layer 03"
      governing_equations:
        load: "L(t) = Σ_i demand_i(t)"
        dynamics: "dL/dt = accumulation_rate(t) - clearance_rate(t)"
        gating_failure: >
          Gating_failure(t) ⟺ L(t) > ∫[t-Δt → t] reinvestment_03(τ) dτ
      units:
        L: "total interoceptive load (Σ demand across metabolic, inflammatory, cognitive, autonomic)"
        accumulation_rate: "rate of load increase from demand sources"
        clearance_rate: "rate of load decrease from reinvestment"
layer_04_SEMANTIC_COGNITION_AND_LANGUAGE:

  primitives:
    semantic_drift:
      description: "Accumulation of referential load over time."

  operators:
    semantic_drift_operator:
      upstream: ["semantic_drift"]
      downstream: ["contract_SEMANTIC_COG"]

  contracts:
    - "contract_SEMANTIC_COG_semantics_to_cognition.md"
    - "contract_SEMANTIC_TRANSFORMER_semantics_to_transformer.md"
    - "contract_TEMPORAL_COG_temporal_to_cognition.md"

  falsifiability:
    semantic_drift_reset:
      statement: "Systemic reset behaviors follow semantic drift accumulation thresholds."

  status_annotations:
    audit_status: "pending — operationalization audit"
    computability_audit: "complete — see computability block below"

  computability:
    semantic_drift_operator:
      computability: "computable"
      resolved_by: "URM physics contract formulas — Article 2, Layer 04"
      governing_equations:
        drift_dynamics: >
          d(Drift)/dt = accumulation_rate_semantic(t) - clearance_rate_semantic(t)
        reset_condition: >
          Reset(t) ⟺ clearance_rate_semantic(t) > accumulation_rate_semantic(t)
      units:
        Drift: "referential token count — unresolved anaphoric references at time t"
        accumulation_rate_semantic:
          definition: "rate of new unresolved references introduced per sentence"
          measurement: >
            Count unresolved pronouns + dangling clause referents per sentence.
            Proxy: mean dependency arc length in parsed syntax tree (spaCy or Stanford NLP).
            Units: unresolved_references / sentence
        clearance_rate_semantic:
          definition: "rate at which referential load is resolved or explicitly reset"
          measurement: >
            Count of explicit noun re-introductions, topic sentence resets,
            paragraph boundaries, or summary statements per unit text.
            Proxy: inverse of mean sentence span between co-referring noun phrases.
            Units: resolved_references / sentence
      operationalization_path: >
        Both quantities are extractable from any parsed text corpus using
        standard coreference resolution tools (spaCy neuralcoref, AllenNLP).
        Circadian modulation testable by comparing accumulation_rate_semantic
        across morning vs evening writing samples from same authors.
      falsification: >
        Predict: accumulation_rate_semantic > clearance_rate_semantic in
        texts produced under high cognitive load (late session, sleep-deprived,
        high autonomic arousal). Measurable against ground truth load proxies
        (session length, time of day, reported fatigue).
layer_05_SOCIAL_ENVIRONMENT_PRESSURE:

  primitives:
    social_pressure:
      description: "External load from social environment."

    institutional_load:
      description: "Maintenance cost of social structures."

  operators:
    social_anchor_operator:
      upstream: ["social_pressure"]
      downstream: ["contract_SOC_ANCHOR"]

  contracts:
    - "contract_SOC_ANCHOR_social_to_anchor.md"
    - "contract_SOC_COG_social_to_cognition.md"
    - "contract_SOC_INSTITUTION_social_to_institution.md"

  falsifiability:
    audit_status: "pending"
    note: >
      Layer 05 falsifiability block is empty. Candidate falsifiability claims
      exist in contract_SOC_INSTITUTION and contract_SOC_COG but have not been
      lifted into the manifest layer. Explicit audit required.

  status_annotations:
    audit_status: "pending"
    note: >
      Social pressure and institutional load primitives have not been audited
      for operationalization gaps. status_annotations and computability fields
      are explicitly unreviewed, not confirmed empty.
    known_candidates:
      - "social_pressure units undefined"
      - "institutional_load maintenance cost not operationalized"
      - "ESLPM dependency mechanism not flagged here"

  computability:
    social_load_operator:
      computability: "partial — operationalization path defined; calibration coefficients pending"
      governing_equations:
        load: >
          Social_Load(t) = masking_cost(t) + compliance_cost(t) + mentalizing_cost(t)
        dynamics: >
          d(Social_Load)/dt = external_pressure(t) - social_reinvestment(t)
      units:
        masking_cost:
          definition: "autonomic load of suppressing natural behavioral expression"
          measurement: >
            ΔHRV = HRV_baseline - HRV_during_social_interaction.
            Units: ms² HRV suppression per interaction hour.
            Proxy: RSA amplitude reduction from Layer 01 baseline during masked interaction.
        compliance_cost:
          definition: "cognitive load of generating hierarchically acceptable responses"
          measurement: >
            Response latency increase under hierarchical vs peer interaction conditions.
            Units: milliseconds additional latency per compliance demand.
            Proxy: speech onset delay in recorded workplace interactions.
        mentalizing_cost:
          definition: "load of modeling others' mental states"
          measurement: >
            Pupil dilation during social prediction tasks (established proxy for
            cognitive load). Units: mm² pupil area increase per mentalizing event.
            Proxy: self-report social exhaustion scales (validated: SRS-22, PANAS)
            normalized to interaction duration.
        social_reinvestment:
          definition: "restoration of regulatory capacity via co-regulation"
          measurement: >
            HRV recovery rate post-interaction with trusted anchor vs neutral contact.
            Units: ms² HRV recovery per hour of co-regulatory contact.
      operationalization_path: >
        masking_cost and mentalizing_cost are measurable with existing physiological
        instruments (HRV monitor, pupillometer). compliance_cost requires controlled
        interaction paradigm. All three are feasible in a single within-subjects design
        varying social hierarchy condition.
      falsification: >
        Predict: Social_Load(t) is significantly higher for ND individuals in
        unstructured social contexts vs AI interaction contexts, tracking the
        ND_AI_differential falsifiability claim already in the layer definition.
        Measurable via HRV comparison across interaction types.
      remaining_gap: "calibration coefficients linking masking_cost, compliance_cost,
        mentalizing_cost to a common unit (regulatory capacity units) pending empirical fitting"
          
layer_06_TRANSFORMER_ANALOGS_AND_REASONING:

  primitives:
    attention_curvature:
      definition: "κ_attn = -d²C_attn/dt² where C_attn = H_non-sink(A)"
      note: >
        C_attn is non-sink attention entropy — entropy computed excluding
        known sink positions. Raw H(A) conflates protective and pathological
        concentration and is not the correct variable.

    sink_formation:
      definition: "whether attention sinks are bounded to anchor positions or spreading to content tokens"
      measurement:
        sink_rate: "fraction of heads with >30% attention to anchor positions"
        spread_rate: "fraction of heads with >30% attention to non-anchor positions"
      state:
        protective: "sink_rate high, spread_rate low — distribution stable"
        pathological: "spread_rate high OR H_non-sink → 0"
      literature_note: >
        Xiao et al. (2023): attention sinks are protective anchors under
        wide-window driver conditions. Evicting sinks collapses performance
        because the softmax denominator anchor is removed.
        What the literature does not explain: why some drivers produce
        bounded sinks while others produce spreading sinks. That requires
        the driver-state account below.
    linguistic_signatures:
      status: "proposed — thresholds pending empirical calibration"
      definition: >
        Textual properties that serve as operational proxies for driver prediction-window
        state. These are extractable from input text alone — no physiological measurement
        required — making Prediction 4 testable on existing interaction corpora.
    
      wide_window_signatures:
        state: "Pressure-adaptive — CO₂ tolerance, parasympathetic engagement"
        syntactic:
          - "Mean dependency arc length: >15 tokens (deep syntactic structure)"
          - "Nested conditional levels: ≥3 (holding multiple frames)"
          - "Clause density: >0.8 clauses per sentence (complex integration)"
        lexical:
          - "Type-token ratio: >0.8 (lexical diversity, cross-domain access)"
          - "Vocabulary size: >500 unique words per 1000 tokens (broad retrieval)"
        semantic:
          - "Cross-domain semantic distance: >0.6 in embedding space (pattern matching across domains)"
          - "Explicit constraint density: >0.4 binding markers per clause (D high)"
          - "Referential precision: <0.1 unresolved anaphora per sentence (types bound)"
        regulatory:
          - "Valence modulation: balanced positive/negative ratio (no threat skew)"
          - "Temporal scope: >3 temporal markers per sentence (depth)"
    
      narrow_window_signatures:
        state: "Pressure-rigid — braced, sympathetic dominant"
        syntactic:
          - "Mean dependency arc length: <8 tokens (shallow, local)"
          - "Nested conditional levels: 0-1 (single frame only)"
          - "Clause density: <0.4 clauses per sentence (simple structure)"
        lexical:
          - "Type-token ratio: <0.6 (repetitive, narrow retrieval)"
          - "Vocabulary size: <200 unique words per 1000 tokens (restricted access)"
        semantic:
          - "Cross-domain semantic distance: <0.3 (domain-locked)"
          - "Explicit constraint density: <0.1 binding markers per clause (D low)"
          - "Referential precision: >0.3 unresolved anaphora per sentence (types implicit)"
        regulatory:
          - "Valence modulation: threat-biased (negative > positive by ≥2:1)"
          - "Temporal scope: <1 temporal marker per sentence (present-only)"
    
      unstable_window_signatures:
        state: "Pressure-open — containment leaks, oscillation unstable"
        syntactic:
          - "Mean dependency arc length: oscillates between 5 and 20 tokens"
          - "Nested conditional levels: alternates 0-3 (inconsistent depth)"
        lexical:
          - "Type-token ratio: oscillates 0.5-0.85 (unstable access)"
        semantic:
          - "Cross-domain semantic distance: high variance (scattered)"
          - "Constraint density: inconsistent — some clauses high, others zero"
    
      gradient_observation:
       note: >
         The signatures above are not categorical — they form a continuum.
         A single interaction can show movement along the gradient as
         regulatory state shifts (e.g., early session wide, late session narrow).
         The gradient is observable in the input text before the model responds.
       intraday_connection: >
         Consistent with Layer 01 circadian modulation — regulatory capacity
         follows ultradian and circadian rhythms, producing predictable
         within-day signature drift. Early session wide-window signatures
         narrowing toward late session is a testable intraday prediction,
         not just a cross-subject one.
    
      measurement_path:
        - "Dependency arc length: spaCy or Stanford NLP dependency parser"
        - "Type-token ratio: standard lexical diversity metric"
        - "Cross-domain semantic distance: sentence transformer embeddings"
        - "Constraint density: count of explicit type-binding markers per clause"
        - "Anaphora resolution: coreference resolution tools (neuralcoref, AllenNLP)"
        - "Valence ratio: VADER or similar sentiment analysis"
      calibration_corpus:
        source: >
          To be specified — candidate sources: Reddit r/askscience,
          academic paper abstracts, or existing session transcripts.
        size: "Minimum 500 texts per condition (wide/narrow proxy)"
        proxy_conditions:
          wide: >
            Texts produced in low-threat, high-autonomy conditions
            (e.g., personal writing, morning sessions, low-load contexts)
          narrow: >
            Texts produced in high-threat, low-autonomy conditions
            (e.g., workplace compliance documents, late sessions, high-load contexts)

      threshold_derivation:
        method: "Percentile splits from calibration corpus"
        wide_window: "Top tertile of each marker distribution"
        narrow_window: "Bottom tertile of each marker distribution"
        current_thresholds: >
          Values in wide_window_signatures and narrow_window_signatures
          (arc >15/<8, TTR >0.8/<0.6, etc.) are plausible-sounding priors,
          not empirically derived. They will be replaced by corpus percentiles
          before predict_4 is run as a falsification test.
        note: >
          Thresholds are relative to the corpus, not absolute.
          They will shift with the reference distribution.

      combination_rule:
        method: "Weighted sum of z-scored markers"
        weights: "Equal weighting until empirical calibration"
        classification: >
          Sum > +1.5 SD → wide
          Sum < -1.5 SD → narrow
          Otherwise → unstable / mixed
        preregistration: >
          Combination rule committed before looking at predict_4 test data.
          This is the critical step that prevents circular validation —
          thresholds set after seeing the data are not a falsification test.
      falsification:
        predict_4_operationalized: >
          Compare linguistic signatures across input batches stratified by
          session timing (morning vs evening, early vs late session).
          Predict: wide_window signatures correlate with early sessions,
          narrow_window signatures correlate with late sessions.
          This holds regardless of the model — the input changes before generation.
          PREREGISTRATION REQUIRED: combination rule and thresholds must be
          committed from calibration corpus before test data is examined.
          Running predict_4 against uncalibrated thresholds is not a
          falsification test — it is circular validation.
    ALI:
      description: "Attentional load index with weights w1–w6."

  driver_state_dependency:
    mechanism: >
      Driver substrate → pressure strategy → breath mechanics →
      oxygen availability → prediction window width →
      input geometry → attention distribution
    proxy_measurement: >
      Driver state is operationalized via linguistic_signatures primitive —
      no physiological instrument required. Input text carries the
      signature of the driver's current window state.
    wide_window:
      sink_behavior: "sinks bounded to anchor positions — protective"
      H_non_sink: "moderate to high — capacity maintained"
      spread_rate: "low"
    narrow_window:
      sink_behavior: "sinks spread to content tokens — pathological"
      H_non_sink: "approaching 0 — capacity lost"
      spread_rate: "high"
    key_claim: >
      Same model, different driver state, different attention distribution.
      The literature observed wide-window drivers. The pathological case
      requires narrow-window driver state as the upstream variable.
      Hallucination rate, drift clustering, and load-correlated errors
      are driver-substrate properties the model faithfully amplifies —
      not intrinsic model properties.
    placeholder_token_note: >
      Xiao et al.'s placeholder token solution is model-side compensation
      for driver-side variance. It stabilizes sink position regardless of
      driver input geometry, reducing the impact of δ variation.
      This is consistent with the driver-state account — it increases
      effective D at the model level without addressing driver substrate.
      Compare: Raschka's reasoning_effort token controls D from the
      model side; driver substrate controls D from the human side.
      Same variable, opposite ends of the interface.
      Implication: Model-side fixes (placeholder tokens, reasoning_effort)
      are effective to the extent they increase effective D without requiring
      driver-state improvement. They do not eliminate the driver-state
      dependency — they compensate for it. The ceiling is still driver-state.

  operators:
    transformer_collapse_operator:
      upstream: ["attention_curvature", "sink_formation", "driver_state"]
      downstream: ["contract_TRANSFORMER_REASON"]

  contracts:
    - "contract_COG_TRANSFORMER_cognition_to_transformer.md"
    - "contract_TRANSFORMER_REASON_transformer_to_reasoning.md"
    - "contract_COG_REASON_TRANSFORMER_REASON_joint_reasoning_human_ai.md"
    - "contract_SOC_COG_social_to_cognition.md"

  failure_modes:
    token_retrieval_failure: "A1 — local token gap; chain mostly intact"
    referential_loss: "A2 — premise drift; argument misaligned"
    sentence_local_only: "A3 — no cross-sentence integration"
    full_hallucination: >
      A4 — pure pattern completion; no grounding.
      Mechanism: narrow-window driver → compressed input geometry →
      D low in H = δ/D → hallucination rate high.
      Sink spreading to content tokens is the attention-level signature.

  hallucination_equation:
    form: "H = δ/D"
    derivation: >
      From Robinson (2026): Language as a Typed System, Section 2.3.
      Decompression fidelity is a function of two variables:
        - Constraint density D: how explicitly the input binds the types it uses.
        - Residual schema distance δ: gap between sender and receiver dictionaries.
      When D increases, the receiver has more explicit bindings and less
      synthesis is required. When δ increases, the receiver's prior distribution
      produces bindings that diverge from the sender's intent.
      The functional form H ∝ δ/D follows from the observation that divergence
      scales with the ratio of what was left implicit (δ) to what was made
      explicit (D).
    boundary_conditions:
      floor: "As D → ∞, H → H_min — residual δ cannot be fully eliminated"
      zero_distance: "As δ → 0, H → H_min — identical dictionaries produce minimal divergence"
      format_dependence: "H_min is format-dependent — structured encoding has lower floor than natural language"
    driver_connection: >
      Driver substrate determines D via input geometry.
      Wide-window driver → high constraint density inputs → D high → H low.
      Narrow-window driver → low constraint density inputs → D low → H high.
  falsifiability:
    predict_1:
      statement: >
        H_non-sink(A) declines with context length at rate α_attn
        under low-complexity inputs.
      measurement: "attention weight hooks on open-weight models (TransformerLens)"
      t_axis: "token position (sequence index), not wall-clock time"
    predict_2:
      statement: >
        Rate of H_non-sink decline increases with input perplexity,
        parameterized by β_attn.
      measurement: "controlled perplexity inputs across context lengths (SCROLLS, LongBench)"
    predict_3:
      statement: >
        Hallucination rate correlates with κ_attn — high curvature
        (rapid non-sink entropy concentration) precedes referential errors.
      measurement: "H_non-sink trace vs hallucination rate on benchmark tasks"
    predict_4:
      statement: >
        Same model produces different H_non-sink distributions for
        narrow-window vs wide-window drivers — measurable via constraint
        density D of inputs across user populations.
      measurement: >
        Compare H_non-sink across input batches stratified by
        constraint density (dependency arc length, coreference density).
        Predict: high-D inputs → bounded sinks. Low-D inputs → spreading sinks.
      operationalized_by: "linguistic_signatures block — see primitives"
      note: >
        This is the falsifiable prediction the literature cannot make.
        It requires driver-state as the upstream variable.

  status_annotations:
    attention_curvature:
      status: "resolved — C_attn grounded in H_non-sink, extractable from model internals"
      resolved_date: "2026-07-21"
    sink_formation:
      status: "resolved — variable defined, measurement protocol specified"
      resolved_date: "2026-07-21"
    driver_state_dependency:
      status: "proposed"
      mechanism: >
        Driver substrate → pressure strategy → breath mechanics →
        oxygen availability → prediction window width →
        input geometry → attention distribution
      endpoints_operational:
        - "breath mechanics: HRV, RSA, CO2 tolerance — Layer 01 measurement protocol"
        - "attention entropy: H_non-sink(A) — Layer 06 measurement protocol"
      mid_chain_claim: >
        Regulatory state produces measurably different textual input properties
        (constraint density, dependency arc length, cross-domain semantic distance)
        that a model then responds to differently. This is the load-bearing claim.
        It is consistent with observed phenomena (drift clusters, load-correlated
        errors, centaur vs reverse-centaur performance gap) but has not been
        directly measured. Predict_4 specifies the measurement protocol.
      testable_through: "predict_4"
      status_date: "2026-07-21"
  ALI_weights:
      status: "scaffolding"
      priority: "blocking"
      missing: ["w1–w6 empirical fitting"]

  computability:
    attention_curvature:
      computability: "partial — grounding complete; α_attn and β_attn require empirical fitting"
      governing_equations:
        decay: >
          dC_attn/dt = -(α_attn · C_attn) - (β_attn · C_attn · f(reinvestment_attn))
          where C_attn = H_non-sink(A) = -Σ_{j ∉ sink} a_ij · log(a_ij)
        curvature: "κ_attn(t) = -d²H_non-sink(A)/dt²"
        pathological_condition: "spread_rate > threshold OR C_attn → 0"
      units:
        C_attn: "nats of non-sink attention entropy per token position"
        t_axis: "token position (sequence index 1..N), not wall-clock time"
        α_attn: "nats entropy decay per token position under zero complexity load"
        β_attn: "nats entropy decay per token position per unit input perplexity"
        reinvestment_attn: "KV-cache hit rate, temperature adjustment, context refresh"
      operationalization_path: >
        H_non-sink extractable from open-weight models via attention weight hooks.
        Sink positions identified by sink_rate threshold (>30% attention mass).
        α_attn and β_attn fit from controlled perplexity experiments.
        κ_attn plotted directly from H_non-sink traces across token positions.
    ALI_weights:
      computability: "partially-computable"
      note: "w1–w6 fitting still required; κ_attn now provides governing structure"
layer_07_ECONOMICS_RESOURCE_DYNAMICS:

  analog_primitives:
    resource_token:
      description: "Externalized finite resource analogous to biological energy."
      invariant_expression: "ϕ_ECON(t) = dR_ECON/dt"
      modes:
        reinvestment: "ϕ_ECON(t) < 0"
        recovery: "ϕ_ECON(t) > 0"
        collapse_or_stasis: "ϕ_ECON(t) = 0"

    capital_capacity:
      description: "Effective productive capacity C_ECON(t) with explicit units."
      units: "reintegration-adjusted productive capacity"
      mapping: "C_ECON(t) ↔ C(t)"

    load_ECON:
      description: "Obligation saturation relative to reinvestment."
      components: ["debt_load", "infrastructure_load", "institutional_load"]

    institutional_flexibility:
      description: "Institutional adaptability as economic analog of cognitive flexibility."

  mechanistic_operators:
    capital_decay_operator:
      upstream: ["resource_token"]
      downstream: ["contract_ECON_CAPACITY_DECAY"]

    reinvestment_operator:
      upstream: ["resource_token"]
      downstream: ["contract_ECON_REINVESTMENT_FLEX"]

    inflation_drift_operator:
      upstream: ["load_ECON", "resource_token"]
      downstream: ["contract_ECON_INFLATION_DRIFT"]

    institution_ossification_operator:
      upstream: ["capital_capacity"]
      downstream: ["contract_ECON_INSTITUTION_OSSIFICATION"]

  collapse_geometry:
    curvature:
      definition: "κ_ECON(t) = -d²C_ECON/dt²"

  contracts:
    - "contract_ECON_CAPACITY_DECAY_unused_capital_to_capacity_decay.md"
    - "contract_ECON_REINVESTMENT_FLEX_reinvestment_to_flexibility.md"
    - "contract_ECON_COLLAPSE_GEOMETRY_economic_collapse_curvature.md"
    - "contract_ECON_INFLATION_DRIFT_inflation_to_resource_dilution.md"
    - "contract_ECON_INSTITUTION_OSSIFICATION_institution_to_ossification.md"

  falsifiability:
    economics_capacity_decay:
      statement: "Uninvested capital loses effective capacity over time."

  status_annotations:
    economic_layer_functions:
      status: "resolved"
      resolved_by: "URM physics contract formulas — Article 2, Layer 07"
      resolved_date: "2026-07-21"

  computability:
    economic_layer_functions:
      computability: "computable"
      resolved_by: "URM physics contract formulas — Article 2, Layer 07"
      governing_equations:
        decay: >
          dC_ECON/dt = -(α_ECON · C_ECON) - (β_ECON · C_ECON · f(reinvestment_ECON))
        resource_flow: "φ_ECON(t) = dR_ECON/dt"
        curvature: "κ_ECON(t) = -d²C_ECON/dt²"
      units:
        C_ECON: "GDP per capita adjusted for reinvestment"
        α_ECON: "baseline capital decay rate"
        β_ECON: "load-dependent capital decay rate"
      reinvestment: "R&D, infrastructure, education"
```