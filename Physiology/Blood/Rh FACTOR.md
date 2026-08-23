# Rh FACTOR

* **Definition :** Rh factor is an antigen present on RBCs.
* **Discovery :** Discovered by **Landsteiner and Wiener** *(first discovered in Rhesus monkey)*.
* **Antigenicity :** Only **D-antigen** is strongly antigenic in humans.
  * a. **Rh +ve :** 85% of people (D-antigen present)
  * b. **Rh -ve :** 15% of people (D-antigen absent)

> **Difference from ABO Group System :**  
> Antigen D does **not** have a naturally occurring antibody (*anti-D*).  
> If Rh +ve blood is transfused into an Rh -ve person, **anti-D is developed in that person**.

---

### INHERITANCE OF Rh ANTIGEN

* Rhesus factor is an **inherited dominant factor**.

* **Genotypes :—**
  * a. **Homozygous Rhesus +ve :** $\text{DD}$
  * b. **Heterozygous Rhesus +ve :** $\text{Dd}$
  * c. **Homozygous Rhesus -ve :** $\text{dd}$

| Father Genotype | Mother Genotype | Offspring Outcome |
| :--- | :--- | :--- |
| **Father $\text{DD}$ ($\text{Rh}^+$)** *(Homozygous)* | **Mother $\text{dd}$ ($\text{Rh}^-$)** | **100% offspring are $\text{Dd}$ ($\text{Rh}^+$ - Heterozygous)** |
| **Father $\text{Dd}$ ($\text{Rh}^+$)** *(Heterozygous)* | **Mother $\text{dd}$ ($\text{Rh}^-$)** | **50% $\text{Dd}$ ($\text{Rh}^+$)** and **50% $\text{dd}$ ($\text{Rh}^-$)** |
| **Father $\text{dd}$ ($\text{Rh}^-$)** *(Homozygous)* | **Mother $\text{dd}$ ($\text{Rh}^-$)** | **100% offspring are $\text{dd}$ ($\text{Rh}^-$)** |

> ![alt text](images/Rhfactor.png)

---

## TRANSFUSION REACTIONS DUE TO Rh INCOMPATIBILITY

```mermaid
flowchart TD
    subgraph First_Transfusion ["1st Exposure (Rh+ blood to Rh- person)"]
        A["Rh- person receives Rh+ blood (1st time)"] --> B["Rh antibodies (anti-D) develop slowly within 1 month"]
        B --> C["Transfused RBCs present in recipient's blood agglutinated"]
        C --> D["Agglutinated cells lysed by macrophages"]
        D --> E["Antibodies developed in recipient remain forever"]
    end

    subgraph Second_Transfusion ["2nd Exposure (Subsequent Transfusion)"]
        E --> F["Person receives Rh+ blood (2nd time)"]
        F --> G["Immediate agglutination of donor RBCs"]
        G --> H["Severe transfusion reactions occur immediately"]
    end

```

