# HEME CATABOLISM / BILIRUBIN METABOLISM

> ### Headings
> ![alt text](images/HemeCataHedings.png)

**Site :** Macrophages of Reticuloendothelial System (Liver, Spleen, Bone Marrow)

---

### Synthesis & Transport Pathway

```mermaid
flowchart TD
    HB["Hb (Hemoglobin)"]
    GLOBIN["Globin &rarr; Amino acids"]
    HEME["Heme"]
    BV["Biliverdin (green)"]
    BR["Bilirubin (yellow)<br>(Unconjugated bilirubin)"]
    COMPLEX["Albumin-Bilirubin Complex"]
    LIVER["Liver"]

    HB --> GLOBIN
    HB --> HEME
    HEME -->|"Heme oxygenase (Microsome)<br>+ NADPH, O₂<br>Cleaves α-methenyl bridge<br>Releases Fe³⁺, CO"| BV
    BV -->|"Biliverdin Reductase<br>Methenyl bridge &rarr; Methylene bridge<br>(III & IV pyrrole)"| BR
    BR -->|"+ Albumin (Transport)"| COMPLEX
    COMPLEX --> LIVER
```

---

### Albumin Binding Sites

* **High affinity binding site :** $\approx 25\text{ mg}$
* **Low affinity site :** Easily detached and diffuses into tissue in diseases

---

### Metabolism of Bilirubin

* 1. Uptake of bilirubin in Hepatocytes


* 2. Conjugation


* 3. Secretion into bile canaliculi

# BILIRUBIN UPTAKE & CONJUGATION

---

### 1. Uptake of Bilirubin in Hepatocyte (Facilitated Diffusion)

* **Transport Mechanism :** Albumin-bound bilirubin ($\text{Alb-Bil}$) in the blood dissociates; free bilirubin crosses the sinusoidal membrane into hepatocytes via **facilitated diffusion**.
* **Kinetics :**
  * Large capacity system.
  * **Not a rate-limiting step**, even in pathological states.
* **Intracellular Binding (Ligandin Proteins / Y-Protein) :**
  * Binds bilirubin inside the hepatocyte.
  * **Prevents efflux** of bilirubin back into the bloodstream.
  * Keeps bilirubin in a **solubilized state**.
* **Clinical Correlation :** Defect in uptake is associated with **Gilbert syndrome / disease**.

---

### 2. Conjugation & Hepatic Fate

```mermaid
flowchart TD
    UB["<b>Bilirubin (Unconjugated)</b>"]
    
    UB -->|"+ UDP-Glucuronate<br>UDP-Glucuronyl Transferase<br>(Deficient in Crigler-Najjar Type 1 & 2)"| BMG["<b>Bilirubin monoglucuronide</b>"]
    
    BMG -->|"+ UDP-Glucuronate<br>UDP-Glucuronyl Transferase"| BDG["<b>Bilirubin diglucuronide</b><br>(Conjugated Bilirubin)<br><i>• Water soluble<br>• Non-toxic</i>"]
    
    BDG -->|Primary Pathway| BILE["<b>Secreted into bile</b><br>↓<br>Enters into intestine"]
    
    BDG -->|Alternative Pathway| PORTAL["Some part spills into <b>Portal Circulation via MRP-3</b>"]
    
    PORTAL --> REUPTAKE["<b>Reuptake by Hepatocytes</b><br>via Organic Anion Transporters (OAT proteins):<br><b>OATP 1B1 & 1B3</b><br><i>(Mutation causes Rotor Syndrome)</i>"]

```

---

### Clinical Summary

* **Crigler-Najjar Syndrome (Types 1 & 2) :** Deficiency of **UDP-Glucuronyl Transferase**, impairing conversion of unconjugated bilirubin to its glucuronide forms.
* **Rotor Syndrome :** Mutation in **$\text{OATP 1B1}$ & $\text{OATP 1B3}$**, impairing hepatic reuptake and storage of conjugated bilirubin.


--- 

# 3. SECRETION INTO BILE CANALICULI & CONGENITAL HYPERBILIRUBINEMIAS

* **Rate Limiting Step :** Active transport via **MRP 2 (Multidrug Resistance-like Protein 2)**.
* **Mutation :** Mutation in MRP 2 leads to **Dubin-Johnson Syndrome**.

---

### Excretion & Enterohepatic Fate Pathway

```mermaid
flowchart TD
    CB["<b>Conjugated bilirubin</b>"]
    BILE["<b>Bile</b>"]
    GUT["<b>Ileum, colon</b>"]
    URO["<b>Urobilinogen</b>"]
    STERCO["<b>Stercobilinogen</b><br>↓<br><b>Feces</b>"]
    UROBILIN["<b>Urobilin</b><br>↓<br><b>Excreted in Urine</b><br>(Yellow color)"]

    CB --> BILE
    BILE --> GUT
    GUT -->|"Colonic Bacteria"| URO
    URO --> STERCO
    URO -->|"Enterohepatic circulation &rarr; Kidneys"| UROBILIN

```

