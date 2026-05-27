# Contract: MET ↔ AUTO
## Metabolic ↔ Autonomic
*Load alongside minimal_core.md for detailed work on this contract.*

---

## Contract Summary

**Input layer:** MET — fuel availability, glucose levels, CO2/O2 status, mitochondrial state, pH

**Output layer:** AUTO — sympathetic/parasympathetic balance, vagal tone, HRV

**Primary crossover point:** Carotid body chemoreceptors (peripheral) and hypothalamic glucoreceptors (central) — sensing metabolic state and translating it into autonomic drive via the NTS

**Key risk:** Shortcircuiting this contract produces chronic sympathetic dominance from metabolic dysfunction that presents as anxiety, cardiovascular disease, or autonomic dysregulation — treating the AUTO layer without addressing the MET layer produces partial and temporary relief

**Distinguishing feature:** This is the most explicitly bidirectional contract in the stack. AUTO feeds back into MET with equal mechanical force — autonomic state directly controls insulin secretion, hepatic glucose release, and metabolic rate. Neither direction is primary.

---

## Why This Contract Is Critical

This contract is the metabolic entry point to the entire regulatory stack. Dietary and metabolic dysfunction enters the regulatory system here first, before propagating upward through every contract above. It is also the contract where the most well-established modern metabolic epidemics — insulin resistance, metabolic syndrome, type 2 diabetes, obesity — are mechanistically located.

Critically: the bidirectionality creates self-reinforcing loops in both the healthy and dysregulated directions. A well-regulated metabolic state supports good vagal tone which supports good insulin secretion which supports metabolic stability. A dysregulated metabolic state drives sympathetic dominance which impairs insulin secretion which worsens metabolic regulation. Understanding which loop the system is in determines whether intervention at the MET or AUTO layer is more tractable.

---

## The Complete Chain — Both Directions

### MET → AUTO (Metabolic state drives autonomic output)

```
Blood glucose / CO2 / O2 / pH
  → Carotid body glomus cells (peripheral chemoreceptors)
    + Hypothalamic glucoreceptors (central chemoreceptors)
      → Carotid sinus nerve → NTS integration
        → Sympathetic nervous system activation
          (if metabolic stress: high glucose, hypoxia, hypercapnia)
        OR → Parasympathetic upregulation
          (if metabolic stability: normal glucose, normocapnia)
            → HRV / vagal tone shift
              → Downstream autonomic state
```

### AUTO → MET (Autonomic state drives metabolic output)

```
Vagal tone / parasympathetic drive
  → Efferent vagal fibers → pancreatic β cells
    → Glucose-stimulated insulin secretion (↑ with high vagal tone)
  → Efferent vagal fibers → liver
    → Hepatic glucose release (↓ with high vagal tone)
  → Hypothalamic autonomic circuits
    → Metabolic rate, appetite, energy allocation
      → Metabolic state
```

---

## Link-by-Link Mechanism

### Link 1: Metabolic state → Carotid body activation
The carotid bodies are peripheral chemoreceptors located at the bifurcation of the common carotid artery. They classically sense arterial O2, CO2, and pH. Critically — they are also metabolic sensors for glucose. Hypercaloric diets cause carotid body overactivation in animal models, which appears to be at the origin of insulin resistance and hypertension, core features of metabolic syndrome and type 2 diabetes. Carotid sinus nerve activity feeds into the NTS to induce autonomic and cardiorespiratory responses.

Insulin itself activates carotid chemoreceptors — even small increases in plasma insulin have marked sympathoexcitatory effects through this pathway. High glucose → high insulin → carotid body activation → sympathetic drive → further autonomic dysregulation. The metabolic and autonomic loops are coupled at this single anatomical structure.

**Chain completeness:** Load-bearing. Carotid body anatomy, chemosensitivity, and metabolic sensing are mechanically documented. The insulin-carotid body-sympathetic chain is confirmed in both animal models and humans.

---

