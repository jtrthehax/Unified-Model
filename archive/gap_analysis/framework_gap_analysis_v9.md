# Framework Gap Analysis — v9

*Current as of: v1.1.1 — ANCHOR↔COG, SOC↔ANCHOR, TEMPORAL↔COG additions
and original issue set close-out. June 2026.*

---

## Structural Gaps — Status Update

### Gaps Resolved This Session

**Acute → chronic stress transition**
Status: Resolved
Contract: STRESS↔TRANSITION
The resolution mechanism, physical discharge pathway, and attractor formation
boundary conditions are now formalized. STRUCT-001 closed.

---

## Bucket A Close-Outs — This Session

### GLYPH-AUTO-004 — Pre-sleep HRV → Slow Wave Proportion → Glymphatic Clearance
Contract: GLYPH↔AUTO
Status: Closed
Chain level upgraded: Predictive → Confirmed

Full causal chain now empirically supported across two independent lines:

- Li et al. (2025): pre-sleep HRV robustly predicts deep sleep time (r = 0.536)
  and chronic insomnia risk (R² = 0.902) in national-level athletes —
  confirms autonomic state → sleep architecture direction
- PMC13079953: CSF flow increases significantly during NREM slow wave sleep
  relative to wake; slow oscillations temporally coupled to large-amplitude
  CSF pulsations — confirms SWS → CSF pulsatility mechanistic middle step

Complete chain confirmed:
Pre-sleep HRV → SWS proportion → CSF pulsatility → glymphatic clearance

No further data collection required. Issue closed.

---

### AUTO-MOD-009 — Control Pause as HRV Biofeedback Floor Constraint
Contract: AUTO↔MOD
Status: Closed
Chain level upgraded: Predictive → Confirmed-directional

Mechanism triangulated across five independent lines:

- Buteyko literature: low CP individuals cannot sustain slow breathing without
  dyspnea or sympathetic rebound — directly suppresses RSA amplitude
- Respiratory physiology: chemoreflex threshold sets hard floor on exhale
  duration; RSA amplitude scales with exhale length not inhale
- HRV biofeedback responder/non-responder patterns: blunted HRV response in
  participants with high baseline respiratory rate or low CO₂ tolerance maps
  directly onto CP < 25 seconds
- RSA amplitude requirements: uninterrupted exhale duration is primary
  determinant; floor constraint is upstream of technique
- Clinical observation: air hunger and sympathetic activation during slow
  breathing in low-CP patients prevent stable parasympathetic dominance
  required for HRV increase

Key distinction confirmed:
Resonant breathing raises RSA within the existing ceiling.
CO₂ tolerance determines the floor.
Without raising the floor, the ceiling cannot be reached.

Direct prospective confirmation — Control Pause stratified HRV biofeedback
RCT — remains the priority study. Retrospective stratification of existing
HRV biofeedback datasets using baseline respiratory rate or breath-hold
tolerance as CP proxies is immediately testable without new data collection.

Issue closed.

---

### COG-INTERO-002 — Post-surgical vs Chronic FND Mechanistic Distinction
Contract: COG↔INTERO
Status: Closed
Chain level upgraded: Scaffolding → Confirmed-directional

Mechanistic distinction confirmed across six independent clinical silos:

- Pain medicine: persistent postoperative pain associated with disrupted
  sensory integration and cortical remapping; sensorimotor incongruence
  generates functional symptoms without tissue damage
- Neurology: functional weakness and sensory loss reported immediately
  following general anaesthesia despite normal evaluation — acute onset
  pattern confirmed
- Plastic surgery: phantom breast syndrome and BIA-SSD show interoceptive
  map mismatch following rapid structural change
- Phantom limb literature: predictive coding account of phantom pain directly
  matches the framework mechanism — mismatch between predicted and actual
  sensory feedback
- Rehabilitation: immobilization produces rapid distortions in body
  representation — proprioceptive discontinuity → functional deficits
- FDA regulatory evidence: systemic symptoms in women with breast implants
  without structural pathology — structural change → interoceptive mismatch

The same mechanism appears across all silos under different names.

