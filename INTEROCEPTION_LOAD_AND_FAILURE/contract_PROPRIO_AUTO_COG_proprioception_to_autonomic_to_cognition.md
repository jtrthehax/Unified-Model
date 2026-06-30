# Contract: PROPRIO → AUTO → COG
### Unified‑Model Regulatory Architecture — Contract Layer

**Expanded Filename:**  
`contract_PROPRIO_AUTO_COG_proprioception_to_autonomic_to_cognition.md`

**Ontology Layer:**  
INTEROCEPTION_LOAD_AND_FAILURE

**Direction of Influence:**  
PROPRIO → AUTO → COG

**Upstream Dependencies:**  
- LOAD → PROPRIO  

**Downstream Dependencies:**  
- AUTO → MOD  
- COG → REASON  

**Cross‑Contract References:**  
- `contract_AUTO_MOD_autonomic_to_modulation.md`  
- `contract_COG_REASON_cognition_to_reasoning.md`  
- `contract_ANCHOR_COG_anchor_to_cognition.md`  

**Canonical Bootloader:**  
https://github.com/jtrthehax/Unified-Model/blob/main/PHYSICS_SUBSTRATE_CORE/minimal_core_physics.md

**Repository Root:**  
https://github.com/jtrthehax/Unified-Model

**Primary Scientific Artifact (Zenodo DOI):**  
https://doi.org/10.5281/zenodo.20417459

---

## Contract Summary

**Input layer:** PROPRIO — ascending proprioceptive signals from muscle spindles, Golgi tendon organs, and joint mechanoreceptors; cerebellar forward model error; postural load distribution; movement trajectory and corrective micro-adjustment

**Output layer:** AUTO — sympathetic/parasympathetic balance, vagal tone, postural threat prior; COG — cognitive precision weighting, threat prior updating, available bandwidth for non-postural processing

**Primary crossover point:** The cerebellar forward model — descending motor predictions compared against ascending proprioceptive signal → corrective prediction error → autonomic coupling through postural stability signal and cognitive coupling through safety evidence for prior updating

**Key risk:** When proprioceptive signal quality degrades — through hypermobility, injury, ND motor planning differences, or chronic postural asymmetry — the corrective signal fails. The system has no mechanism to update threat priors through movement. Sustained sympathetic loading follows, and graded exposure fails not from motivation but from sensory substrate.

**Distinguishing feature:** This is the only sensory input contract where the regulatory consequence is primarily carried through movement accuracy rather than signal amplitude. The channel does not degrade loudly — it degrades silently, producing regulatory instability in the absence of obvious pain or injury, and treatment failure in the absence of obvious mechanism.

---
## The Primary Crossover Point

Ascending proprioceptive signals — from muscle spindles, Golgi tendon organs, 
and joint mechanoreceptors — feed the cerebellar predictive model continuously. 
The cerebellum holds a forward model of expected movement state: given the motor 
command that was issued, what proprioceptive signal should arrive and when? The 
comparison between predicted and actual signal generates a corrective prediction 
error that drives micro-adjustment and updates the motor model.

This corrective loop is normally invisible — the errors are small, the updates 
are continuous, and postural stability is maintained without conscious tracking. 
But the loop has two critical outputs beyond motor correction:

**Autonomic coupling:** Stable stance with symmetric bilateral load is a 
continuous low-amplitude signal to the autonomic system that the postural 
environment is manageable. Vagal tone rises. Sympathetic load decreases. The 
regulatory architecture receives a sustained permissive signal from the 
periphery. Unstable stance, asymmetric load, or unpredictable postural 
perturbations produce the reverse — sympathetic activation as compensatory 
stabilization strategy, vagal brake withdrawal.

**Cognitive coupling:** When the cerebellar forward model runs accurately — 
when predicted movement matches actual movement — the threat prior receives 
continuous updating toward safety. The body is doing what the prediction said 
it would do. The COG↔INTERO boundary receives evidence against threat 
prediction. When the forward model fails — when proprioceptive noise prevents 
accurate comparison — the same boundary receives no safety evidence. Threat 
priors are neither confirmed nor disconfirmed. The prior dominates by default.

This is the core mechanism: proprioceptive signal quality determines whether 
movement can serve as evidence for prior updating. When the signal is clean, 
movement is a corrective signal. When the signal is degraded, movement is noise — 
and the cognitive system treats the absence of corrective evidence as implicit 
threat confirmation.

