# COAGULATION OF BLOOD

* **Clotting is the process** in which blood loses its fluidity and becomes a jelly-like mass few minutes after it is shed out.

---

## FACTORS INVOLVED IN BLOOD CLOTTING

* Coagulation of blood occurs through a series of reactions due to activation of a group of substances called **clotting factors**.

### Mnemonic for Clotting Factors
> *"Foolish People Try Climbing Long Slopes After Christmas, Some People Have Fallen"*

| Factor | First Letter | Name of Factor |
| :--- | :---: | :--- |
| **Factor I** | **F** | Fibrinogen |
| **Factor II** | **P** | Prothrombin |
| **Factor III** | **T** | Thromboplastin |
| **Factor IV** | **C** | Calcium ($\text{Ca}^{2+}$) |
| **Factor V** | **L** | Labile factor |
| **Factor VII** | **S** | Stable factor |
| **Factor VIII** | **A** | Antihemophilic factor A |
| **Factor IX** | **C** | Christmas factor |
| **Factor X** | **S** | Stuart–Prower factor |
| **Factor XI** | **P** | Plasma thromboplastin antecedent |
| **Factor XII** | **H** | Hageman factor |
| **Factor XIII** | **F** | Fibrin-stabilising factor |

---

## CLOTTING MECHANISM (ENZYME CASCADE THEORY)

* Clotting factors are proteins *(in form of enzymes)*.
* All factors are present in the form of **inactive proenzymes** $\longrightarrow$ converted into **active enzymes** $\longrightarrow$ enforce clot formation.
* **Cascade Process :** Occurs through a series of steps, each step initiating the next until the final step is reached.

---

### 3 STAGES OF BLOOD CLOTTING

* a. **Stage 1 :** Formation of prothrombin activator
* b. **Stage 2 :** Conversion of prothrombin to thrombin
* c. **Stage 3 :** Conversion of fibrinogen to fibrin

---

### COMPREHENSIVE CASCADE (STAGES 1, 2 & 3)

```mermaid
flowchart TD
    %% STAGE 1: INTRINSIC PATHWAY
    subgraph Stage1_Intrinsic ["Stage 1: Intrinsic Pathway"]
        Endo["Endothelial damage + collagen exposure"] -->|"Kallikrein + HMW Kininogen"| XIIa["Factor XIIa"]
        XII["Factor XII"] --> XIIa
        XIIa -->|"HMW Kininogen"| XIa["Factor XIa"]
        XI["Factor XI"] --> XIa
        XIa -->|"Ca²⁺"| IXa["Factor IXa"]
        IX["Factor IX"] --> IXa
        IXa -->|"Factor VIII + Ca²⁺"| Xa_int["Factor Xa"]
        X_int["Factor X"] --> Xa_int
    end

    %% STAGE 1: EXTRINSIC PATHWAY
    subgraph Stage1_Extrinsic ["Stage 1: Extrinsic Pathway"]
        Trauma["Tissue trauma"] --> TP["Tissue thromboplastin (Glycoprotein + Phospholipid)"]
        TP -->|"Factor VII"| Xa_ext["Factor Xa"]
        X_ext["Factor X"] --> Xa_ext
    end

    %% PROTHROMBIN ACTIVATOR FORMATION
    Xa_int -->|"Factor V + Platelet Phospholipid + Ca²⁺"| PA["Prothrombin Activator"]
    Xa_ext -->|"Factor V + Phospholipid + Ca²⁺"| PA

    %% STAGE 2
    subgraph Stage2 ["Stage 2: Thrombin Formation"]
        Prothrombin["Prothrombin (Factor II)"] -->|"Prothrombin Activator + Ca²⁺"| Thrombin["Thrombin (Factor IIa)"]
    end
    PA --> Stage2

    %% POSITIVE FEEDBACK
    Thrombin -.->|"Positive Feedback (Activates Factor V & VIII)"| PA

    %% STAGE 3
    subgraph Stage3 ["Stage 3: Fibrin Formation & Meshwork"]
        Fibrinogen["Inactive Fibrinogen"] -->|"Thrombin (Loss of 2 pairs of polypeptides)"| FibMono["Active Fibrinogen (Fibrin Monomer)"]
        FibMono -->|"Polymerization"| LooseFib["Loosely arranged strands of fibrin"]
        LooseFib -->|"Factor XIII + Ca²⁺"| TightFib["Dense & tight fibrin threads (Stable Clot)"]
    end
    Thrombin --> Stage3

```

> ![alt text](images/BloodCoagulation.png)

---

## STAGE 1: FORMATION OF PROTHROMBIN ACTIVATOR

Occurs through **two pathways**:

### 1. Intrinsic Pathway

* Initiated by platelets **within blood itself**.

```mermaid
flowchart TD
    A["During injury (blood vessels ruptured)"] --> B["Endothelium damaged (collagen is exposed)"]
    B --> C["Factor XII (Hageman factor) in contact with collagen"]
    C -->|"Kallikrein, HMW Kininogen"| D["Activated Factor XII (XIIa)"]
    D -->|"HMW Kininogen"| E["Activated Factor XI (XIa)"]
    E -->|"Factor IV (Calcium)"| F["Activated Factor IX (IXa)"]
    F -->|"Factor VIII + Calcium"| G["Activates Factor X (Xa)"]
    G --> H["Reacts with platelet phospholipid & Factor V (in presence of Ca²⁺)"]
    H --> I["PROTHROMBIN ACTIVATOR"]

```

---

### 2. Extrinsic Pathway

* Initiated by **tissue thromboplastin** formed from injured tissues.

```mermaid
flowchart TD
    A["Tissues that are damaged (injury)"] --> B["Release Tissue Thromboplastin (Factor III)<br><i>(Contains proteins, phospholipids, glycoprotein)</i>"]
    B -->|"Activates Factor VII"| C["Activated Factor X (Xa)"]
    C --> D["Reacts with Factor V & phospholipid component of tissue thromboplastin + Ca²⁺"]
    D --> E["PROTHROMBIN ACTIVATOR"]

```

---

## STAGE 2: CONVERSION OF PROTHROMBIN TO THROMBIN

* Blood clotting is centered around **thrombin formation**, which triggers clot assembly.

$$\text{Prothrombin} \xrightarrow{\text{Prothrombin Activator} + \text{Ca}^{2+}} \text{Thrombin}$$

* **Positive Feedback Effect :—**
Thrombin accelerates the activation of **Factor V and Factor VIII**, accelerating further prothrombin activator formation.

---

## STAGE 3: CONVERSION OF FIBRINOGEN TO FIBRIN

* Final stage of blood clotting.

$$\text{Inactive Fibrinogen} \xrightarrow[\text{(Loss of 2 pairs of polypeptides)}]{\text{Thrombin}} \text{Active Fibrinogen (Fibrin Monomer)}$$

$$\downarrow$$

$$\text{Polymerization}$$

$$\downarrow$$

$$\text{Loosely arranged strands of Fibrin}$$

$$\downarrow \ \text{Factor XIII (Fibrin-Stabilizing Factor)} + \text{Ca}^{2+}$$

$$\text{Dense \& tight fibrin threads}$$

$$\downarrow$$

$$\text{Aggregate to form a meshwork of \textbf{Stable Clot}}$$

