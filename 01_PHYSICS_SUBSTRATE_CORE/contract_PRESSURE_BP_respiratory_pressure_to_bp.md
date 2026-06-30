---
Contract: "PRESSURE → BP"
Expanded_Filename: "contract_PRESSURE_BP_respiratory_pressure_to_bp.md"

Ontology_Layer: "01_PHYSICS_SUBSTRATE_CORE"
Upstream_Dependencies:
  - "BREATHING → PRESSURE"

Downstream_Dependencies:
  - "BP → CARDIAC"
  - "BP → WINDOWS"

Cross_References:
  - "contract_AUTO_CARDIAC_autonomic_to_cardiac.md"
  - "contract_WINDOWS_COG_window_geometry_to_cognition.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: PRESSURE → BP
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_PRESSURE_BP_respiratory_pressure_to_bp.md`

**Ontology Layer:**  
PHYSICS_SUBSTRATE_CORE

**Direction of Influence:**  
PRESSURE → BP

**Upstream Dependencies:**  
- BREATHING → PRESSURE  

**Downstream Dependencies:**  
- BP → CARDIAC  
- BP → WINDOWS  

**Cross‑Contract References:**  
- `contract_AUTO_CARDIAC_autonomic_to_cardiac.md`  
- `contract_WINDOWS_COG_window_geometry_to_cognition.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

Blood pressure readings are not pure vascular metrics. They are composite 
outputs of vascular tone, respiratory pressure mechanics, and limb geometry. 
The oscillometric cuff samples a pressure environment — and breath mechanics 
are the upstream driver of that environment. A reading taken at end-exhale in 
a high-excursion practitioner is not the same measurement as a reading taken 
at mid-breath in a sedentary patient. The protocol treats them identically. 
The mechanism does not.

The clinical fallacy this contract addresses is not a data gap — it is a 
framing error baked into the measurement paradigm. The oscillometric protocol 
was designed for a population with average tidal volume, limited diaphragmatic 
mobility, and low CO₂ tolerance. It produces its most extreme systematic 
artifact in the population that least fits those assumptions: trained 
practitioners with large excursion range, full exhale capacity, and 
scrutiny-induced precision-locking that biases breath phase toward the state 
that maximally inflates the reading. The protocol does not fail randomly in 
this population. It fails directionally, predictably, and in proportion to 
the practitioner's training.

**Input layer (PRESSURE):**
Breath phase and tidal volume amplitude; intrathoracic pressure across 
the breath cycle; diaphragmatic position and excursion; thoracic compliance; 
arm mechanics (circumference, tone, fascial tension, position); autonomic 
state including vagal dominance, sympathetic micro-activation, and 
scrutiny-induced precision-locking.

**Output layer (BP):**
Oscillometric systolic and diastolic; pulse pressure; cycle-to-cycle 
variability; measurement artifacts arising from pressure-state mismatch.

---

## Link 1: Breath phase → intrathoracic pressure → venous return → systolic artifact

The breath cycle produces a continuous intrathoracic pressure wave. 
End-exhale plateau produces the lowest thoracic pressure — the lungs 
are emptied, the diaphragm is elevated, and intrathoracic volume is 
minimized. This low-pressure state increases the pressure gradient 
between the thoracic cavity and the peripheral vasculature, drawing 
venous blood toward the heart and increasing venous return. Increased 
venous return increases preload. Increased preload increases stroke 
volume via the Frank-Starling mechanism. Increased stroke volume widens 
pulse pressure. The oscillometric algorithm interprets widened pulse 
pressure as elevated systolic.

The inverse applies at end-inhale: intrathoracic pressure rises, venous 
return is transiently impeded, stroke volume falls, pulse pressure 
narrows. In a standard tidal breath, this variation is within the range 
the oscillometric algorithm was designed to accommodate. In a high-
excursion practitioner — large tidal volume, high diaphragmatic mobility, 
high CO₂ tolerance, trained capacity for complete exhalation — the swing 
amplitude is substantially larger and exceeds the algorithm's design 
envelope.