---

## Link 1: The hypermobility failure mode

Hypermobility — particularly in connective tissue disorders like EDS — degrades 
proprioceptive signal quality through a specific structural mechanism. Joint 
stability normally depends on ligamentous tension providing a consistent 
mechanoreceptive loading pattern across the joint range. Mechanoreceptors in 
hypermobile joints fire across a wider range of positions than intended — the 
joint moves beyond the expected envelope — producing a proprioceptive signal 
that is structurally ambiguous.

The cerebellar forward model receives a predicted joint position. The ascending 
signal reports a different position — not because the movement was unexpected, 
but because the mechanical envelope of the joint is inconsistent. The system 
generates a corrective error. The correction adjusts motor output. The new motor 
output produces another position that is again outside expected parameters. The 
loop runs continuously without converging on a stable model.

The autonomic consequence is sustained sympathetic loading. The system cannot 
achieve stable postural prediction and responds by increasing rigidity 
parameters — muscle co-contraction, postural bracing, breath-holding — as 
compensatory stabilization. These are the same patterns that high sympathetic 
tone produces in chronic threat states. The mechanism is different — postural 
instability rather than threat perception — but the autonomic output is 
identical. The result is a regulatory baseline that appears to reflect chronic 
threat even when no threat is present.

The cognitive consequence is high load on explicit movement tracking. Posture 
and gait that should be automatic require continuous conscious monitoring. The 
bandwidth dedicated to explicit postural correction is bandwidth that is not 
available for other cognitive processes. This is one mechanism behind the 
fatigue profile characteristic of hypermobility presentations: the cost is 
not primarily metabolic but attentional — sustained explicit processing of 
what should be implicit automatic function.

**Chain completeness:** Proprioceptive impairment in EDS/hypermobility: 
Load-bearing in the hypermobility literature. Autonomic dysregulation as 
a comorbidity of EDS: load-bearing clinically. The mechanism linking them 
through cerebellar forward model failure: scaffolding — mechanistically 
coherent, requires dedicated empirical assembly.

---

## Link 2: Why graded exposure requires signal quality

The fear-avoidance loop described in NOCI↔COG establishes that chronic pain 
maintains itself by preventing the specific corrective signal — demonstrated 
safe movement — that would update the threat prior. Graded exposure works by 
systematically forcing that corrective signal through. This is the established 
mechanism.

What the NOCI↔COG contract does not address is the condition under which the 
corrective signal, once generated, actually updates the prior. The proprioceptive 
channel determines this. A movement performed within the graded exposure protocol 
produces a nociceptive outcome — less damage than predicted, or no damage at all. 
That outcome needs to register as a prediction error against the threat prior. 
For it to register, the movement signal arriving at the cerebellar model must be 
clean enough for the comparison to run.

In populations with degraded proprioceptive signal quality — hypermobility, 
chronic postural compensation, ND motor planning differences — the comparison 
does not run cleanly. The movement occurs. The absence of damage occurs. But 
the proprioceptive signal from the movement is noisy enough that the cerebellar 
model cannot confirm that the predicted movement matched the actual movement. 
Without that confirmation, the safety signal is ambiguous. Ambiguous safety 
evidence against a high-precision threat prior does not update the prior — the 
prior wins on precision weighting.

This predicts a specific failure mode in graded exposure: patients who engage 
fully with the protocol, perform movements within tolerance, experience no 
significant pain, and still show minimal prior updating — because the 
proprioceptive channel is not generating the clean corrective signal the 
updating process requires. The treatment failure looks motivational. The 
mechanism is sensory.

The intervention implication is sequential: proprioceptive signal quality should 
be established before or alongside graded exposure, not after it fails. 
Interventions that improve joint mechanoreception — orthotics, compression 
garments, movement training focused on controlled range — are not adjunctive to 
graded exposure. They are the precondition for graded exposure to work.

**Chain completeness:** Graded exposure mechanism via NOCI↔COG: load-bearing. 
Proprioceptive signal quality as precondition for prior updating: 
scaffolding — mechanistically derived, no direct empirical confirmation as 
deliberate protocol combination. Proprioceptive-specific failure mode in graded 
exposure: predictive.

