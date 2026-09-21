# Traffic Accident Data Wrangling & Public Risk Analytics

## 📊 Project Overview
This repository contains a comprehensive data science and public policy analytics workflow developed in **RStudio** to evaluate urban traffic infrastructure safety and driver risk profiles. Utilizing a large-scale data architecture of **28,470 structural observations and 32 tracking variables**, this project conducts rigorous data integrity audits, preprocessing transformations, and predictive visual modeling.

## 🔎 Key Technical Implementations
*   **Advanced Data Wrangling:** Deployed the `tidyverse` ecosystem (`dplyr`, `tidyr`) to clean, filter, and isolate computational outliers—such as rectifying structural machine-input errors (e.g., age values flagged at 255).
*   **Risk Metric Formulation:** Formulated a new conditional risk parameter (`harm`) combining cross-sectional variables of injuries and fatalities to evaluate the probability of severe road casualties.
*   **Multivariate Data Visualization:** Programmed dynamic trend lines, data discretizations (`cut()`), and grouped column charts (`geom_col(position = "dodge")`) via `ggplot2` to map high-risk temporal clusters.

## 💻 Tech Stack & Libraries
*   **Language:** R (v4.3+)
*   **Core Packages:** `tidyverse`, `dplyr`, `ggplot2`, `pander`, `viridis`, `ggthemes`

---
## 🌐 Live Interactive Dashboard
You can access the full, publication-ready interactive HTML report compiled directly from R Markdown via GitHub Pages here:
[https://github.io](https://github.com/umahani-art)