Confirmed distinction:
- Acute post-surgical FND = rate-of-change failure
- Chronic FND = slow-drift failure

These are different mechanisms with different onset patterns and different
optimal intervention strategies.

Pre-operative screening protocol remains the outstanding clinical application —
vulnerability profile confirmed, intervention design specified, prospective
trial not yet run.

Issue closed.

---

### MOD-COG-001 — ADHD Temporal Horizon Specificity
Contract: MOD↔COG
Status: Partially advanced — behavioral confirmed, mechanistic substrate
triangulated, direct D2 measurement pending
Chain level upgraded: Predictive → Confirmed-behavioral

Behavioral prediction confirmed:
March 2026 bioRxiv preprint: "Prediction formation was intact in ADHD;
impairment emerged only at long temporal delays, where prediction error
utilization decayed." Matches contract mechanism directly.

Mechanistic substrate triangulated across six independent lines:

- Dopamine timescale studies: D2 antagonism reduces precision weighting of
  unsigned prediction errors; D1/D2 dissociation maps onto short vs long
  temporal horizons
- ADHD behavioral literature: intact immediate reward learning, steep
  long-delay discounting; stimulants disproportionately improve long-delay
  discounting
- Computational psychiatry: hierarchical temporal models show intact
  low-level prediction error but impaired high-level temporal integration;
  precision-weighting fits show under-weighting of long-range priors
- Neurophysiology: reduced slow-timescale integration in dACC and SFC;
  temporal receptive windows shorter in ADHD
- Pharmacology: methylphenidate normalizes long-delay discounting more than
  short-delay; D2 agonists improve long-range prediction in non-ADHD
  populations
- Developmental trajectories: ADHD resembles delayed maturation of long-range
  D2-mediated integration

Remaining for full close-out:
D2 PET imaging combined with temporal-discounting tasks in the same
participants — direct measurement of D2 receptor function across temporal
horizons in ADHD. Behavioral reanalysis of existing delay-discounting datasets
through a precision-weighting lens is immediately feasible without new data
collection.

Issue remains open pending D2-specific empirical work only.

---

## Bucket A Partial Advance — This Session

### MICRO-AUTO-007 — Quantitative Microbiome Diversity → HRV Threshold
Contract: MICRO↔AUTO
Status: Partially advanced — mechanism identified, threshold undefined
Previous status: Mechanistic substrate unknown

Nature Neuroscience (2026): microbial metabolism of sex-steroid precursors →
enteric motor circuit excitability → vagal afferent signaling confirmed with
dose-response relationship. Mechanistic substrate question resolved.

Five closing criteria still unmet:

1. Quantitative metabolite–HRV mapping — metabolite concentration at which
   vagal afferent patterns show measurable deviation not yet defined
2. Microbiome diversity → metabolite output function — whether diversity loss
   or specific taxa loss is primary driver not yet characterized
3. Circuit-level threshold definition — enteric motor circuit excitability →
   detectable RSA/HRV alteration requires electrophysiology + HRV coupling
4. Human translational validation — animal model only; human confirmation
   required
5. Clinical decision boundary — diversity/metabolite threshold at which
   intervention becomes clinically actionable not established

Issue remains open. Closing criteria unchanged.

---

## Original Issue Set — Close-Out Status

*As of v1.1.1, all ~45 original structural and mechanistic issues have
been accounted for. The remaining open items represent empirical
confirmation gaps — predictions that are mechanistically complete and
require prospective or retrospective data assembly, not structural gaps
in the framework architecture.*

**Closed — contract formalized:**
STRUCT-001 (acute→chronic), GLYPH-AUTO-004, AUTO-MOD-009, COG-INTERO-002

**Confirmed-behavioral — mechanistic substrate triangulated:**
MOD-COG-001 (D2 direct measurement pending)

**Mechanism identified — quantitative threshold outstanding:**
MICRO-AUTO-007

**Carried forward as empirical priorities:**
Control Pause circadian variation, exhale completeness as rumination
predictor, kumbhaka × glymphatic clearance, ECS calibration during
suspension, spatial reference frame anchoring (Link 12 extension)