### Link 2: NTS integration → Autonomic output
Carotid sinus nerve activity is integrated in the NTS — the same brainstem structure that receives vagal afferent input from the gut, heart, and lungs. The NTS is the convergence point where metabolic and autonomic signals are processed together. From the NTS, output drives sympathetic activation (via the rostral ventrolateral medulla) or parasympathetic modulation (via the DMV). This is the same NTS that sits at the AUTO ↔ MOD crossover — metabolic dysfunction and autonomic dysregulation converge at the same anatomical hub.

**Chain completeness:** Load-bearing. NTS anatomy and its role in autonomic output are foundational neuroscience.

---

### Link 3: Vagal tone → Insulin secretion (AUTO → MET direction)
The vagus nerve bidirectionally connects the CNS with the pancreas, liver, and gut — presenting a key pathway for central control of blood glucose. Efferent vagal activity directed to the islets of Langerhans stimulates insulin secretion under hyperglycemic conditions and glucagon secretion under hypoglycemic conditions. This context-sensitivity is important — the vagal signal is not simply "more insulin" but "appropriate response given current glucose level." High vagal tone supports accurate, context-appropriate insulin response. Low vagal tone impairs this sensitivity.

Vagal stimulation also inhibits hepatic glucose release — meaning the vagus simultaneously increases insulin secretion AND reduces the liver's glucose output, working both sides of the glucose equation.

**Chain completeness:** Load-bearing. Vagal innervation of pancreatic β cells and the functional consequences for insulin secretion are mechanically documented across multiple experimental approaches including optogenetic confirmation.

---

### Link 4: Sympathetic activation → Metabolic dysregulation loop
Sympathetic activation, in concert with parasympathetic withdrawal, is a major contributor to the development of metabolic disorders and an important mediator of associated cardiovascular consequences. The mechanism: sympathetic dominance → reduced vagal tone → impaired insulin secretion → glucose dysregulation → further carotid body activation → more sympathetic drive. The loop is self-reinforcing once established.

This is the mechanism by which chronic psychological stress produces metabolic disease — not through direct tissue damage but through sustained autonomic state change that degrades the metabolic regulatory capacity through this contract.

**Chain completeness:** Load-bearing. Sympathetic overactivity as contributor to metabolic syndrome is established. The specific loop mechanism is scaffolding — the individual links are documented, the self-reinforcing nature is mechanistically derivable but requires explicit longitudinal confirmation.

---

### Link 5: HRV biofeedback → Glucose metabolism (full bidirectional validation)
Resonant frequency breathing maximizes HRV through rhythmization of breathing, heartbeat, and blood pressure — upregulating parasympathetic activity and suppressing sympathetic activity. This shifts ANS sympathovagal balance. The hypothesis under clinical trial: this shift improves glucose metabolism in prediabetes through the vagal → insulin secretion pathway. This study is the explicit clinical test of the full bidirectional chain — breathing changes HRV changes autonomic balance changes glucose metabolism.

**Chain completeness:** Scaffolding → moving toward load-bearing. The mechanistic chain is complete. Clinical validation in humans is in progress.

---

## Operating States

| State | MET Input | AUTO Output | Loop Direction | Clinical Signature |
|---|---|---|---|---|
| **Regulated** | Stable glucose, normal CO2 | Balanced HRV, high vagal tone | Virtuous — each layer supports the other | Normal metabolism, good cardiovascular function |
| **Post-meal parasympathetic** | Elevated glucose, nutrient sensing | Vagal increase, "rest and digest" | Normal — AUTO responds to MET appropriately | Post-meal calm, digestion active, insulin releasing |
| **Insulin resistant** | High chronic glucose, CB overactivation | Sympathetic dominant, low HRV | Vicious — high glucose drives sympathetic, which impairs insulin, which worsens glucose | Metabolic syndrome, anxiety, cardiovascular risk |
| **Chronic stress** | Normal diet but sustained sympathetic input | Low vagal tone, impaired insulin secretion | Vicious — stress alone degrades metabolic regulation | Normal diet, worsening glucose tolerance, unexplained weight gain |
| **Hypoglycemic** | Low glucose | Sympathetic emergency activation | Compensatory — system trying to restore glucose | Anxiety, tremor, urgency — identical to threat response |
| **Post-exercise** | Depleted glucose, elevated CO2/lactate | Initial sympathetic, then parasympathetic recovery | Adaptive — stress then restoration | HRV dip then recovery, metabolic recalibration |