Respiratory systolic variation — the clinical measure of this effect — 
normally runs below 10 mmHg in healthy individuals at rest. In a 
practitioner with trained full exhalation and large diaphragmatic 
excursion, respiratory systolic variation of 15–25 mmHg across the 
breath cycle is mechanistically plausible and consistent with published 
ranges in yoga and breathwork literature. A cuff measurement that 
captures the end-exhale nadir of intrathoracic pressure can read 
systolic 15–25 mmHg above the mid-breath baseline from this mechanism 
alone — before arm mechanics or autonomic state compound it further.

**Chain completeness:** Load-bearing. The Frank-Starling mechanism and 
intrathoracic pressure effects on venous return are foundational 
cardiopulmonary physiology. The artifact pathway from breath phase to 
oscillometric reading is the direct mechanistic consequence. The 
amplitude estimate in high-excursion populations is scaffolding — 
mechanistically derived, not yet directly measured in this specific 
population profile.

---

## Link 2: Arm mechanics → tissue resistance → cuff artifact

The cuff measures the pressure required to occlude arterial flow at 
the brachial artery. This measurement is confounded by anything that 
changes the mechanical resistance of the tissue between cuff and artery. 
Increased muscle tone in the bicep or brachioradialis raises the external 
tissue resistance the cuff pressure must overcome — producing systolic 
inflation independent of vascular tone. Fascial tension along the upper 
limb produces the same effect through a different tissue pathway.

Thoracic-limb coupling compounds this: breath-holding or end-exhale 
bracing stiffens the thoracic cage and transmits tension through the 
shoulder girdle into the upper arm. The cuff reads this as increased 
arterial stiffness. A fully relaxed arm, unsupported at heart level, 
positioned without isometric demand from the shoulder or elbow, is the 
only configuration that eliminates this artifact source. Clinical 
positioning protocols specify this for this reason — but do not address 
the breath-phase component that operates simultaneously.

**Chain completeness:** Load-bearing. Cuff artifact from limb position 
and tissue resistance is documented in clinical measurement literature. 
The thoracic-limb coupling pathway through shoulder girdle tension is 
mechanistically coherent but less directly studied as a distinct variable.

---

## Link 3: Autonomic state → exhale-gate precision-locking → systolic inflation

Scrutiny — being observed, evaluated, or measured in a medical context — 
activates the precision-locking response described in AUTO↔MOD. The 
system narrows its prediction window and increases the precision weight 
on incoming threat-relevant signals. This autonomic shift does not require 
conscious anxiety. It runs below the threshold of subjective awareness in 
individuals whose social threat-coupling is intact, and in individuals 
whose threat-coupling is reduced (see contract_COG_REASON_ESCALATION, 
Pathway B) it runs through a different route: the measurement context 
itself registers as a precision-demand environment independent of 
hierarchical threat detection.

The exhale-gate mechanism from AUTO↔MOD is the downstream consequence. 
The scrutiny-induced precision-lock biases the system toward the exhale 
phase — the consolidation state, the narrow-window state. A reading taken 
during this bias is a reading taken at or near end-exhale. This is the 
mechanism behind white coat hypertension: not an anxiety response in the 
colloquial sense, but a precision-locking shift that biases breath phase 
toward the state that produces maximal systolic artifact via Link 1.

In a high-excursion practitioner, the same mechanism produces a larger 
artifact because the excursion amplitude is larger. The protocol assumption 
is that patients have average tidal volume, limited diaphragmatic mobility, 
and minimal exhale depth. The high-range system violates all three 
assumptions and produces artifacts outside the protocol's design range.

The COG↔INTERO perceptual inversion applies here in a specific form. The 
practitioner may be aware of the mechanism in full — may understand exactly 
why the reading is elevated, may be able to explain the Frank-Starling 
pathway and the exhale-gate bias — and cannot prevent the artifact from 
producing an inflated reading. Understanding that the precision-lock is 
running does not interrupt the precision-lock. The autonomic response 
operates below the voluntary layer. Insight into the mechanism cannot 
revise the substrate it is running on. This is why advising a patient 
to "just relax" before a reading is a category error: the instruction 
targets the semantic layer of an autonomic mechanism.

