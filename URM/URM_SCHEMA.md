```yaml
# ============================================================
# URM CANONICAL YAML SCHEMA v1.0
# ============================================================
# All layers and contracts follow this exact structure.
# Fields marked [REQUIRED] must be present.
# Fields marked [OPTIONAL] may be omitted if not applicable.
# ============================================================

layer_{N}:
  # ----- IDENTIFICATION -----
  id: "XX_LAYER_NAME"                    # [REQUIRED] Unique identifier
  name: "LAYER_NAME"                     # [REQUIRED] Human-readable name
  role: "Brief description"              # [REQUIRED] One-sentence role
  
  # ----- KEYWORDS -----
  keywords:                              # [REQUIRED] Searchable terms
    - "keyword1"
    - "keyword2"
  
  # ----- OPERATORS -----
  operators:                             # [REQUIRED] Transformation functions
    - "operator_name"
    - "operator_name"
  
  # ----- PRIMITIVES (Layer 01 only) -----
  primitives:                            # [OPTIONAL] Physics primitives
    primitive_name:
      description: "What it is"
      mechanism: "How it works"          # [REQUIRED] Mechanistic explanation
      measurement: "How to measure"      # [OPTIONAL] Measurement protocol
      status: "resolved | proposed | scaffolding | pending"
  
  # ----- MECHANISM (Unified field) -----
  mechanism:                             # [REQUIRED] The causal chain
    description: "What happens"          # One clear paragraph
    causal_chain:                        # Step-by-step
      - step_1: "Oscillation drops"
      - step_2: "RSA collapses"
      - step_3: "Right hemisphere demand exceeds supply"
    key_insight: "The single most important takeaway"
    why_claude_missed_it: "Only if applicable"  # [OPTIONAL] Meta-audit note
  
  # ----- COLLAPSE MODES -----
  collapse_modes:                        # [OPTIONAL] Failure modes
    mode_name:
      description: "What happens"
      trigger: "What causes it"
      downstream: ["layer_02", "layer_03"]
      status: "proposed | resolved"
  
  # ----- CONTRACTS -----
  contracts:                             # [OPTIONAL] Cross-layer connections
    - "contract_NAME.md"
  
  # ----- EQUATIONS (Stable) -----
  equations:                             # [OPTIONAL] Mathematical formulations
    variable_name:
      equation: "dX/dt = ..."
      units: "units of measurement"
      definition: "What the variable means"
  
  # ----- PREDICTIONS (Stable) -----
  predictions:                           # [OPTIONAL] Falsifiable claims
    predict_N:
      statement: "What will happen"
      mechanism: "Why it will happen"
      measurement: "How to measure it"
      falsification: "What would disprove it"
      status: "proposed | resolved | pending"
  
  # ----- STATUS (Live) -----
  status:                                # [REQUIRED] Progress tracking
    overall:
      status: "resolved | proposed | scaffolding | pending"
      last_updated: "YYYY-MM-DD"
      note: "Brief status description"
    gaps:                                # [OPTIONAL] Known gaps
      - "Description of gap"
      - "Description of gap"
    resolved_items:                      # [OPTIONAL] What's been resolved
      - "Item resolved on YYYY-MM-DD"
    blocking_items:                      # [OPTIONAL] What blocks progress
      - "Item blocking completion"
  
  # ----- COMPUTABILITY (Live) -----
  computability:                         # [REQUIRED] Measurement status
    variable_name:
      computability: "computable | partial | proposed | pending"
      resolved_by: "Citation or method"
      measurement_path: "How to measure"
      remaining_gap: "What's missing"
      status_date: "YYYY-MM-DD"
```
