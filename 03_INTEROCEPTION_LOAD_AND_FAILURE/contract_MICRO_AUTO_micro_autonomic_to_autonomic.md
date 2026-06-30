---
Contract: "MICRO → AUTO"
Expanded_Filename: "contract_MICRO_AUTO_micro_autonomic_to_autonomic.md"

Ontology_Layer: "03_INTEROCEPTION_LOAD_AND_FAILURE"
Upstream_Dependencies:
  - "LOAD → MICRO"

Downstream_Dependencies:
  - "AUTO → MOD"
  - "AUTO → CARDIAC"

Cross_References:
  - "contract_AUTO_MOD_autonomic_to_modulation.md"
  - "contract_AUTO_CARDIAC_autonomic_to_cardiac.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: MICRO → AUTO
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_MICRO_AUTO_micro_autonomic_to_autonomic.md`

**Ontology Layer:**  
INTEROCEPTION_LOAD_AND_FAILURE

**Direction of Influence:**  
MICRO → AUTO

**Upstream Dependencies:**  
- LOAD → MICRO  

**Downstream Dependencies:**  
- AUTO → MOD  
- AUTO → CARDIAC  

**Cross‑Contract References:**  
- `contract_AUTO_MOD_autonomic_to_modulation.md`  
- `contract_AUTO_CARDIAC_autonomic_to_cardiac.md`

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

**Input layer:** MICRO — gut microbiome composition, microbial metabolite production, gut epithelial integrity, enteroendocrine cell signaling

**Output layer:** AUTO — sympathetic/parasympathetic balance, vagal tone, HRV, central autonomic regulation

**Primary crossover point:** Vagal afferent fibers in the gut wall sensing microbial metabolites (primarily SCFAs) via enteroendocrine cells and direct terminal receptors → NTS → central autonomic network

**Key risk:** Shortcircuiting this contract produces autonomic dysregulation sourced from the gut that presents as cardiovascular, psychiatric, or cognitive dysfunction — treating the AUTO layer without addressing microbiome composition produces partial and unstable improvement

**Distinguishing feature:** This contract has the highest signal/noise ratio implication in the stack. A healthy microbiome produces clean SCFA signal on the vagal channel. A dysbiotic microbiome simultaneously reduces signal quality (less SCFA) and raises the noise floor (more LPS, more inflammatory cytokines). Both effects compound — the channel degrades in both directions simultaneously.

---

## Why This Contract Matters

The gut contains more neurons than the spinal cord. Ninety percent of the body's serotonin is produced in the gut. The vagus nerve runs through the gut wall and samples its chemical environment continuously. This is not a peripheral system sending occasional status updates — it is a primary regulatory input channel running in real time.

The microbiome modulates this channel constantly through its metabolite output. Change the microbiome composition and you change what the vagus is reading, which changes what the brain believes about body state, which changes autonomic output, which changes every contract above this one. Sugar and processed food don't just cause metabolic problems — they degrade the primary regulatory sensing channel the entire stack depends on.

---

## The Complete Chain — Both Directions

### MICRO → AUTO (Microbiome drives autonomic output)

```
Dietary fiber fermentation by gut bacteria
  → SCFA production (butyrate, acetate, propionate)
    → Two parallel pathways to vagal afferents:
    
    PATH A (Indirect via EECs):
      SCFAs bind FFAR2/FFAR3 receptors on enteroendocrine cells
        → EECs release serotonin, GLP-1, PYY, CCK
          → These mediators activate vagal afferent receptors
            → OR: EECs form direct synaptic neuropod connections
              to vagal afferent fibers
    
    PATH B (Direct):
      Butyrate acts directly on vagal afferent terminals
        → Vagal afferent firing
    
    → Both paths → NTS integration
      → Parasympathetic upregulation / HRV increase
        → Autonomic balance improvement