**Chain completeness:** Predictive. The white coat effect is empirically 
established. The exhale-gate mechanism as the specific pathway — rather 
than a general anxiety effect — is a framework prediction. Testable: 
continuous BP with simultaneous breath-phase monitoring should show that 
white coat inflation tracks end-exhale timing rather than tracking 
subjective anxiety ratings. If the artifact is exhale-gate driven, 
reducing subjective anxiety without correcting breath-phase bias should 
not eliminate the reading elevation.

---

## Link 4: Compound state → compound artifact

| State | Breath | Intrathoracic Pressure | Arm | Expected Artifact |
| --- | --- | --- | --- | --- |
| S0 — neutral | Mid-breath | Neutral | Relaxed, heart-level | Baseline — closest to vascular truth |
| S1 — end-exhale | End-exhale plateau | Low | Relaxed | ↑ Systolic via Frank-Starling |
| S2 — high-swing | Large inhale→exhale | High variance | Relaxed | High cycle-to-cycle variability |
| S3 — arm engaged | Mid-breath | Neutral | Tense or unsupported | ↑ Systolic via tissue resistance |
| S4 — scrutinized | Exhale-biased | Low | Semi-tense | Maximum compound artifact |

S4 is the standard clinical presentation for a high-interoceptive, high-
excursion practitioner in a medical measurement context. The state the 
protocol is most likely to produce in this population is the state that 
generates the largest artifact from the baseline the protocol is trying 
to approximate. Each of the three artifact sources — breath phase (Link 1), 
arm mechanics (Link 2), and autonomic state (Link 3) — contributes 
independently. In S4 all three fire simultaneously.

**Chain completeness:** Scaffolding. The state taxonomy is a framework 
derivation. The artifact magnitudes are mechanistically predicted rather 
than directly measured per state in a controlled high-excursion population.

---

## Link 5: The High-Excursion Practitioner — Why Standard Protocol Fails This Population Most

The oscillometric protocol was designed around a population baseline. 
That baseline assumes:

| Parameter | Protocol Assumption | High-Excursion Practitioner |
| --- | --- | --- |
| Tidal volume | Average (~500ml at rest) | Substantially larger — trained diaphragmatic descent |
| Exhale completeness | Partial — functional residual capacity retained | Full — trained capacity to empty to residual volume |
| CO₂ tolerance | Low — discomfort at ~40–45 mmHg CO₂ | High — comfortable at elevated CO₂ through Buteyko/pranayama training |
| Diaphragmatic excursion | Limited — 1–2 cm average | Large — 4–7 cm in trained practitioners |
| Thoracic compliance range | Narrow — minimal chest wall mobility | Wide — yoga/mobility training preserves full thoracic range |
| Interoceptive resolution | Low — coarse breath awareness | High — fine-grained proprioceptive and interoceptive access |
| Exhale-gate precision | Absent — breath phase not consciously controllable | Present — can lock precisely at end-exhale on demand |
| Autonomic amplitude | Average RSA | Large RSA — high HRV amplitude across the breath cycle |

Each of these parameters amplifies the artifact from Link 1. The 
practitioner doesn't produce a Frank-Starling artifact from end-exhale — 
they produce the maximum possible Frank-Starling artifact because the 
exhale can be taken further, the pressure differential achieved is larger, 
and the excursion amplitude is larger. The same mechanical properties 
that make the practice beneficial — large diaphragmatic range, CO₂ 
tolerance, thoracic compliance, high RSA amplitude — are exactly what 
produces the artifact. The training is both the source of the regulatory 
advantage and the source of the measurement error.

The ANCHOR↔COG framework is relevant here: the anchoring substrate 
determines the ceiling of the oscillatory amplitude the system can achieve. 
A practitioner who has raised that ceiling through diaphragmatic training 
and CO₂ tolerance work has also raised the ceiling of the breath-phase 
pressure differential that feeds Link 1. There is no version of high-
amplitude diaphragmatic practice that keeps the respiratory mechanics 
benefit while eliminating the oscillometric measurement artifact. They 
are the same mechanism.