---

## Drug Effects Through This Contract

| Substance/Intervention | Mechanism at this Contract | Effect |
|---|---|---|
| GLP-1 agonists (Ozempic, Wegovy) | Central GLP-1R activation produces sympathoexcitation — HR increases, HRV decreases. Cardiovascular benefits operate through anti-inflammatory and endothelial mechanisms, not vagal restoration. Carotid body inhibition confirmed in animal models but does not dominate the clinical autonomic picture | **Revised from original claim.** Clinical and wearable data show HR increase and HRV decrease with GLP-1 RA use. The cardiovascular benefits are real and substantial but the mechanism is not the autonomic rebalancing originally predicted. Cravings reduction likely operates through hypothalamic GLP-1R effects on appetite circuits, not through CAP restoration |
| Metformin | Reduces hepatic glucose output → less chronic CB stimulation → modest sympathetic reduction | Gentle autonomic improvement as secondary effect |
| Caffeine | Adenosine blockade → sympathetic activation → CB sensitization → glucose mobilization | Masks MET fuel depletion signal, temporarily restores sympathetic tone without fixing underlying fuel state |
| Stimulants (chronic) | Sustained sympathetic activation → reduced vagal tone → impaired insulin secretion | Can worsen glucose regulation with chronic use despite short-term performance enhancement |
| Alcohol | Blocks gluconeogenesis → hypoglycemia risk → sympathetic emergency activation → HRV disruption | Directly disrupts MET→AUTO signal accuracy |
| HRV biofeedback | Breathing rhythm → RSA → vagal tone increase → insulin secretion improvement | Full chain intervention targeting the AUTO→MET direction |
| Ketogenic diet | Reduces glucose dependence → less CB glucose stimulation → reduced insulin demand → lower sympathetic drive from glucose dysregulation | Metabolic state stabilization reduces CB overactivation |

**The GLP-1 mechanism — revised:**
The dramatic cardiovascular benefits of GLP-1 agonists — reducing heart attack and stroke risk beyond what glucose control alone would predict — are real and confirmed. The original framework prediction attributed this to carotid body inhibition restoring vagal tone. Clinical and wearable data contradict this: GLP-1 RA use produces HR increase and HRV decrease in humans, indicating net sympathoexcitation rather than vagal restoration.

The cardiovascular benefits likely operate through anti-inflammatory and endothelial mechanisms — GLP-1 receptors are expressed on immune cells and endothelium — rather than through the MET↔AUTO autonomic chain originally proposed. The carotid body inhibition mechanism may be valid in animal models at specific doses but does not dominate the clinical autonomic picture in humans.

This is a genuine correction of a framework prediction that was mechanistically plausible but directionally wrong on the autonomic effect. The cardiovascular benefits exceeding glucose control alone remain confirmed. The mechanism requires a different explanation than originally stated. Cravings reduction likely operates through hypothalamic GLP-1R effects on appetite and reward circuits rather than through CAP restoration.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing**
Carotid body denervation or pharmacological inhibition should produce measurable improvement in both autonomic balance (HRV increase) and metabolic regulation (insulin sensitivity) simultaneously and rapidly — before any weight loss or dietary change. This prediction is already partially confirmed in animal models and is the basis for carotid body as a therapeutic target in metabolic syndrome.

**Prediction 2 — Chain completeness: Scaffolding**
HRV measured before dietary intervention should predict the magnitude of metabolic response to that intervention. Higher baseline vagal tone should predict faster and more complete glucose normalization — because the AUTO→MET direction of the contract is more functional.

**Prediction 3 — Chain completeness: Scaffolding**
Psychological stress interventions (that demonstrably improve HRV) should produce lagged but measurable improvement in glucose tolerance even without dietary change. The lag time reflects the time required for restored vagal tone to rebuild insulin secretory capacity.

**Prediction 4 — Chain completeness: Predictive**
ND populations with documented autonomic dysregulation and low baseline HRV should show higher rates of glucose dysregulation than would be predicted by diet alone — because their chronic autonomic state is impairing the AUTO→MET direction of this contract continuously.

