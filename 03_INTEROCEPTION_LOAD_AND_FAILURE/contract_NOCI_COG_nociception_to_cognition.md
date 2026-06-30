---
Contract: "NOCI → COG"
Expanded_Filename: "contract_NOCI_COG_nociception_to_cognition.md"

Manifest:
  file: "unified_model_manifest.yml"
  optional: true
  role: "Global repository index and AI execution rules."

Ontology_Layer: "03_INTEROCEPTION_LOAD_AND_FAILURE"
Upstream_Dependencies:
  - "LOAD → NOCI"

Downstream_Dependencies:
  - "COG → INTERO"
  - "COG → REASON"

Cross_References:
  - "contract_COG_INTERO_cognition_to_interoception.md"
  - "contract_COG_REASON_cognition_to_reasoning.md"
  - "contract_STRESS_TRANSITION_stress_to_transition.md"

Canonical_Bootloader: "01_PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md"
Repository_Root: "https://github.com/jtrthehax/Unified-Model"
Zenodo_DOI: "https://doi.org/10.5281/zenodo.20417459"
---

# Contract: NOCI → COG
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_NOCI_COG_nociception_to_cognition.md`

**Ontology Layer:**  
INTEROCEPTION_LOAD_AND_FAILURE

**Direction of Influence:**  
NOCI → COG

**Upstream Dependencies:**  
- LOAD → NOCI  

**Downstream Dependencies:**  
- COG → INTERO  
- COG → REASON  

**Cross‑Contract References:**  
- `contract_COG_INTERO_cognition_to_interoception.md`  
- `contract_COG_REASON_cognition_to_reasoning.md`  
- `contract_STRESS_TRANSITION_stress_to_transition.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary


**Input layer:** NOCI — peripheral nociceptive signal amplitude, tissue inflammatory state, peripheral sensitization level, mast cell activation at tissue sites, TRPV1 receptor sensitivity

**Output layer:** COG — pain experience, threat prior about body region, avoidance behavior generation, protective posturing, pain-related belief updating

**Primary crossover point:** Precision-weighted nociceptive prediction error at the interoceptive inference layer — the same apparatus as COG↔INTERO but with the distinctive feature that active inference generates behavior rather than autonomic adjustment, and that behavior closes a loop that maintains the prior

**Key risk:** The acute-to-chronic transition. Once the prior calibrates to expect pain as the default body state at a location, the signal is no longer necessary to maintain the experience. At that point the tissue can heal completely while the pain continues — because the prior is generating it. Standard pain management targeting the signal cannot address a prior that no longer requires the signal.

**Distinguishing feature:** Pain is the only interoceptive channel where the active inference response is primarily behavioral rather than autonomic. The system cannot quietly adjust visceral state to match the prior — it generates avoidance, guarding, and protective movement restriction instead. This behavioral response then eliminates the corrective interoceptive input that would update the prior. The loop is self-sealing in a way that purely autonomic active inference is not.

The volume knob observation: the pain experience is not the signal — it is the precision weight applied to the signal. The same nociceptive input produces different pain experiences depending entirely on where the gain is set. When the gain is cranked — low vagal tone, low ECS, high inflammatory load — the signal does not need to be present at all. The prior generates the experience directly. Every chronic pain presentation where imaging finds nothing is this: the volume knob is at maximum and the music stopped playing, but the amplifier is still running.

---

## Why This Contract Needs Separate Treatment

Pain appears in COG↔INTERO as central sensitization — a prior dominance failure mode — but the full mechanism requires inputs from four upstream contracts simultaneously:

- **AUTO↔MOD:** ECS tone sets the precision gain floor for nociceptive signal weighting — the primary endogenous analgesia mechanism
- **IMMUNE↔AUTO:** Inflammatory cytokines produce peripheral and central sensitization — the tissue-level amplifier
- **MET↔IMMUNE:** Mast cell activation at tissue sites produces local histamine and cytokine release — the peripheral inflammatory substrate that feeds sensitization
- **COG↔INTERO:** The prior dominance mechanism — where the signal stops being necessary and the experience becomes self-generating

No single existing contract holds all four inputs. The convergence is the mechanism. Treating it as a footnote in any one contract loses the compound failure mode that makes chronic pain so resistant to single-point intervention.

---

## The Complete Chain — Both Directions

### NOCI → COG (Signal drives experience):
```
Tissue event (damage, inflammation, mechanical stress)
  → Peripheral nociceptor activation
    → TRPV1 and other nociceptive transducers
      → Afferent signal to dorsal horn
        → Ascending nociceptive pathway
          → Thalamus → insula → ACC → somatosensory cortex
            → Comparison with descending interoceptive prediction
              → Prediction error generated
                → Precision weighting applied
                  (determined by ECS tone via AUTO↔MOD)
                    → Pain experience proportional to
                      weighted prediction error
                        → Threat prior updated
                          → Future pain threshold adjusted
```