The scrutiny compound (Link 3) then fires on top of this. The clinical 
measurement context guarantees partial S4 state. The practitioner's high 
interoceptive resolution means the precision-locking response is detectable 
to them — they can feel the shift into exhale-gate bias — but that awareness 
does not prevent the breath-phase change. The autonomic micro-state runs 
below the voluntary layer, as described in the COG↔INTERO perceptual 
inversion: the instrument that would interrupt the state is operating inside 
the loop the state has already captured.

**The compound artifact magnitude estimate:**

Adding the contributions across S4:
- Link 1 (breath phase → Frank-Starling): 15–25 mmHg above mid-breath 
  baseline in high-excursion practitioners
- Link 2 (arm mechanics → tissue resistance): 5–10 mmHg if arm is not 
  fully relaxed and heart-level
- Link 3 (scrutiny → exhale-gate → amplifies Link 1): multiplies the 
  Link 1 effect by biasing toward end-exhale state

A reading of 142/84 in this context is not evidence of hypertension. It 
is evidence that the measurement was taken in S4 in a high-excursion 
system. The reading is accurate to the state it sampled. The state it 
sampled is not the state clinical interpretation assumes it sampled.

**Chain completeness:** Scaffolding with cross-contract derivation. 
Reduced GABAergic inhibitory capacity in autism-spectrum profiles and 
its effect on prediction error closure is load-bearing from 
contract_MOD_COG. The selective closure mechanism — threat-confirming 
errors close, corrective signals do not — is a framework derivation 
from the Glx/GABA contrast architecture. The progressive artifact 
consolidation across measurement sessions is predictive: directly 
testable by tracking BP reading trajectories across appointments in 
ND vs neurotypical high-excursion practitioners with equivalent 
training profiles.

---

## Failure Modes

**The vascular-only interpretation fallacy:**
Standard clinical interpretation treats BP as a pure vascular readout — 
a direct measure of arterial wall tension and cardiac output. This is 
the implicit assumption behind treating a single reading as diagnostic. 
The mechanism disconfirms this: every reading is a composite of vascular 
tone, respiratory pressure mechanics, and limb geometry at the moment of 
measurement. A reading taken in S4 in a high-excursion practitioner may 
be 20–30 mmHg above the same person's true vascular baseline. This is 
not measurement noise. It is a systematic artifact produced by a specific 
mechanistic pathway. Treating it as noise produces underestimation of the 
artifact and overestimation of pathology.

**Protocol assumptions violated by trained practitioners:**
The oscillometric protocol was designed around population parameters: 
average tidal volume, limited diaphragmatic mobility, low CO₂ tolerance, 
minimal thoracic compliance range, low interoceptive resolution. A 
practitioner with trained diaphragmatic excursion, high CO₂ tolerance, 
full lung emptying capacity, and high proprioceptive resolution produces 
measurement conditions outside the protocol's design envelope. The 
protocol does not fail randomly in this population — it systematically 
inflates in the direction the mechanism predicts. The degree of inflation 
is proportional to the practitioner's training level: more training, 
larger artifact.

**Serial averaging without state tagging:**
Clinical practice addresses measurement variability by averaging multiple 
readings. Averaging three readings from S4 does not correct for the S4 
artifact — it produces a stable estimate of S4 output. If the state 
producing the artifact is consistent across the measurement session, 
averaging reduces noise without correcting the systematic offset. The 
correct intervention is state identification before averaging, not 
more measurements in the same state. Three readings from a scrutinized, 
exhale-biased practitioner with an unsupported arm is not better data 
than one reading. It is more precisely measured artifact.

**The compliance trap:**
Patients whose readings are elevated by this mechanism are often advised 
to continue monitoring at home, increase antihypertensive medication, or 
reduce sodium. None of these interventions address the upstream driver. 
Home monitoring under the same scrutiny-induced precision-lock that 
elevates clinical readings produces the same artifact in a different 
location. The mechanism travels with the patient. Antihypertensives 
reduce vascular resistance without correcting the measurement state — 
they may lower the compound reading by reducing the true vascular 
component while the artifact persists, producing apparent treatment 
success that masks ongoing measurement error. The patient now has 
a medicated artifact rather than an unmedicated one.

