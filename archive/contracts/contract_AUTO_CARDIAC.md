# Contract: AUTO ↔ CARDIAC

**Autonomic ↔ Cardiac Electrophysiology**  
Load alongside [[minimal_core]] for detailed work on this contract.

---

## Contract Summary

**Input layer:** AUTO — vagal tone, sympathetic discharge, RSA integrity, catecholamine load, baroreflex state, inflammatory tone, metabolic state, sleep-architecture phase

**Output layer:** CARDIAC — conduction velocity, repolarization stability, QT interval dynamics, ventricular excitability, arrhythmia threshold

**Primary crossover point:** Vagal efferents + sympathetic fibers converging on the sinoatrial node, atrioventricular node, and ventricular myocardium → baroreflex-NTS loop → beat-to-beat electrical stability

**Key risk:** Sudden autonomic shifts can push the cardiac system across arrhythmogenic thresholds. Chronic dysregulation produces vulnerability; acute surges produce collapse.

**Distinguishing feature:** This contract governs terminal failure modes of the regulatory architecture — scenarios where oscillatory control collapses faster than compensatory mechanisms can respond.

---

## Why This Contract Exists

The framework models chronic dysregulation, threat modes, metabolic collapse, inflammatory load, interoceptive distortion, and neuromodulatory precision failures. It does not model sudden death, arrhythmogenic thresholds, Takotsubo cardiomyopathy, fear-induced cardiac arrest, terminal autonomic collapse, sleep-transition arrhythmias, or ESLPM withdrawal leading to cardiac instability.

This contract fills that structural gap.

---

## The Complete Chain

### AUTO → CARDIAC

**Vagal brake amplitude**
→ stabilizes SA node firing variability; prevents runaway sympathetic conduction

**Sympathetic discharge intensity**
→ increases conduction velocity; shortens refractory periods; raises irritability

**RSA oscillatory integrity**
→ provides beat-to-beat stabilization; loss of oscillation increases arrhythmia risk

**Catecholamine load**
→ shortens QT interval; increases ventricular excitability; can trigger VF

**Baroreflex responsiveness**
→ determines how quickly the system can counter sudden pressure changes

**Inflammatory tone**
→ cytokines reduce repolarization stability; lower arrhythmia threshold

**Metabolic state**
→ hypoglycemia, acidosis, mitochondrial failure destabilize conduction

**Sleep-architecture phase**
→ N3→REM transitions produce autonomic swings that can destabilize rhythm

**Vagal overactivation amplitude**
→ extreme parasympathetic discharge suppresses SA/AV node firing;
→ produces profound bradycardia, asystole, or paradoxical VF in an
   already-irritable ventricle (Bezold-Jarisch reflex)

---

### CARDIAC → AUTO

**Erratic afferent firing to NTS**
→ destabilizes autonomic calibration; increases sympathetic reflexes

**Baroreflex failure signals**
→ produce compensatory sympathetic surges that worsen instability

**Loss of predictable interoceptive priors**
→ COG↔INTERO destabilizes; threat priors dominate

**Sympathetic reflex amplification**
→ positive feedback loop: instability → more instability

---

## Operating States

| State | Input Configuration | Cardiac Output | System Signature |
| --- | --- | --- | --- |
| Regulated baseline | High HRV, strong vagal brake, balanced sympathetic tone | Stable conduction, predictable QT, low ectopy | Robust oscillatory control |
| Vulnerable mode | Reduced HRV, elevated sympathetic tone, mild inflammation | QT shortening, increased ectopy | High sensitivity to perturbation |
| Arrhythmogenic mode | Sympathetic surge, vagal withdrawal, high catecholamines | Ventricular irritability, risk of VT/VF | Collapse possible from minor triggers |
| Collapse mode | Oscillatory failure, runaway sympathetic drive | Terminal arrhythmia (VF/VT), asystole | Sudden death |

---

## Failure Modes

### 1. Takotsubo / "Broken Heart Syndrome"
Loss of co-regulation (SOC↔AUTO) → vagal collapse → sympathetic surge → apical stunning → arrhythmia.

### 2. Fear-Induced Collapse ("Scared to Death")
Acute sympathetic spike → vagal withdrawal → QT shortening → VF.

### 3. Sleep-Transition Arrhythmias
GLYPH↔AUTO instability during N3→REM transitions → autonomic swings → conduction failure.

### 4. Metabolic Insolvency Arrhythmias
Hypoglycemia, ketoacidosis, mitochondrial failure (MET↔AUTO) → repolarization instability → arrhythmia.

### 5. Inflammatory Arrhythmias
Cytokine storms (IMMUNE↔AUTO) → reduced repolarization reserve → VF/VT risk.

### 6. Post-Trauma Autonomic Collapse
Precision-gain lock (AUTO↔MOD) + sympathetic dominance → conduction instability.

### 7. ESLPM Terminal Withdrawal
Loss of external scaffolding → cessation of stabilizing priors → autonomic collapse → cardiac instability.