---

## Link 3: Bilateral rhythmic movement and cognitive stabilization

Bilateral rhythmic movement — walking, swimming, drumming, bilateral tapping, 
certain yoga sequences — produces a proprioceptive signal pattern with 
distinctive regulatory properties. The alternating bilateral load generates a 
rhythmic cerebellar prediction-confirmation cycle: left-right-left-right, each 
stride confirming the motor prediction for that stride, generating a continuous 
low-amplitude stream of matched prediction signals.

This pattern is structurally distinct from the non-rhythmic proprioceptive 
stream. Rhythmic bilateral confirmation is not just the absence of mismatch — 
it is positive evidence of accurate world-modelling at a consistent frequency. 
The cerebellar model is receiving confirmation that its predictions are correct, 
repeatedly, at a pace that entrains the prediction cycle itself.

The cognitive consequence runs through the MOD↔COG boundary. The precision 
weighting system receives a sustained signal that the motor prediction model is 
running accurately. This generalizes — accurately running prediction models in 
the motor domain contribute to the overall precision weighting state that 
governs cognitive function. Bilateral rhythmic movement is a direct input to 
the precision gain control mechanism that determines prediction window width.

The cross-cultural ubiquity of bilateral rhythmic practices in contexts of 
emotional regulation and ritual — walking, rocking, drumming, dance — is 
consistent with this mechanism. These practices are independently discovered 
interfaces to the cerebellar confirmation cycle as a regulatory input channel. 
That cross-cultural convergence is suggestive but is not itself a mechanism 
confirmation.

**A note on EMDR:** EMDR involves bilateral stimulation and produces prior 
updating on threat-relevant content. The contract does not use EMDR as the 
primary case for this link because the confirmed mechanism for EMDR efficacy 
operates through a different channel. Bilateral eye movement forces bilateral 
hemispheric engagement through the oculomotor system, preventing the 
unilateral left-hemisphere precision lock that characterizes PTSD — this is 
the mechanism that enables prior updating during EMDR, and it belongs to 
[[contract_AUTO_MOD_autonomic_to_modulation]] and [[contract_MOD_COG_modulation_to_cognition]], not to the proprioceptive 
cerebellar channel described here. The two mechanisms are not mutually 
exclusive — bilateral proprioceptive rhythm and bilateral oculomotor tracking 
could both contribute regulatory inputs simultaneously — but they are 
mechanistically distinct and should not be collapsed. EMDR's efficacy is 
load-bearing for the oculomotor-hemispheric mechanism. It is not evidence for 
the cerebellar confirmation cycle claim.

**Chain completeness:** Cross-cultural ubiquity of bilateral rhythmic 
regulation practices: load-bearing as a convergent behavioral pattern. 
Cerebellar prediction-confirmation cycle as the mechanism: scaffolding — 
mechanistically coherent derivation from the cerebellar forward model 
architecture, no direct empirical confirmation as a deliberate regulatory 
protocol. Precision gain modulation as the pathway to cognitive stabilization: 
predictive — requires dedicated empirical assembly.

---
## Link 4: ND motor profiles and the planning-execution gap

ND motor profiles — particularly in autism and DCD — are characterized not by 
weakness or structural impairment but by a specific pattern of difficulty at 
the planning-execution boundary. Motor plans are available. Execution is slower 
to initiate, less predictable in timing, and more variable in trajectory. 
The standard framing is that this reflects poor motor coordination. The 
framework frames it differently.

If the cerebellar forward model is generating predictions based on a 
proprioceptive history that is more variable than neurotypical — either 
because proprioceptive signal quality is lower, or because the model's 
prior calibration window was shorter or differently weighted during 
development — then the confidence interval on any motor prediction is 
wider. The system knows what movement it intends to make. It has lower 
confidence about what proprioceptive signal that movement will produce. 
This lower confidence produces slower commitment to execution: the system 
is more likely to hold at the planning stage while it waits for 
higher-confidence prediction conditions.

This predicts that ND motor planning difficulty should be specifically 
worse in novel motor contexts — where the forward model has less historical 
data — and better in highly rehearsed, predictable movement sequences 
where the confidence interval on the proprioceptive prediction is narrow. 
This matches the observed profile: ND motor difficulty in novel or 
variable environments, relative fluency in highly practised routines.