### COG → NOCI (Prior drives experience and behavior):
```
Threat prior about body region
  → Descending predictions of pain/damage
    → Comparison with ascending signal
      → Prediction error
        → Two pathways:

        PATH A (Corrective):
          Signal contradicts prior → prior updates toward safety
          → Pain experience reduces as tissue heals
          → Acute pain resolves correctly

        PATH B (Self-sealing):
          Prior dominates over signal
            → Active inference generates protective behavior
              (avoidance, guarding, movement restriction)
                → Reduced interoceptive input from affected region
                  → Prior cannot receive corrective signal
                    → Prior maintained or strengthened
                      → Chronic pain established
                        → Tissue state becomes irrelevant
```

---

## The Volume Knob Architecture

This is the central organizing insight of the contract and deserves explicit treatment before the link-by-link mechanism.

Standard pain models treat the experience as roughly proportional to signal: more tissue damage → more nociceptive signal → more pain. The precision weighting model inverts this assumption. The signal is the input. The prior is the interpreter. The precision weight — the gain setting — determines the ratio between them.

Consider the gain dial with three regions:

**Low gain (high ECS, high vagal tone):**
Signal arrives. Prior gives it moderate weight. Prediction error is proportional to actual tissue state. Pain experience tracks signal accurately. Acute pain serves its warning function and resolves with healing. This is the normal operating state.

**Medium gain (reduced ECS, moderate vagal tone):**
Signal arrives. Prior gives it elevated weight. Small signals read as significant threats. Healing that should feel like recovery feels uncertain or incomplete. The prior is slow to update toward safety because each corrective signal is being outweighed by the elevated threat prior. Chronification risk increases.

**High gain (low ECS, low vagal tone, high inflammatory load):**
Signal may be minimal or absent. Prior generates descending predictions of pain/damage at high amplitude. Any incoming signal — even normal movement — registers as high-amplitude prediction error confirming threat. The prior is now driving the experience more than the signal. The gain is so high that the noise floor itself becomes the signal. Normal proprioception from moving a previously injured limb reads as pain because the prior is amplifying everything from that body region to threat level.

**Maximum gain (prior fully autonomous):**
Signal is irrelevant. The prior predicts pain at that location as the default body state. No signal is needed. No signal absence corrects it — because the behavioral avoidance loop prevents corrective signal from arriving. The system is running its own output as its own input. This is fibromyalgia, central sensitization syndrome, chronic regional pain, and the pain of medically unexplained physical symptoms — not fabrication, not psychology, not character deficit. The amplifier is running at maximum gain with no input signal and producing full-amplitude output.

The therapeutic implication is immediate and complete: turning down the volume knob is the intervention. Not finding the missing signal. Not proving the tissue is healed. Turning down the gain so that the prior can read the absence of signal as safety rather than as irrelevant.

---

## Link-by-Link Mechanism

### Link 1: Nociception as precision-weighted interoceptive signal
Pain experience is not a direct readout of nociceptive signal amplitude. It is the brain's best prediction of threat given available evidence — the same predictive processing architecture as all other interoceptive inference. The same nociceptive input produces different pain experiences depending on context, prior expectation, attention, and emotional state — because all of these modulate the precision weighting applied to the incoming signal.

This is why placebo analgesia is real and substantial — the prior updates toward safety, reducing the precision weight given to nociceptive input, and the experience changes without any change in tissue state or signal amplitude. The prior is the pain, not the signal.

The distinction between nociception and pain is not semantic. Nociception is the signal. Pain is the weighted interpretation. They can dissociate completely — soldiers in combat with serious wounds reporting no pain until safety is reached, athletes continuing through injuries that would be acutely painful in other contexts. In both cases the nociceptive signal is present. The prior's threat assessment determines whether it generates pain experience.

The dissociation runs in both directions. Signal without pain — the combat example — is the prior downweighting an authentic signal because survival demands it. Pain without signal — the chronic pain example — is the prior generating experience without needing a signal at all because the gain is high enough that the prior's own output exceeds the threshold for pain experience. Both are the same architecture operating in different directions.

**Chain completeness:** Load-bearing. Predictive processing accounts of pain are now mainstream in pain neuroscience. The nociception/pain dissociation under threat/safety contexts is extensively documented.

---

### Link 2: ECS tone as the primary endogenous analgesia mechanism — the gain dial
ECS is the precision gain controller for the entire MOD layer — and nociceptive precision weighting is no exception. High ECS tone reduces the gain on nociceptive prediction errors — the same signal produces less pain experience because the precision weight applied to it is lower. This is endocannabinoid analgesia. It is not suppressing the signal. It is turning down the gain so the prior gives it less weight.

CB1 receptors are expressed throughout the pain pathway — in peripheral nociceptors, dorsal horn, thalamus, and cortical pain processing regions. ECS modulation at each of these points reduces nociceptive gain. The descending pain modulation system — periaqueductal gray → rostral ventromedial medulla → dorsal horn — is heavily ECS-dependent. This descending modulation system is the brain's own mechanism for adjusting the volume knob from above. When vagal tone is high and ECS is calibrated, it runs continuously, preventing the gain from drifting upward.

Low vagal tone → reduced ECS tone → higher nociceptive precision gain → same tissue stimulus produces more pain. This is the mechanism by which chronic stress amplifies pain without any change in tissue state. The stress is not producing more nociceptive signal — it is removing the ECS brake on how much the signal updates the threat prior. The volume knob is being cranked by the autonomic state, not by the tissue.