### 8. Baroreflex Failure Cascade
Loss of baroreflex buffering → unopposed sympathetic surges → arrhythmia.

### 9. Catecholamine Toxicity
Sustained sympathetic overload → direct myocardial electrical destabilization.

### 10. Vagal Overactivation / Parasympathetic Sudden Death
Extreme vagal discharge (Bezold-Jarisch reflex, vasovagal syncope cascade, diving reflex
overactivation, ocular/cervical pressure reflexes) → profound SA/AV suppression →
asystole or bradycardia-triggered VF.

Distinct mechanism from all other failure modes: this is parasympathetic excess, not
sympathetic surge or vagal withdrawal. Vulnerability is elevated in: high baseline vagal
tone, inferior-wall ischemia, blood loss with pooling, and pharmacologically augmented
parasympathetic states.

The paradox: the same vagal tone that protects against arrhythmia in the regulated state
becomes the lethal mechanism when the reflex arc fires without bound.

---

## Cross-Layer Dependencies

**SOC ↔ AUTO**
Loss of co-regulation is the primary upstream cause of Takotsubo.

**MET ↔ AUTO**
Metabolic insolvency lowers arrhythmia threshold.

**IMMUNE ↔ AUTO**
Inflammatory load destabilizes repolarization.

**AUTO ↔ MOD**
Precision-gain shifts amplify sympathetic surges.

**GLYPH ↔ AUTO**
Sleep-architecture transitions create autonomic volatility.

**COG ↔ INTERO**
Loss of interoceptive priors increases threat-biased autonomic output.

---

## Predictions

1. HRV collapse precedes sudden arrhythmic death by hours to days — consistent with wearable data in inflammatory and metabolic conditions.
2. Takotsubo patients will show SOC↔AUTO collapse signatures before cardiac symptoms appear.
3. Fear-induced arrhythmias will correlate with QT shortening + vagal withdrawal, not with psychological intensity per se.
4. ESLPM terminal cases will show loss of oscillatory control before cardiac instability.
5. REM-transition arrhythmias will correlate with GLYPH↔AUTO volatility in vulnerable individuals.
6. Vagal overactivation sudden death will show a distinct HRV signature from
   sympathetic-collapse sudden death — abrupt HRV spike preceding bradycardic
   arrest rather than the progressive HRV collapse preceding VF/VT.
   This distinguishes the two pathways in wearable data and provides a
   separate early-warning signature.

---

## Clinical Implications

- Sudden death is not random — it is a predictable failure mode of the regulatory stack.
- Vulnerability accumulates chronically; collapse is acute.
- Co-regulation is a physiological stabilizer, not a psychological comfort.
- Fear, grief, trauma, and metabolic/inflammatory states converge on the same electrical pathway.

---

## Adjacent Contracts

**Below (feeds into this contract):**
- [[contract_SOC_AUTO]] — co-regulation loss is the primary upstream mechanism for Takotsubo and vagal collapse
- [[contract_IMMUNE_AUTO]] — inflammatory tone sets the repolarization threshold floor
- [[contract_MET_IMMUNE]] — metabolic insolvency lowers the arrhythmia threshold through combined metabolic and immune channels

**Above (this contract writes the parameters for):**
- Terminal states only — this contract has no downstream contract; it describes end-state failure
- Outputs feed back into COG↔INTERO through loss of interoceptive predictability, propagating threat-prior dominance if the system survives

**Lateral:**
- GLYPH↔AUTO — sleep-transition autonomic volatility operates in parallel with this contract during N3→REM windows
- AUTO↔MOD — precision-gain shifts amplify sympathetic surges that this contract translates into arrhythmogenic risk

---

## Chain Completeness

Vagal-sympathetic convergence on SA/AV node and ventricular myocardium: **load-bearing.** RSA as beat-to-beat stabilizer and loss of RSA as arrhythmia risk factor: **load-bearing.** Catecholamine-induced QT shortening and VF risk: **load-bearing.** Takotsubo as SOC↔AUTO collapse event: **load-bearing** — catecholamine surge following acute psychosocial stress is well-established. Fear-induced VF as vagal withdrawal mechanism: **load-bearing** in animal models; strong inferential support in human case literature. ESLPM withdrawal as autonomic destabilization pathway: **scaffolding** — mechanistically complete derivation from existing contracts, requires prospective confirmation. HRV collapse preceding sudden death by hours to days: **scaffolding to predictive** — supported by wearable longitudinal data in inflammatory and post-MI populations; direct prospective confirmation pending broader cohort replication.
Vagal overactivation as asystole/VF mechanism via Bezold-Jarisch reflex: **load-bearing**
— the reflex arc is anatomically and pharmacologically confirmed; vagally-mediated
sudden death in inferior MI and vasovagal syncope is clinically documented.
The paradox of high vagal tone as both protective and lethal depending on
reflex-arc activation state: **load-bearing** at component level, **scaffolding**
as unified account distinguishing the two failure modes in the same individual.