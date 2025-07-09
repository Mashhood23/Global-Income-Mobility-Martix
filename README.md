# 🌍 Global Income Mobility Analysis (2003–2023)

This project analyzes global income mobility across 100 countries between 2003 and 2023. It uses GDP per capita (PPP) data to group countries into fixed income categories (Low, Middle, High) and examines how countries transition between these groups over 20 years.

The results are presented as a **mobility matrix** and visualized using R.

---

## 📊 Features

- Fetches GDP per capita (PPP) data directly from the World Bank using the [`WDI`](https://cran.r-project.org/web/packages/WDI/index.html) package.
- Classifies countries into **quartile-based income groups** (¼ = Low, ½ = Lower-Middle, 1 = Upper-Middle, 2 = High).
- Constructs a **transition (mobility) matrix** showing how countries move between groups from 2003 to 2023.
- Outputs an interactive HTML report.

---

## 🚀 Installation

### Requirements
- R (>= 4.0)
- RStudio (recommended)
- The following R packages:
  - `WDI`
  - `dplyr`
  - `tidyr`
  - `knitr`
  - `rmarkdown`
  - `ggplot2` (optional for visualizations)

### Install dependencies in R
```R
install.packages(c("WDI", "dplyr", "tidyr", "knitr", "rmarkdown", "ggplot2"))