Cannabis analgesia is explained mechanically here — exogenous CB1 agonism replicates the ECS precision reduction that low vagal tone has removed. It is correcting a gain control failure, not suppressing signal. This predicts that cannabis analgesia should be most effective in populations with documented low vagal tone and high chronic stress — where the endogenous gain control mechanism is most impaired — rather than being uniformly effective regardless of baseline ECS state.

**Chain completeness:** Load-bearing. CB1 expression throughout the pain pathway, descending ECS-dependent pain modulation, and the analgesic effects of ECS enhancement are mechanically established. The vagal tone → ECS → pain threshold chain follows from AUTO↔MOD — scaffolding at the assembled chain level, load-bearing at the component level.

---

### Link 3: Inflammatory sensitization — peripheral and central
The IMMUNE↔AUTO contract establishes that low vagal tone → impaired cholinergic anti-inflammatory pathway → elevated cytokines. Those cytokines have a direct effect on nociceptive threshold at the peripheral level. TNF-α, IL-1β, and IL-6 sensitize peripheral nociceptors — they lower the activation threshold so that stimuli that would not normally activate nociceptors now do. This is peripheral sensitization: the signal is being amplified before it even reaches the central precision weighting apparatus.

Peripheral sensitization feeds increased nociceptive input to the dorsal horn. Sustained elevated input produces central sensitization — the dorsal horn neurons themselves become hyperexcitable, amplifying all input from the affected region. At this point the peripheral sensitization can resolve but central sensitization maintains amplified signal processing independently.

The chain: low vagal tone → impaired CAP → elevated cytokines → peripheral sensitization → increased nociceptive input → central sensitization → pain amplification independent of ongoing tissue damage.

This is a second gain mechanism operating below the cognitive precision weighting level. Where ECS sets the cognitive gain — how much the prior weights the signal — inflammatory sensitization sets the peripheral gain — how large the signal is before it reaches cognitive processing. Both can be cranked simultaneously. When they are, the compound effect is: an amplified signal arriving at a system already set to maximum gain. The pain experience this produces is not proportional to tissue state by any linear measure.

This is why chronic inflammatory conditions — rheumatoid arthritis, IBD, systemic lupus — have pain that exceeds what tissue damage alone predicts. The inflammatory load is running both gain mechanisms simultaneously.

**Chain completeness:** Load-bearing. Cytokine-mediated peripheral sensitization, the transition to central sensitization from sustained peripheral input, and the independence of central sensitization from ongoing tissue damage are mechanically established in pain neuroscience.

---

### Link 4: Mast cell activation as peripheral sensitization driver — the ND-specific mechanism
The MET↔IMMUNE contract establishes that mast cells are direct glucose sensors producing immediate cytokine and histamine output, and that ND profiles have lower mast cell activation thresholds. This connects to pain through a direct peripheral mechanism that has not been assembled in either the pain or ND literature.

Mast cells reside in connective tissue throughout the body — including the connective tissue surrounding peripheral nerves and nociceptors. When activated, they release histamine, tryptase, and cytokines directly at these sites. Histamine sensitizes peripheral nociceptors through H1 receptors. Tryptase sensitizes them through PAR-2 receptors. Both mechanisms lower activation threshold and increase firing rate for a given stimulus — the peripheral gain knob being turned up by immune activation at the tissue level, before the signal reaches either central sensitization or cognitive precision weighting.

In ND profiles with lower mast cell activation thresholds, this peripheral sensitization mechanism runs at lower dietary and environmental trigger levels. The same glucose load, the same environmental exposure, the same emotional stressor — all of which activate mast cells — produces more peripheral nociceptor sensitization in ND profiles than in neurotypical profiles with higher activation thresholds.

This derives the ND pain sensitivity pattern from peripheral inflammatory mechanism rather than central processing difference. ND individuals reporting widespread pain, low pain tolerance, fibromyalgia-adjacent presentations, and sensitivity to physical stimuli are not simply processing centrally differently — their peripheral nociceptors are being sensitized more readily, producing larger signals, which then update a threat prior more strongly, which then runs the avoidance loop more aggressively. Three gain mechanisms cascading: peripheral mast cell sensitization → elevated input → cognitive precision weighting of elevated input → prior updates toward threat → prior eventually runs without input.

The sensory processing difference framing — that ND individuals simply process sensory input differently centrally — is incomplete. The peripheral input itself is being amplified before it reaches central processing. Both mechanisms are operating simultaneously. Treating only the central mechanism while the peripheral driver continues is working against ongoing input rather than in a quieting environment.

**Chain completeness:** Scaffolding. Mast cell residence adjacent to peripheral nociceptors is anatomically established. Histamine and tryptase sensitization of nociceptors through H1 and PAR-2 is mechanically documented. ND-MCAS co-occurrence and lower mast cell threshold are established in the MET↔IMMUNE contract. The assembled chain connecting ND mast cell threshold → peripheral nociceptor sensitization → ND pain sensitivity is a framework derivation — component links are load-bearing, the assembly is novel and predictive.