---

### Quantitative Bilirubin Production

* $1\text{ gm Hb} \longrightarrow 35\text{ mg bilirubin}$
* $\mathbf{6\text{ gm Hb}}$ degraded per day

---

### Congenital Hyperbilirubinemia

```mermaid
flowchart TD
    CH["<b>Congenital Hyperbilirubinemia</b>"]
    
    UCH["<b>&uarr; Unconjugated bilirubin</b><br>(&uarr; Indirect bilirubin)"]
    CH2["<b>&uarr; Conjugated Bilirubin</b><br>(&uarr; Direct bilirubin)"]
    
    CN["<b>Crigler-Najjar syndrome</b><br>• Type 1: Complete deficiency of UDP-glucuronyl Transferase<br>• Type 2: Partial deficiency UGT"]
    GS["<b>Gilbert disease</b><br>• Defect in uptake of bilirubin in liver"]
    
    DJ["<b>Dubin-Johnson syndrome</b><br>• Mutation: MRP2<br>• Defect in excretion of conjugated bilirubin<br>• Black colored liver"]
    RS["<b>Rotor Syndrome</b><br>• Mutation: OAT 1B1, 1B3<br>• Defect in excretion<br>• No staining of liver"]

    CH --> UCH
    CH --> CH2
    
    UCH --> CN
    UCH --> GS
    
    CH2 --> DJ
    CH2 --> RS

```

---

# TYPES OF HEMOGLOBIN & HEMOGLOBIN DERIVATIVES

---

## TYPES OF HEMOGLOBIN

<table>
  <thead>
    <tr>
      <th align="left">Type of Hb</th>
      <th align="center">Component Subunit</th>
      <th align="left">Description / Significance</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Adult Hb (HbA)</b></td>
      <td align="center">$\alpha_2\beta_2$</td>
      <td>The major Hb in humans (<b>90%</b>)</td>
    </tr>
    <tr>
      <td><b>HbA₂</b></td>
      <td align="center">$\alpha_2\delta_2$</td>
      <td>Minor component in adult (<b>2 - 5%</b>)</td>
    </tr>
    <tr>
      <td><b>Fetal Hb (HbF)</b></td>
      <td align="center">$\alpha_2\gamma_2$</td>
      <td><b>&lt; 2%</b> in adults</td>
    </tr>
    <tr>
      <td><b>Glycated Hb (HbA₁c)</b></td>
      <td align="center">$\alpha_2\beta_2\text{-Glucose}$</td>
      <td><b>&lt; 5%</b>; increases in Diabetes Mellitus (DM)</td>
    </tr>
  </tbody>
</table>
---

## HEMOGLOBIN DERIVATIVES

```mermaid
flowchart TD
    HD["<b>Hemoglobin Derivatives</b>"]
    
    NORM["<b>Normal Derivatives</b><br>- OxyHb<br>- deoxyHb<br>- HbCO₂"]
    ABNORM["<b>Abnormal Derivatives</b><br>- MetHb<br>- HbCO<br>- SulfHb<br>- Cyanhemoglobin"]
    
    HD --> NORM
    HD --> ABNORM

```

---

### Normal Derivatives

* **1. Oxyhemoglobin ($\text{OxyHb}$) :**

$$\text{Hb with } \text{O}_2$$


* **2. Deoxyhemoglobin ($\text{deoxyHb}$) :**

$$\text{Hb without } \text{O}_2$$


* **3. Carbaminohemoglobin ($\text{HbCO}_2$) :**
  * $\text{CO}_2$ is non-covalently bound to the globin chain of $\text{Hb}$.
  * Transports $\text{CO}_2$ in blood.



---

### Abnormal Derivatives

* **4. Methemoglobin ($\text{MetHb}$) :**
  * Contains $\mathbf{Fe^{3+}}$ instead of $\text{Fe}^{2+}$ in the heme group.
  * **Unable to transport oxygen**.


* **5. Carbonylhemoglobin / Carboxyhemoglobin ($\text{HbCO}$) :**
  * $\text{CO}$ binds to $\text{Fe}^{2+}$ in heme in cases of **$\text{CO}$ poisoning** or **smoking**.
  * Carbon monoxide has a **much higher affinity** for $\text{Fe}^{2+}$ than $\text{O}_2$.


* **6. Sulfhemoglobin & Cyanhemoglobin :**
  * **Sulfhemoglobin :** Formed in poisoning by $\mathbf{H_2S}$.
  * **Cyanhemoglobin :** Formed in **cyanide poisoning**.


