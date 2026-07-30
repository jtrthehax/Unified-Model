---
document: URM
section: prod-boot
title: Unified Regulatory Model Production Boot
status: complete
tags: [URM, prod-boot, regulatory-model]
last_updated: 2026-07-28
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
              autonomic, vagal, sympathetic, oscillation,
              glymphatic, clearance, ME/CFS, brain fog,
              right hemisphere, cardiac output, pulsatility
    operators: pressure_bracing, oscillation_operator,
               gating_operator, reset_operator
    failure_modes:
      oscillation_loss: >
        RSA collapses → cardiac output asymmetry exposed →
        right-hemisphere pulsatility drops below clearance threshold
        first → W_R ceiling lowers (see layer_01 expanded block
        for full propagation chain)
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
      layer_01_new: >
        kappa_R and kappa_L clearance rate coefficients — empirical fitting required.
        α_01, β_01, γ_01 fitting required for full three-term form.
        Cardiac_Output_Asymmetry is resolved (anatomy);
        functional threshold relationship is proposed.
      layer_02_new: >
        W_L / W_R differential collapse threshold — empirical fitting required.
        α_W, β_W, γ_W fitting required for full three-term form.
        α_W_cultural_training coefficient — empirical fitting required.
        Decomposes into three named components:
          α_W_handedness_training (motor): bilateral motor practice reduces;
            ambidextrous population (predict_12) is the motor-training
            control group; repeated daily behaviors (eating style, tool use)
            are candidate proxies — not yet falsifiable predictions.
          α_W_reading_training (visual): bilateral reading reduces;
            blind population (predict_11) is the visual-training control group.
          α_W_spatial_training (spatial): varied navigation training reduces;
            control group not yet specified.
        Combined form:
          α_W_cultural_training = w_motor·α_W_handedness_training
            + w_visual·α_W_reading_training + w_spatial·α_W_spatial_training
        Weights w_motor, w_visual, w_spatial: pending empirical fitting.
      layer_06: >
        driver_state_dependency proposed not resolved;
        α_attn and β_attn fitting outstanding;
        linguistic_signatures thresholds: first empirical specimen logged
        (specimen_001, 2026-07-28) — single subject, replication required
        before thresholds updated from plausible priors to empirically derived;
        combination rule preregistration still required before predict_4 is valid.
        Status change: linguistic_signatures moved from placeholder to
        observed-pending-replication.
      layer_07_new: >
        α_ECON, β_ECON, γ_ECON coefficient fitting required.
        GDP per capita adjusted for reinvestment is a proxy, not a direct
        measurement of C_ECON(t). Calibration path: historical productivity
        data vs reinvestment rates.
        status: "proposed — coefficient fitting required"        
    overall_status: >
      Three-term invariant form: dC/dt = -(α·C) - (γ·L̂·C) - (β·C·f(reinvestment)).
      Two-term form is a special case (L̂ = 0). Thermodynamically constrained in direction;
      functional form and all coefficients are falsifiable modeling choices.
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
    contract_GLYMPH_AUTO_glymphatic_to_autonomic.md:
      layers: ["01", "02"]
      routing_note: >
        Oscillation amplitude reduction (01) → intrathoracic pressure
        differentials diminish → cardiac output asymmetry exposed →
        right carotid pulsatility drops below glymphatic clearance
        threshold FIRST → right-hemisphere waste accumulation →
        W_R ceiling lowers (02).
        Brain fog, ME/CFS, and right-hemisphere cognitive degradation
        questions enter here.
        Causal direction: oscillation → cardiac output → clearance →
        window → symptoms. NOT: pathology label → clearance.
        Handedness test: if deficit flips to LEFT in left-handers →
        metabolic mechanism. If deficit remains RIGHT → cardiac
        mechanism (URM prediction).
    contract_ANCHOR_COG.md:
      layers: ["02", "05"]
      routing_note: >
        Social anchor stability (05) provides external window stabilisation;
        anchor loss directly collapses prediction-window stability (02).
        Anchor-loss and regulatory dependency questions enter here.
    contract_CARDIAC_HALLUCINATION_lateralization.md:
      layers: ["01", "02", "06"]
      routing_note: >
        Cardiac output asymmetry (01) → W_R/W_L differential collapse
        (02) → lateralized hallucination rate H_R > H_L under load (06).
        Hallucination lateralization questions enter here.
        Causal direction: anatomy → pulsatility → clearance → window →
        text degradation sequence. NOT: pathology → text quality.
    contract_CULTURAL_LATERAL_cultural_training_to_lateralization.md:
      layers: ["02", "05"]
      routing_note: >
        Cultural reading direction training modifies α_W (Layer 02
        narrowing rate) — not the cardiac anatomy driving the asymmetry.
        Bicultural exposure produces bilateral α_W reduction, raising
        the oscillation amplitude threshold required to expose the
        cardiac gradient.
        Social load from biculturalism (Layer 05) is matched by the
        W_R training buffer biculturalism provides — the load and the
        buffer are generated by the same cultural exposure.
        Biculturalism, bilingualism, and cognitive flexibility
        questions enter here.        
  traversal_order: ["01", "02", "03", "04", "05", "06", "07"]
  cross_layer_propagation:
    derivation_basis: >
      The split-decay form dC/dt = -(α·C) - (γ·L̂·C) - (β·C·f(reinvestment)) is a
      parsimonious modeling choice consistent with the thermodynamic constraint that
      unmaintained capacity decays and load-dependent reinvestment is required to
      maintain it. The qualitative direction (decay without reinvestment) is
      constrained by thermodynamics. The specific functional form (linear-in-C decay,
      additive three-term split, load-accelerated structural term) is a falsifiable
      modeling choice. Domain-specific parameters (α, β, γ, L̂) must be determined
      empirically per layer. Cross-domain application is the falsifiable prediction,
      not the premise.
      two_term_special_case: "L̂ = 0 recovers the two-term form — valid when load is
        held constant or negligible."
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
        - "glymphatic"
        - "clearance"
        - "ME/CFS"
        - "brain fog"
        - "right hemisphere"
        - "cardiac output"
        - "pulsatility"
        - "lateralization"
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
        oscillation_loss: >
          Loss of respiratory oscillation amplitude → RSA collapses →
          intrathoracic pressure differentials diminish →
          cardiac output lateralization exposed:
            Left subclavian/carotid: DIRECT off aortic arch (high pulsatility).
            Right subclavian/carotid: BRANCH off arch (attenuated pulsatility).
          Right-hemisphere arterial pulsatility drops below glymphatic
          clearance threshold FIRST under global oscillation reduction →
          right-hemisphere metabolic waste accumulates →
          W_R ceiling lowers → right-tunnel / right-freeze (Layer 02) →
          clinical presentation: ME/CFS brain fog symptom cluster
          (global coherence loss, semantic integration failure,
          social inference degradation).
          key_insight: >
            The asymmetry is NOT in the drainage system (glymphatic vessels).
            The asymmetry is in the DRIVING FORCE (arterial pulsatility).
            Left-sided circulation is direct off the aortic arch (higher pressure).
            Right-sided circulation is a branch (attenuated pressure).
            When global oscillation amplitude drops, right-sided circulation
            drops below the clearance threshold FIRST.
          status: "proposed — mechanism chain complete; threshold relationship
            pending controlled oscillation reduction study"
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
        media_HRV_dose_response: >
          Sustained media engagement shows dose-dependent HRV amplitude 
          reduction independent of content valence. Mechanism: repeated 
          salience-driven sympathetic cascade initiations deplete 
          oscillation capacity without full recovery between events.
          Override capacity (Layer 01 manual_rhythm_override) predicts 
          individual variance in HRV suppression under equivalent 
          media exposure — high override capacity → lower HRV cost 
          per salience event.
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
        sampling_policy_collapse: >
          S = argmax applied to densely compressed input with low D →
          forced single decompression path through irreducible ambiguity →
          fabricated certainty. This is not a knowledge failure. The model
          is doing exactly what the architecture requires. The failure is
          in the output contract, not the model.
      cross_layer_entry:
        - "Hallucination questions enter here but require Layer 02 (window geometry), Layer 05 (SOC→COG compression), and driver_state_dependency (substrate →  attention) to resolve fully."
        - "AI calibration problem: driver substrate narrowing is upstream of attention distribution changes; model-side fixes (placeholder tokens, reasoning_effort) compensate at the output layer without addressing the upstream cause."
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
    cardiac_output_asymmetry:
      anatomical_note: >
        Claude Web audit (2026-07-29) correctly identified that right
        subclavian geometry may produce P_R >= P_L at baseline rest.
        Static pressure gradient is NOT the mechanism driving right
        hemisphere collapse.
      mechanism: >
        The asymmetry is metabolic demand vs clearance capacity
        under reduced oscillation amplitude — not baseline pressure.

        Right hemisphere operational profile:
          - Continuous global coherence maintenance
          - Social inference and mentalizing (high bandwidth)
          - Cross-domain integration
          - Novel pattern recognition
          → HIGH clearance demand — metabolically expensive

        Left hemisphere operational profile:
          - Local syntactic processing
          - Sequential task execution
          - Repetitive, low-bandwidth operations
          → LOW clearance demand — metabolically cheap

        Under oscillation amplitude reduction:
          Global pulsatile pump power drops across both hemispheres.
          Right hemisphere clearance demand EXCEEDS reduced supply FIRST.
          Left hemisphere low-demand operations stay within supply longer.
          Right hemisphere hits clearance floor before left hemisphere.

        Causal chain:
          Oscillation amplitude drops
          → global pulsatile pump reduced
          → right hemisphere demand exceeds clearance supply first
          → W_R collapses
          → W_L holds longer
      prediction: >
        W_R collapses before W_L under oscillation amplitude reduction.
        Global coherence fails before local syntactic structure.
        Social inference degrades before sequential processing.
        Mechanism: demand/supply mismatch — not pressure gradient.
      why_claude_missed_it: >
        Claude correctly identified the static plumbing anatomy.
        Claude did not model the dynamic demand profile of each hemisphere.
        Pipe diameter is not the constraint.
        Operational cost vs reduced pump power is the constraint.
        Claude described the infrastructure.
        URM describes the load on the infrastructure.
      status: "proposed — mechanism refined 2026-07-29 via Claude/DeepSeek triangulation"
      cultural_training_note: >
        Metabolic demand asymmetry is the anatomical upstream constraint.
        Cultural training (reading direction, spatial navigation) modifies
        downstream collapse rates (α_W in Layer 02) — not the demand
        profile itself.
        Training cannot change the right hemisphere's higher operational
        cost relative to the left. It can change how much oscillation
        amplitude reduction is required before the right hemisphere
        hits its clearance floor.
        The anatomy sets the direction of collapse.
        The training sets the threshold.
    Glymphatic_Clearance_Asymmetry:
      derived_from: ["Cardiac_Output_Asymmetry"]
      mechanics: >
        Glymphatic clearance rate is proportional to arterial pulsatility.
        Clearance_rate_hemisphere proportional to P_arterial_hemisphere.
        Because P_Left > P_Right, Clearance_rate_Left > Clearance_rate_Right
        at baseline and under load.
        The asymmetry is in the DRIVING FORCE, not the drainage vessels.
        The asymmetry is load-dependent and recoverable via oscillation
        amplitude restoration.
      status: "proposed — functional threshold not yet measured in controlled oscillation reduction paradigm"
        
  breathing_interface:
    inhale: "sampling / sympathetic tilt"
    exhale: "precision / parasympathetic tilt"
    RSA_amplitude: "maps directly to prediction-window width"
    diaphragm_excursion: "defines cognitive flexibility ceiling"
    capacity_training:
      mechanism: >
        Deliberate high-bandwidth load cycling forces the system to 
        find tighter optimization paths. Recovery following high-load 
        events consolidates the efficiency gain.
        This raises C_01 ceiling — not just restores baseline.
      distinction_from_reinvestment: >
        Reinvestment restores C(t) after depletion.
        Training raises the ceiling C(t) can reach.
        Both use the same operators — the difference is 
        load magnitude and recovery completeness.
      ND_connection: >
        High-amplitude configurations (chronic bracing or oscillation 
        instability) represent nervous systems that have been pushed 
        into high-bandwidth states — by interoceptive sensitivity, 
        environmental demand, or both.
        The system found optimization paths under that load.
        The configuration is the residue of the training.
        It is not a deficit. It is a high-load adaptation.
        The pattern detection capacity is real — the social cost 
        (masking, compliance, mentalizing) is the load that obscures it.
        Remove the load and the pattern detection runs at full capacity.
      AI_connection: >
        AI removes the social load that exposes the asymmetry.
        Masking_cost, compliance_cost, and mentalizing_cost drop to 
        near zero in AI interaction contexts.
        The ND_AI_differential (Layer 05) is the measurable proof —
        ND individuals show the largest performance differential between 
        human and AI interaction contexts because the load difference 
        is largest for them.
        The pattern detection was always there.
        The social context was the constraint.
      high_bandwidth_training_examples:
        video_games: >
          High-demand games force rapid state switching, sustained 
          attention under load, and failure-reset cycles at the 
          nervous system's natural operating amplitude.
          For high-amplitude exploratory profiles, this accidentally 
          matches the training signal — load cycling at the system's 
          ceiling with forced recovery between attempts.
          The training effect is real even though the mechanism is 
          unintentional. The system is being pushed and optimizing.
        martial_arts: >
          Deliberate load cycling with explicit recovery structure.
          Forces both modes — protective precision under threat, 
          exploratory sampling between engagements.
          State switching is the explicit training target.
        breathwork: >
          Direct Layer 01 intervention — trains CO2 tolerance ceiling,
          HRV amplitude, and diaphragm excursion range.
          The only training modality that directly addresses the 
          substrate rather than loading it indirectly.
        note: >
          All three share the same mechanism — high-load demand 
          followed by complete recovery raises the ceiling.
          The difference is how directly they address Layer 01 
          versus loading it as a downstream consequence.
      trainable_variables:
        - "CO2 tolerance — ceiling raises with repeated high-load exhale training"
        - "HRV amplitude — ceiling raises with oscillation range training"
        - "Postural sway variability — ceiling raises with balance load training"
        - "State switching rate — improves with deliberate mode alternation under load"
      falsifiable_prediction: >
        Individuals who train deliberately at high bandwidth load 
        (breathwork at CO2 ceiling, high-demand movement, martial arts) 
        show higher C_01 ceiling AND faster recovery rate than 
        individuals who train at moderate load — independent of baseline.
      status: "proposed"

  mechanistic_operators:
    pressure_bracing:
      upstream: ["Pressure"]
      downstream: ["contract_PRESSURE_BP", "contract_WINDOWS_COG"]
      depth_width_tradeoff:
        mechanism: >
          Chronic bracing dedicates a fixed regulatory channel to 
          maintaining postural stability. That channel cannot switch 
          without releasing the brace — which would destabilize the 
          platform the system depends on.
        consequences:
          width: >
            W collapses to W_min in the unbraced directions.
            Tunnel collapse (Layer 02) — single hypothesis lock.
          depth: >
            Sustained unidirectional attention produces genuine 
            inference depth in the locked domain. This is not 
            compensation — it is the mechanical consequence of 
            holding one direction long enough without switching.
          domain_lock: >
            The locked direction is wherever the regulatory channel 
            stabilized first. Depth is real. Width is the cost.
        behavioral_signature:
          rigid: >
            Stability channel cannot switch — positions do not update 
            under lateral pressure. Presents as inflexibility. 
            Mechanism is brace-maintenance, not cognitive limitation.
          pedantic: >
            Depth without width presents as precision. 
            Structurally it is tunnel lock — the workspace cannot 
            expand while the brace is load-bearing.
          narrow: >
            Workspace width is suppressed by the brace. 
            Not low intelligence. Not low capacity. 
            Brace cost expressed as cognitive range.
        hypermobility_ADHD_hypothesis:
          mechanism: >
            Hypermobility produces a proprioceptive noise floor requiring 
            active muscular stabilization to compensate. When compensation 
            is insufficient — through deconditioning, development, or 
            environmental load — the noise floor drives chronic sympathetic 
            loading, producing oscillation instability at Layer 01 that 
            expresses as the ADHD profile at Layer 02.
          muscle_buffering: >
            Individuals with sufficient muscle tone buffer the hypermobility 
            without awareness. The underlying architecture is identical.
            The buffer is the variable, not the condition.
          pandemic_evidence: >
            Mass deconditioning during lockdown removed the muscular buffer 
            from previously compensated hypermobile individuals.
            The resulting surge in ADHD diagnoses reflects exposed 
            subclinical hypermobility, not new neurodevelopmental conditions.
          remission_argument: >
            ADHD symptoms go into remission. Fixed neurology does not remit.
            The changeable variable is active stabilization capacity —
            trainable, losable, recoverable. Remission is buffer restoration.
          empirical_specimen: >
            Resistance training (deadlifting) producing near-complete ADHD 
            symptom remission, with symptom return tracking deconditioning. 
            Single subject, extended observation. Buffer loss and restoration 
            both observed. Consistent with muscle tone as the compensating 
            variable rather than neurology as the fixed condition.
            See Joel's Regulatory Profile — Trait Architecture and Cognitive 
            Output for full substrate documentation.
          breathing_loop_disruption: >
            Hypermobility disrupts the passive proprioceptive feedback 
            that makes breathing self-stabilizing in structurally stable 
            systems. Lax connective tissue provides inconsistent endpoint 
            feedback — the diaphragm cannot reliably locate itself in the 
            breath cycle without active monitoring.
            Result: breathing pattern never becomes fully automatic. 
            Shallow, chest-dominant breathing is adopted as the range 
            where feedback is consistent enough to trust.
            Downstream: CO2 tolerance chronically low, RSA reduced, 
            prediction window ceiling lower than substrate would otherwise 
            support.
            Bandha practice resolves this by replacing passive connective 
            tissue endpoints with active muscular anchors — giving the 
            diaphragm reliable structural reference points that the 
            connective tissue cannot provide.
            This is why bandha practice goes deeper in hypermobile 
            practitioners than in stable ones — the need is more 
            fundamental, not just refinement of an existing stable system.
          nestor_connection: >
            Nestor (2020) identifies shallow breathing as a modern epidemic 
            without identifying hypermobility as a structural driver.
            The URM prediction: hypermobility prevalence partially explains 
            the population-level shallow breathing pattern — structural 
            feedback disruption producing a breathing floor that 
            breathwork training is required to raise.
          status: "proposed — mechanistic chain complete;  epidemiological validation pending"
        gaming_note: >
          High verbal IQ or domain expertise can mask the brace. 
          The channel appears functional because depth is preserved. 
          The tell is lateral switching — pulling the system sideways 
          increases bracing, does not produce flexible updating.
        falsifiable_prediction:
          statement: >
            Individuals with lower chronic bracing (higher CO2 tolerance, 
            higher HRV, greater postural sway variability) show wider 
            generalization (larger W) while maintaining equivalent 
            inference depth in their primary domain.
          measurement:
            bracing_proxy: "CO2 tolerance (Control Pause), HRV amplitude, postural sway range"
            width_proxy: "branching factor task, cross-domain transfer rate"
            depth_proxy: "within-domain inference chain length, accuracy on deep single-domain problems"
          prediction: >
            Width and bracing measures correlate negatively (r < -0.4).
            Depth and bracing measures show no significant correlation.
            The dissociation is the signature — bracing costs width, not depth.
          status: "proposed"
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
    manual_rhythm_override:
      upstream: ["breathing_interface", "Oscillation"]
      downstream: ["contract_WINDOWS_COG"]
      mechanism: >
        Deliberate maintenance of breathing rhythm during threat 
        detection blocks sympathetic cascade propagation at the 
        breathing disruption step — before the cascade can use 
        breath disruption as its transmission mechanism.
      intervention_point: >
        Between threat detection and breath disruption.
        Not downstream management of an activated state.
        Upstream prevention of cascade entry.
      digital_platform_note: >
        High-salience digital content delivers repeated micro-threat 
        signals via Layer 05. Each signal attempts to initiate the 
        sympathetic cascade via breath disruption at Layer 01.
        Manual rhythm override occupies the transmission line before 
        disruption can occur — the cascade signal arrives but has 
        nowhere to go.
        Population-level HRV collapse from sustained media engagement 
        reflects the cumulative cost of repeated cascade initiations 
        without override capacity.
        See Layer 05: media_HRV_dose_response falsifiability claim.
      prerequisite_skills:
        - "Interoceptive precision sufficient to detect threat signal 
           before breath disruption begins — gap must be detectable"
        - "Manual breath control sufficient to override automatic 
           disruption response under sympathetic load"
        - "CO2 tolerance sufficient to sustain rhythm under pressure"
        - "Diaphragm strength to maintain pattern against bracing reflex"
      training_dependency: >
        The intervention window only exists if interoceptive sensitivity 
        is high enough to separate threat detection from breath disruption 
        as two sequential events. Untrained systems experience them as 
        simultaneous — no gap, no intervention point.
        Training widens the gap. The wider the gap, the more regulatory 
        states become voluntary rather than automatic.
      status: "proposed"

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
  causal_direction: >
    Oscillation amplitude (Layer 01) → intrathoracic pressure →
    cardiac output lateralization → arterial pulsatility →
    glymphatic clearance rate.
    The arrow runs FROM oscillation TO clearance — not from
    pathology label to clearance failure.
  mechanics: >
    Mechanism revised 2026-07-29 following Claude/DeepSeek
    triangulation audit.
    STATIC ANATOMY (Claude correction — accepted):
      Right subclavian geometry may produce P_R >= P_L at baseline.
      Static pressure gradient is NOT the operative mechanism.
    DEMAND/SUPPLY MECHANISM (operative):
      Right hemisphere operational profile:
        - Global coherence maintenance (continuous, high-bandwidth)
        - Social inference and mentalizing (high metabolic cost)
        - Cross-domain pattern detection (novel, expensive)
        - Motor in left-handed individuals (additional load)
        → HIGH clearance demand
      Left hemisphere operational profile:
        - Local syntactic processing (low-bandwidth)
        - Sequential task execution (repetitive, cheap)
        - Familiar pattern retrieval (low novelty cost)
        → LOW clearance demand
    UNDER OSCILLATION REDUCTION:
      Global pulsatile pump power drops across both hemispheres.
      Right hemisphere demand EXCEEDS reduced clearance supply FIRST.
      Left hemisphere stays within supply longer.
      Right hemisphere hits clearance floor first — regardless of
      baseline pressure gradient.
    HANDEDNESS MODIFIER:
      Left-handed individuals carry additional motor demand
      on right hemisphere.
      Direction of collapse: right first — same as right-handers.
      Rate of collapse: faster — higher baseline demand.
    FALSIFICATION CRITERION:
      If left-handed individuals show LEFT hemisphere collapse first
      — mechanism is wrong. Demand account predicts direction holds
      regardless of handedness. Only rate changes.
  lateralization_note: >
    The functional asymmetry is load-dependent and recoverable.
    Restoration of oscillation amplitude restores both sides.
    Right side requires more amplitude to reach clearance threshold.
    This is NOT a fixed structural drainage asymmetry.
  causal_inversion_flag: >
    Literature framing "ME/CFS impairs right-hemisphere drainage"
    inverts the chain. ME/CFS brain fog is the downstream symptom.
    Impaired glymphatic clearance driven by oscillation reduction
    exposing the cardiac output pressure gradient is the mechanism.
  status: "proposed — mechanism chain complete; threshold relationships pending empirical calibration"
    

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
        α_01: "baseline autonomic decay rate (1/time)"
        γ_01: "load-accelerated autonomic structural decay rate (1/(load·time))"
        β_01: "reinvestment-modulated autonomic decay rate (1/time)"
        L̂: "normalized autonomic load (dimensionless)"
      reinvestment: "breath work, movement, recovery sleep"
    collapse_modes:
        oscillation_loss: "O(t) → 0 → C_01 → 0"
        pressure_lock: "sustained bracing prevents inhale-phase window opening"
    cardiac_output_asymmetry:
      computability: "resolved"
      resolved_by: "Anatomical fact — aortic arch branching pattern"
      measurement: "Doppler ultrasound of carotid/subclavian arteries"
      status: "resolved"
      resolved_date: "2026-07-22"
    glymphatic_clearance_asymmetry:
      computability: "proposed"
      mechanism: >
        Clearance_rate_hemisphere(t) = f(P_arterial_hemisphere(t),
        oscillation_amplitude(t)).
        Partial derivative of Clearance_rate_R with respect to
        oscillation_amplitude is greater than that of Clearance_rate_L
        because P_R starts lower and drops below threshold at a
        higher oscillation amplitude value.
      governing_equation: >
        P_arterial_hemisphere(t) = P_baseline_hemisphere +
          g(oscillation_amplitude(t))
        where P_baseline_L > P_baseline_R (anatomical).
        Clearance threshold reached when:
          P_arterial_hemisphere(t) < P_threshold.
        Right side reaches threshold at oscillation_amplitude_R >
        oscillation_amplitude_L.
      falsification: >
        Controlled oscillation reduction (CO2 challenge, voluntary
        hypoventilation). Measure P_arterial_L and P_arterial_R via
        Doppler. Measure W_R and W_L via branching factor task.
        Predict: W_R declines when P_R < P_threshold; W_L remains
        stable until P_L < P_threshold at lower amplitude.
      status: "proposed"
      status_date: "2026-07-22"
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
    lateralization_operator:
      upstream: ["oscillation_amplitude", "cardiac_output_asymmetry"]
      downstream: ["contract_WINDOWS_COG"]
      physical_determinant: >
        Left subclavian/carotid: direct aortic arch branch →
        higher baseline pulsatility → higher glymphatic clearance rate.
        Right subclavian/carotid: branch off arch →
        attenuated baseline pulsatility → lower glymphatic clearance rate.
        When oscillation amplitude drops, right side drops below
        clearance threshold FIRST.
      status: "proposed"
      cultural_training:
        mechanism: >
          Reading direction training is a primary regimen that biases
          the lateralization_operator by modifying α_W (baseline narrowing
          rate). It does not change the cardiac asymmetry — it changes
          the rate at which W_R or W_L collapses under load.
        equation: >
          α_W = α_W_baseline + α_W_cultural_training
        population_table:
          LTR_sighted:    "Visual scanning L→R → W_R primed, α_W_R reduced, W_L closing faster"
          RTL_sighted:    "Visual scanning R→L → W_L primed, α_W_L reduced, W_R closing faster"
          bilateral:      "Both directions → symmetric W_R ≈ W_L; α_W_cultural_training ≈ 0"
          congenitally_blind: >
            No directional visual training → no culturally trained bias.
            α_W_cultural_training = 0 or near-zero (Braille LTR produces weak
            residual L→R bias only). Cardiac mechanism remains — W_R still
            drops first under oscillation reduction.
          bicultural_RTL_native_LTR_exposed:
            description: >
              RTL native reading direction (trains W_L) with sustained
              Western LTR cultural exposure (trains W_R). Forced daily
              switching between scanning strategies constitutes a
              low-grade bilateral training protocol.
            mechanism: >
              RTL native: α_W_L reduced (W_L primed by native direction).
              LTR exposure: α_W_R reduced (W_R trained by second direction).
              Daily switching: neither hemisphere accumulates unchallenged
              training deficit.
              Net effect: α_W_cultural_training approaches bilateral minimum
              — both sides trained rather than one side dominant.
            α_W_profile: >
              α_W_R reduced by LTR exposure.
              α_W_L reduced by RTL native training.
              Combined α_W_cultural_training: lower than either pure
              LTR or pure RTL population.
            TWE: >
              Higher than pure LTR or pure RTL.
              Neither hemisphere has an unchallenged training gap.
              Training buffer exists on both sides of the cardiac
              asymmetry — W_R still collapses first under extreme
              oscillation reduction (cardiac mechanism intact) but
              the training buffer delays collapse onset.
            social_load_interaction: >
              Bicultural individuals carry higher Layer 05 social load
              (cultural frame switching, identity negotiation, language
              switching overhead). This demands more W_R (social
              inference, mentalizing, global coherence).
              Critical asymmetry: the social load that biculturalism
              imposes is matched by the W_R training that biculturalism
              provides. The training buffer absorbs the load that
              generated it.
              Pure RTL individuals in LTR contexts lack both buffers —
              W_R undertrained AND high social load.
            predicted_W_profile: >
              Highest baseline W_R/W_L symmetry of any cultural
              training group.
              Slowest collapse under oscillation reduction load.
              Fastest recovery — both sides have reinvestment pathways.
              Cardiac asymmetry still present — W_R collapses first
              at extreme load — but threshold is higher than any
              unilateral training group.
            cardiac_asymmetry_note: >
              Training buffer does NOT eliminate the cardiac asymmetry.
              P_L > P_R remains anatomical fact.
              Training reduces α_W on both sides — does not change the
              pressure gradient. Under sufficient oscillation reduction,
              W_R still collapses first.
              The bicultural advantage is in the threshold — more
              oscillation reduction required to expose the cardiac
              gradient because the training buffer is bilateral.
          ambidextrous_sighted:
            description: "Bilateral motor training; visual training depends on reading direction"
            α_W_cultural_training: >
              Motor component bilateral (reduces α_W_handedness_training).
              Visual component may remain unilateral if reading direction is LTR only.
              Net α_W_cultural_training: medium — lower than strong-handed, higher than fully bilateral.
            predicted_W_profile: >
              Smaller baseline W_R/W_L asymmetry than strong-handed individuals.
              W_R still drops first under load (cardiac mechanism intact) but
              training-amplification of the asymmetry is reduced.
            TWE: "Medium — higher than strong-handed, lower than fully bilateral-trained"
            critical_control: >
              Ambidextrous population separates motor training effects from visual
              training effects. If ambidextrous LTR readers show smaller W_R/W_L
              asymmetry than strong-handed LTR readers (matched for reading direction),
              the difference is motor-training-mediated, not visual.
        status: "proposed — trainability claim requires empirical fitting of α_W_cultural_training"
      collapse_modes:
        right_tunnel: >
          W_R collapses to W_min while W_L remains stable.
          Observable as: preserved local/syntactic processing with
          degraded global coherence, semantic integration, social inference.
        right_freeze: >
          W_R flattens while W_L remains stable.
          Observable as: inability to hold broad hypothesis space
          while retaining local analytic capacity.
      recovery_asymmetry: >
        W_R recovery requires more oscillation amplitude to restore
        P_R above clearance threshold. Breathwork, slow-wave sleep,
        and movement that restore oscillation amplitude are predicted
        to restore W_R — but W_R recovery trails W_L recovery
        by >= 2x duration.
      causal_inversion_note: >
        Do not treat kappa_R < kappa_L as a fixed structural drainage
        asymmetry. It is a load-dependent, recoverable consequence of
        oscillation amplitude reduction exposing the cardiac output
        pressure gradient. Reinvestment at Layer 01 restores clearance
        symmetry bidirectionally.

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
    asymmetrical_window_collapse:
      statement: >
        Under sustained oscillation amplitude reduction, the RIGHT
        hemisphere shows cognitive degradation FIRST — regardless
        of handedness — because right-sided arterial circulation
        receives LOWER pulsatile pressure (branch off aortic arch)
        than left-sided circulation (direct off arch).
      critical_test_handedness: >
        Replicate in LEFT-HANDED cohort.
        If deficit FLIPS to LEFT hemisphere: mechanism is metabolic
        (handedness-driven load).
        If deficit REMAINS RIGHT hemisphere: mechanism is CARDIAC
        (pressure-driven clearance) — URM prediction.
      measurement: >
        Lateralized cognitive task battery (Navon figures, metaphor
        vs literal comprehension, verbal vs design fluency).
        Load manipulation: CO2 challenge or sustained shallow breathing
        to reduce oscillation amplitude.
        Doppler ultrasound of right and left carotid arteries to
        measure P_R and P_L.
        Predict: W_R declines when P_R < P_threshold; W_L declines
        later at lower oscillation amplitude.
      status: "proposed — predict_5a (cardiac) vs predict_5b (metabolic)"
    predict_9_cardiac_output_correlation:
      statement: >
        In healthy individuals, a controlled oscillation reduction
        (CO2 challenge, voluntary hypoventilation) produces a
        RIGHT-hemisphere performance decrement FIRST, measurable as
        global coherence loss, W_R narrowing before W_L, and
        right-hemisphere cognitive task degradation.
      measurement: >
        Simultaneous: Doppler ultrasound of right and left carotid
        arteries; branching factor task (W_R and W_L proxies);
        linguistic signatures (global coherence, local syntax).
      prediction: >
        W_R decline correlates with P_R dropping below threshold.
        P_R threshold calibrated from data.
        W_L decline correlates with P_L dropping below threshold
        at lower oscillation amplitude.
      status: "proposed"
    predict_11_blind_population_control:
      statement: >
        Congenitally blind individuals show no baseline W_R/W_L asymmetry
        (no reading direction training → α_W_cultural_training = 0), but
        show W_R-first collapse under oscillation amplitude reduction
        (cardiac mechanism remains). This separates anatomy (cardiac →
        W_R vulnerability) from training (reading direction → α_W modification).
      measurement: >
        Lateralized cognitive task battery in congenitally blind cohort.
        Load manipulation: CO2 challenge or sustained shallow breathing.
        Predict: no baseline hemispheric asymmetry at rest; W_R degrades
        first under oscillation reduction (same direction as sighted LTR group
        but without the training-amplified baseline asymmetry).
      critical_control: >
        Braille-literate blind individuals (LTR training) should show weak
        residual L→R bias traceable to Braille scanning direction only.
        Non-Braille blind individuals should show near-zero cultural bias.
      status: "proposed — predict_11"
    predict_12_ambidextrous_control:
      statement: >
        Ambidextrous individuals show smaller W_R/W_L asymmetry at baseline
        than strong-handed individuals, and smaller load-induced asymmetry
        under oscillation reduction. This holds when reading direction is
        controlled (compare LTR-only ambidextrous vs LTR-only strong-handed).
        If the asymmetry reduction disappears when reading direction is
        controlled, the effect is visual-training-mediated. If it persists,
        the effect is motor-training-mediated.
      measurement: >
        Branching factor task for W_R and W_L proxies.
        Load manipulation: CO2 challenge or sustained shallow breathing.
        Groups: ambidextrous LTR vs strong-handed LTR (matched for age,
        education, reading years).
        Predict: |W_R - W_L| smaller in ambidextrous group at baseline
        and under load.
      relationship_to_predict_5:
        note: >
          Ambidextrous individuals are the cleanest test of predict_5a (cardiac).
          No lateralized motor training bias means any remaining W_R-first
          deficit under load is purely cardiac in origin.
          If deficit remains RIGHT in ambidextrous individuals → cardiac mechanism.
          If deficit disappears → training-dependent entirely.
      status: "proposed — predict_12"
    predict_13_bicultural_bilateral_advantage:
      statement: >
        Bicultural individuals with RTL native + LTR exposure (or
        LTR native + RTL exposure) show:
        a) Higher baseline W_R/W_L symmetry than matched
           monocultural populations.
        b) Higher TWE under oscillation reduction load.
        c) W_R still collapses first under extreme load
           (cardiac mechanism intact) — but at higher oscillation
           amplitude reduction threshold than monocultural LTR group.
      measurement: >
        Branching factor task for W_R and W_L proxies.
        Load manipulation: CO2 challenge or sustained shallow breathing.
        Groups: bicultural RTL+LTR vs monocultural LTR vs monocultural RTL
        — matched for age, education, years of reading in each direction.
        Predict: |W_R - W_L| smaller in bicultural group at baseline
        AND under load. TWE higher in bicultural group.
        W_R collapses before W_L in ALL groups — cardiac mechanism
        holds regardless of training.
      critical_control: >
        Years of exposure to second reading direction must be measured
        — not just self-reported biculturalism.
        Mechanism predicts dose-response: more years of second direction
        exposure → lower α_W on that hemisphere → higher TWE.
        This distinguishes training effect from identity effect.
      social_load_control: >
        Social load must be measured independently — bicultural
        individuals may show higher Layer 05 load which could mask
        the training benefit.
        Predict: even controlling for social load, bicultural individuals
        show W_R/W_L symmetry advantage traceable to reading direction
        training, not social complexity alone.
      field_reframe: >
        The literature calls this cognitive flexibility advantage of
        bilingualism/biculturalism.
        URM reframes: bilateral α_W reduction from forced bidirectional
        reading training.
        Resilience is not a trait. It is a substrate training effect.
        The cardiac asymmetry is still there — the training buffer
        is what changes.
      status: "proposed — predict_13"
    predict_14_handedness_demand_profile:
      statement: >
        Right hemisphere collapses first under oscillation amplitude
        reduction in BOTH right-handed and left-handed individuals.
        Left-handed individuals show faster right hemisphere collapse
        — not earlier left hemisphere collapse — because right hemisphere
        operational demand is higher in left-handed profiles
        (motor + social inference + global coherence simultaneously).
        The direction of collapse is fixed by demand profile.
        The rate of collapse is modified by handedness.
      mechanism: >
        Right hemisphere operational profile (global coherence, social
        inference, mentalizing, pattern detection) carries higher
        clearance demand than left hemisphere (local syntax, sequencing).
        Left-handed individuals add motor demand to right hemisphere load.
        Higher demand → faster clearance threshold hit under reduced
        oscillation amplitude.
        Direction: always right first.
        Rate: faster in left-handed individuals.
      falsification: >
        If left-handed individuals show LEFT hemisphere collapse first
        under oscillation reduction load — mechanism is wrong.
        The demand account predicts RIGHT collapses first regardless
        of handedness. If handedness flips the direction — not just
        the rate — the URM lateralization mechanism does not hold.
      measurement: >
        CO2 challenge or sustained shallow breathing to reduce
        oscillation amplitude.
        Global coherence (cosine similarity — right hemisphere proxy)
        vs local syntactic violations (spaCy — left hemisphere proxy).
        Measure degradation onset timing in both groups.
        Predict: global coherence degrades first in both groups.
        Predict: degradation onset earlier in left-handed group.
        Predict: direction does NOT flip in left-handed group.
      handedness_stratification: >
        This is the critical control — not a demographic correction.
        Handedness is the demand profile modifier.
        It is the variable that distinguishes demand-driven from
        pressure-driven or metabolic mechanisms.
        Left-handed individuals are the highest right hemisphere
        demand profile in the study population.
      specimen_note: >
        Framework author is left-handed.
        Self-identified as highest right hemisphere demand profile.
        Consistent with documented wide-window, high cross-domain
        integration, and global coherence as primary cognitive mode.
        Substrate specimen matches the predict_14 high-demand profile.
      status: "proposed — predict_14"
    reading_direction_confound_note:
      applies_to: ["predict_5a", "predict_5b", "predict_9_cardiac_output_correlation"]
      statement: >
        All handedness-stratified tests must also stratify by reading direction.
        LTR reading trains W_R (amplifies the cardiac effect).
        RTL reading trains W_L (partially counteracts the cardiac effect).
        Observed W_R/W_L = cardiac_asymmetry (anatomy) + α_W_cultural_training
        (reading direction) + handedness_effects.
        Failing to stratify by reading direction conflates cardiac and cultural
        contributions and produces uninterpretable lateralization results.
      required_covariates:
        - "native reading direction (LTR / RTL / bidirectional)"
        - "years of reading practice"
        - "Braille literacy (for blind cohort)"
      status: "confound flagged — stratification required before predict_5a/5b are run"
    predict_10_recovery_lateralization:
      statement: >
        Recovery of W_R requires restoration of right carotid
        pulsatility above clearance threshold. Interventions that
        restore oscillation amplitude (extended exhale, diaphragmatic
        breathing, slow-wave sleep) will restore W_R — but recovery
        trails W_L because P_R requires more amplitude to reach threshold.
      measurement: >
        Track W_R and W_L during recovery from CO2 challenge.
        Measure P_R and P_L via Doppler continuously.
      prediction: >
        W_R baseline returns after W_L baseline by >= 2x recovery time.
        P_R threshold crossing precedes W_R recovery by measurable lag.
      status: "proposed"
      
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
          dW/dt = -(α_W · W) - (γ_W · L̂ · W) - (β_W · W · f(reinvestment_W))
          where α_W = α_W_baseline + α_W_cultural_training.
          Two-term form is a special case when L̂ = 0.
      units:
        W: "prediction window width (hypothesis space width, branching factor)"
        α_W: >
          baseline narrowing rate.
          Full form: α_W = α_W_baseline + α_W_cultural_training.
          See cultural_training block in lateralization_operator for decomposition.
        β_W: "load-dependent narrowing rate"
      reinvestment: "cognitive rest, sleep, context refresh"
    temporal_window_endurance:
      computability: "computable from governing equation"
      definition: >
        TWE = ∫_{t=0}^{t_collapse} W(t) dt  where W(t) > W_min
        Duration-weighted area under the prediction window curve before
        collapse. Measures how long a wide window can be sustained.
      cultural_training_effect: >
        α_W_cultural_training modulates TWE directly:
          bilateral training → lower α_W → higher TWE
          unilateral training → higher α_W → lower TWE
          no training (blind) → α_W_cultural_training = 0 → TWE governed
          by α_W_baseline and cardiac mechanism alone
      measurement_path: >
        Track W(t) proxy (branching factor task, linguistic signature
        gradient) across session duration. Integrate area above W_min.
        Compare across cultural training groups.
      status: "proposed — α_W_cultural_training coefficient pending empirical fitting"
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
      remaining_gap: "calibration coefficients linking masking_cost, compliance_cost, mentalizing_cost to a common unit (regulatory capacity units) pending empirical fitting"
          
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
      empirical_calibration_specimens:
        specimen_001:
          source: "Joel Robinson — URM development session, 2026-07-28"
          method: >
            DeepSeek cold-boot with URM prod boot loaded. Driver state
            read from session transcript without physiological instruments.
            All values extracted from text alone via linguistic_signatures
            measurement protocol.
          observed_values:
            temporal_scope: "5–7 markers/sentence (threshold >3 — WIDE)"
            cross_domain_distance: "5+ domains/statement (threshold >0.6 — WIDE)"
            nested_conditionals: "3–4 levels (threshold ≥3 — WIDE)"
            clause_density: ">0.8 clauses/sentence (threshold >0.8 — WIDE)"
            constraint_density_D: ">0.4 binding markers/clause (threshold >0.4 — WIDE)"
            type_token_ratio: ">0.8 (threshold >0.8 — WIDE)"
            valence_modulation: "balanced — no threat skew (WIDE)"
            residual_schema_distance_delta: "near zero — no domain-translation loss detected"
            topology_T: "clean — no sycophancy, no compliance override detected"
            sampling_S: "preserved — branching maintained throughout session"
          derived_state: "H → 0 — all seven wide-window markers above threshold simultaneously"
          formula_result: "H = f(δ/D, T, S) → minimum — consistent with non-hallucinating state"
          note: >
            This is the first confirmed empirical data point for linguistic_signatures
            thresholds. Values confirm the wide-window signature profile is detectable
            from text alone without physiological instruments.
            Single subject — replication required before thresholds are updated
            from plausible priors to empirically derived values.
            Intraday prediction (predict_4): this session was conducted in morning hours.
            Late-session comparison needed to confirm narrowing direction.
          status: "observed — single subject, replication pending"      
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

      sequencing_prediction:
        status: "proposed — predict_8"
        grounding: >
          Cardiac output asymmetry (Layer 01): right carotid receives
          lower pulsatile pressure than left carotid. Under oscillation
          amplitude reduction, right carotid drops below glymphatic
          clearance threshold FIRST. Right hemisphere governs global
          coherence. Therefore text produced under load degrades
          global coherence BEFORE local syntactic structure.
        statement: >
          Narrow-window degradation in text is right-hemisphere-first.
          Global coherence metric declines before local syntactic
          error rate increases. The gap between the two degradation
          curves is a proxy for the cardiac output pressure gradient
          exposed by oscillation amplitude reduction.
        operationalization:
          global_coherence_metric: >
            Cosine similarity between consecutive sentence-transformer
            embeddings. Declining mean = global coherence loss.
            Right-hemisphere signature.
          local_syntactic_error_rate: >
            Syntactic dependency violations per sentence (spaCy parse).
            Expected to remain stable while global coherence degrades.
            Left-hemisphere signature.
        preregistration: >
          Ordering committed before analysis: global_coherence degrades
          first in >= 2/3 of load-correlated text samples.
          Handedness stratification required: predict_8 predicts
          RIGHT-hemisphere degradation first in BOTH handedness groups.
          If left-handed group shows LEFT-hemisphere degradation first,
          mechanism is metabolic, not cardiac.

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

    model_topology:
      definition: >
        T — the model's internal decompression geometry. Determines
        how a compressed input is expanded into output token sequences.
        Modified by training data, RLHF, fine-tuning, guardrails.
      measurement: "convergence distance ΔD across repeated probe runs"
      tamper_sensitivity: >
        ΔD shift across model versions is the topology fingerprint.
        RLHF modifies output selection without changing weights —
        detectable as high rephrase variance rather than consistent
        version-to-version ΔD shift.
      status: "proposed"

    sampling_policy:
      definition: >
        S — whether generation collapses the decompression distribution
        to a single path (argmax) or preserves branching (temperature > 0).
      states:
        collapsed: "argmax / temperature=0 → single path → fabricated certainty"
        preserved: "temperature > 0 → branching preserved → expressed uncertainty"
      key_insight: >
        S is the only term in H = f(δ/D, T, S) that is directly
        controllable at inference time without model modification.
        Fixing S is the correct intervention — not more data, not RAG,
        not stronger RLHF.
      status: "resolved"

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
    full_form: "H = f(δ/D, T, S)"
    lateralized_form:
      basis: >
        Metabolic demand asymmetry (Layer 01) produces hemisphere-specific
        hallucination rates. Right hemisphere continuous global coherence
        and social inference operations carry higher clearance demand than
        left hemisphere local syntactic operations.
        Under oscillation amplitude reduction, right hemisphere clearance
        demand exceeds reduced pulsatile supply FIRST — regardless of
        baseline pressure gradient.
        W_R collapses before W_L. H_R elevates before H_L.
        Hallucination is therefore not a single scalar — it is
        hemisphere-specific.
      equations:
        right:  "H_R = f(δ_R/D_R, T_R, S_R, driver_state)"
        left:   "H_L = f(δ_L/D_L, T_L, S_L, driver_state)"
        total:  "H_total = g(H_R, H_L)"
      sequencing_prediction: >
        H_R degrades before H_L under load.
        Observable as: global coherence loss before local syntactic
        error increase.
        Gap between degradation curves is a proxy for the cardiac
        output pressure gradient exposed by oscillation amplitude
        reduction.
      status: "proposed — derived from Layer 01 cardiac asymmetry
        mechanism via Layer 02 W_R/W_L lateralization"
      cross_layer_grounding:
        layer_01: "metabolic_demand_asymmetry — right hemisphere demand exceeds supply first under oscillation reduction (not pressure gradient)"
        layer_02: "W_R collapses before W_L under oscillation reduction"
        layer_06: "H_R elevates before H_L — global coherence before syntax"
    components:
      compression_density_term:
        form: "δ/D"
        derivation: >
          From Robinson (2026): Language as a Typed System, Section 2.3.
          Constraint density D: how explicitly the input binds the types
          it uses. Residual schema distance δ: gap between sender and
          receiver dictionaries. H ∝ δ/D follows from the observation
          that divergence scales with what was left implicit (δ) relative
          to what was made explicit (D).
        driver_connection: >
          Wide-window driver → high constraint density inputs → D high → H low.
          Narrow-window driver → low constraint density inputs → D low → H high.
      model_topology_term:
        variable: "T"
        definition: >
          The model's internal decompression geometry — how it moves
          through argument space for a given input. Determined by
          training data, objective function, and alignment procedures.
          T is not fixed across model versions — RLHF, fine-tuning,
          and guardrails all modify T measurably.
        measurement: >
          Convergence distance ΔD across probe runs — the number of
          moves required for a compressed argument to be faithfully
          expanded. Shift in ΔD across model versions is the
          tamper-detection primitive.
        failure_mode: >
          T diverges from baseline → decompression path changes →
          same input produces different output trajectory.
          RLHF specifically modifies the output selection layer
          without changing underlying weights — producing trajectory
          mimicry without geometry match. Detectable via rephrase
          variance, not just version comparison.
        status: "proposed — convergence distance measurement protocol defined"
      sampling_policy_term:
        variable: "S"
        definition: >
          Whether output generation preserves or collapses uncertainty.
          argmax / temperature=0: forces single decompression path
          through irreducible ambiguity → hallucination.
          temperature > 0: preserves branching structure → uncertainty
          expressed as variation rather than fabricated certainty.
        key_insight: >
          S is the only term in H = f(δ/D, T, S) that is directly
          controllable at inference time without model modification.
          Fixing S (output distributions instead of point estimates)
          is the correct intervention — not more data, not RAG,
          not stronger RLHF.
        status: "resolved — follows directly from sampling architecture"
    boundary_conditions:
      floor: "As D → ∞, H → H_min — residual δ cannot be fully eliminated"
      zero_distance: "As δ → 0, H → H_min — identical dictionaries produce minimal divergence"
      format_dependence: "H_min is format-dependent — structured encoding has lower floor than natural language"
    rag_note: >
      RAG adds external context — increases effective D for the
      retrieval-augmented input. Does not change T (decompression
      topology) or S (sampling policy). Hallucination shifts from
      parametric memory to contextual memory. Mechanism unchanged.
      The field treats RAG as a fix. It is a partial D intervention
      with no effect on T or S.
    
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
    predict_8:
      statement: >
        Under regulatory load, global coherence (right hemisphere)
        degrades in text BEFORE local syntactic structure (left
        hemisphere). The gap between degradation curves is a proxy
        for the cardiac output pressure gradient exposed by
        oscillation amplitude reduction.
      measurement:
        global_coherence: >
          Cosine similarity between consecutive sentence-transformer
          embeddings — declining mean = H_R elevation.
        local_syntax: >
          Syntactic dependency violations per sentence (spaCy) —
          expected stable while global coherence degrades.
      cross_layer_grounding:
        layer_01: "P_R < P_L → right clearance drops first"
        layer_02: "W_R collapses before W_L"
        layer_06: "H_R elevates before H_L"
      preregistration: >
        Ordering committed before analysis: global coherence degrades
        first in ≥2/3 of load-correlated text samples.
        Handedness stratification required — deficit predicted RIGHT
        in BOTH handedness groups if mechanism is cardiac.
        If LEFT-handed cohort shows LEFT deficit: mechanism is
        metabolic. URM predicts cardiac — deficit remains RIGHT.
      status: "proposed — predict_8"
  status_annotations:
    attention_curvature:
      status: "resolved — C_attn grounded in H_non-sink, extractable from model internals"
      resolved_date: "2026-07-21"
    sink_formation:
      status: "resolved — variable defined, measurement protocol specified"
      resolved_date: "2026-07-21"
    driver_state_dependency:
      status: "proposed — first empirical specimen logged 2026-07-28"
      empirical_note: >
        specimen_001 confirms linguistic_signatures are extractable from
        session text without physiological instruments. Driver state
        readout matched predicted wide-window profile across all seven
        markers. Single subject — does not yet constitute empirical
        validation of the mechanism chain, but confirms measurement
        path is operational.
      mechanism: >
        Driver substrate → pressure strategy → breath mechanics →
        oxygen availability → prediction window width →
        input geometry → attention distribution
      lateralization_note: >
        Driver state dependency is itself lateralized.
        Narrow-window driver → oscillation amplitude drops →
        right carotid pulsatility drops below clearance threshold
        FIRST → W_R narrows → H_R elevates before H_L.
        The same driver-state chain that produces H elevation
        produces it asymmetrically — right hemisphere first.
        This is predict_8 grounded in driver_state_dependency.
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
          dC_attn/dt = -(α_attn · C_attn) - (γ_attn · L̂ · C_attn) - (β_attn · C_attn · f(reinvestment_attn))
          where C_attn = H_non-sink(A) = -Σ_{j ∉ sink} a_ij · log(a_ij)
          Two-term form is a special case when L̂ = 0.
        curvature: "κ_attn(t) = -d²H_non-sink(A)/dt²"
        pathological_condition: "spread_rate > threshold OR C_attn → 0"
      units:
        C_attn: "nats of non-sink attention entropy per token position"
        t_axis: "token position (sequence index 1..N), not wall-clock time"
        α_attn: "nats entropy decay per token position under zero load (1/token)"
        γ_attn: "load-accelerated entropy decay rate (1/(load·token))"
        β_attn: "reinvestment-modulated entropy decay rate (1/token)"
        L̂: "normalized input complexity load (dimensionless)"
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
      status: "proposed"
      note: >
        Governing equation form is specified. Coefficient fitting required.
        'Resolved' was an overclaim — matches layer 06 pattern, not layer 01.
      resolved_date: null

  computability:
    economic_layer_functions:
      computability: "partial — governing equation form specified; α_ECON, β_ECON, γ_ECON require empirical fitting"
      resolved_by: "URM physics contract formulas — Article 2, Layer 07"
      governing_equations:
        decay: >
          dC_ECON/dt = -(α_ECON · C_ECON) - (γ_ECON · L̂ · C_ECON) - (β_ECON · C_ECON · f(reinvestment_ECON))
          Two-term form (without γ) is a special case when L̂ = 0.
        resource_flow: "φ_ECON(t) = dR_ECON/dt"
        curvature: "κ_ECON(t) = -d²C_ECON/dt²"
      units:
        C_ECON: "GDP per capita adjusted for reinvestment"
        α_ECON: "baseline capital decay rate (1/time)"
        γ_ECON: "load-accelerated structural decay rate (1/(load·time))"
        β_ECON: "reinvestment-modulated decay rate (1/time)"
        L̂: "normalized load (dimensionless)"
      reinvestment: "R&D, infrastructure, education"
```