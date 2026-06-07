# Rat Growth Analysis – Spaghetti Plots & Covariance Matrices

**Tracking rat growth over time.**  
Spaghetti plots reveal individual weight trajectories across four treatment groups. Mean weight trends show group‑level patterns. Covariance and correlation matrices uncover how weekly measurements relate to each other. Built in **R** with `ggplot2` and `tidyverse`.

## 📌 Overview

This project analyses longitudinal weight data from rats assigned to four different treatment groups.  
Key analyses include:

- **Spaghetti plots** – individual rat trajectories over weeks  
- **Mean weight plots** – average trend per treatment group  
- **Covariance & correlation matrices** – relationships between weight measurements at different time points  

All visualisations and matrix calculations are performed in base R and `tidyverse`.

## 📁 Repository contents

- `Spaghetti_plot_Cov_Cor.R` – Main R script (data import, plotting, matrix computation)  
- `README.md` – This file

## 🔧 Required R packages

```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "tidyr", "knitr"))