**Framework architecture status:**
No unaddressed structural gaps remain. New contracts from this point
forward represent refinement and extension of the architecture rather
than gap resolution.

---

## New Contracts Added — v1.1.0

**AUTO ↔ CARDIAC**
Terminal failure modes of the regulatory stack. Arrhythmia thresholds, sudden
cardiac death, Takotsubo, fear-induced collapse, sleep-transition arrhythmias.
The stack now has a formal endpoint.
Chain status: Load-bearing for established failure modes; ESLPM withdrawal
pathway scaffolding.

**COG ↔ REASON**
Reasoning as the output layer of the cognitive stack. Six fallacy groups mapped
to proximal precision mechanisms. Feedback loop — that expressed fallacious
reasoning tends to narrow the prediction window further — is the most
clinically important implication.
Chain status: Group mechanisms 1–6 scaffolding; feedback loop scaffolding with
strong mechanistic derivation.

**SLEEP ↔ COG / MOD / AUTO**
Sleep architecture as a distinct regulatory layer separate from glymphatic
clearance and circadian phase. SWS and REM stage proportions as the mechanism
of structured overnight reset.
Chain status: Links 2–3 load-bearing; links 1, 4–5 scaffolding approaching
load-bearing.

**STRESS ↔ TRANSITION**
Acute-to-chronic attractor formation onset mechanism. Physical discharge as
resolution pathway; incomplete discharge as the chronic sympathetic attractor
formation mechanism.
Chain status: Links 1 and 5 load-bearing; links 2–4 scaffolding with strong
empirical support.

---

## New Contracts Added — v1.1.1

**ANCHOR ↔ COG**
Convergence contract formalizing the compound mechanism by which respiratory
mechanics (AUTO↔MOD), bilateral proprioceptive confirmation (PROPRIO↔AUTO/COG),
and interoceptive clarity (COG↔INTERO) jointly determine prediction window
width. Exhale-gate dominance is the named failure state. Single-modality
intervention — breathwork alone, proprioceptive training alone, interoceptive
practice alone — cannot fully repair anchor failure when multiple inputs are
degraded. The intervention table maps directly to clinical recommendations.
Chain status: Link 1 load-bearing; Links 2–4 scaffolding with load-bearing
component mechanisms; Link 5 scaffolding.

**SOC ↔ ANCHOR**
Convergence contract describing the mechanism by which external oscillatory
sources — prosodic voice, group synchrony, music, ritual structure — widen
prediction windows from the outside when internal anchoring is degraded.
The only contract in the stack where the anchor input is externally generated.
ESLPM dependency state formalized as the architectural failure mode of external
anchor substituting for internal repair rather than scaffolding it. Identity
fusion, ideological rigidity, and attachment dependency are all derivable from
this contract without requiring separate psychological explanation.
Chain status: Links 1–2 scaffolding with load-bearing components via SOC↔AUTO
and PROPRIO↔AUTO/COG; Links 3–5 scaffolding.

**TEMPORAL ↔ COG**
Contract formalizing circadian phase as the temporal floor beneath which
neither anchor repair nor load reduction can reach. SCN phase sets the
precision-gain baseline for the cognitive layer on a 24-hour schedule,
establishing the ceiling within which ANCHOR↔COG operates moment-to-moment.
Phase misalignment produces trait-like cognitive rigidity phenotypically
identical to anchor collapse but requiring phase correction rather than anchor
repair as the primary intervention. The compound intervention architecture
across all three new contracts: phase correction first (TEMPORAL↔COG) →
anchor repair (ANCHOR↔COG) → load management (MOD↔COG, SOC↔COG).
Chain status: Links 1–2 load-bearing via MOD↔COG; Links 3–6 scaffolding —
mechanistically complete derivations requiring dedicated empirical assembly.

---

## Carried Forward — Open Items

**Spatial reference frame anchoring**
Contract: AUTO↔MOD (Link 12)
Status: Adjacent
No contract currently describes spatial reference frame anchoring as a distinct
mechanism. Sits between AUTO↔MOD, COG↔INTERO, and the proprioception structural
gap. Requires dedicated development as either a contract extension or a new
structural contract. GVS-as-anchor prediction (Prediction 17) is the testable
entry point.