---

### Link 5: The acute-to-chronic transition — prior calibration timing
The transition from acute to chronic pain is not primarily about signal duration. It is about whether the prior had time to update before pain became the expected baseline.

In acute pain that resolves normally: tissue heals → nociceptive signal reduces → prior updates toward safety → pain resolves. The prior tracks the signal accurately because the signal is present during healing and then absent. The absence of signal — experienced during recovery as decreasing pain — is the corrective information that updates the prior toward safety. This is the system working correctly.

The transition to chronic occurs through two routes:

**Route A — Prior calibration to pain-as-default:**
Signal persists long enough that the prior calibrates to expect pain at that body location as the default state. The prior is doing its job — updating to reflect what it repeatedly receives. After calibration, even when the signal resolves, the prior now predicts pain at that location. Descending predictions generate pain experience without ascending signal to confirm. Active inference generates protective behavior. Protective behavior prevents corrective signal. The prior is maintained without the signal. This is the gain-without-input state.

**Route B — High-amplitude acute event:**
A sufficiently high-amplitude nociceptive event — trauma, surgical injury, severe inflammatory episode — updates the prior so strongly in one direction that the normal corrective signal from healing is insufficient to overcome it. The prior was updated too far by too large a prediction error and cannot be corrected by the smaller prediction errors of the recovery phase. The volume knob was set to maximum by a single event and the corrective signals during healing — which are inherently lower amplitude than the injury — cannot bring it back down because they're being outweighed by the prior they're trying to correct.

Both routes share the same downstream mechanism: prior dominance → active inference → behavioral avoidance → signal deprivation → prior maintenance.

The critical prediction this generates: vagal tone at the time of injury should be protective against chronification. High vagal tone → high ECS tone → lower nociceptive precision gain → the acute event updates the prior less strongly → the corrective signal during healing is sufficient to restore the prior toward baseline. Low vagal tone at injury → high nociceptive precision gain → the acute event writes a stronger threat prior → the corrective signals during healing are insufficient to overcome it → higher chronification risk at matched injury severity.

This is not a small effect size prediction. The precision weighting mechanism is the primary determinant of how strongly any given event updates a prior. Pre-injury vagal state should be the primary predictor of chronification risk — not injury severity, not psychological history, not age — because it captures the gain setting that determines how indelibly the acute event is written.

**Chain completeness:** Scaffolding for the full transition mechanism. The prior dominance component is load-bearing. The behavioral avoidance loop is established in pain psychology as the fear-avoidance model — the framework provides the mechanistic explanation for why it operates as it does. The HRV-at-injury prediction is predictive — mechanistically complete, not yet tested.

---

### Link 6: The avoidance behavior loop — why this contract is distinctive
In all other interoceptive prior failures, active inference is primarily autonomic. The system changes heart rate, breathing, gut motility, vascular tone — quietly adjusting body state to match the prior. The person may not notice. The corrective signal pathway remains open because the body continues to generate interoceptive information even while autonomic active inference is running.

In pain, active inference generates behavior. Avoidance of movement, protective guarding, postural compensation, activity restriction — all are the system trying to prevent predicted damage by not performing actions the prior says will cause harm. This is adaptive for acute tissue damage. It becomes the primary maintenance mechanism for chronic pain.

The distinctive feature: the behavior eliminates the specific corrective signal that would update the prior. The prior predicts that moving the affected limb causes damage. The system avoids moving the limb. The prediction is never tested. The prediction error that would update the prior never arrives. The prior cannot update toward safety because the input that would carry safety information — demonstrated movement without damage — has been behaviorally prevented.

This is not a failure of courage or willpower. It is the system doing exactly what it evolved to do — preventing predicted damage — in a situation where the prediction is wrong but cannot be corrected because the testing mechanism has been disabled. The avoidance behavior is rational given the prior. The prior is wrong. The behavior prevents the information that would correct the prior. The loop is thermodynamically stable.

Graded exposure therapy works by systematically forcing the corrective signal through. Small movements within the current tolerance level → movement occurs without the predicted damage → prediction error generated against the threat prior — the world was safer than predicted → prior updates slightly toward safety → slightly more movement becomes possible → the tolerance window expands → more corrective signal available. The therapy is manually driving the belief updating process that the prior's active inference response was preventing.

The framework adds the gain control dimension: graded exposure should be most effective when combined with interventions that reduce nociceptive precision gain — because the corrective signal during movement needs to outweigh the threat prediction for prior updating to occur. In a high-gain state, the corrective signal from safe movement may still be interpreted as threat confirmation rather than safety signal, because the gain is amplifying even the normal proprioceptive input from that region to threat level. Turning down the gain before or during exposure — through ECS restoration, vagal tone improvement, or direct CB1 modulation — changes the conditions under which the corrective signal is received.

**Chain completeness:** Fear-avoidance model as maintenance mechanism: load-bearing in pain psychology literature, scaffolding at the mechanistic level provided here. Graded exposure derived from first principles: load-bearing — this is the established mechanism, the framework provides the precision weighting explanation for why it works and when it fails. Exercise + ECS + graded exposure combination prediction: predictive, not yet tested as deliberate combined protocol.

