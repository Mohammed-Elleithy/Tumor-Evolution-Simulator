# Tumor Evolution Simulator

## Overview

Cancer is increasingly understood as an evolutionary disease. Tumors consist of heterogeneous populations of cells that undergo selection in response to treatment, immune surveillance, and environmental pressures.

This project implements a simplified computational simulation demonstrating how treatment-resistant cancer clones can survive therapy and eventually dominate a tumor population.

The simulation is inspired by the clonal evolution theory of cancer and serves as an educational model for understanding tumor heterogeneity, selection pressure, treatment resistance, and relapse.

---

## Scientific Question

How can a small population of resistant cancer cells survive treatment and eventually cause tumor relapse despite an initially successful therapeutic response?

---

## Biological Background

### Tumor Heterogeneity

Tumors are not composed of identical cells.

Different subpopulations (clones) may possess distinct genetic and phenotypic characteristics. Some clones may be sensitive to treatment, while others may be resistant.

### Clonal Evolution

Cancer cells continuously evolve through mutation and selection.

When treatment is applied:

* Sensitive clones are eliminated.
* Resistant clones survive.
* Resistant clones expand.
* Relapse may occur.

### Selection Pressure

Therapeutic interventions act as selection pressures.

Cells susceptible to treatment are removed, while resistant cells gain a survival advantage.

---

## Simulation Assumptions

### Initial Population

* 990 treatment-sensitive cells
* 10 treatment-resistant cells

### Treatment Effect

Sensitive cells:

* 95% die during each treatment cycle

Resistant cells:

* 95% survive each treatment cycle

### Resistant Cell Growth

Surviving resistant cells continue proliferating and expand over time.

---

## Results

The simulation demonstrates:

1. Rapid elimination of sensitive cells.
2. Survival of resistant cells.
3. Expansion of resistant clones.
4. Tumor relapse driven by resistant populations.

The resulting dynamics mirror fundamental principles of cancer evolution and treatment resistance observed in clinical oncology.

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Google Colab

---

## Future Improvements

Future versions may include:

* Mutation-driven resistance
* Immune surveillance by T cells and NK cells
* Tumor microenvironment modeling
* Nutrient competition
* Hypoxia
* Multiple resistant clones
* Immunotherapy simulations

---

## Educational Objectives

This project demonstrates concepts in:

* Cancer Biology
* Tumor Evolution
* Clonal Selection
* Treatment Resistance
* Computational Oncology
* Systems Biology

---

## Disclaimer

This simulation is intended for educational and exploratory purposes only. It does not represent the full biological complexity of real tumors and should not be interpreted as a clinical model.

---

## References

### Foundational Cancer Evolution Paper

Nowell PC.

The clonal evolution of tumor cell populations.

Science. 1976.

https://www.science.org/doi/10.1126/science.959840

### Hallmarks of Cancer

Hanahan D, Weinberg RA.

The Hallmarks of Cancer.

https://www.cell.com/fulltext/S0092-8674(00)81683-9

### Hallmarks of Cancer: The Next Generation

Hanahan D, Weinberg RA.

https://www.cell.com/fulltext/S0092-8674(11)00127-9

### National Cancer Institute

https://www.cancer.gov

### The Cancer Genome Atlas (TCGA)

https://www.cancer.gov/tcga

---