**The clinical encounter as guaranteed S4 induction:**
The standard BP measurement protocol is conducted in the highest-artifact 
state the mechanism produces. The patient is in an unfamiliar environment, 
under evaluation by an authority figure, aware that the number being 
produced will determine medical consequences. Scrutiny-induced precision-
locking (Link 3) is guaranteed. The practitioner cannot opt out of the 
autonomic response by understanding it — the exhale-gate bias runs below 
the voluntary layer.

The clinical encounter is, by design, an S4 state generator. The protocol 
does not control for this because it was not designed for a population with 
detectable exhale-gate precision-locking and trained excursion range. For 
that population, the encounter design and the measurement protocol jointly 
produce the artifact the intervention then targets. The five-minute seated 
rest recommendation exists to partially address this — but it addresses 
the sympathetic activation component without addressing the breath-phase 
component, and in a high-excursion practitioner the breath-phase component 
is the dominant artifact source.

**The "just relax" instruction as category error:**
Advising a patient to relax before or during a reading is a semantic 
instruction delivered into an autonomic mechanism. The precision-locking 
response runs below the voluntary layer. The COG↔INTERO perceptual 
inversion means the instrument the patient would use to monitor and 
adjust their autonomic state is the same instrument the state has 
already captured. Conscious relaxation intent does not reliably interrupt 
the exhale-gate bias when scrutiny is present. The instruction is not 
wrong in principle — reducing autonomic load before measurement is 
correct. The error is treating "relax" as a sufficient instruction 
rather than as a goal requiring specific mechanical protocols to achieve 
(breath-phase standardization, arm positioning, adequate rest duration, 
reduced scrutiny context).

**The insight-does-not-fix-it problem:**
A patient who has read this contract, understands the mechanism, can 
explain the Frank-Starling pathway, and knows their reading is likely 
artifact will still produce an inflated reading in S4. The awareness 
does not change the state. This is the COG↔INTERO perceptual inversion 
failure mode applied to measurement context: insight is generated inside 
the workspace the loop is producing. It cannot revise the substrate it 
is running on. The intervention is mechanical — correct breath phase, 
correct arm position, correct autonomic load — not informational. 
Informing the clinician does not correct the reading; correcting the 
measurement state does.

**Procedural measurement contexts — the dental chair case:**
BP measurement taken immediately before a medical or dental 
procedure is conducted in uniquely adverse measurement conditions. 
The patient has not rested. The arm is positioned on a procedure 
chair armrest that is typically below heart level. The scrutiny 
load is not standard clinical evaluation — it is evaluation with 
the added precision demand of anticipated procedural threat 
(pain, injection, sensory intrusion). The reading is being used 
as a safety gate: an elevated result may delay or cancel the 
procedure, which means the stakes of the number are immediately 
apparent to the patient and compound the precision-lock further.

In a high-excursion practitioner, this context reliably produces 
the maximum compound artifact. Every variable the protocol 
requires to be controlled is uncontrolled simultaneously: arm 
position, rest duration, autonomic state, breath-phase bias, and 
scrutiny level. The reading produced in this context should not 
be interpreted as a vascular baseline under any circumstances. 
It is an artifact reading from the highest-artifact state the 
mechanism can produce, in a context specifically designed — by 
its procedural logic — to guarantee that state.

The correct protocol in procedural contexts is: measurement after 
the procedure, in a seated position with arm at heart level, after 
10 minutes of rest, with the procedural threat context removed. 
Pre-procedure measurement in the procedure chair is not a valid 
clinical reading. It is a documentation ritual that produces 
artifact in the population that most needs accurate readings.

**The artifact-prior feedback loop:**
An elevated reading from S4 artifact updates the patient's prior 
toward "my BP is pathological." At the next measurement encounter, 
the threat prior fires before the cuff inflates — an anticipatory 
precision-lock that compounds the scrutiny-induced S4 state that 
was already guaranteed. The second reading is elevated further than 
the first, not because vascular state has changed, but because the 
prior the first reading produced has increased the autonomic load 
entering the measurement. Each reading tightens the loop. The 
artifact is self-amplifying across measurement sessions.