The regulatory consequence extends beyond motor function. An ND nervous 
system that approaches motor execution with lower confidence is receiving 
more ambiguous proprioceptive feedback across all movement contexts. The 
sustained low-confidence proprioceptive environment contributes to the 
threat prior dominance and autonomic baseline described elsewhere in the 
framework. The motor planning gap is not a separate issue from the 
regulatory instability — it is one of the input streams maintaining it.

**Chain completeness:** ND motor planning differences: load-bearing 
clinically. Cerebellar forward model calibration as mechanism: 
scaffolding. Regulatory consequence of sustained low-confidence 
proprioception: predictive.

---

## Predictions This Contract Generates

**Prediction 1 — Chain completeness: Load-bearing (partial)**
Proprioceptive acuity measures (joint position sense error, threshold for 
detection of passive movement) should predict graded exposure outcome 
in chronic pain populations independently of pain threshold, catastrophizing 
score, and depression severity. Populations with impaired proprioceptive 
acuity should show attenuated prior updating even under equivalent movement 
exposure. This directly tests the signal quality precondition hypothesis.

**Prediction 2 — Chain completeness: Scaffolding**
HRV measures in EDS/hypermobility populations should show improvement 
following interventions targeting proprioceptive signal quality — 
compression garments, orthotics, controlled movement retraining — 
even without dedicated autonomic intervention. Effect size should 
correlate with the degree of proprioceptive acuity improvement.

**Prediction 3 — Chain completeness: Scaffolding**
Bilateral rhythmic movement added to static verbal therapy protocols 
should produce larger prediction error resolution on threat-relevant 
content than the same cognitive content processed under static conditions. 
The effect should be largest in populations with high baseline sympathetic 
tone — because the precision gain reduction from bilateral movement is 
doing more regulatory work in a higher-load state.

**Prediction 4 — Chain completeness: Predictive**
ND motor planning latency should correlate with proprioceptive signal 
variability — not with muscle strength or structural motor capacity. 
In novel movement contexts, response initiation latency should predict 
joint position sense error at baseline. In rehearsed movement contexts, 
the correlation should disappear as the forward model's confidence 
interval narrows with repetition.

**Prediction 5 — Chain completeness: Predictive**
Movement practices with high proprioceptive demand — yoga, martial arts, 
dance — should produce measurable HRV improvement through a pathway 
distinct from the metabolic and ECS mechanisms identified in the 
existing literature. Controlling for metabolic load and session 
duration, the HRV improvement should correlate with movement 
complexity and proprioceptive precision demand rather than with 
intensity alone.

---

Yes. Based on what's in the vault, here are the four missing sections drafted in house style. Drop them in after the Predictions section and before Adjacent Contracts.

---

## The Complete Chain

```
Descending motor command
  → Cerebellar forward model generates prediction
    (expected proprioceptive signal given command issued)
      → Movement executes
        → Ascending proprioceptive signal arrives
          (muscle spindles, GTOs, joint mechanoreceptors)
            → Comparison: predicted vs actual

            If signal clean:
              → Small corrective error
                → Motor model updates fluidly
                  → Autonomic coupling: stable prediction
                    → Vagal tone rises, sympathetic load drops
                  → Cognitive coupling: safety evidence generated
                    → Threat prior updates toward baseline

            If signal degraded:
              → Noisy or ambiguous error
                → Motor model cannot converge
                  → Autonomic coupling: instability detected
                    → Sympathetic activation as compensatory bracing
                  → Cognitive coupling: no safety evidence generated
                    → Threat prior maintained by default
                      → Prior dominates by precision weighting
```

---

## Operating States

