# ACTION POTENTIAL

> ### Headings
> ![alt text](images/APheadings.png)

* **Definition :** A series of electrical changes that occur in membrane potential when muscle / nerve is stimulated.
* **Action potential occurs in 2 phases :—**
  * a. **Depolarisation :** Initial phase of action potential in which inside becomes positive & outside becomes negative. Polarized state (RMP) is abolished, resulting in depolarisation.
  * b. **Repolarisation :** Phase of action potential which reverses back to RMP (inside becomes negative & outside becomes positive). Polarised state is re-established.

---

### PROPERTIES OF ACTION POTENTIAL VS GRADED POTENTIAL

| Action Potential | Graded Potential |
| :--- | :--- |
| • Propagative | • Non-propagative |
| • Long-distance signal | • Short-distance signal |
| • Both depolarization and repolarization | • Only depolarization or hyperpolarization |
| • Obeys all-or-none law | • Does not obey all-or-none law |
| • Summation is not possible | • Summation is possible |
| • Has refractory period | • No refractory period |

---

## ACTION POTENTIAL CURVE

* **Definition :** Graphical registration of electrical activity that occurs in an excitable tissue (muscle after excitation / stimulation).
* **3 Major Parts :—**
  * a. Latent period
  * b. Depolarisation
  * c. Repolarisation

---

### 1. Latent Period
* Period when no change occurs in electrical potential immediately after applying stimulus.
* **Duration :** 0.5 – 1 msec.

> **Stimulus Artifact :—**  
> When stimulus applied $\longrightarrow$ slight irregular deflection of baseline for very short period $\longrightarrow$ because of disturbance in muscle due to leakage of current from stimulating electrode to recording electrode.

---

### 2. Depolarization
* Muscle depolarized for about 15 mV (up to -75 mV).
* **Firing Level :** After initial slow depolarisation for 15 mV $\longrightarrow$ rate of depolarisation increases suddenly $\longrightarrow$ point at which depolarisation rate increases is the **firing level**.
* **Overshoot :** From firing level $\longrightarrow$ curve reaches isoelectric potential (0 potential) $\longrightarrow$ then shoots up (overshoots) beyond 0 potential up to **+55 mV**.

---

### 3. Repolarisation
* Initially, repolarization occurs rapidly and then becomes slow.

* **Spike Potential :** Rapid rise in depolarisation & rapid fall in repolarisation taken together.
  * **Duration :** 0.4 msec.
* **After-Depolarisation / Negative After-Potential :** Rapid fall in repolarisation followed by a slow repolarisation.
  * **Duration :** 2 – 4 msec.
* **After-Hyperpolarisation / Positive After-Potential :** After reaching resting level (-90 mV) $\longrightarrow$ becomes more negative beyond resting level $\longrightarrow$ after this, RMP is restored.
  * **Duration :** 50 msec.

> ![alt text](images/APgraph.png)

---

### PHASES & CHANNEL DYNAMICS (TIMELINE)

```mermaid
flowchart LR
    subgraph LP ["Latent Period (0 – 0.5 ms)"]
        A["Point A: Stimulus Applied<br>Opening of few Na⁺ channels"]
    end

    subgraph DP ["Depolarization (0.5 – 1.5 ms)"]
        B["Point B: Firing Level<br>Opening of many Na⁺ channels (Rapid influx)"]
        Overshoot["Overshoot (+55 mV)"]
    end

    subgraph RP ["Repolarization (1.5 – 4.0 ms)"]
        C["Point C: Peak / Spike Potential<br>Closure of Na⁺ channels & opening of K⁺ channels"]
        AfterDepol["After-Depolarization (Slow repolarization)"]
        D["Point D: After-Hyperpolarization<br>Excess K⁺ efflux → Closure of K⁺ channels"]
    end

    A --> B --> Overshoot --> C --> AfterDepol --> D

```

---

## IONIC BASIS OF ACTION POTENTIAL

```mermaid
flowchart TD
    A["During onset of depolarisation"] --> B["Voltage-gated Na⁺ channels open (Slow influx of Na⁺)"]
    B --> C["Na⁺ channel activation (Depolarisation reaches 7 to 10 mV)"]
    C --> D["Na⁺ channels start opening at a faster rate<br>(Na⁺ transport is short-lived)"]
    D --> E["At the same time, K⁺ channels start opening<br>(Leads to efflux of K⁺ out of cell)"]
    E --> F["Causing repolarisation<br>(K⁺ channels open for longer time)"]
    F --> G["Causes efflux of more number of K⁺ producing more negativity inside"]
    G --> H["Causes hyperpolarisation"]
    H --> I["RMP restored"]

```


