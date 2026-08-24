# MECHANISM OF SECRETION OF HCl

* **Davenport Theory :—**
  * $\text{HCl}$ secretion is an **active process**.
  * Takes place in the **canaliculi of parietal (oxyntic) cells** in gastric glands.
  * Energy is derived from the **oxidation of glucose**.
* $\text{CO}_2$ is derived from the metabolic activities of the parietal cell.
* Enzyme **Carbonic Anhydrase** is present in high concentration inside parietal cells.

---

### CELLULAR MECHANISM & FLOWCHART

> ![alt text](images/HCLsecn.png)

```mermaid
flowchart TD
    subgraph ECF ["Extracellular Fluid (ECF)"]
        CO2_in["CO₂"]
        NaCl["NaCl → Na⁺ + Cl⁻"]
        NaHCO3["NaHCO₃ (Alkaline Tide)"]
    end

    subgraph Parietal_Cell ["Parietal Cell Cytoplasm"]
        CA["CO₂ + H₂O ⇌ H₂CO₃<br><i>(Catalyzed by Carbonic Anhydrase)</i>"]
        Dissoc["H₂CO₃ ⇌ H⁺ + HCO₃⁻"]
        HCO3_out["HCO₃⁻ exchanged out to ECF"]
        Cl_trans["Cl⁻ enters from ECF & transported across"]
    end

    subgraph Canaliculus ["Gastric Canaliculus (Lumen)"]
        H_pump["H⁺ actively pumped out"]
        Cl_out["Cl⁻ secreted into canaliculi"]
        HCl_final["<b>HCl (Gastric Acid)</b><br>H⁺ + Cl⁻ → HCl"]
    end

    CO2_in --> CA
    CA --> Dissoc
    Dissoc -->|H⁺| H_pump
    Dissoc -->|HCO₃⁻| HCO3_out
    NaCl --> Cl_trans
    Cl_trans --> Cl_out
    HCO3_out --> NaHCO3
    H_pump --> HCl_final
    Cl_out --> HCl_final

```

---

### OVERALL CHEMICAL REACTION

$$\text{CO}_2 + \text{H}_2\text{O} + \text{NaCl} \longrightarrow \text{HCl} + \text{NaHCO}_3$$

---

## REGULATION OF HCl SECRETION

<table>
  <thead>
    <tr>
      <th align="left">Stimulants of Secretion of HCl</th>
      <th align="left">Inhibitors of Secretion of HCl</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        • <b>Gastrin</b><br>
        • <b>Histamine</b><br>
        • <b>Vagal stimulation</b>
      </td>
      <td>
        • <b>Secretin</b><br>
        • <b>Peptide YY</b><br>
        • <b>Gastric Inhibitory Polypeptide (GIP)</b>
      </td>
    </tr>
  </tbody>
</table>

