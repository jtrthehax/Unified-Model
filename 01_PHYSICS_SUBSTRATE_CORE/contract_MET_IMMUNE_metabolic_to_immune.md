---
Contract: "MET → IMMUNE"
Expanded_Filename: "contract_MET_IMMUNE_metabolic_to_immune.md"

Manifest:
  file: "unified_model_manifest.yml"
  optional: true
  role: "Global repository index and AI execution rules."

Ontology_Layer: "01_PHYSICS_SUBSTRATE_CORE"
Upstream_Dependencies:
  - "PRESSURE → MET"

Downstream_Dependencies:
  - "IMMUNE → AUTO"

Cross_References:
  - "contract_IMMUNE_AUTO_immune_to_autonomic.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: MET → IMMUNE
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_MET_IMMUNE_metabolic_to_immune.md`

**Ontology Layer:**  
PHYSICS_SUBSTRATE_CORE

**Direction of Influence:**  
MET → IMMUNE

**Upstream Dependencies:**  
- PRESSURE → MET  

**Downstream Dependencies:**  
- IMMUNE → AUTO  

**Cross‑Contract References:**  
- `contract_IMMUNE_AUTO_immune_to_autonomic.md`

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary


**Input layer:** MET — blood glucose level, insulin state, adipose tissue metabolism, mitochondrial function, fuel availability

**Output layer:** IMMUNE — mast cell activation state, macrophage polarization, cytokine production, inflammatory threshold sensitivity

**Primary crossover point:** Hyperglycemia → direct mast cell activation → TNF-α, IL-1, IL-6, IL-33 release → these cytokines both worsen insulin resistance AND further activate mast cells. The crossover point is bidirectional and self-reinforcing.

**Key risk:** The MET↔IMMUNE contract contains the most directly diet-responsive self-reinforcing loop in the entire stack. High glucose activates mast cells which produce cytokines which cause insulin resistance which raises glucose which further activates mast cells. The loop runs on dietary input and closes within hours of glucose exposure. Every processed, high-glycemic meal is a loop activation event.

**Distinguishing feature:** This is the contract that makes diet a regulatory systems problem rather than just a metabolic one. Sugar and ultra-processed food are not primarily problematic because of calories — they are problematic because they activate the immune layer, which then propagates inflammatory signal upward through IMMUNE↔AUTO into every contract above. The immune layer is the amplifier that turns dietary pattern into systemic regulatory dysfunction.

---

## Why This Contract Completes the Metabolic Architecture

The MET↔AUTO contract established that metabolic state drives autonomic balance through chemoreceptors. The MICRO↔AUTO contract established that microbiome dysbiosis raises the inflammatory noise floor on the vagal channel. The IMMUNE↔AUTO contract established that the cholinergic anti-inflammatory pathway governs immune activation through vagal tone.

This contract sits beneath all three — it is where dietary pattern translates into immune activation before reaching any of those contracts. High glucose → mast cell activation → cytokine release → IMMUNE↔AUTO contract receives inflammatory input → vagal tone compressed → every contract above degrades. The chain runs from what you ate to how well your brain works within hours.

---

## The Complete Chain — Both Directions

### MET → IMMUNE (Metabolic state drives immune activation):
```
Elevated blood glucose (hyperglycemia)
  → Direct mast cell activation
    (glucose-dependent ATP production required for mast cell function)
      → Rapid degranulation:
        Histamine, serotonin, proteases, heparin
      → Late phase cytokine synthesis:
        TNF-α, IL-1β, IL-6, IL-33, IL-6
          → Systemic inflammatory state
            → Macrophage M1 polarization in adipose tissue
              → Further TNF-α, IL-1β production
                → Insulin receptor signaling impaired (JNK/NF-κB activation)
                  → Insulin resistance worsened
                    → Further glucose elevation
```

### IMMUNE → MET (Immune activation drives metabolic dysfunction):
```
Pro-inflammatory cytokines (TNF-α, IL-1β, IL-6)
  → JNK and NF-κB pathway activation
    → Serine phosphorylation of insulin receptor substrate
      → Impaired insulin receptor signaling
        → Reduced glucose uptake by cells
          → Hyperglycemia maintained/worsened
            → Further mast cell activation
              → Loop closes and self-amplifies
