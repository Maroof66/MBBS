# REGULATION OF PANCREATIC SECRETION

> ### HEADINGS 
> ![alt text](images/headingsRegOfPan.png)

* Secretion of pancreatic juice is regulated by both **nervous and hormonal factors**.

---

### STAGES OF PANCREATIC SECRETION

Occurs in **3 stages** *(corresponds with the 3 phases of gastric secretion)*:
* a. Cephalic phase
* b. Gastric phase
* c. Intestinal phase

---

## 1. CEPHALIC PHASE

* Regulated by **nervous mechanism through reflex action**.
* **2 Types :—**
  * a. Unconditioned reflex
  * b. Conditioned reflex

---

### A. Unconditioned Reflex

```mermaid
flowchart TD
    A["Presence of food in mouth stimulates taste buds & other receptors"] --> B["Sensory (afferent) impulses reach dorsal nucleus of vagus"]
    B --> C["Efferent impulses (vagal efferent nerve fibers) reach pancreatic acini"]
    C --> D["Vagal efferent nerve endings secrete acetylcholine"]
    D --> E["Stimulates pancreatic secretion"]

```

---

### B. Conditioned Reflex

```mermaid
flowchart TD
    A["Impulses from special sensory organs (eye, ear, & nose) / sight, smell, thought of food"] --> B["Afferent fibers of neural circuits to cerebral cortex"]
    B --> C["Impulses pass through dorsal nucleus of vagus & vagal efferents"]
    C --> D["Reach pancreatic acini (vagal nerve endings secrete acetylcholine)"]
    D --> E["Stimulates pancreatic secretion"]

```

---

## 2. GASTRIC PHASE

* **Secretion of pancreatic juice** when food enters the stomach.
* This phase is under **hormonal control (Gastrin)**.

```mermaid
flowchart TD
    A["Food enters stomach (Gastric secretion)"] --> B["Gastrin secreted by G-cells"]
    B --> C["Gastrin transported to pancreas through blood"]
    C --> D["Stimulates pancreatic secretion"]

```

---

## 3. INTESTINAL PHASE

* **Secretion of pancreatic juice** when chyme enters the intestine.
* This phase is also under **hormonal control**:
* Some hormones **stimulate** pancreatic secretion.
* Some hormones **inhibit** pancreatic secretion.



---

### HORMONES STIMULATING PANCREATIC SECRETION

* a. **Secretin**
* b. **Cholecystokinin (CCK / CCK-PZ)**

---

#### 1. Secretin

* **Production :** Produced by **S-cells** of mucous membrane in duodenum & jejunum.

$$\text{Inactive Prosecretin} \xrightarrow{\text{Acid chyme (HCl)}} \text{Secretin}$$


* **Actions of Secretin :—**
* a. Stimulates secretion of **watery juice** *(rich in bicarbonate ions and high in volume)*.
* b. Increases pancreatic secretion by acting on **pancreatic ductules** via **cyclic AMP (cAMP)** as second messenger.



---

#### 2. Cholecystokinin (CCK / Cholecystokinin–Pancreozymin / CCK-PZ)

* **Production :** Secreted by **I-cells** in duodenal & jejunal mucosa.
* **Stimulant for Release :** Chyme containing digestive products such as **fatty acids (FA), peptides, and amino acids (AA)**.
* **Actions of Cholecystokinin :—**
* a. Stimulates secretion of **pancreatic juice** *(rich in enzymes and very low in volume)*.
* b. Acts on **pancreatic acinar cells** via **Inositol Triphosphate ($\text{IP}_3$)** as second messenger.



---

### HORMONES INHIBITING PANCREATIC SECRETION

* a. **Pancreatic Polypeptide (PP) :—** Secreted by PP cells in islets of Langerhans of pancreas.
* b. **Somatostatin :—** Secreted by D-cells in islets of Langerhans of pancreas.
* c. **Peptide YY :—** Secreted by intestinal mucosa.
* d. **Other Peptides :—** Such as ghrelin & leptin.

---

## SCHEMATIC REGULATION SUMMARY

```mermaid
flowchart TD
    %% CEPHALIC
    subgraph Cephalic_Phase ["CEPHALIC PHASE: Nervous"]
        CR["Conditioned reflex<br>(Sight, smell, thought & hearing of food)"]
        UR["Unconditioned reflex<br>(Presence of food in mouth)"]
        Vagus["Vagus nerve"]
        CR --> Vagus
        UR --> Vagus
        Vagus --> Sec1["Secretion of pancreatic juice"]
    end

    %% GASTRIC
    subgraph Gastric_Phase ["GASTRIC PHASE: Hormonal"]
        Bolus["Bolus in stomach / Gastric secretion"] --> Gastrin["Gastrin"]
        Gastrin --> Sec2["Secretion of pancreatic juice"]
    end

    %% INTESTINAL
    subgraph Intestinal_Phase ["INTESTINAL PHASE: Hormonal"]
        Chyme["Chyme in intestine"] --> Sec_Horm["Secretin"]
        Chyme --> CCK_Horm["Cholecystokinin"]
        Sec_Horm --> SecBic["Secretion of pancreatic juice<br>(Rich in bicarbonate)"]
        CCK_Horm --> SecEnz["Secretion of pancreatic juice<br>(Rich in enzymes)"]
    end

```

> ![alt text](images/regnofpancreassecretion.png)