| State                                     | Proprioceptive Signal                                                    | Autonomic Output                                                | Cognitive Output                                                          | Clinical Signature                                                                                           |
| ----------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Intact signal, stable movement**        | Clean, consistent mechanoreceptor firing within joint envelope           | Vagal tone high, sympathetic load low                           | Threat prior updates toward safety continuously                           | Normal baseline regulatory function                                                                          |
| **Hypermobility / EDS**                   | Structurally ambiguous — mechanoreceptors fire outside expected envelope | Sustained sympathetic loading, postural bracing, breath-holding | Bandwidth consumed by explicit postural tracking                          | Chronic regulatory dysregulation without obvious threat; fatigue profile disproportionate to activity level  |
| **ND motor planning — novel context**     | Variable, lower-confidence forward model predictions                     | Elevated sympathetic tone during initiation phase               | Higher threshold for movement commitment; initiation latency elevated     | Movement hesitation in unfamiliar contexts; relative fluency in rehearsed sequences                          |
| **ND motor planning — rehearsed context** | Adequate — forward model has sufficient historical data                  | Sympathetic load lower, initiation smoother                     | Threat prior less activated                                               | Competent performance in practiced routines; apparent inconsistency confuses observers                       |
| **Graded exposure, clean signal**         | Sufficient for cerebellar comparison to run                              | Safety evidence generated per movement cycle                    | Threat prior updates toward safety with each exposure                     | Graded exposure works as intended                                                                            |
| **Graded exposure, degraded signal**      | Too noisy for cerebellar comparison to confirm match                     | No safety evidence generated                                    | Threat prior unchanged despite completed movements                        | Graded exposure failure that looks motivational; mechanism is sensory                                        |
| **Chronic postural compensation**         | Asymmetric, high co-contraction loading pattern                          | Sustained sympathetic tone, reduced vagal brake                 | Implicit threat confirmation from postural prediction failures            | Fatigue, cognitive fog, and anxiety without identifiable stressor                                            |
| **Bilateral rhythmic movement**           | Consistent rhythmic confirmation stream at cerebellar model              | Vagal tone rises, precision gain reduces                        | Prediction window widens; threat prior receives sustained safety evidence | Regulatory stabilization through movement — walking, swimming, drumming                                      |

---

## Failure Modes

**Treating regulatory instability in hypermobility as psychological:**
EDS and hypermobility presentations routinely include anxiety, fatigue, and autonomic dysregulation. These are attributed to psychological comorbidity or poor coping. The contract predicts they are mechanically generated — sustained sympathetic loading from a cerebellar forward model that cannot converge on stable postural prediction. The autonomic output is identical to chronic threat states. The mechanism is entirely different. Interventions targeting anxiety directly while leaving proprioceptive signal quality unaddressed are treating the output of the mechanism rather than the mechanism. 

**Misattributing graded exposure failure to motivation:**
When graded exposure fails in chronic pain populations — full protocol engagement, adequate movement, no significant pain, minimal prior updating — the standard attribution is catastrophizing, low motivation, or treatment resistance. The contract predicts a proportion of these failures are proprioceptive: the corrective signal was generated but was too noisy for the cerebellar comparison to confirm it, so no safety evidence reached the threat prior. The treatment failure is sensory, not psychological. Proprioceptive signal quality should be assessed before graded exposure is repeated or escalated. 

**Missing the sequential intervention requirement:**
Orthotics, compression garments, and joint-stabilising movement training are routinely described as adjunctive to pain management or graded exposure — something added after primary treatment. The contract places them as preconditions. Clean proprioceptive signal is required for graded exposure to produce prior updating. Establishing signal quality first is not augmentation. It is the substrate without which the primary intervention cannot function. Reversing the sequence produces the predictable result: the primary intervention fails, and the adjunct is never tried because the patient has already dropped out. 

**ND motor difficulty framed as coordination deficit:**
The standard clinical framing of ND motor profiles — particularly DCD and autism — treats planning-execution difficulties as coordination or motor control problems requiring motor skills training. The contract frames them as forward model calibration problems: wider confidence intervals on proprioceptive predictions producing slower execution commitment under novel conditions. Motor skills training in novel contexts applies the intervention to the wrong layer. High-repetition rehearsal in predictable environments narrows the confidence interval, which is why it works. Understanding the mechanism predicts which training designs produce benefit and which produce frustration without transfer. 

---

## Drug and Intervention Effects Through This Contract