```

---

## Link-by-Link Mechanism

### Link 1: High glucose directly activates mast cells
High glucose increases the expression of proinflammatory and proallergic cytokines, the secretion of TNF-α, and β-hexosaminidase activity in human mast cells. Hyperglycemia directly promotes the activation of human mast cells — this is a direct glucose-to-immune-activation pathway requiring no intermediary.

Mast cell activation requires glucose and ATP for both the rapid degranulation phase and the late cytokine synthesis phase. Glycolytic blockade suppresses inflammatory cytokine production in mast cells — confirming that glucose availability is the metabolic fuel for mast cell inflammatory function. More glucose available → more ATP → more mast cell activation capacity.

Mast cells are phylogenetically ancient innate immune sentinel cells residing in most connective and mucosal tissues, located in close proximity to the vasculature. They are positioned to respond immediately to changes in local glucose and metabolic state — this is not an incidental pathway, it is a metabolic sensing function of the innate immune system.

**Chain completeness:** Load-bearing. Direct glucose → mast cell activation → TNF-α, IL-6 production is mechanically confirmed in human mast cell studies.

---

### Link 2: Mast cells contribute to insulin resistance and metabolic syndrome
Mast cells contributed to diet-induced obesity by producing the inflammatory cytokines IL-6 and other mediators. Mast cells are part of the adipose tissue immune compartment — white adipose tissue contains mast cells, macrophages, T cells, and other immune cells that under obesity conditions contribute to a complex network of inflammation and insulin resistance.

Proinflammatory cytokines produced by mast cells and macrophages — particularly TNF-α — mediate insulin resistance. TNF-α is overexpressed in white adipose tissue from obese subjects, and lack of TNF-α or its receptor improves insulin sensitivity and glucose homeostasis. The immune cells in adipose tissue are not bystanders to metabolic dysfunction — they are active drivers of it through cytokine production.

Certain inflammatory cytokines including IL-1 and IL-33 not only are produced by mast cells but also activate them — creating a secondary autocrine amplification loop within the immune layer itself.

**Chain completeness:** Load-bearing. Mast cell contribution to diet-induced obesity and insulin resistance through TNF-α is mechanically documented.

---

### Link 3: Macrophage polarization as the metabolic-immune amplifier
The systemic nutritional status and acute increases in glucose metabolic flux impact macrophage polarization — shifting the M2 (anti-inflammatory) to M1 (pro-inflammatory) balance in metabolically stressed adipose tissue. M1 macrophages produce TNF-α and reactive oxygen species that worsen inflammation and further impair insulin signaling.

The M1/M2 balance is a dynamic equilibrium that glucose state directly influences. High glucose drives M1 polarization → more TNF-α → worse insulin resistance → higher glucose → more M1 polarization. This is a second self-reinforcing loop running in parallel with the mast cell loop, both feeding the same inflammatory output.

**Chain completeness:** Load-bearing. M1/M2 macrophage polarization driven by metabolic state and its consequences for insulin resistance are mechanically documented in immunometabolism literature.

---

### Link 4: Cytokines → insulin receptor impairment → hyperglycemia (IMMUNE→MET direction)
Enhanced macrophage infiltration and secretion of various inflammatory cytokines in white adipose tissue activate JNK and NF-κB, causing local and systemic insulin resistance. This is the molecular mechanism: TNF-α and IL-1β activate intracellular kinases (JNK, IKK) that phosphorylate the insulin receptor substrate at serine residues rather than the normal tyrosine residues — this serine phosphorylation inhibits downstream insulin signaling, blocking glucose uptake even when insulin is present.

The result: high cytokine environment → cells cannot respond to insulin despite insulin being present → glucose stays elevated in bloodstream → further immune activation. The IMMUNE→MET direction completes the loop. Insulin resistance is not primarily a pancreatic problem — it is an inflammatory problem whose origin is often in the immune layer dysregulation driven by dietary glucose load.

**Chain completeness:** Load-bearing. JNK/NF-κB mediated serine phosphorylation of insulin receptor substrate as the mechanism of cytokine-induced insulin resistance is mechanically established.

---

### Link 5: The ND-specific mast cell hyperreactivity
The MET↔IMMUNE contract sits beneath the ND regulatory profile in a specific way. Mast cell activation and sensitivity (MCAS) co-occurs with autism, ADHD, dysautonomia (POTS), and hypermobility (hEDS) at rates significantly above population baseline. The same connective tissue variation that affects breathing mechanics and proprioceptive input in ND profiles also affects mast cell density and distribution — connective tissue is where mast cells reside.

The comorbidity cluster is now well-documented. Approximately half of people with ADHD are hypermobile. The MCAS-EDS-dysautonomia trifecta has been extended to a septad including autism, ADHD, dyspraxia, dyslexia, and Tourette's — with connective tissue influencing mast cell behaviour and mast cells releasing substances that affect connective tissue bidirectionally. A case series of eight patients with neuropsychiatric disorders refractory to standard treatment — including ADHD, OCD, depression, anxiety, and panic — showed significant improvement when underlying MCAS was identified and treated with mast cell-directed therapy. This confirms the immune-to-cognitive chain running upward through IMMUNE↔AUTO→MOD→COG.

This means ND profiles often have a lower mast cell activation threshold — less glucose elevation required to trigger degranulation, lower environmental or dietary trigger threshold. The immune layer is pre-sensitized. The consequence: even moderate dietary glucose loads produce immune activation that in a lower-sensitivity profile would not occur. The energy rerouting from exploration to defense — immune activation consuming resources that would otherwise be available for cognitive and regulatory function — runs at lower trigger thresholds in ND populations.

This is why dietary management is disproportionately impactful for ND regulatory health. The MET↔IMMUNE contract has a lower activation threshold and produces larger upstream consequences per unit of glucose load.

**Chain completeness:** Approaching load-bearing. MCAS-ND comorbidity cluster is well-documented across autism, ADHD, and dyspraxia. Connective tissue → lower activation threshold is mechanistically confirmed. MCAS treatment improving refractory neuropsychiatric symptoms confirms the immune-cognitive chain. Specific glucose threshold in ND vs NT populations: still requires direct testing — the lower threshold is implied by the comorbidity pattern but needs quantitative confirmation.

---

## Operating States — Conditions Derivable From This Contract

| Condition | Contract Mechanism | Derivable? |
|---|---|---|
| **Type 2 diabetes** | MET→IMMUNE→MET loop fully established → progressive insulin resistance | Yes — inflammatory insulin resistance mechanism is mainstream |
| **Metabolic syndrome** | Multiple tissue compartments simultaneously in inflammatory-metabolic loop | Yes — same mechanism at larger scale |
| **MCAS in ND** | Low activation threshold + dietary triggers → high immune load → energy rerouted from exploration to defense | Yes — derived from ND-MCAS co-occurrence data |
| **Obesity** | Adipose tissue as immune organ → mast cells + macrophages driving inflammatory loop → systemic insulin resistance | Yes — adipose immunology is established |
| **Allergic disease** | Mast cell hyperreactivity sensitized by metabolic state | Yes — metabolic state modulates allergic threshold |
| **Type 3 diabetes (Alzheimer's)** | Chronic insulin resistance → brain glucose deprivation → neuroinflammation → amyloid pathology | Yes — insulin resistance-Alzheimer's mechanism confirmed |
| **Cardiovascular disease** | Inflammatory-metabolic loop → endothelial inflammation → atherosclerosis | Yes — inflammatory mechanism of CVD is established |
| **Post-meal cognitive fog** | Glucose spike → acute mast cell activation → histamine release → neuroinflammatory episode → transient cognitive impairment | Yes — mechanistically derivable, experientially common |
| **Sugar craving loop** | Mast cell activation → histamine → appetite stimulation → more sugar sought → more activation | Yes — histamine as appetite modulator is documented |

---

## Drug and Dietary Intervention Effects Through This Contract

| Intervention | Mechanism at this Contract | Effect |
|---|---|---|
| Ketogenic diet | Reduces glucose availability → less mast cell glycolytic fuel → higher activation threshold → less baseline immune activation | Direct contract reset through substrate removal |
| Low glycemic index diet | Flattens glucose curve → reduces peak mast cell activation events | Reduces loop trigger frequency |
| Metformin | AMPK activation → suppresses glycolysis in mast cells and macrophages → reduces inflammatory cytokine production | Anti-inflammatory through immune metabolic pathway — this is why metformin's benefits extend beyond glucose lowering |
| GLP-1 agonists | Improved glucose handling → reduced mast cell activation → reduced TNF-α → improved insulin sensitivity | Complementing the MET↔AUTO mechanism with direct immune-metabolic effect |
| Quercetin | Natural mast cell stabilizer → inhibits degranulation | Reduces acute mast cell activation without addressing underlying glucose drive |
| Cromolyn sodium | Mast cell stabilizer → reduces degranulation | Treats immune output rather than metabolic input |
| Elimination diet | Removes IgE/IgG-mediated mast cell trigger foods | Reduces parallel activation pathways without addressing glucose drive |
| Intermittent fasting | Extended glucose-low periods → mast cell activation threshold recovery → loop interruption | Periodic contract reset through substrate reduction |
| Anti-histamines | Block histamine receptor → reduce one output of mast cell activation | Downstream symptom management — does not address the loop |
| Exercise (acute) | Brief glucose consumption → mast cell activation → resolved through anti-inflammatory cytokine (IL-6 myokine) response | Acute loop activation followed by robust anti-inflammatory resolution — trains the loop's resolution capacity |

**The metformin insight:**
Metformin's benefits beyond glucose lowering — anti-inflammatory effects, cardiovascular protection, possible cognitive benefits — are explained by this contract. By activating AMPK and suppressing glycolysis in immune cells, metformin directly reduces the mast cell and macrophage inflammatory capacity that drives the IMMUNE→MET loop. The drug is doing two things simultaneously: reducing hepatic glucose output at the MET layer and reducing immune cell inflammatory output at the IMMUNE layer. Both effects target this contract from different sides.

**The post-meal cognitive fog mechanism:**
Glucose spike → acute mast cell activation → rapid histamine, serotonin, and cytokine release → transient neuroinflammatory episode → cognitive function degradation lasting 1-3 hours. This is mechanically derivable. The experiential phenomenon of post-meal cognitive fog is not metabolic sluggishness from digestion — it is a brief immune activation event propagating upward through the stack to degrade the MOD and COG layers.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing**
Blood glucose peak magnitude after meals should predict mast cell tryptase and histamine levels within 2-4 hours — directly measuring the MET→IMMUNE activation. The correlation should hold independently of total caloric load, isolating the glucose-specific immune activation pathway.

**Prediction 2 — Chain completeness: Scaffolding**
Dietary intervention reducing glycemic variability (low GI diet, ketogenic, time-restricted eating) should produce measurable reduction in baseline mast cell activation markers (tryptase, histamine, prostaglandins) independent of weight change — confirming that glucose is the primary activating input rather than adiposity per se.

**Prediction 3 — Chain completeness: Scaffolding**
ND individuals should show lower glucose threshold for detectable mast cell activation compared to neurotypical controls — directly testing the lower activation threshold prediction. This would establish the MET↔IMMUNE contract as a key mediator of ND-specific dietary sensitivity and provide mechanistic grounding for the observed dietary management benefits in ND populations.

**Prediction 4 — Chain completeness: Predictive**
Post-meal cognitive performance measures should track glucose-mast cell activation curves — cognitive impairment timing should lag glucose peak by 30-90 minutes, matching the mast cell degranulation and cytokine synthesis timeline. This would establish the dietary-cognitive chain across the MET→IMMUNE→AUTO→MOD→COG pathway as a directly measurable sequence.

**Prediction 5 — Chain completeness: Predictive**
Mast cell stabilizers (cromolyn, quercetin, ketotifen) should show cognitive performance benefits in populations with documented MCAS or high mast cell reactivity — not through direct cognitive mechanism but by interrupting the IMMUNE→AUTO→MOD→COG cascade. The cognitive benefit should appear on the same timescale as the anti-inflammatory effect.

---

## Failure Modes

**Treating insulin resistance as purely metabolic:**
The conventional view of insulin resistance focuses on pancreatic function, hepatic glucose production, and peripheral glucose uptake. The immune mechanism — TNF-α and IL-1β impairing insulin receptor signaling through JNK/NF-κB — is documented but not integrated into standard treatment protocols. Anti-inflammatory intervention alongside glucose management should produce better outcomes than glucose management alone, because the loop has two entry points being addressed simultaneously rather than one.

**Treating MCAS in ND without dietary component:**
MCAS is typically managed with antihistamines, mast cell stabilizers, and trigger avoidance. The MET↔IMMUNE contract predicts that dietary glucose management is as important as trigger avoidance because glucose is a direct mast cell activator regardless of IgE-mediated triggers. Managing MCAS without managing dietary glucose load is treating half the activation pathway.

**Missing the post-meal cognitive window:**
Cognitive-demanding work scheduled without regard to post-meal immune activation timing produces systematically worse outcomes during the peak activation window (roughly 1-3 hours post high-glycemic meal). Scheduling high-cognitive-demand work before meals or after the activation window has resolved — or eating in ways that flatten the glucose curve — is a direct application of this contract to productivity and cognitive performance that is essentially never applied systematically.

The mechanism is now named in peer-reviewed literature: "brain fog may be due to inflammatory molecules, including adipocytokines and histamine released from mast cells, further stimulating microglial activation and causing focal brain inflammation." More than 90% of mast cell disorder patients experience moderate to severe brain fog almost daily — the same ND-MCAS cluster where this contract predicts the highest impact. The timing study measuring cognitive impairment against the mast cell degranulation curve has not been run, but the mechanism is confirmed.

**The estrogen-histamine cross-contract interaction — clinical complication for ND women:**
The INTERO↔DEV contract confirms that high-estrogen phases open the plasticity window through perineuronal net dissolution. This contract identifies that estrogen also modulates mast cell activation threshold and histamine metabolism. In ND women with MCAS, these two effects co-occur in the same phase of the menstrual cycle — the plasticity window opens while mast cell reactivity may be simultaneously elevated. The net therapeutic access depends on which effect dominates. Neither contract currently accounts for this interaction in clinical planning. For ND women with MCAS, chronotherapy protocols derived from the estrogen-plasticity mechanism should be evaluated against their MCAS load before application.

---

## Adjacent Contracts

**Below this contract:**
- MET is the input layer — dietary pattern and metabolic state are the upstream drivers
- This contract represents the first immune amplification of metabolic dysfunction before it propagates through IMMUNE↔AUTO

**Above this contract feeds into:**
- IMMUNE ↔ AUTO: The cytokine output of this contract is the primary input to the cholinergic anti-inflammatory pathway contract — chronic MET↔IMMUNE loop activation continuously degrades vagal tone through the IMMUNE↔AUTO pathway
- MET ↔ AUTO: Glucose dysregulation from insulin resistance also directly hits the chemoreceptor pathway — both contracts are receiving signal from the same metabolic failure simultaneously

**The compound failure mode:**
When MET dysregulation is present, it typically hits both MET↔AUTO (through chemoreceptors) and MET↔IMMUNE (through mast cell activation) simultaneously. Both outputs converge on the AUTO layer from different directions — carotid body driving sympathetic activation from one side while cytokines compress vagal tone from the other. The compound effect on HRV and autonomic balance is substantially greater than either pathway alone. This is the mechanism of accelerated cardiovascular deterioration in metabolic syndrome — it's not one pathway but two converging on the same target.

**Lateral:**
- MICRO ↔ AUTO: Gut dysbiosis produces LPS that drives immune activation through a parallel pathway — the MICRO and MET contracts often co-dysregulate, creating compound immune load from two directions simultaneously
- INTERO ↔ DEV: Chronic early-life MET↔IMMUNE loop activation from dietary pattern during developmental windows may alter the immune calibration baseline written into the DEV contract — establishing a higher mast cell reactivity setpoint that persists lifelong

---

## Origin Note

This contract emerged from the sugar-as-regulatory-problem observation made throughout the framework's development. Sugar was identified early as raising the inflammatory noise floor and making it harder to read regulatory signals accurately. The question was: what is the specific mechanism? The answer required moving below the autonomic and microbiome contracts to find where dietary glucose first enters the immune system — and the answer is mast cells as direct glucose sensors producing immediate cytokine output.

The ND-MCAS connection was the minority invariant. Why do ND populations show disproportionate dietary sensitivity, disproportionate mast cell reactivity, and disproportionate benefit from dietary management? The answer from this contract: their lower mast cell activation threshold means the MET↔IMMUNE loop activates at glucose levels that would not trigger significant immune response in the general population. The regulatory system is running hotter immunologically per unit of dietary glucose, consuming proportionally more resources from the exploration-defense balance.

The post-meal cognitive fog derivation was a clean prediction from the contract — if glucose activates mast cells which release histamine and cytokines which propagate through IMMUNE↔AUTO into the cognitive stack, then cognitive impairment should follow glucose peaks with a predictable lag. The fact that this is universally experienced but rarely explained mechanistically is a characteristic example of the framework providing the missing connective tissue between a well-documented phenomenon and its mechanism.

*Chain status: Links 1-4 are load-bearing with mechanistic confirmation across multiple research streams. Link 5 (ND-specific threshold) is scaffolding requiring explicit empirical assembly. Compound failure mode (both MET↔AUTO and MET↔IMMUNE simultaneously) is a structural derivation. Post-meal cognitive fog prediction is predictive — mechanistically complete, not yet formally tested as a chain.*
