# SHOCK

> ### Headings
> ![alt text](images/Headingsofshock.png)

* **Shock :** Refers to depression or suppression of body functions produced by any disorder.
* **Circulatory Shock :** Refers to shock developed by **inadequate blood flow throughout the body** *(a life-threatening condition)*.

---

## MANIFESTATION OF CIRCULATORY SHOCK

$$\text{Insufficient blood flow to tissues (particularly brain)}$$
$$\downarrow$$
$$\text{Due to severe reduction in Cardiac Output (CO)}$$

* a. **$\downarrow$ Cardiac Output (CO)** $\longrightarrow$ Arterial Blood Pressure (BP) drops down.
* b. **Low BP** $\longrightarrow$ Produces **reflex tachycardia** and **reflex vasoconstriction**.
* c. **Tachycardia** $\longrightarrow \downarrow$ Decreases diastolic period:
  $$\downarrow \text{ Diastolic Filling} \longrightarrow \downarrow \text{ Stroke Volume (SV) \& Systolic BP} \longrightarrow \downarrow \text{ Pulse Pressure } (< 20\text{ mmHg})$$
* d. **$\downarrow$ Velocity of blood flow** $\longrightarrow$ Causes **stagnant hypoxia**.
* e. **Skin becomes pale and cold** due to intense vasoconstriction.
* f. **Cyanosis develops** with worsening hypoxia *(especially visible on ear lobes and fingertips)*.
* g. **$\downarrow$ GFR and urinary output** due to profound fall in renal perfusion pressure.
* h. **Metabolic activities of myocardium accelerate** due to $\downarrow$ blood flow and $\uparrow$ heart rate:
  $$\text{Anaerobic glycolysis} \longrightarrow \text{Large amount of lactic acid formed} \longrightarrow \textbf{Metabolic Acidosis}$$

---

## STAGES OF CIRCULATORY SHOCK

Circulatory shock occurs in **3 distinct stages**:
* 1. **1ˢᵗ Stage / Compensated Stage** *(Non-progressive)*
* 2. **2ⁿᵈ Stage / Progressive Stage** *(Decompensated)*
* 3. **3ʳᵈ Stage / Irreversible Stage** *(Refractory)*

---

### 1. FIRST STAGE / COMPENSATED STAGE (NON-PROGRESSIVE)

* **Features :** Regulated by **negative (–ve) feedback control mechanisms**; corrects blood loss of $< 10\%$ of total blood volume.
* **Compensatory Mechanisms Involved :—**
  * a. **Baroreceptor Mechanism :** Initiates strong sympathetic stimulation $\longrightarrow$ Tachycardia, vasoconstriction $\longrightarrow \uparrow$ BP.
  * b. **Renin-Angiotensin-Aldosterone (Renal) Mechanism :** Restores blood volume through vasoconstriction and $\text{Na}^+$ / water retention.
  * c. **Antidiuretic Hormone (ADH) Mechanism :** Potent vasoconstriction and free water retention.

```mermaid
flowchart TD
    Loss["Acute loss of less than 10% of total blood"] --> VR["Decreased venous return"]
    VR --> CO["Decreased cardiac output"]
    CO --> BP["Decreased blood pressure"]
    
    BP --> Comp["<b>Compensatory Mechanisms</b>"]
    
    Comp --> Baro["<b>Baroreceptor Mechanism</b>"]
    Comp --> Renal["<b>Renal Mechanism</b>"]
    Comp --> ADH["<b>ADH Mechanism</b>"]
    
    Baro --> Tach["Tachycardia"]
    Baro --> Vasc["Vasoconstriction"]
    
    Renal --> Renin["Renin secretion"]
    Renin --> AT2["Angiotensin II"]
    AT2 --> Aldo["Secretion of aldosterone"]
    
    ADH --> Ret["Water and sodium retention"]
    Aldo --> Ret
    Vasc --> AT2
    
    Tach --> IncCO["Increased cardiac output"]
    Ret --> IncVol["Increased blood volume"]
    IncVol --> IncCO2["Increased cardiac output"]
    
    IncCO --> NormalBP["<b>Increased Blood Pressure (Restored)</b>"]
    IncCO2 --> NormalBP

```

> ![alt text](images/firststageofshock.png)

---

### 2. SECOND STAGE / PROGRESSIVE STAGE (DECOMPENSATED)

* **Features :** Occurs with **$10\% - 15\%$ acute loss of total blood volume**.
* A **positive (+ve) feedback vicious cycle** develops, making normal regulatory mechanisms inadequate to compensate.
* Bacterial toxins (**Endotoxins**) worsen myocardial depression.

```mermaid
flowchart TD
    Loss2["Acute loss of 10% to 15% of total blood"] --> VR2["Severe reduction in venous return"]
    VR2 --> CO2["Severe reduction in cardiac output"]
    CO2 --> BP2["Severe decrease in blood pressure"]
    
    BP2 --> MyoIsch["Severe myocardial ischemia"]
    BP2 --> VMC["Suppression of vasomotor center"]
    
    MyoIsch --> Toxins["Release of toxins from damaged cardiac tissue"]
    Toxins --> CardDet["Further deterioration in cardiac function"]
    
    CardDet --> TissDet["Deterioration of other tissues"]
    
    VMC --> VasoDil["Severe vasodilatation"]
    VasoDil --> LowBP2["Further decrease in blood pressure"]
    LowBP2 --> Thrombus["Thrombus formation in capillaries"]
    Thrombus --> Obstruct["Obstruction in capillary blood flow"]
    Obstruct --> IncHydro["Increased capillary hydrostatic pressure"]
    
    IncHydro --> IncPerm["Increased capillary permeability"]
    IncPerm --> FluidDiff["Fluid diffusion into interstitial space"]
    FluidDiff --> TissDet

```

> ![alt text](images/2ndstageofshock.png)

---

### 3. THIRD STAGE / IRREVERSIBLE STAGE (REFRACTORY)

* **Features :** Occurs with **acute loss of $> 15\%$ of total blood volume**.
* Also called the **Refractory Stage**.
* Leads inevitably to **death** due to complete failure of vital organ perfusion, severe cerebral ischemia, and myocardial collapse.

```mermaid
flowchart TD
    Loss3["Acute loss of more than 15% of total blood"]
    
    Loss3 --> CorFlow["Decreased coronary blood flow"]
    Loss3 --> CerFlow["Decreased cerebral blood flow"]
    Loss3 --> SympDis["Continuous sympathetic discharge"]
    
    CorFlow --> MI["Myocardial ischemia"]
    MI --> CardFail["Cardiac failure"]
    
    CerFlow --> CerIsch["Cerebral ischemia"]
    CerIsch --> VMCFail["Failure of vasomotor center"]
    VMCFail --> GenVD["Generalized vasodilatation"]
    GenVD --> Pool["Pooling of blood in veins"]
    
    SympDis --> VenuConst["Constriction of venules and precapillary sphincters"]
    VenuConst --> RedVenFlow["Reduced venous blood flow"]
    RedVenFlow --> NoWash["Failure to washout metabolites"]
    NoWash --> RelVD["Release of local vasodilators"]
    RelVD --> DilatVein["Dilatation of veins"]
    
    DilatVein --> DecVR["Decreased venous return"]
    Pool --> DecVR
    
    DecVR --> DrastCO["Drastic decrease in cardiac output"]
    CardFail --> DrastCO
    
    DrastCO --> DrastBP["Drastic fall in blood pressure"]
    DrastBP --> Death["<b>DEATH</b>"]

```

> ![alt text](images/3rdstageofshock.png)