| Intervention | Mechanism | Effect |
|---|---|---|
| Compression garments | Increase mechanoreceptor loading consistency across joint range | Improved signal quality → cerebellar comparison can run → safety evidence generated → prior updating possible |
| Orthotics | Constrain joint range to expected envelope | Reduces mechanoreceptor firing outside intended range → signal ambiguity decreases → forward model convergence improves |
| Controlled range movement training | Builds forward model confidence interval through rehearsal | Narrows prediction uncertainty → initiation latency decreases → movement becomes corrective rather than noise |
| Graded exposure (on clean substrate) | Forces corrective movement signal through threat prior | Works as intended when proprioceptive signal quality is sufficient for comparison to confirm safety [^2] |
| Bilateral rhythmic movement | Generates rhythmic cerebellar prediction-confirmation stream | Positive safety evidence at consistent frequency → precision gain reduces → prediction window widens [^1] |
| Yoga / martial arts / dance | High proprioceptive precision demand with controlled repetition | Builds forward model accuracy over time → HRV improvement via autonomic coupling, distinct from metabolic pathway [^1] |
| Anti-inflammatory intervention | Reduces connective tissue inflammatory load → mechanoreceptor signal quality improvement | Upstream contract repair — [[contract_IMMUNE_AUTO_immune_to_autonomic]] feeds into signal substrate [^3] |
| Proprioceptive taping (kinesiology tape) | Augments mechanoreceptor input at specific joint sites | Increased signal amplitude → reduced ambiguity → improved forward model comparison |

---

## Origin Note

This contract emerged from two convergent observations. The first was the hypermobility-dysautonomia comorbidity pattern — autonomic dysregulation appearing at rates far above base in EDS populations, without a mechanism that any single contract in the stack could explain. The MET, IMMUNE, and MICRO contracts address metabolic and inflammatory routes into autonomic state. None addressed the continuous postural proprioceptive stream that runs in parallel with all of them.

The second was the graded exposure failure pattern in chronic pain. NOCI↔COG establishes the fear-avoidance loop and graded exposure as its resolution mechanism. The framework provides the mechanism for why exposure works. It does not explain why it sometimes fails in patients who are fully engaged. The missing variable was proprioceptive signal quality — the condition under which the corrective signal, once generated, actually registers as safety evidence rather than noise. 

The ND motor difficulty observation was the minority invariant. The planning-execution gap in autism and DCD is well-documented clinically and consistently attributed to motor coordination deficit. The contract reframes it: not coordination but forward model confidence interval. The prediction that difficulty should be context-specific — worse in novel, better in rehearsed — was derived from the mechanism before checking the clinical literature. It matches. This reframe has direct intervention implications: rehearsal works because it narrows the confidence interval, not because it trains a skill. The same training logic applied to novel contexts should fail, and it does. 

*Chain status: Links 1 and 3 are scaffolding with load-bearing components — proprioceptive impairment in EDS and ND motor profiles are clinically load-bearing; the cerebellar forward model as the connecting mechanism requires dedicated empirical assembly. Link 2 is scaffolding approaching load-bearing — graded exposure mechanism is load-bearing via NOCI↔COG; proprioceptive signal quality as the precondition for prior updating is mechanistically complete but not yet tested as a deliberate protocol variable. Link 4 is scaffolding. Predictions 1 and 5 are the highest-priority empirical tests the contract generates.*

---
## Adjacent Contracts

**Feeds into this contract:**
- [[contract_MET_AUTO_metabolic_to_autonomic]] — metabolic load during movement affects autonomic baseline
- [[contract_IMMUNE_AUTO_immune_to_autonomic]] — inflammatory state degrades connective tissue → reduces mechanoreceptor signal quality
- [[contract_NOCI_COG_nociception_to_cognition]] — nociceptive precision gain determines the signal-to-noise ratio within which proprioceptive corrective signals must compete

**This contract writes into:**
- [[contract_COG_INTERO_cognition_to_interoception]] — accurate movement prediction updates the body-state prior
- [[contract_AUTO_MOD_autonomic_to_modulation]] — postural stability modulates vagal tone → CB1 / hemispheric lateralization
- [[contract_MOD_COG_modulation_to_cognition]] — precision gain state set by proprioceptive inputs affects all downstream cognition

**Convergence note:**
PROPRIO↔AUTO/COG is a convergence point for multiple upstream contracts 
simultaneously — immune-driven connective tissue degradation, metabolic 
load affecting movement capacity, nociceptive gain amplifying movement 
signals to threat level, and developmental calibration of the motor 
forward model. Presentations involving proprioceptive dysregulation are 
therefore compound failure states by architecture. Single-point intervention 
— pain management alone, or movement therapy alone — cannot resolve them. 
This places the contract in the same structural category as NOCI↔COG: 
a convergence contract requiring multi-layer intervention design.