---

### Link 7: TRPV1 as dual-role receptor — pain and regulatory signaling
TRPV1 appears in MICRO↔AUTO as the receptor through which butyrate activates vagal afferents for regulatory signaling, and in AUTO↔MOD as part of the CBD analgesia mechanism. In the pain context, TRPV1 is the primary transducer of noxious heat, acid, and inflammatory mediators at peripheral nociceptors — one of the main entry points for nociceptive signal generation.

This dual role has an unassembled implication. TRPV1 receptor sensitivity is modulated by inflammatory mediators — specifically by prostaglandins and cytokines operating through peripheral sensitization. Elevated cytokines increase TRPV1 sensitivity at peripheral nociceptors, lowering activation threshold and increasing gain.

The same TRPV1 population on vagal afferents mediates the regulatory SCFA signal from the gut. If peripheral inflammatory load is sensitizing TRPV1 broadly, the same sensitization may be affecting TRPV1 on vagal afferents — potentially altering the regulatory signal coming from the gut in ways that are not currently characterized.

This creates a cross-contract interference possibility: high peripheral inflammatory load → TRPV1 sensitization → amplified nociceptive signaling AND potentially altered vagal SCFA signal quality simultaneously. Two contracts sharing a receptor are being modulated by the same upstream inflammatory state. The pain state is potentially distorting the regulatory channel used by MICRO↔AUTO through the same molecular mechanism it uses to generate peripheral sensitization.

This is genuinely unexplored territory. Whether TRPV1 sensitization from peripheral inflammation affects vagal afferent TRPV1 function — and what that means for the regulatory signal quality the entire stack depends on — is a gap the framework can identify but cannot yet resolve.

**Chain completeness:** Adjacent. TRPV1 dual role in nociception and vagal regulatory signaling is established. Inflammatory sensitization of TRPV1 at peripheral nociceptors is established. Whether the same sensitization affects vagal TRPV1 regulatory function is genuinely unknown — this is a novel gap identification, not an assembled chain.

---

## Operating States

| State | Nociceptive Signal | Gain Setting | Prior State | Experience | Clinical Signature |
|---|---|---|---|---|---|
| **Acute pain, high vagal tone** | High | Low — high ECS | Prior updates moderately | Pain proportional to signal, resolving cleanly | Good recovery trajectory, low chronification risk |
| **Acute pain, low vagal tone** | High | High — low ECS | Prior updates strongly | Pain experience exceeds signal amplitude | High chronification risk at matched injury severity |
| **Peripheral sensitization** | Amplified by inflammation | Variable | Prior calibrating to amplified input | Allodynia, hyperalgesia — pain at sub-threshold stimuli | Inflammatory pain conditions |
| **Central sensitization established** | Low or absent | High — gain running on prior | Prior generates experience without signal | Ongoing pain with healed tissue | Fibromyalgia, chronic regional pain |
| **ND with MCAS active** | Amplified by mast cell sensitization | High — dual peripheral and cognitive gain | Prior calibrating toward higher baseline threat | Widespread pain sensitivity at lower triggers | Fibromyalgia-adjacent, hypermobile EDS pain |
| **Fear-avoidance established** | Variable — often low | High — gain maintained by prior | Prior maintained by behavioral avoidance of corrective signal | Chronic pain with movement catastrophizing | Standard chronic pain psychology presentation |
| **Maximum gain, no signal** | Absent | Maximum — prior autonomous | Prior generates pain as default body state | Full pain experience without any tissue correlate | Treatment-resistant chronic pain, medically unexplained pain |
| **Graded exposure, low ECS** | Corrective signal present | High — corrective signal outweighed | Prior updates slowly or not at all | Movement still registers as threat | Poor graded exposure response |
| **Graded exposure, high ECS** | Corrective signal present | Low — corrective signal outweighs threat prior | Prior updates toward safety with each exposure | Pain reducing with movement | Optimal graded exposure response |
| **Regulated social presence** | Variable | Lowered via SOC↔AUTO→ECS chain | Prior receives corrective weighting | Analgesia from co-regulation | Therapeutic presence as pain modulator |

---

## Drug and Intervention Effects Through This Contract