**Prediction 5 — Chain completeness: Predictive**
The timing of meals relative to circadian phase should interact with this contract — parasympathetic tone peaks at specific circadian phases (generally daytime), meaning glucose tolerance is better during high-vagal-tone windows. Eating outside those windows should produce measurable metabolic differences even with identical food. This is partially confirmed by chronobiology literature on breakfast vs late eating.

---

## Failure Modes

**Treating anxiety as psychological when it is metabolic:**
Hypoglycemia produces an autonomic emergency response — sympathetic activation, cortisol release, adrenaline — that is physiologically identical to a threat response. Many presentations of anxiety, panic, and irritability are hypoglycemic events misread as psychological. The MET→AUTO chain is producing the signal correctly; the interpretation layer is attributing it to the wrong cause.

**Treating metabolic syndrome as a diet problem:**
If the MET↔AUTO contract is in a vicious loop, dietary intervention alone is insufficient — the autonomic dysregulation continues to impair insulin secretion regardless of glucose intake reduction. Both sides of the contract require simultaneous intervention. Treating diet without addressing autonomic state produces slower response and high relapse rates.

**The stress-metabolism split in medical practice:**
Cardiology, endocrinology, and psychiatry each own a piece of this contract without owning the contract itself. The patient with metabolic syndrome, anxiety, and cardiovascular risk is a single regulatory failure distributed across three specialties, each treating their visible output without seeing the shared mechanism.

---

## Adjacent Contracts

**Below (feeds into this contract):**
- MET ↔ IMMUNE: Glucose dysregulation → mast cell activation → inflammation → autonomic disruption arrives here as further sympathetic pressure
- MICRO ↔ AUTO: Microbiome-derived metabolites and SCFAs affect glucose regulation and insulin sensitivity — microbiome dysfunction amplifies MET layer dysregulation

**Above (fed by this contract):**
- AUTO ↔ MOD: Autonomic state output here becomes the primary input for ECS tone and precision gain calibration
- IMMUNE ↔ AUTO: The autonomic output here modulates the cholinergic anti-inflammatory pathway — low vagal tone removes the brake on inflammation

**Lateral:**
- Circadian rhythm: Sets the amplitude of parasympathetic tone across the 24-hour cycle — this contract's AUTO→MET direction is strongest during peak parasympathetic phase. Meal timing, exercise timing, and sleep all interact with this envelope.

---

## Key Unresolved Links

1. **Carotid body glucose sensing specificity:** The mechanism by which carotid body glomus cells sense glucose (vs O2/CO2) is not fully characterized. Whether glucose sensing is direct or mediated through local metabolic changes (lactate, pH) requires further work. This matters for whether dietary glucose or total metabolic load is the primary activating signal.

2. **Quantitative HRV threshold for insulin secretion impairment:** At what HRV level does vagal tone become insufficient to support normal insulin secretion? The directional relationship is established but the clinical threshold is not defined. This is the link needed to make HRV a clinically actionable metabolic biomarker.

3. **Reversibility timeline:** How quickly does restored vagal tone (through breathing intervention or VNS) produce measurable improvement in insulin secretory capacity? The human clinical trial data is emerging but not yet conclusive on timescales.

---

## Origin Note

This contract emerged from the glucose-brain-anxiety connection early in the framework's development. The key insight was that hypoglycemia produces an autonomic emergency response physiologically identical to threat — meaning the MET→AUTO direction was directly generating what appeared to be psychological symptoms. The bidirectionality — that autonomic state also controls insulin secretion — was derived from the architecture before being confirmed in the literature.

The GLP-1 agonist explanation (cardiovascular benefits via carotid body inhibition rather than purely glucose control) was derived from the model and subsequently confirmed as the actual proposed mechanism in the pharmacological literature.

*Chain status: Partially load-bearing. MET→AUTO direction (Links 1-2) is mechanically solid. AUTO→MET direction (Link 3) is load-bearing. Self-reinforcing loop (Link 4) is scaffolding. Clinical intervention chain (Link 5) moving toward load-bearing.*
