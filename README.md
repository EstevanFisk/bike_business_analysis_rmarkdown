# 🚲 R-Powered Strategic Retail Intelligence: From Performance Audit to Market R&D

[![R](https://img.shields.io/badge/Language-R-276DC3.svg?style=flat&logo=r)](https://www.r-project.org/)
[![Tidymodels](https://img.shields.io/badge/Framework-Tidymodels-orange?style=flat)](https://www.tidymodels.org/)
[![XGBoost](https://img.shields.io/badge/Model-XGBoost-black?style=flat)](https://xgboost.ai/)
[![Reporting](https://img.shields.io/badge/Reporting-R_Markdown-blue?style=flat&logo=rstudio)](https://rmarkdown.rstudio.com/)
[![R Markdown](https://img.shields.io/badge/Reporting-R_Markdown-276DC3?style=flat&logo=rstudio&logoColor=white)](https://rmarkdown.rstudio.com/)

Analytical results are only as valuable as the transparency behind them. In high-stakes environments—from the private sector to classified DoD spaces—the **"black box" is a liability.** This suite represents a gold standard for **Literate Programming**, transitioning from high-level operational audits to deep-dive market optimization. It ensures that strategic recommendations are always backed by a visible, reproducible technical trail.

---

## 🏛️ Project Architecture: Three Pillars of Intelligence

### I. Executive Sales Performance Dashboard
**The Operational Source of Truth.**
This central hub provides a real-time audit of revenue health. It facilitates seamless drilling from quarterly trends down to weekly localized performance across 30 retail bike shop customers.
* **Strategic Focus:** Rapid evaluation of revenue concentration and "health/wealth" metrics for resource optimization.
* **Technical Highlight:** Reactive backend allows stakeholders to audit quarterly, monthly, and weekly sales trends through localized trend detection.



### II. Strategic R&D: Algorithmic Gap Analysis
**Portfolio Optimization & Market Benchmarking.**
Addressing the "Market Entry" problem, this module identifies "blind spots" in the current 97-model fleet to establish high-fidelity pricing benchmarks for new configurations.
* **Discovery:** Identified two "Blue Ocean" opportunities: an **Aluminum-frame Over Mountain** line and an **Aluminum-frame Triathlon** line.
* **The Engine:** Leverages an **XGBoost pricing engine** to ensure internal price parity.
* **Validation:** Compares XGBoost against Linear, GLMNET, and Random Forest architectures to ensure the most robust predictive accuracy.

### III. Behavioral Intelligence: High-Dimensional Market Mapping
**Latent Market Discovery via Clustering.**
To drive targeted marketing, this module uncovers latent behavioral patterns within the customer base to transition from generic outreach to highly targeted campaigns.
* **Methodology:** Employs **K-Means Clustering** integrated with **UMAP (Uniform Manifold Approximation and Projection)**.
* **The "Practitioner" Difference:** Unlike traditional PCA, UMAP preserves the local structure of the data, providing a more accurate visual representation of distinct customer "landscapes."
* **Segments Identified:** 4 distinct profiles based on "Premium vs. Economic" and "Road vs. Mountain" preferences.



---

## 🧰 Technical Stack & Methodology

| Layer | Technology | Role |
| :--- | :--- | :--- |
| **Orchestration** | `R Markdown` | Literate programming with interactive code-folding for auditability. |
| **ML Framework** | `Tidymodels` (`parsnip`, `rsample`, `recipes`) | Streamlined model training, outlier detection, and validation. |
| **Algorithms** | `XGBoost`, `Random Forest`, `K-Means`, `UMAP` | High-performance predictive modeling and dimensionality reduction. |
| **Data Viz** | `Plotly`, `ggplot2`, `ggrepel` | Interactive visualizations with dynamic tooltips and hover-effects. |
| **Themes** | `Flatly` | Clean, professional UI/UX for stakeholder-ready reports. |

---

## 🛡️ Built for Auditability
Every report in this suite features **interactive code-folding.** By prioritizing transparency, these documents allow technical peers to inspect the data transformations and model parameters directly inline. This ensures the methodology is not a "black box" but a fully auditable asset—a requirement maintained from my background in regulated and classified environments.

---

## 🚀 Installation & Reproducibility

1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/EstevanFisk/bike_business_analysis_rmarkdown.git
    ```
2.  **Restore Environment:**
    Ensure you have `RStudio` and the following libraries:
    ```R
    install.packages(c("tidyverse", "tidyquant", "parsnip", "umap", "plotly", "broom"))
    ```
3.  **Run Reports:**
    Open any `.Rmd` file in the `reports/` folder and click **Knit**.

---

### Connect with the Architect
* [Portfolio Website](https://estevanfisk.com/)
* [GitHub Profile](https://github.com/EstevanFisk)
* [LinkedIn](https://www.linkedin.com/in/estevanfisk/)