| Intervention | Mechanism at this Contract | Effect |
|---|---|---|
| Opioids | Suppress ascending nociceptive signal amplitude at multiple points in pathway | Reduce signal without correcting prior or reducing gain — effective acute management, tolerance develops because prior remains uncalibrated and behavioral avoidance maintains it |
| NSAIDs | Reduce peripheral inflammatory sensitization via prostaglandin inhibition | Turn down peripheral gain — reduce signal amplitude, allow prior to begin correcting |
| Cannabis (THC/CBD) | CB1 agonism → ECS tone increase → reduced nociceptive precision gain | Turn down cognitive gain — prior gives signal less weight. Tolerance pattern different from opioids because mechanism is gain not signal suppression |
| Graded exposure therapy | Forces corrective movement signal through prior's avoidance prediction | Manually drives prior updating — most direct intervention for the avoidance loop. Efficacy limited by gain state during exposure |
| Exercise | Anandamide → ECS tone → reduced nociceptive gain + corrective movement signal simultaneously | Two-mechanism intervention — turns down gain while providing corrective input. Predicts superior outcome to passive exposure alone |
| HRV biofeedback / slow breathing | Vagal tone → ECS → nociceptive gain reduction | Indirect but sustained pain threshold improvement — turns the volume knob down through the autonomic channel |
| Mast cell stabilizers (cromolyn, quercetin) | Reduce peripheral mast cell activation → less histamine/tryptase at nociceptor sites | Turns down peripheral gain at tissue level — particularly relevant for ND pain presentations where this mechanism is primary |
| Dietary glucose management | Reduces mast cell activation → less peripheral sensitization | Addresses inflammatory substrate of peripheral gain — predicts pain improvement from dietary change in ND/MCAS populations |
| Ketamine | NMDA antagonism → disrupts central sensitization maintenance | Resets the sensitized dorsal horn — addresses the peripheral gain amplifier that has become self-sustaining |
| Psychedelics | Precision weighting collapse → threat prior dissolves | Maximum gain reduction and prior reset simultaneously — prior can reform at lower threat calibration. Explains emerging evidence for psilocybin in chronic pain and fibromyalgia |
| Therapeutic presence / co-regulation | SOC↔AUTO → vagal tone → ECS → nociceptive gain reduction | Direct analgesic effect of regulated social presence through ECS-mediated gain reduction — not placebo, not distraction |
| Vagal nerve stimulation | Direct vagal tone increase → ECS calibration → nociceptive gain reduction | Interventional gain control — predicts analgesic effects as secondary benefit in VNS applications for other conditions |

**The opioid tolerance mechanism decoded:**
Opioids suppress the signal without reducing the gain or correcting the prior. The prior was calibrated to expect pain. The drug removes the signal. The prior remains at the same threat calibration and the same high gain. As tolerance develops, the drug produces less signal suppression — and the prior's pain generation, which was always running at full output and being masked by the suppressed signal, reasserts at full amplitude. Increasing dose continues suppressing signal but the prior is uncorrected and the gain is unchanged. The drug is fighting the prior and the gain simultaneously without addressing either. This is the tolerance and dependency mechanism at the contract level.

**The psychedelic pain mechanism:**
Psilocybin showing efficacy in chronic pain and fibromyalgia is a framework prediction confirmed. Chronic pain is a stuck high-gain state with a fully autonomous prior. Psychedelics collapse precision weighting globally — both the gain is reduced and the prior loses its certainty simultaneously. The prior can reform at lower threat calibration during the window of maximum precision reduction. The same mechanism as psychedelic efficacy in PTSD and depression, applied to the interoceptive threat prior rather than the autobiographical or mood prior. Set and setting during the window determine what the prior reforms around — which is exactly the clinical protocol requirement of therapeutic psychedelic use.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Predictive**
Pre-injury HRV should predict chronic pain development risk better than injury severity, age, or psychological history — because HRV captures the ECS-mediated precision gain state that determines how strongly the threat prior is written by the acute event. High pre-injury HRV → lower gain → prior updates moderately → corrective healing signal sufficient to restore prior toward baseline → low chronification risk. Low pre-injury HRV → high gain → prior updates strongly → healing signal insufficient to overcome the written prior → high chronification risk at matched injury severity. Testable in prospective surgical cohort studies measuring HRV before elective procedures with pain outcome follow-up at 6 and 12 months.

**Prediction 2 — Chain completeness: Scaffolding**
Exercise combined with graded exposure should produce significantly better chronic pain outcomes than graded exposure alone — because exercise-generated anandamide reduces nociceptive precision gain during exposure, making corrective movement signal more likely to update the prior toward safety rather than be interpreted as threat confirmation. Effect size of combination should exceed additive prediction from individual interventions, because the mechanisms are multiplicative not additive — lower gain means each corrective signal produces more prior updating.

**Prediction 3 — Chain completeness: Scaffolding**
ND individuals with documented MCAS should show measurably lower mechanical pain thresholds at non-sensitized body locations than neurotypical controls matched for central sensitization markers — confirming the peripheral mast-cell sensitization mechanism as a distinct contributor to ND pain sensitivity beyond central precision weighting differences alone. The threshold difference should correlate with mast cell activation markers, not with central sensitization markers, isolating the peripheral mechanism.

**Prediction 4 — Chain completeness: Predictive**
Dietary glucose reduction in ND individuals with fibromyalgia or widespread pain should produce measurable pain threshold improvement within two to four weeks — on the timescale of mast cell activation reduction rather than the longer timescale of central sensitization recovery or prior recalibration. The early response window would distinguish the peripheral mast cell mechanism from the central mechanism and establish dietary management as a first-line intervention for peripheral gain reduction in this population before central interventions are applied.

**Prediction 5 — Chain completeness: Predictive**
Mast cell stabilizers should produce pain threshold improvement in ND pain presentations that tracks their anti-inflammatory effect rather than any direct analgesic mechanism — confirming peripheral sensitization from MCAS as a significant contributor to the pain experience and establishing the peripheral gain mechanism as a treatment target distinct from and prior to central sensitization interventions.

