# Wheat Yield Analysis: Multi-Factor ANOVA & Statistical Modeling

## Project Overview
This project applies **Analysis of Variance (ANOVA)** techniques to agricultural data to evaluate how different wheat varieties and phytosanitary treatments influence crop yield. The study focuses on identifying significant main effects and testing for potential interactions between biological and chemical factors.

## Key Objectives
* **Variety Assessment:** Determine if specific wheat varieties (A, B, C, or D) lead to significantly different yields.
* **Treatment Evaluation:** Analyze the impact of phytosanitary treatments on productivity.
* **Interaction Analysis:** Test whether the effectiveness of a treatment depends on the specific wheat variety used.
* **Statistical Validation:** Use F-tests and p-values to make data-driven agricultural recommendations.

## Technical Stack
* **Language:** Python
* **Key Libraries:**
    * `Pandas` & `NumPy`: Data manipulation and structural analysis.
    * `Seaborn` & `Matplotlib`: Exploratory Data Analysis (EDA) and distribution plotting.
    * `Statsmodels`: Advanced statistical modeling and ANOVA table generation.

## Methodological Approach
1. Visualizing yield distributions across varieties using boxplots to detect trends and outliers.
2. **One-Way ANOVA:** Testing the individual effect of wheat varieties on yield.
3. **Two-Way ANOVA with Interaction:** Implementing a complete model (`Yield ~ Variety * Treatment`) to observe the synergy between factors.
4. **Hypothesis Testing:** Interpreting p-values against the 5% significance level to accept or reject null hypotheses.

## Statistical Insights
* **Insignificant Interactions:** The analysis proved that phytosanitary treatments perform consistently across all wheat varieties (p-value > 0.05 for interaction).

## 📁 Repository Structure
* `wheat_yield_anova.ipynb`: The complete Python notebook with statistical tests and visualizations.
* `README.md`: Project documentation and summary of findings.