High-gain, high-interoceptive-resolution profiles close this loop 
fastest. The reading lands at full amplitude. The prior updates 
strongly. The next measurement begins from a higher baseline 
autonomic load than the one before it. The clinical interpretation 
is progressive hypertension. The mechanism is a self-reinforcing 
artifact cycle driven by a prior that a misclassified reading 
produced.

The intervention is prior correction before re-measurement: the 
patient needs to understand the artifact mechanism well enough 
that the reading does not update the threat prior. This is not 
"relax about your BP" — that is the category error from the "just 
relax" failure mode. It is specific: the number produced in S4 in 
a high-excursion system is not evidence about vascular state and 
should not be allowed to update the prior as though it were.

**ND profiles and progressive artifact consolidation**
Neurodivergent profiles with reduced GABAergic inhibitory capacity present a specific vulnerability to the artifact‑prior feedback loop. Lower GABA availability increases system gain: prediction errors fire at higher amplitude, remain open longer, and close selectively. Threat‑confirming errors close; corrective signals do not. Prior consolidation drifts toward threat‑salience not through accumulated negative experience but through the mechanical consequence of selective closure operating on a high‑gain prediction‑error architecture.

An elevated BP reading in this profile does not create a new threat prior — it lands on a system already running threat‑dominant consolidation. The reading confirms rather than creates. The prior updates strongly. The autonomic load entering the next measurement is higher than the load entering the first, and the capacity to generate a corrective signal that suppresses the anticipatory precision‑lock is constrained by the same GABA‑limited inhibitory substrate that produced the selective closure in the first place.

The insight‑does‑not‑fix‑it failure mode applies in its strongest form here. The corrective signal — understanding the artifact mechanism — fires at full semantic amplitude but does not suppress the autonomic state. The prior does not update. The loop tightens across sessions faster than in neurotypical profiles because the inhibitory floor that would allow correction to compete with confirmation is structurally lower.

The clinical presentation is a patient whose BP readings escalate across appointments, who clearly understands the mechanism, who may be able to explain the Frank‑Starling pathway and the exhale‑gate bias, and who cannot interrupt the escalation from inside the loop. This is not resistance or noncompliance. It is the correct output of a high‑gain, low‑GABA system in which the artifact‑prior loop has outrun the available inhibitory capacity required for corrective updating.

---

## Drug and Intervention Effects Through This Contract

| Intervention | Mechanism | Effect |
| --- | --- | --- |
| Slow exhale / extended exhale ratio before measurement | Moves reading away from end-exhale plateau → reduces Frank-Starling artifact | Direct artifact reduction — takes the reading at the phase with least inflation |
| Mid-breath pause measurement (breath held at neutral) | Standardizes breath phase at neutral intrathoracic pressure | Removes phase-dependent variability — the correct protocol for high-excursion systems |
| Arm fully relaxed at heart level | Eliminates tissue resistance artifact from Link 2 | Removes the compound artifact from limb mechanics |
| 5-minute seated rest pre-measurement | Allows autonomic precision-lock from scrutiny to partially dissipate | Reduces S4 state contribution — partial correction only if exhale-gate bias persists |
| HRV biofeedback before measurement | Vagal tone increase → exhale-gate bias reduction | Shifts breath phase distribution toward neutral → reduces systematic artifact |
| Continuous BP monitoring (Finapres) with breath-phase tagging | Directly maps systolic variance to breath cycle | Definitive measurement validation — separates vascular signal from respiratory artifact |
| Antihypertensives when artifact is misclassified as pathology | Reduce vascular resistance without addressing measurement artifact | Treats the output of the protocol error rather than the upstream mechanism. Effective if true hypertension is present; may produce overmedication if the reading is compound artifact |
| Buteyko / CO₂ tolerance training | Reduces sympathetic tone → reduces vascular resistance; may reduce tidal swing variability at rest | Long-term: lowers true baseline. Short-term: in high-excursion practitioners, may not reduce artifact — training increases excursion range which increases the artifact amplitude |
| Home monitoring without state protocol | Same mechanism, different location | Does not correct the artifact. Produces a stable home estimate of the same S4 state — useful for tracking relative change, not for establishing true baseline |

