# UE 905 – Statistical Analyses 📊

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-276DC3?style=flat)
![lme4](https://img.shields.io/badge/lme4-276DC3?style=flat)

Advanced statistical modelling applied to forest inventory data, using linear models, mixed models, and generalized linear models in R.

---

## 🌍 Project Context

This project was developed as part of the **UE 905 – Statistical Analyses** course in the **SIGMA Master's program** (Agro Toulouse / Université Toulouse II – Jean Jaurès).  

The main objective was to **apply and interpret various statistical models** on forest inventory data collected in southern France, focusing on:
- the effects of spatial sampling designs on tree diameters (DBH),
- the influence of past logging events,
- and the occurrence of cavities in different species.

---

## 🧪 Analyses Performed

1. **ANOVA** — Testing the effect of sampling plots on *Carpinus betulus* DBH.  
2. **Linear regression** — Exploring the relationship between `lastLog` (time since last logging) and DBH for *Quercus* species.  
3. **Hierarchical ANOVA** — Grouping sampling plots into spatial triangles to test structured spatial effects.  
4. **Linear mixed model (LMM)** — Assessing whether `lastLog` explains plot-level variability.  
5. **Binomial GLM** — Modelling the presence of tree cavities as a function of DBH and site characteristics.

Each model includes **diagnostics of residuals**, **hypothesis verification**, and a detailed interpretation of the results.

<p align="center">
  <img src="images/anova_diagnostics.png" alt="ANOVA residual diagnostics example" width="600">
</p>

---

## 🛠 Technologies & Tools

- **R** (packages: `lme4`, `ggplot2`, `DHARMa`, `dplyr`, `MuMIn`, `car`)  
- **RMarkdown** for report generation  
- **Git / GitHub** for version control

---

## 🚀 How to Run

1. Clone the repository:

```bash
   git clone https://github.com/caslumali/UE905_AnalyseStatistique_ML.git
   cd UE905_AnalyseStatistique_ML
```

2. Open `UE_905_BBHL.Rmd` in **RStudio** and run the chunks sequentially.

3. Knit the RMarkdown file to generate the **PDF report**.

---

## 📎 Repository Structure

```
UE905_AnalyseStatistique_ML/
├── UE_905_BBHL.Rmd    # Main RMarkdown analysis script
├── UE_905_BBHL.pdf    # Final report with results
├── dataProjet_2025.csv # Input dataset (if available)
├── projet2024-2025.pdf # Original project description
└── README.md
```

---

## ✍️ Authors

Doris BALLOT, Audrey BARBIERO, Robin HECKENDORN, Lucas LIMA
📅 2025 – Master 2 SIGMA

---