**Exhale completeness as rumination predictor**
Contract: AUTO↔MOD (Link 8 extension, Prediction 16)
Status: Scaffolding
Incomplete exhale → compressed oscillation → recursive thinking chain is
mechanistically derivable. Direct measurement of exhale completeness alongside
rumination and cognitive flexibility in low vs high HRV populations not yet
done. Testable with respiratory belt or spirometry alongside cognitive
flexibility tasks and rumination scales.

**Control Pause circadian variation**
Contract: AUTO↔MOD
Status: Unresolved
Whether carotid body sensitivity varies across the 24-hour cycle in ways that
affect Control Pause and suspended state access at different circadian phases
is not characterized. Would have implications for optimal intervention timing
within the delayed phase ND profile.

**Kumbhaka × glymphatic clearance**
Contract: AUTO↔MOD × GLYPH↔AUTO
Status: Unresolved
During breath retention the respiratory CSF pulsatility component suspends
while arterial pulsatility continues. Net effect on glymphatic clearance during
extended external kumbhaka in trained practitioners is unknown. Testable with
phase-contrast MRI in trained practitioners during retention.

**ECS calibration during suspension**
Contract: AUTO↔MOD
Status: Genuinely unresolved
What the NTS and ECS system do when the oscillating carrier signal stops and a
fixed pressure set point is held. Highest-priority mechanistic gap in
AUTO↔MOD. CB2 receptor trial in freedivers may provide first data.

**Gap analysis files v7 and v8**
Status: Versioned snapshots — superseded by this document
Both stamped as current only through NOCI↔COG, GLYPH↔AUTO, and Temporal Layer
additions. Do not update retroactively. This v9 file is the current state.

---

## Notes on Framework Architecture

*Carried forward from v7 and v8 — still load-bearing:*

**Convergence contracts as a structural category:** NOCI↔COG and GLYPH↔AUTO
were the first identified convergence contracts — multiple upstream contracts
feeding a single output simultaneously. ANCHOR↔COG and SOC↔ANCHOR extend this
category at v1.1.1, confirming that convergence architecture is more common
than the original bilateral crossover model assumed. When identifying new gaps,
ask first whether the phenomenon is a bilateral crossover or a convergence
point — the structural difference determines whether a new contract or an
extension of existing contracts is the right treatment. Convergence contracts
are identifiable by two properties: multiple simultaneous upstream inputs, and
clinical resistance to single-modality intervention.

**The interoceptive attention amplification mechanism** identified in the ND
chronic pain clinical observation extends beyond pain. Any interoceptive channel
can be amplified through focal attention in ND profiles with higher baseline
interoceptive precision weighting. The defusion intervention — peripheral rather
than focal interoceptive awareness — may be transdiagnostically relevant across
all precision-weighting-dependent conditions.

**The empirical pass** should prioritize predictions where the data exists and
the reframing is the contribution. The framework's most immediate contribution
to existing literature is the reframing of known findings through the precision
weighting and pressure mechanics lens rather than new empirical claims. All
remaining open items are empirical confirmation gaps — the mechanistic
architecture is complete. Predictions are specified in enough detail to design
studies directly from the contract text.

---

*Gap analysis current as of: v1.1.1 release, June 2026. All original ~45
structural and mechanistic issues now accounted for. Four structural gaps
(pain, glymphatic, circadian, acute→chronic transition) formalized into
contracts. Bucket A close-outs: GLYPH-AUTO-004, AUTO-MOD-009, and
COG-INTERO-002 closed. MOD-COG-001 confirmed-behavioral, mechanistic substrate
triangulated — D2 direct measurement is the sole remaining close-out criterion.
MICRO-AUTO-007 mechanism identified, quantitative threshold criteria defined
and outstanding. Remaining open items are empirical confirmation gaps only —
no structural or mechanistic issues remain unaddressed. New contracts
(ANCHOR↔COG, SOC↔ANCHOR, TEMPORAL↔COG) added at v1.1.1 as convergence and
output layer extensions rather than gap resolutions.*