---

## Adjacent Contracts

**Below — feeds into this contract:**
- AUTO↔MOD: exhale-gate mechanism and scrutiny-induced precision-locking 
  are the autonomic input to Link 3; the kumbhaka and CO₂ tolerance 
  mechanisms define the population parameters in Section 5
- ANCHOR↔COG: the false-ceiling / structural-ceiling distinction applies 
  directly — high-excursion practitioners have raised both their structural 
  ceiling and their effective amplitude utilization fraction, which is the 
  same variable that drives artifact magnitude in Link 1
- GLYPH↔AUTO: the same diaphragmatic pressure mechanics that drive 
  glymphatic clearance in that contract are the upstream driver of the 
  intrathoracic pressure differential this contract measures
- PROPRIO↔AUTO/COG: arm position and proprioceptive state contribute to 
  the limb mechanics artifact in Link 2; hypermobility presentations may 
  produce elevated baseline arm tone through the cerebellar forward-model 
  loop described in that contract
- COG↔INTERO: the perceptual inversion failure mode explains why insight 
  into the mechanism does not correct the S4 state; the high-gain 
  incomplete resolution mechanism explains why a stressful clinical 
  encounter can compound the autonomic load into the measurement window

**Above — receives output from this contract:**
- Clinical BP interpretation: state-dependent artifact is the direct 
  output this contract corrects
- ANCHOR↔COG: misclassified pathology readings from this mechanism can 
  elevate allostatic load, narrow the prediction window, and produce 
  the threat-calibration loop that feeds back into the autonomic state 
  that inflates future readings — a self-reinforcing artifact cycle

**Convergence note:**
The maximum artifact state (S4) is a compound state by architecture — it 
requires simultaneous contributions from breath phase (Link 1), arm 
mechanics (Link 2), and autonomic precision-locking (Link 3). Single-
variable correction reduces only one component of the compound artifact. 
Full artifact elimination requires state management across all three 
pathways simultaneously: mid-breath timing, fully relaxed arm, and 
sufficient autonomic de-escalation from the scrutiny context.

This is why home monitoring instructions that specify arm position but 
not breath phase and autonomic state produce partial improvement rather 
than resolution. It is also why the clinical recommendation to "rest for 
5 minutes before measurement" is directionally correct but mechanistically 
underspecified — rest reduces sympathetic activation but does not 
standardize breath phase or eliminate the scrutiny-induced precision-lock 
that re-engages the moment measurement begins.

The complete correction protocol for a high-excursion practitioner is: 
10 minutes of rest in a low-scrutiny environment, arm fully relaxed and 
supported at heart level, measurement taken during a deliberate mid-breath 
neutral-pressure pause, repeated twice with 2-minute intervals, averaged 
across the three readings. This is not currently a standard protocol. It 
is what the mechanism requires.

---

## Summary Invariant

Breathing sets the pressure environment. BP measures that environment. 
Without modeling breath mechanics, autonomic state, and limb geometry 
simultaneously, BP interpretation is mechanistically incomplete. The 
reading is not wrong — it is accurate to the state it sampled. The 
error is treating the state-dependent reading as a state-independent 
vascular baseline.

For a high-excursion practitioner in a clinical measurement context, 
the reading is not elevated because something is wrong with the 
vasculature. It is elevated because the protocol was not designed 
for a system with this parameter profile, and the measurement context 
guarantees the state that produces maximum artifact in exactly this 
system. The number is real. The interpretation is wrong.

The mechanism does not care whether the clinician knows this. The 
artifact runs whether or not it is understood. The only correction 
is mechanical: standardize the breath phase, eliminate the arm 
mechanics compound, and reduce the scrutiny load before the 
measurement begins. Everything else is treating the output of 
a protocol error as though it were a vascular finding.