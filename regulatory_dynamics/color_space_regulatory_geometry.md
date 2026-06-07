# **📄 Synthesis Document: Color‑Space Geometry ↔ Regulatory Geometry**
### *A unifying explanation for why regulatory states map to universal color regions*

---

## **1. Purpose of This Document**
This synthesis document formalizes the structural equivalence between:

- **human color‑space geometry**, and  
- **the cognitive–reasoning manifold described in the COG ↔ REASON contract**, and  
- **the regulatory‑state manifold described across the minimal core and adjacent contracts.**

This equivalence explains:

- why internal regulatory states reliably map to specific color regions,  
- why these mappings are **universal** rather than subjective,  
- and why reasoning distortions follow the same geometric rules as perceptual distortions.

This document exists so that individual contracts do not need to carry this explanatory load.

---

## **2. Core Claim**
> **Color perception and regulatory-state computation share the same underlying metric geometry.  
> Therefore, color regions correspond to regulatory modes because both systems implement the same invariants.**

This is not metaphorical.  
It is a structural isomorphism.

---

## **3. Shared Geometric Invariants**

### **3.1 Neutral Axis**
Color‑space:  
- black–white axis defines the perceptual zero-line.

Regulatory system:  
- inhale–exhale midpoint defines the cognitive neutral axis.

**Shared property:**  
Both systems require a stable reference line to compute distances, transitions, and similarity.

---

### **3.2 Curvature**
Color‑space:  
- luminance changes alter curvature (Bezold–Brücke effect).

Regulatory system:  
- precision gain alters curvature of the reasoning manifold.

**Shared property:**  
Curvature determines how “straight” the shortest path feels.

---

### **3.3 Geodesics**
Color‑space:  
- perceptual transitions follow shortest paths in the metric.

Regulatory system:  
- reasoning transitions follow shortest paths given precision and window width.

**Shared property:**  
Distortions arise when curvature increases or the neutral axis drifts.

---

## **4. Mapping Color Regions to Regulatory Modes**

### **4.1 Blue — Stability / Baseline**
Color‑space:  
- sits near the neutral axis  
- low curvature  
- perceptually stable  

Regulatory system:  
- centered prediction window  
- balanced precision  
- anchored reasoning  

**Interpretation:**  
Blue corresponds to the regulatory baseline.

---

### **4.2 Green — Exploration / Openness**
Color‑space:  
- low curvature region  
- smooth transitions  
- high discriminability  

Regulatory system:  
- wide prediction window  
- low prior dominance  
- exploratory reasoning  

**Interpretation:**  
Green corresponds to the exploratory mode.

---

### **4.3 Red/Yellow — Reactivity / Urgency**
Color‑space:  
- high curvature  
- small changes → large perceptual shifts  

Regulatory system:  
- precision spikes  
- narrowed window  
- rigid shortcuts  
- threat‑biased inference  

**Interpretation:**  
Red/yellow correspond to reactive modes.

---

### **4.4 Purple — Boundary / Liminal**
Color‑space:  
- near manifold edges  
- low stability  
- high sensitivity  

Regulatory system:  
- identity boundary  
- introspection  
- liminal reasoning  

**Interpretation:**  
Purple corresponds to boundary states.

---

## **5. Why This Mapping Is Universal**
Because both systems — visual color perception and regulatory-state computation — are:

- biological  
- metric  
- invariant  
- geometry‑driven  

The mapping is not preference‑based.  
It is **structural**.

This explains why:

- people with wide windows “feel green,”  
- people with stable baselines “feel blue,”  
- people in precision spikes “feel red/yellow,”  
- people in identity transitions “feel purple.”

You are not reading personality.  
You are reading **geometry**.

---

## **6. Placement in the Framework**
This synthesis document sits **above**:

- COG ↔ REASON  
- COG ↔ INTERO  
- MOD ↔ COG  
- AUTO ↔ MOD  

and provides the geometric substrate that those contracts rely on.

It should be referenced in:

- COG ↔ REASON (mechanism of fallacies)  
- minimal_core.md (regulatory manifold definition)  
- any future perceptual or cognitive contracts  

---

## **7. Invariant Statement**
> **Color-space geometry is the perceptual expression of the same manifold the regulatory system uses internally.  
> Therefore, color regions are reliable, universal markers of regulatory modes.**

---

## **8. Optional Mermaid Diagram (GitHub‑compatible)**

```mermaid
flowchart TD
    A[Regulatory Geometry] --> B[Neutral Axis]
    A --> C[Curvature]
    A --> D[Geodesics]

    B --> E[Blue Region<br/>Stability]
    C --> F[Green Region<br/>Exploration]
    C --> G[Red/Yellow<br/>Reactivity]
    D --> H[Purple<br/>Liminal]

    E --> I[Centered Reasoning]
    F --> J[Exploratory Reasoning]
    G --> K[Shortcut Reasoning / Fallacies]
    H --> L[Identity-Edge Reasoning]

flowchart TD
    subgraph REG[Regulatory Geometry]
        A[Prediction Window / Precision Gain]
        B[Neutral Axis]
        C[Curvature]
        D[Geodesics]
    end

    subgraph COLOR[Color-Space Regions]
        E[Blue<br/>Stability]
        F[Green<br/>Exploration]
        G[Red / Yellow<br/>Reactivity]
        H[Purple<br/>Liminal / Boundary]
    end

    subgraph REASON[Reasoning Modes]
        I[Anchored Reasoning]
        J[Exploratory Reasoning]
        K[Shortcut / Fallacy-Prone Reasoning]
        L[Identity-Edge Reasoning]
    end

    A --> B
    A --> C
    A --> D

    B --> E
    C --> F
    C --> G
    D --> H

    E --> I
    F --> J
    G --> K
    H --> L

    classDef blue fill:#1e3a8a,stroke:#0f172a,color:#f9fafb;
    classDef green fill:#15803d,stroke:#052e16,color:#f9fafb;
    classDef red fill:#b91c1c,stroke:#450a0a,color:#f9fafb;
    classDef yellow fill:#ca8a04,stroke:#78350f,color:#f9fafb;
    classDef purple fill:#6d28d9,stroke:#3b0764,color:#f9fafb;

    class E blue;
    class F green;
    class G red;
    class H purple;

```
