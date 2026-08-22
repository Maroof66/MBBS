# IRON METABOLISM

* **Trace element**
* **Total body content :—** 3 to 5 gm (75% $\longrightarrow$ Hb)

---

### PROTEINS CONTAINING IRON

* **Heme & Non-Heme Proteins :—**
  * Hemoglobin
  * Myoglobin
  * Cytochromes
  * Iron-sulfur proteins
  * Cyt P450
* **Enzymes :—**
  * Catalase
  * Xanthine oxidase
  * Tryptophan pyrrolase
  * NOS (Nitric oxide synthase)
  * Aconitase

---

### FUNCTIONS

* a. **Transport of $\text{O}_2$ to tissues** and $\text{CO}_2$ to lungs
* b. **Important constituent of myoglobin** in muscle
* c. **Electron transport chain** (Cytochrome & Fe-S proteins)
* d. **Detoxification** (Cyt P450)
* e. **Antioxidant**
* f. **Purine degradation** (Xanthine oxidase)
* g. **Tyrosine metabolism**

---

### RECOMMENDED DIETARY ALLOWANCE (RDA)

* **Adult male :—** 10 mg
* **Female :—** 20 mg
* **Pregnancy and lactation :—** 40 mg

---

### SOURCES

* **Green leafy vegetables :—** 20 mg / 100 gm
* **Pulses :—** 10 mg / 100 gm
* **Cereals :—** 5 mg / 100 gm
* **Liver :—** 5 mg / 100 gm
* **Meat :—** 2 mg / 100 gm
* **Others :—** Jaggery, dry fruits, beetroots, etc.

---

## ABSORPTION, TRANSPORT AND STORAGE

| Factors $\uparrow\uparrow$ Iron Absorption | Factors $\downarrow\downarrow$ Iron Absorption |
| :--- | :--- |
| • Vitamin C<br>• Gastric HCl<br>• Small peptides<br>• Cysteine | • Phytate<br>• Oxalate<br>• Phosphate<br>• Lead |

---

### MECHANISM OF ABSORPTION & TRANSPORT

```mermaid
flowchart TD
    Diet["Dietary Iron (Fe³⁺)"]
    Red["Vit C / Duodenal Cyt B"]
    Fe2["Fe²⁺"]
    DMT1["DMT1 (Divalent Metal Transporter 1)"]
    Entero["Duodenal Enterocyte"]
    StorageE["Ferritin (Fe³⁺)"]
    FP["Ferroportin"]
    Fe2_blood["Fe²⁺"]
    Cp["Ceruloplasmin"]
    Fe3_blood["Fe³⁺"]
    TF["Transferrin (Transport form)<br>[Apotransferrin + Fe³⁺]"]
    
    Diet -->|Reduced by| Red
    Red --> Fe2
    Fe2 -->|Enters via| DMT1
    DMT1 --> Entero
    Entero -.-> StorageE
    Entero -->|Exits via| FP
    FP --> Fe2_blood
    Fe2_blood -->|Oxidized by| Cp
    Cp --> Fe3_blood
    Fe3_blood --> TF
    
    subgraph Tissue_Destinations ["Fate of Iron"]
        TF -->|Storage Form| SF["Ferritin / Hemosiderin<br><i>(Liver, Spleen, Bone Marrow)</i>"]
        TF -->|Utilization| UF["Hb, Mb, Cytochromes, Enzymes"]
    end

```

> ![alt text](images/Iron.png)

---

### REGULATION & EXCRETION

* **Hepcidin $\longrightarrow$** Regulate iron level $\longrightarrow$ $\downarrow$ intestinal absorption:
* Peptide produced by liver.
* Blocks ferroportin.
* Causes internalization and degradation of cellular iron exporter [DMT-1 / Ferroportin].


* **Iron is the "One-way Element" :—**
* Utilized and reutilised again & again.
* $< 1\text{ mg/day}$ excreted in $\longrightarrow$ bile, sweat, hair loss.
* **Mucosal Block Theory :—** At mucosal level, regulation of iron level occurs.
* **Almost no iron excreted through urine.** Feces contains unabsorbed & trapped iron in intestinal cells that are desquamated.



---

## CLINICAL SIGNIFICANCE: IRON DEFICIENCY ANEMIA

### Causes:

* $\uparrow$ Demand
* $\downarrow$ Intake
* Chronic blood loss
* Lead
* Repeated pregnancies

### Symptoms:

* a. **Anemia $\longrightarrow$ Microcytic hypochromic anemia:**
* RBCs have less Hb than normal
* Small sized RBCs
* $\downarrow\text{ MCV}$, $\downarrow\text{ MCH}$


* b. **Apathy :—**
* Sluggish, dull child
* Decreased school performance
* Fatigue, weakness



### Lab Diagnosis:

* $\downarrow\text{ Hb}$
* *Normal range:* $14\text{ – }16\text{ gm/dL}$ in males; $13\text{ – }15\text{ gm/dL}$ in females


* $\uparrow\text{ Total Iron Binding Capacity (TIBC)}$
* $\text{Serum Iron } \downarrow$, $\text{Serum Ferritin } \downarrow$
* $\downarrow\text{ MCV}$, $\downarrow\text{ MCH}$

### Treatment:

* Oral iron therapy: $100\text{ – }200\text{ mg/day}$
* Increase consumption of dietary iron
* Treatment of underlying cause
* IV iron in severe cases

---

## IRON OVERLOAD DISORDERS

### 1. Hemosiderosis

* Excess iron due to $\uparrow$ absorption.
* **Iron overload disorder** due to accumulation of **hemosiderin**.
* The pigment does not damage the parenchymal cells.
* Found in **Bantu tribe of South Africa** *(also called **Bantu siderosis**)*.

---

### 2. Hemochromatosis

* **Excess iron deposited in:** Skin, bone marrow, liver, spleen, pancreas.

```mermaid
flowchart TD
    HC["Excess Iron Deposition<br>(Hemochromatosis)"]
    
    HC -->|1| Skin["Skin: Yellow-brown discoloration<br>(Bronze Pigmentation)"]
    HC -->|2| Panc["Pancreas: Impaired glucose tolerance<br>→ Diabetes"]
    HC -->|3| Liv["Liver: Cirrhosis of liver"]
    
    Skin --> BD["Bronze Diabetes"]
    Panc --> BD
    Liv --> BD

```

> **Bronze Diabetes :—** Triad of bronze pigmentation of skin (1), diabetes due to pancreatic damage (2), and cirrhosis of liver (3).
