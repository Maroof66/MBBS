# ELECTRICAL POTENTIAL IN SA NODE (PACEMAKER POTENTIAL)

* **Resting Membrane Potential / Pacemaker Potential :—**
  * Pacemaker potential is an **unstable resting membrane potential** (also called **prepotential**).
  * In the SA node, **each impulse automatically triggers the next impulse**.
  * **RMP in SA Node :** $-55\text{ to } -60\text{ mV}$ *(compared to $-85\text{ to } -95\text{ mV}$ in ordinary cardiac muscle fibers)*.

* **Action Potential Characteristics :—**
  * Depolarization starts slowly until the **threshold level of $-40\text{ mV}$** is reached.
  * Rapid upstroke peaks up to **$+5\text{ mV}$ (rapid depolarization)**, followed by rapid repolarization.

> ![alt text](images/APinCVS.png)

---

## IONIC BASIS OF ELECTRICAL ACTIVITY IN PACEMAKER

```mermaid
flowchart TD
    subgraph Prepotential ["1. Pacemaker Potential (Prepotential)"]
        Na_leak["Na⁺ ions leak into pacemaker fibers (I_f / Funny current)"] --> SlowDep1["Slow initial depolarization"]
        SlowDep1 --> T_Ca["Transient T-type Ca²⁺ channels open"]
        T_Ca --> SlowDep2["Slow Ca²⁺ influx continues depolarization to threshold (-40 mV)"]
    end

    subgraph Depol ["2. Rapid Depolarization (Phase 0)"]
        Threshold["Threshold (-40 mV) reached"] --> L_Ca["Opening of L-type Ca²⁺ channels"]
        L_Ca --> Ca_Influx["Rapid influx of Ca²⁺ ions (Upstroke to +5 mV)<br><i>(Note: Depolarization is Ca²⁺-dependent, NOT Na⁺-dependent)</i>"]
    end

    subgraph Repol ["3. Repolarization (Phase 3)"]
        Peak["Peak reached (+5 mV)"] --> K_Efflux["Opening of K⁺ channels & prolonged K⁺ efflux"]
        K_Efflux --> Hyperpol["Causes repolarization down to maximum diastolic potential (-60 mV)"]
        Hyperpol --> Cycle["Re-activates Na⁺ leakage → Initiates next action potential cycle"]
    end

    SlowDep2 --> Threshold
    Ca_Influx --> Peak

```