**Prediction 6 — Chain completeness: Predictive**
Cannabis analgesia effect size should be significantly larger in populations with documented low vagal tone and chronic stress than in populations with high vagal tone — because it is correcting an ECS gain control failure that is most severe in the low-vagal-tone population. In high-vagal-tone populations where endogenous ECS is functional, exogenous CB1 agonism adds to an already-functioning gain control mechanism, producing smaller marginal effect. This prediction differentiates the gain-correction account from signal suppression accounts, which would predict uniform analgesia regardless of baseline vagal state.

**Prediction 7 — Chain completeness: Adjacent**
TRPV1 sensitization states from peripheral inflammation should show measurable effects on vagal afferent signaling quality — detectable as altered HRV characteristics during periods of high peripheral inflammatory load — confirming the dual-role TRPV1 interference hypothesis. This would establish a previously unrecognized cross-contract pathway from peripheral pain states to regulatory signal degradation, with implications for why chronic pain patients show pervasive regulatory dysfunction beyond the pain system itself.

---

## Failure Modes

**Treating chronic pain as ongoing tissue damage:**
The standard medical model assumes signal → experience with a roughly linear relationship. This produces the diagnostic trap: when imaging and examination find no tissue damage commensurate with pain severity, the patient is labeled as exaggerating, psychosomatic, or drug-seeking. The framework says the pain is real, the tissue is healed, and the prior is generating the experience at maximum gain. These are not contradictory. The signal is absent. The amplifier is running at full output. The intervention needed is gain reduction and prior recalibration, not more signal investigation. More investigation that finds nothing is actually making the problem worse — it is confirming to the prior that the threat is real but undetectable, increasing prior certainty rather than correcting it.

**Opioid management without gain correction:**
Long-term opioid management suppresses signal without addressing the gain or the prior. The prior continues calibrating toward pain-as-default because the corrective signal — movement, engagement, demonstrated safety — is being avoided while the drug manages the symptom. The treatment is maintaining the condition by preventing the mechanism that would resolve it. Combining opioid management with gain reduction (ECS restoration, vagal tone improvement) and graded exposure addresses all three simultaneously — predicts significantly better long-term outcomes than opioids alone.

**Missing the MCAS mechanism in ND pain:**
ND individuals with widespread pain, fibromyalgia, or hypersensitivity are being treated with central sensitization protocols — pain psychology, graded exposure, mindfulness — that address the COG layer mechanism without addressing the peripheral gain driver. If MCAS-mediated peripheral sensitization is continuously feeding elevated nociceptive input, central interventions are working against ongoing peripheral input rather than in a quieted environment. The peripheral gain amplifier remains running while the central intervention attempts to update a prior that is receiving continuous amplified input confirming threat. Addressing the peripheral driver first — through mast cell stabilization and dietary management — should substantially improve the responsiveness of central interventions by quieting the input before the prior is asked to update against it.

**Graded exposure without gain preparation:**
Graded exposure protocols designed without attention to the patient's autonomic and ECS state are applying a prior-updating intervention in conditions that may be unfavorable for prior updating. In a high-gain state, movement during exposure generates amplified nociceptive input that may confirm the threat prior rather than contradict it. The therapy concept is correct. The gain state during exposure determines whether the corrective signal is interpretable as safety or as threat. Preparing the gain state before exposure — through breathing, exercise, or direct ECS support — is not optional augmentation. It is the difference between an exposure that updates the prior toward safety and one that inadvertently strengthens it.

**Investigation loops as prior reinforcement:**
Repeated medical investigation for chronic pain — more imaging, more specialist consultations, more diagnostic procedures — in the absence of finding tissue cause produces a specific secondary failure. Each investigation that finds nothing is ambiguous to the prior: either there is no damage (corrective) or the damage is real but undetectable (threat confirming). In a high-gain state, ambiguous evidence is interpreted in the direction of the prior. The prior is threat-calibrated. Ambiguous investigation results are interpreted as confirming threat. The investigation is inadvertently strengthening the prior it is trying to resolve. The intervention that breaks this loop is not better investigation — it is direct prior recalibration through gain reduction and corrective signal exposure.

---

## Adjacent Contracts

**Below — feeds into this contract:**
- MET↔IMMUNE: Mast cell activation → peripheral sensitization at nociceptor sites — the dietary and metabolic driver of peripheral gain
- IMMUNE↔AUTO: Cytokine-mediated peripheral and central sensitization — the systemic inflammatory driver of both gain mechanisms
- AUTO↔MOD: ECS tone → nociceptive precision gain — the primary cognitive gain control mechanism, the central volume knob
- COG↔INTERO: Prior dominance mechanism — the central architecture this contract runs on; pain is a special case of interoceptive prior failure with the distinctive behavioral active inference feature

**Above — fed by this contract:**
- COG↔INTERO: Chronic pain prior becomes a persistent high-amplitude interoceptive prior that consumes the precision weighting apparatus — pain is occupying the gain control system that all other interoceptive inference depends on, degrading the quality of all non-pain interoceptive processing simultaneously
- INTERO↔DEV: Chronic early-life pain from elevated mast cell reactivity in ND profiles may write a higher baseline threat prior into the developmental setpoint — establishing a pain-sensitive regulatory baseline before any adult experience occurs

