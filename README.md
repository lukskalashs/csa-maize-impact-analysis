# Evaluating the Impact of Climate-Smart Agriculture on Smallholder Maize Farming Outcomes in North-West South Africa

[![Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-yellow.svg)](https://colab.research.google.com/github/lukskalashs/csa-maize-impact-analysis/blob/main/Group_1_The_Standard_Deviants.ipynb)
[![Looker Studio](https://img.shields.io/badge/Dashboard%20on-Looker%20Studio-orange.svg)](https://lookerstudio.google.com/u/0/reporting/c33378ab-1332-4df5-8dfa-14fcf2b7c77d/page/sU7LF?s=g-Kgzrjoax4)

---

## Table of Contents
1.  [Project Overview](#1-project-overview)
2.  [Research Question](#2-research-question)
3.  [Data Source](#3-data-source)
4.  [Methodology & Tools](#4-methodology--tools)
5.  [Key Findings & Insights](#5-key-findings--insights)
6.  [Interactive Dashboard](#6-interactive-dashboard)
7.  [Presentation Slides](#7-presentation-slides)
8.  [Limitations & Recommendations](#8-limitations--recommendations)
9.  [How to Run the Analysis](#9-how-to-run-the-analysis)
10. [Group Members](#10-group-members)

---

## 1. Project Overview

South African smallholder maize farmers face significant challenges due to climate change, including reduced productivity, food insecurity, and income instability. Climate-smart agricultural (CSA) practices, such as drought-tolerant varieties, mulching, crop diversification, and zero tillage, are increasingly promoted as potential solutions.

This project applies exploratory data analysis (EDA) to a comprehensive dataset to extract meaningful insights and assess the impact of CSA adoption on smallholder maize farming outcomes in North-West South Africa. The goal is to provide evidence-based insights that can inform policy and practice for enhancing agricultural sustainability and improving farmer livelihoods.

---

## 2. Research Question

The central question addressed in this analysis is:

**"To what extent does the adoption of climate-smart agricultural (CSA) practices improve maize productivity and household food-nutrition security among smallholder farmers in North-West South Africa?"**

---

## 3. Data Source

The analysis utilizes a comprehensive dataset collected from 316 smallholder farmers in North-West Province between 2022 and 2023. This dataset provides household-level information covering:
* Demographics
* CSA practices adopted
* Maize yield and income
* Food consumption (including HDDS and HFIAS)
* Socioeconomic characteristics

The data is sourced from a study by Omotayo et al., published in a Data in Brief article on ScienceDirect: [https://www.sciencedirect.com/science/article/pii/S2352340924006929](https://www.sciencedirect.com/science/article/pii/S2352340924006929).

---

## 4. Methodology & Tools

This project involved a comprehensive Exploratory Data Analysis (EDA) to uncover patterns and relationships within the dataset.

**Tools Used:**
* **Python:** For data manipulation, analysis, and visualization.
* **Google Colab:** The primary environment for conducting the EDA, including data cleaning, feature engineering, clustering, and visualization.
* **Pandas, Matplotlib, Seaborn:** Key Python libraries for data processing and visualization.
* **Looker Studio:** For building an interactive data dashboard.

**Analytical Steps:**
1.  **Data Cleaning & Preparation:** Proper handling of values, formatting of data types, and creation of useful derived columns.
2.  **Descriptive Insights:** Summarizing key variables, distributions, and demographics (e.g., age, gender, household size) to understand CSA adoption patterns. Clustering and grouping data were applied to gain deeper insights.
3.  **Comparative Analysis:** Visual and statistical comparison between CSA adopters and non-adopters, focusing on metrics such as maize productivity, Household Dietary Diversity Scores (HDDS), and Household Food Insecurity Access Scale (HFIAS).
4.  **Interpretation:** Analyzing the relationships between specific CSA practices and outcome variables (productivity, HDDS, HFIAS) with contextual insight.
5.  **Visualization:** Creating well-labelled, readable, and relevant graphs/charts (e.g., boxplots, histograms, scatterplots, bar charts) to substantiate evidence.

The detailed code and analysis steps are documented in the Google Colab Notebook.

---

## 5. Key Findings & Insights

Our exploratory data analysis provides quantitative evidence to address the research question, revealing several key insights into the impact of CSA practices on smallholder maize farming outcomes:

* **Impact on Household Food Security:** Our analysis indicates a strong relationship between CSA adoption scores and household food security. Specifically, low CSA adoption scores are associated with low Household Food Security Scores, while medium CSA adoption scores correlate with the highest Household Food Security Scores. This suggests that while some CSA adoption is beneficial, the relationship is not always linear, and other factors might influence food security.
* **Impact on Maize Productivity:** We observed that higher CSA adoption generally boosts maize yields. Median productivity rises from low to high adoption levels, with high adopters demonstrating top performance, including the highest yields and standout outliers. However, the medium adoption group shows wide variability, indicating inconsistent results with partial adoption. This suggests that the extent of CSA adoption boosts, but does not guarantee, productivity.
* **Effectiveness of Specific CSA Practices:** Across all practices, CSA users consistently yield more than non-users. Inter-Cropping, Intensification, and Agroforestry show the biggest yield gains. This highlights CSA's overall effectiveness, though the impact varies, suggesting some practices are more effective under certain conditions.
* **Influencing Factors:** Outliers in all CSA adoption groups (low, medium, high) suggest that factors beyond just CSA adoption, such as soil quality, water availability, and farmer experience, also significantly affect yields. The variability at higher adoption levels further reflects that the quality of implementation matters, not just the adoption itself.

*(Screenshot demonstrating the relationship between CSA Score and HH Food Security Score:)*
![CSA Score vs. HH Food Security Score](assets/Screenshot%202025-07-15%20111210.png)

*(Screenshot demonstrating the relationship between CSA Score and Maize Yield per Hectare:)*
![CSA Score vs. Maize Yield per Hectare](assets/Screenshot%202025-07-15%20111247.png)

---

## 6. Interactive Dashboard

An interactive dashboard has been developed using Looker Studio to effectively communicate the findings and allow for deeper exploration of the data. This dashboard includes toggles, filters, and selectors to compare adopters/non-adopters and filter by household characteristics, providing clarity in text and filters.

**View the interactive dashboard here:**
[https://lookerstudio.google.com/u/0/reporting/c33378ab-1332-4df5-8dfa-14fcf2b7c77d/page/sU7LF?s=g-Kgzrjoax4](https://lookerstudio.google.com/u/0/reporting/c33378ab-1332-4df5-8dfa-14fcf2b7c77d/page/sU7LF?s=g-Kgzrjoax4)

---

## 7. Presentation Slides

A comprehensive presentation, titled "EDAB Presentation - The Standard Deviants - Group 1," was delivered, summarizing the project, methodology, and key findings. This presentation provides an executive overview of the analysis, addressing the research question with evidence, and concludes with actionable recommendations.

**View the presentation slides (PDF):**
[presentations/EDAB2714_1.pdf](https://github.com/lukskalashs/csa-maize-impact-analysis/blob/main/EDAB2714_1.pdf)

**View the presentation slides (PowerPoint):**
[presentations/EDAB2714_1.pptx](https://github.com/lukskalashs/csa-maize-impact-analysis/blob/main/EDAB2714_1.pptx)

---

## 8. Limitations & Recommendations

### Limitations
* Missing or dropped variables.
* Potential bias from farmer-reported data.
* Geographic limitations, as the study focused solely on North-West South Africa.
* Limitations in access to the original questionnaire.
* Variability in derived factors, such as binary variables and dataset variables.

### Recommendations
* **Promote CSA among low adopters:** To reduce food insecurity and vulnerability in these segments.
* **Address barriers for high adopters:** Such as water access and market limitations, to further enhance their outcomes.
* **Integrate CSA with complementary interventions:** Including education and income diversification programs.
* **Target moderate adopters with training:** To improve their uptake of CSA practices and overall outcomes.
* **Optimise practices for high adopters:** To help stabilize their yields and food security.
* **Replicate effective strategies:** Learn from successful clusters and expand these strategies across different regions.
* **Investigate variability causes:** To ensure more consistent benefits from CSA adoption.

---

## 9. How to Run the Analysis

To reproduce the analysis performed in this project:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/lukskalashs/csa-maize-impact-analysis.git](https://github.com/lukskalashs/csa-maize-impact-analysis.git)
    cd csa-maize-impact-analysis
    ```
2.  **Open the Google Colab Notebook:**
    Navigate to the `notebooks/` directory and open `Group_1_The_Standard_Deviants.ipynb` in Google Colab.
    [Open Notebook in Colab](https://colab.research.google.com/github/lukskalashs/csa-maize-impact-analysis/blob/main/Group_1_The_Standard_Deviants.ipynb)
3.  **Run all cells:** Execute all cells in the notebook sequentially. Ensure all required libraries are installed (they should be handled by Colab's environment or explicitly listed in your notebook). The code is designed to be reproducible end-to-end.

---

## 10. Group Members

* **Lukhanyo Kalashe** 
* **Suhail Malek**
* **Lwazi Nhlapo**
* **Botlhale Korku Agbotame** 
* **Kgomotso Natasha Sikhonde**
* **Oratile Menyatsoe**
* **Tsholofelo Motlhale** 

---
