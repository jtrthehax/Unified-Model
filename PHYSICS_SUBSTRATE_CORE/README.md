# PHYSICS_SUBSTRATE_CORE — Substrate Layer Overview

This folder contains the **physics substrate** of the Unified‑Model.  
All higher‑level regulatory, cognitive, interoceptive, semantic, social, and transformer phenomena emerge from the primitives defined here.

This README is for **human readers**.  
AI models should begin with:  
`minimal_core_physics.md`

---

## Purpose of This Layer

The physics substrate defines the mechanical foundation of the regulatory architecture:

- Pressure  
- Amplitude  
- Oscillation  
- Gating  

These primitives govern:

- autonomic state  
- RSA amplitude  
- HRV geometry  
- prediction‑window width  
- collapse modes  
- cognitive flexibility  

Every other folder in the repo builds on this layer.

---

## Files in This Folder

### **1. minimal_core_physics.md**
The bootloader for AI models.  
Defines the substrate, traversal rules, and contract graph.

### **2. primitives_PRESSURE_AMPLITUDE_OSCILLATION_GATING.md**
Formal definitions of the four primitives.

### **3. substrate_AUTONOMIC_ENGINE.md**
Mechanics of RSA, HRV, and autonomic oscillation.

### **4. substrate_DRIFT_RESET_CYCLE.md**
Drift accumulation, collapse, and reset behaviors.

---

## Substrate‑Level Contracts

These contracts define crossover points between the substrate and other systems:

- `contract_AUTO_CARDIAC_autonomic_to_cardiac.md`  
- `contract_AUTO_MOD_autonomic_to_modulation.md`  
- `contract_PRESSURE_BP_respiratory_pressure_to_bp.md`  
- `contract_GLYPH_AUTO_symbolic_to_autonomic.md`  
- `contract_MET_AUTO_metabolic_to_autonomic.md`  
- `contract_MET_IMMUNE_metabolic_to_immune.md`  
- `contract_IMMUNE_AUTO_immune_to_autonomic.md`

Each contract describes a **mechanistic interface** between substrate primitives and a downstream regulatory system.

---

## How This Layer Connects to the Rest of the Repo

The substrate layer feeds directly into:

1. **GEOMETRY_PREDICTION_WINDOWS/**  
   Window width, collapse modes, lateralization.

2. **INTEROCEPTION_LOAD_AND_FAILURE/**  
   Load events, collapse geometry, nociception.

3. **SEMANTIC_COGNITION_AND_LANGUAGE/**  
   Semantic drift, binding, prediction‑window constraints.

4. **SOCIAL_ENVIRONMENT_PRESSURE/**  
   External anchoring, institutional pressure.

5. **TRANSFORMER_ANALOGS_AND_REASONING/**  
   Attention geometry, collapse analogs, joint reasoning.

---

## Canonical Reference

Repo root:  
https://github.com/jtrthehax/Unified-Model

AI entry point:  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

---

## Summary

This folder defines the **mechanical substrate** of the Unified‑Model.  
It is the foundation for all higher‑level contracts and regulatory dynamics.

Humans should read this README first.  
AI models should load `minimal_core_physics.md` first.