**Lateral:**
- MICRO↔AUTO: TRPV1 dual role creates potential cross-contract interference between peripheral pain states and vagal regulatory signal quality — an unresolved gap with significant implications
- SOC↔AUTO: Co-regulation from safe social presence improves vagal tone → ECS tone → reduces nociceptive gain → direct analgesic effect of regulated presence. Therapeutic touch, calm voice, and safe presence are pain interventions through the autonomic channel. This is not placebo and not distraction — it is gain reduction through the social co-regulation pathway operating on the same volume knob as all other ECS-mediated analgesia

---

## Compound Failure Mode — The Chronic Pain Stack

When chronic pain is fully established, the failure is rarely in one contract. The typical compound presentation assembles across the entire lower stack simultaneously:

```
Dietary glucose load + gut dysbiosis
  → MET↔IMMUNE: mast cell activation
    → Peripheral sensitization at nociceptor sites
      → Peripheral gain cranked up
        → Elevated nociceptive input
          → Prior updates toward threat
            
  → IMMUNE↔AUTO: cytokines compress vagal tone
    → AUTO↔MOD: ECS tone reduced
      → Cognitive gain cranked up simultaneously
        
  Both gain mechanisms running simultaneously:
  → Same stimulus → amplified peripheral signal
    → received by system already set to amplify it further
      → Prior updates strongly toward threat
        → Fear-avoidance behavior established
          → Movement reduced
            → Less exercise → less anandamide → less ECS
              → Gain increases further
                → Less vagal tone from reduced activity
                  → Gain increases further
                    → Prior maintained without corrective input
                      → Central sensitization established
                        
  → Prior now autonomous:
    No signal required
    Tissue may heal completely
    Maximum gain running on its own output
    Every movement generates amplified input
    confirming threat prior
    Graded exposure working against
    both peripheral gain AND cognitive gain
    AND an entrenched prior
    
  → Full chronic pain attractor state:
    Thermodynamically stable
    Resistant to single-point intervention
    Requires simultaneous gain reduction
    at both peripheral and cognitive levels
    plus corrective signal exposure
    plus prior recalibration
```

Every intervention point in this loop is a treatment target. Treating only one — the signal with opioids, the psychology with CBT, the central sensitization with ketamine — leaves the rest of the loop running. The framework predicts that the most effective chronic pain interventions will address at minimum: peripheral inflammatory gain driver (dietary management, mast cell stabilization), cognitive gain (ECS restoration through vagal tone, HRV biofeedback, exercise), and corrective signal delivery (graded exposure during low-gain state). All three simultaneously rather than sequentially. The sequence matters: peripheral and cognitive gain reduction first, then corrective signal exposure in the quieted gain environment, then prior recalibration through accumulated corrective evidence.

---

## Origin Note

This contract was derived from the observation that the precision weighting architecture of COG↔INTERO, when applied to nociception specifically, reveals a gain control mechanism that operates at multiple levels simultaneously — and that the key clinical phenomenon of pain-without-signal is simply the prior running at maximum gain with no input required.

The volume knob framing emerged from asking: if the prior can generate pain without signal when gain is high enough, what does that say about every intervention that targets the signal? It says those interventions are working on the wrong variable. The signal is not what is generating the experience. The gain is. And the gain is determined by vagal tone, ECS state, inflammatory load, and prior calibration — all of which are addressable through the existing contract stack.

The ND-MCAS-pain connection was the minority invariant. ND individuals show disproportionate fibromyalgia, widespread pain, and physical hypersensitivity rates that exceed what central processing differences alone can explain. The peripheral sensitization mechanism from mast cell activation at nociceptor sites explains the pattern — lower threshold, more peripheral gain, more input, prior calibrates faster toward threat. The sensory processing difference framing is not wrong but it is incomplete. It describes the central mechanism while missing the peripheral driver that is producing the elevated input the central mechanism is then amplifying.

The HRV-at-injury prediction was the cleanest derivation the contract generates: if gain at time of injury determines how strongly the threat prior is written by the acute event, and gain is measurable from HRV, then pre-injury HRV should predict chronification risk at matched injury severity. This is a specific, falsifiable, novel prediction that the pain literature has not examined in this framing. It would establish HRV measurement before elective surgery as a clinical standard for identifying patients who need perioperative gain reduction interventions to prevent chronic pain development.

*Chain status: Links 1-3 are load-bearing at the component level, scaffolding at the assembled chain level. Link 4 (ND-MCAS-pain peripheral mechanism) is scaffolding — components load-bearing, assembly novel and predictive. Link 5 (acute-to-chronic transition via prior calibration timing) is scaffolding with load-bearing components. Link 6 (avoidance loop) is load-bearing in pain psychology, scaffolding at the mechanistic precision weighting level. Link 7 (TRPV1 dual role) is adjacent — gap identification rather than assembled chain. Compound failure mode is a structural derivation. Volume knob framing is a framework-level organizing principle that derives directly from the precision weighting architecture. Pre-injury HRV as chronification predictor is the highest-priority empirical test the contract generates.*