PARALLEL SIGNAL (Danger pathway):
Gram-negative bacteria → LPS production
  → Gut permeability ↑ (dysbiosis → leaky gut)
    → LPS activates TLR4 on vagal afferent fibers
      → Inflammatory signaling to NTS
        → Sympathetic activation
          → HRV compression
```

### AUTO → MICRO (Autonomic state drives microbiome)

```
Vagal efferent activity
  → Gut motility regulation
    → Transit time → selective microbial growth conditions
  → Gut secretion (mucus, digestive enzymes, bile)
    → Epithelial barrier integrity
  → Enteric immune modulation
    → Inflammatory vs tolerogenic gut environment
      → Microbiome composition shift
```

---

## Link-by-Link Mechanism

### Link 1: Microbial fermentation → SCFA production
Gut bacteria ferment dietary fiber into short-chain fatty acids — primarily butyrate, acetate, and propionate. These are the primary molecular currency of the microbiome's communication with the autonomic nervous system. SCFA production is directly dependent on microbiome diversity and dietary fiber availability. A low-fiber, high-sugar diet starves SCFA-producing bacteria while feeding inflammatory species — simultaneously reducing signal and raising noise.

SCFA-producing bacteria include Firmicutes (especially Ruminococcaceae and Lachnospiraceae), Bacteroidetes, and Bifidobacterium species. These are exactly the species supported by fermented foods — kimchi, kefir, kombucha, miso — and depleted by antibiotics, processed food, and sugar.

**Chain completeness:** Load-bearing. SCFA production by gut bacteria and the dietary inputs that support or degrade it are mechanically established.

---

### Link 2: Two parallel gut-to-brain channels — fast and slow — plus the danger pathway
The gut sends two parallel and distinct signal streams to the NTS simultaneously. They carry different information at different timescales. Understanding them as one channel was the original framework's incomplete picture.

**Fast path — neuropod glutamatergic (milliseconds):**
Enteroendocrine cells form direct synaptic connections with vagal nodose neurons — neuropod cells, discovered by Bohórquez lab (2018, Science). These electrically excitable cells use glutamate as neurotransmitter to transduce gut luminal signals in milliseconds. Optogenetic activation of neuropod cells elicits excitatory postsynaptic potentials in connected vagal neurons within milliseconds. In vivo recordings confirm neuropod cells are necessary and sufficient to transduce sugar stimulus to the vagus. Rabies tracing shows the circuit is one synapse from gut lumen to NTS brainstem. Neuropod cells distinguish sugars from artificial sweeteners using SGLT1 — confirming real-time food quality detection. Optogenetic inhibition of the CCK+ neuropod circuit eliminates sugar preference in vivo — the circuit is behaviorally necessary, not redundant.

Signal content: real-time nutrient quality detection. What is being eaten, right now, with millisecond precision.

**Slow path — hormonal (minutes):**
SCFAs bind to free fatty acid receptors (FFAR2/FFAR3, also known as GPR43/GPR41) on enteroendocrine cells. These cells release serotonin, GLP-1, PYY, and CCK in response. These mediators act on receptors in vagal afferent nerve endings through the bloodstream. Neuropod cells contain both large dense-core neuropeptide vesicles (CCK, secretin, serotonin) and small synaptic vesicles (glutamate) — the fast path uses glutamate while the slow path uses neuropeptides co-released into circulation.

Direct path for butyrate: Butyrate activates vagal afferent terminals without requiring EEC intermediary through TRPV1 and other channels. This is the SCFA regulatory signaling path distinct from the neuropod nutrient detection path.

Signal content: regulatory state — satiety, metabolic load, microbiome health via SCFA levels.

**The two-channel architecture:**
Fast and slow paths are not redundant. They carry different information. The fast neuropod path tells the brain what is being eaten now. The slow hormonal path tells the brain the regulatory consequences of what has been eaten. Both terminate at NTS. The original contract described only the slow path. The fast path is a confirmed additional channel that was absent from the framework's description.

Implication for dietary change: because the fast neuropod path detects food quality in real time, dietary shifts produce NTS signal changes within milliseconds of eating — before any metabolic or hormonal effect has time to occur. The brain knows what you ate before digestion begins. This is the mechanism behind immediate cravings changes from dietary composition shifts that are too fast to be explained by metabolic pathways.

**Danger pathway (LPS):** TLR4 receptors are expressed directly on vagal afferent fibers. LPS from gram-negative bacteria floods into the bloodstream through a leaky gut wall, activates these receptors, and transmits inflammatory danger signals to NTS. This raises the noise floor on both channels simultaneously — dysbiosis reduces SCFA signal amplitude and raises LPS noise, degrading signal-to-noise ratio in both directions.

**Chain completeness:** Fast neuropod path: load-bearing, confirmed in Science (2018), replicated with optogenetics and rabies tracing. Signal content distinction (glutamate fast vs. neuropeptide slow): load-bearing. Slow hormonal path: load-bearing. Butyrate direct TRPV1 activation: load-bearing. LPS danger pathway: load-bearing. Whether SCFAs use fast or slow path preferentially: the fast path sugar sensing is confirmed; SCFA sensing via fast neuropod path specifically remains inferential.

---

### Link 3: NTS integration → Autonomic output
Microbiome signals converge at the NTS — the same brainstem hub as the MET↔AUTO and AUTO↔MOD contracts. Vagal afferent inputs from the gut join inputs from the heart, lungs, carotid body, and other viscera at the NTS, where they are integrated into central autonomic output. Healthy microbiome signals (SCFA-driven) produce parasympathetic upregulation and HRV improvement. LPS and inflammatory signals produce sympathetic activation and HRV compression.

Fecal matter transplantation from normotensive (healthy microbiome) to hypertensive animals lowers blood pressure — confirming the full MICRO→AUTO→cardiovascular chain in a direct experimental intervention.

**Chain completeness:** Load-bearing. NTS as convergence point for gut vagal afferents and its role in autonomic output are established. FMT blood pressure evidence confirms the full chain at system level.

---

### Link 4: Gut serotonin → Vagal modulation → Central neurotransmission
Ninety percent of the body's serotonin is produced in gut enterochromaffin cells. This gut-derived serotonin activates vagal afferent fibers, transmitting signals to the NTS and modulating serotonergic neurons in the dorsal raphe nucleus (DRN) and noradrenergic neurons in the locus coeruleus (LC). These are the primary monoamine centers for emotional regulation, arousal, and stress response.

Critically: SCFAs from healthy microbiome enhance expression of TPH1 — tryptophan hydroxylase 1, the rate-limiting enzyme in serotonin synthesis. A healthy microbiome doesn't just improve HRV — it directly modulates the central neurotransmitter environment via the vagal serotonin pathway. SSRIs are targeting the downstream endpoint of a chain that begins in the gut.

**Chain completeness:** Load-bearing. Gut serotonin production, vagal activation, NTS relay to DRN and LC, and SCFA enhancement of serotonin synthesis are all mechanically documented.

---

### Link 5: Vagal efferents → Microbiome composition (AUTO→MICRO direction)
The relationship runs in both directions. Vagal efferent activity regulates gut motility, secretion, and immune environment — all of which determine which bacterial species thrive. High vagal tone promotes diverse, healthy microbiome conditions. Chronic sympathetic dominance reduces vagal efferent activity, slowing motility, reducing secretions, and creating an inflammatory gut environment that favors dysbiotic species.

This creates a self-reinforcing loop exactly parallel to the MET↔AUTO contract: high vagal tone → healthy microbiome → good SCFA signal → better vagal tone. Low vagal tone → dysbiosis → LPS noise → worse vagal tone.

**Chain completeness:** Scaffolding. Vagal efferent regulation of gut physiology is established. Direct quantitative effects on microbiome composition from vagal tone variation in humans needs more assembly.

---

## Operating States

| State | MICRO Input | AUTO Output | Channel Quality | Clinical Signature |
|---|---|---|---|---|
| **Healthy diversity** | High SCFA, low LPS, intact epithelium | High HRV, strong parasympathetic | High signal, low noise | Good mood, resilience, stable digestion |
| **Dysbiotic** | Low SCFA, high LPS, permeable epithelium | Low HRV, sympathetic dominant | Low signal, high noise | Anxiety, IBS, cognitive fog, cardiovascular risk |
| **Post-antibiotic** | Collapsed diversity, minimal SCFA | Transient autonomic instability | Signal loss | Mood disruption, gut symptoms, immune vulnerability |
| **Sugar-loaded** | Inflammatory species dominant, SCFA depleted | Progressive HRV compression | Noise rises as signal falls | Gradually worsening regulatory capacity, craving amplification |
| **Fermented food supported** | Diverse Lactobacillus, Bifidobacterium, good SCFA | HRV maintenance, parasympathetic support | Clean channel | Stable baseline, better stress recovery |
| **Chronic stress** | Dysbiosis from sympathetic-induced gut changes | Further HRV compression | Bidirectional degradation | Stress → gut → more stress loop |

---

## The Signal/Noise Framework

This contract is best understood through signal/noise ratio rather than simple activation/inhibition:

**Signal (health information):**
- SCFA production (butyrate, acetate, propionate) → vagal afferent activation → parasympathetic drive
- Gut serotonin → vagal relay → central monoamine modulation
- GLP-1, CCK from EECs → satiety, metabolic regulation, vagal tone

**Noise (dysregulation information):**
- LPS via TLR4 on vagal afferents → inflammatory danger signal
- Pro-inflammatory cytokines crossing gut epithelium → systemic inflammation
- Disrupted serotonin signaling from dysbiotic microbiome → aberrant NTS input

**The compound degradation problem:**
Sugar and processed food simultaneously:
1. Deplete SCFA-producing bacteria → reduce signal amplitude
2. Feed gram-negative inflammatory bacteria → increase LPS → raise noise floor
3. Increase gut permeability → allow more LPS translocation → amplify noise further
4. Deplete fermented food consumption → remove active signal support

All four effects operate concurrently. This is why dietary shift produces such outsized regulatory effects — it's not changing one variable, it's simultaneously restoring signal and reducing noise across the same channel.

---

## Drug and Dietary Effects Through This Contract

| Substance/Intervention | Mechanism at this Contract | Effect |
|---|---|---|
| Fermented foods (kefir, kimchi, kombucha, miso) | Deliver live cultures + SCFAs directly + support SCFA-producing bacteria | Signal restoration, channel quality improvement, HRV support |
| Dietary fiber | Substrate for SCFA-producing bacteria → SCFA production | Signal amplitude increase |
| Sugar/ultra-processed food | Depletes SCFA producers, feeds inflammatory species, increases LPS | Signal reduction + noise amplification simultaneously |
| Antibiotics | Collapses microbiome diversity, eliminates SCFA producers | Acute signal loss, transient autonomic disruption |
| Probiotics (Lactobacillus, Bifidobacterium) | Restore SCFA-producing and serotonin-supporting species | Gradual signal restoration |
| SSRIs | Target DRN serotonergic neurons downstream of gut serotonin pathway | Treating endpoint without addressing source — explains partial response and dependency |
| Vagal nerve stimulation | Directly increases vagal efferent activity → improves gut environment → shifts microbiome | AUTO→MICRO direction — changes composition through neural pathway |
| Fecal matter transplantation | Directly replaces microbiome composition | MICRO→AUTO direction — most direct intervention, confirmed to change autonomic state |
| Psyllium/prebiotic fiber | Selectively feeds SCFA-producing bacteria | Targeted signal support without direct probiotic delivery |
| Exercise | SCFA-producing bacteria increase → ECS anandamide elevation → anti-inflammatory cytokine reduction confirmed simultaneously in a single 6-week intervention | Cross-contract confirmation — exercise hits MICRO↔AUTO, AUTO↔MOD, and IMMUNE↔AUTO simultaneously through the same ECS-microbiome-inflammation chain |

**The SSRIs-gut observation:**
Most serotonin is produced in the gut. SSRIs block serotonin reuptake centrally. The gut-derived serotonin pathway via vagal afferents to DRN is the upstream source of much of the serotonin SSRIs are managing. Treating the gut microbiome directly should theoretically reduce the demand on the SSRI mechanism — which is what emerging research on microbiome interventions in depression appears to show.

**The TRPV1 shared receptor and exercise motivation loop:**
TRPV1 receptors on vagal afferents mediate butyrate → vagal → NTS regulatory signaling. The same TRPV1 receptor class mediates a separate but connected chain: gut microbiome-derived endocannabinoid metabolites → TRPV1-expressing sensory neurons → dopamine in ventral striatum → exercise motivation. Microbiome depletion or peripheral TRPV1 inhibition abrogates exercise capacity and its rewarding properties in vivo.

This creates a self-reinforcing dysbiosis loop not currently described in any contract:
Dysbiosis → reduced SCFA → reduced TRPV1 vagal signaling → reduced vagal tone (MICRO↔AUTO failure)
Simultaneously: Dysbiosis → reduced endocannabinoid metabolites → reduced TRPV1 exercise reward → reduced exercise motivation → less exercise → less anandamide → less SCFA-producing bacteria → more dysbiosis

The microbiome doesn't just degrade vagal tone through dysbiosis — it degrades the primary motivation for the intervention most likely to restore it. This is why exercise adherence is systematically lower in populations with poor metabolic and gut health. It is not motivational failure. It is a receptor-level regulatory loop making the corrective behavior less rewarding at the same time the need for it increases.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing**
Microbiome diversity metrics (alpha diversity, SCFA-producing species abundance) should positively correlate with HRV across populations independent of other health variables. This is the direct MICRO→AUTO chain prediction. Partially confirmed in existing literature — needs larger systematic study.

**Prediction 2 — Chain completeness: Scaffolding**
Fermented food intervention without other dietary change should produce measurable HRV improvement within 4-8 weeks — the timescale for meaningful microbiome composition shift. Effect size should correlate with baseline microbiome diversity (more degraded baseline = larger HRV improvement with intervention).

**Prediction 3 — Chain completeness: Scaffolding**
ND populations should show higher rates of gut dysbiosis and lower SCFA production than neurotypical controls at matched dietary intake — because their chronic sympathetic activation (low vagal tone) is continuously degrading the AUTO→MICRO direction of this contract. This predicts gut symptoms as a common ND comorbidity through autonomic mechanism, not coincidence.

**Prediction 4 — Chain completeness: Predictive**
The timing and amplitude of HRV improvement following antibiotic treatment should track microbiome recovery curves — specifically the recovery of SCFA-producing species. This would establish the MICRO→AUTO chain as clinically measurable in a controlled natural experiment.

**Prediction 5 — Chain completeness: Predictive**
Vagal nerve stimulation should produce measurable microbiome composition shifts within weeks through the AUTO→MICRO direction — specifically increasing SCFA-producing species abundance through improved gut motility and reduced inflammatory environment. This prediction is testable with current VNS devices and microbiome sequencing.

---

## Failure Modes

**Psychiatric treatment ignoring gut source:**
Depression and anxiety with gut dysbiosis at source are being treated with SSRIs that target the downstream endpoint of a chain that begins in the microbiome. Partial response, extended titration periods, and treatment resistance may in many cases reflect MICRO→AUTO channel degradation that SSRIs cannot address. Adding dietary/microbiome intervention should improve response rates — and early data suggests it does.

**Antibiotic cascades:**
Repeated antibiotic courses collapse microbiome diversity, triggering acute autonomic disruption. The subsequent mood, cognitive, and regulatory symptoms are rarely attributed to the antibiotic's microbiome effects — they're attributed to the original infection or to unrelated causes. The MICRO→AUTO chain is the mechanism making antibiotics a psychiatric risk factor.

**The craving amplification loop:**
Sugar degrades the microbiome which reduces SCFA signal which reduces vagal tone which impairs the regulatory system's ability to read its own state which drives it to seek more compensatory input — more sugar. The system is trying to self-regulate through the only lever it can reach, which is exactly the input that is degrading the sensing channel. The preference is regulatory, as stated in the core framework. The drug being sought is making the problem worse.

---

## Adjacent Contracts

**Below (feeds into this contract):**
- MET ↔ IMMUNE: Glucose dysregulation → inflammatory gut environment → dysbiosis arrives here through dietary and immune pathway
- MET ↔ AUTO: Metabolic state affects gut transit, secretion, and environment — metabolic dysfunction degrades microbiome conditions

**Above (fed by this contract):**
- IMMUNE ↔ AUTO: LPS translocation from leaky gut drives systemic inflammation which impairs vagal tone through the immune contract — MICRO feeds IMMUNE which feeds AUTO through a parallel inflammatory pathway
- AUTO ↔ MOD: Autonomic output from this contract becomes input to ECS and precision gain modulation above

**Lateral:**
- MET ↔ IMMUNE: Shares the LPS/gut permeability mechanism — microbiome dysbiosis and metabolic dysfunction both converge on gut permeability as the failure mode
- Circadian rhythm: Gut microbiome has its own circadian composition rhythm — microbiome composition measurably shifts across the 24-hour cycle. Disrupting circadian timing disrupts the microbiome's SCFA production timing, not just its composition.

---

## Key Unresolved Links

1. **Individual SCFA receptor density variation:** FFAR2/FFAR3 receptor expression on EECs varies between individuals. This variation likely determines the gain of the MICRO→AUTO signal — same SCFA production could produce different vagal responses based on receptor density. This is the individual variation parameter for this contract and is not well characterized.

2. **Neuropod signaling specificity:** What specific signals travel through EEC neuropod direct connections vs the hormonal relay pathway, and at what timescale? The neuropod pathway is ultrafast (milliseconds) while the hormonal pathway is slower (minutes). Whether the two pathways carry different information is not established.

3. **Optimal microbiome diversity threshold:** At what point does microbiome diversity degradation produce measurable HRV impairment? The directional relationship is established but the clinical threshold for when the channel becomes meaningfully noisy is not defined. This is the equivalent of the HRV threshold question in the MET↔AUTO contract.

4. **AUTO→MICRO timescale specificity:** How quickly does vagal tone change produce measurable microbiome composition shift? The direction is established but timescales in humans are not well characterized — this is important for understanding whether autonomic interventions (HRV biofeedback, breathing practice) produce microbiome changes fast enough to be clinically relevant.

---

## Origin Note

This contract emerged from the observation that gut symptoms co-occur with ND and autonomic dysregulation at rates that couldn't be explained by coincidence. The signal/noise framing — that sugar and processed food don't just add bad input but simultaneously reduce good input on the same channel — was derived before the specific SCFA/LPS dual mechanism was confirmed.

The fermented food cross-cultural convergence was the minority invariant here: every traditional food culture independently preserved fermentation practices. Convergent independent discovery across isolated traditions before any mechanistic understanding is the same signal found with breathing practices in contemplative traditions. Both pointed at the same underlying regulatory mechanism before the mechanism was named.

The craving amplification loop — sugar degrading the sensing channel that would otherwise reduce sugar craving — was derived from the principle that preferences are regulatory signals. The system is seeking what regulates it; when the sensing channel is degraded, it cannot accurately identify what will actually help and reaches for what produces the strongest immediate signal instead.

*Chain status: Partially load-bearing. Links 1-4 in the MICRO→AUTO direction are mechanically solid. Link 5 (AUTO→MICRO) is scaffolding. Self-reinforcing loop is scaffolding with strong mechanistic derivation. Signal/noise framework is conceptual derivation awaiting quantitative characterization.*
