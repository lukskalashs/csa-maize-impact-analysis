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

[cite_start]South African smallholder maize farmers face significant challenges due to climate change, including reduced productivity, food insecurity, and income instability[cite: 20]. [cite_start]Climate-smart agricultural (CSA) practices, such as drought-tolerant varieties, mulching, crop diversification, and zero tillage, are increasingly promoted as potential solutions[cite: 21].

[cite_start]This project applies exploratory data analysis (EDA) to a comprehensive dataset to extract meaningful insights and assess the impact of CSA adoption on smallholder maize farming outcomes in North-West South Africa[cite: 23]. The goal is to provide evidence-based insights that can inform policy and practice for enhancing agricultural sustainability and improving farmer livelihoods.

---

## 2. Research Question

The central question addressed in this analysis is:

[cite_start]**"To what extent does the adoption of climate-smart agricultural (CSA) practices improve maize productivity and household food-nutrition security among smallholder farmers in North-West South Africa?"** [cite: 27]

---

## 3. Data Source

[cite_start]The analysis utilizes a comprehensive dataset collected from 316 smallholder farmers in North-West Province between 2022 and 2023[cite: 22]. This dataset provides household-level information covering:
* [cite_start]Demographics [cite: 22]
* [cite_start]CSA practices adopted [cite: 22]
* [cite_start]Maize yield and income [cite: 22]
* [cite_start]Food consumption (including HDDS and HFIAS) [cite: 22]
* [cite_start]Socioeconomic characteristics [cite: 22]

The data is sourced from a study by Omotayo et al. [cite_start](2024), published in a Data in Brief article on ScienceDirect: [https://www.sciencedirect.com/science/article/pii/S2352340924006929](https://www.sciencedirect.com/science/article/pii/S2352340924006929)[cite: 26].

---

## 4. Methodology & Tools

[cite_start]This project involved a comprehensive Exploratory Data Analysis (EDA) to uncover patterns and relationships within the dataset[cite: 25].

**Tools Used:**
* **Python:** For data manipulation, analysis, and visualization.
* [cite_start]**Google Colab:** The primary environment for conducting the EDA, including data cleaning, feature engineering, clustering, and visualization[cite: 25].
* **Pandas, Matplotlib, Seaborn:** Key Python libraries for data processing and visualization.
* [cite_start]**Looker Studio:** For building an interactive data dashboard[cite: 42].

**Analytical Steps:**
1.  [cite_start]**Data Cleaning & Preparation:** Proper handling of values, formatting of data types, and creation of useful derived columns[cite: 87].
2.  [cite_start]**Descriptive Insights:** Summarizing key variables, distributions, and demographics (e.g., age, gender, household size) to understand CSA adoption patterns[cite: 47, 58]. [cite_start]Clustering and grouping data were applied to gain deeper insights[cite: 58].
3.  [cite_start]**Comparative Analysis:** Visual and statistical comparison between CSA adopters and non-adopters, focusing on metrics such as maize productivity, Household Dietary Diversity Scores (HDDS), and Household Food Insecurity Access Scale (HFIAS)[cite: 47, 59].
4.  [cite_start]**Interpretation:** Analyzing the relationships between specific CSA practices and outcome variables (productivity, HDDS, HFIAS) with contextual insight[cite: 47, 60].
5.  [cite_start]**Visualization:** Creating well-labelled, readable, and relevant graphs/charts (e.g., boxplots, histograms, scatterplots, bar charts) to substantiate evidence[cite: 47, 61].

The detailed code and analysis steps are documented in the Google Colab Notebook.

---

## 5. Key Findings & Insights

[cite_start]Our exploratory data analysis provides quantitative evidence to address the research question[cite: 43], revealing several key insights into the impact of CSA practices on smallholder maize farming outcomes:

* **Impact on Household Food Security:** Our analysis indicates a strong relationship between CSA adoption scores and household food security. Specifically, low CSA adoption scores are associated with low Household Food Security Scores, while medium CSA adoption scores correlate with the highest Household Food Security Scores. [cite_start]This suggests that while some CSA adoption is beneficial, the relationship is not always linear, and other factors might influence food security[cite: 1].
* **Impact on Maize Productivity:** We observed that higher CSA adoption generally boosts maize yields. Median productivity rises from low to high adoption levels, with high adopters demonstrating top performance, including the highest yields and standout outliers. However, the medium adoption group shows wide variability, indicating inconsistent results with partial adoption. [cite_start]This suggests that the extent of CSA adoption boosts, but does not guarantee, productivity[cite: 1].
* **Effectiveness of Specific CSA Practices:** Across all practices, CSA users consistently yield more than non-users. Inter-Cropping, Intensification, and Agroforestry show the biggest yield gains. [cite_start]This highlights CSA's overall effectiveness, though the impact varies, suggesting some practices are more effective under certain conditions[cite: 1].
* **Influencing Factors:** Outliers in all CSA adoption groups (low, medium, high) suggest that factors beyond just CSA adoption, such as soil quality, water availability, and farmer experience, also significantly affect yields. [cite_start]The variability at higher adoption levels further reflects that the quality of implementation matters, not just the adoption itself[cite: 1].

*(Screenshot demonstrating the relationship between CSA Score and HH Food Security Score:)*
![CSA Score vs. HH Food Security Score](assets/Screenshot%202025-07-15%20111210.png)

*(Screenshot demonstrating the relationship between CSA Score and Maize Yield per Hectare:)*
![CSA Score vs. Maize Yield per Hectare](assets/Screenshot%202025-07-15%20111247.png)

---

## 6. Interactive Dashboard

[cite_start]An interactive dashboard has been developed using Looker Studio to effectively communicate the findings and allow for deeper exploration of the data[cite: 42]. [cite_start]This dashboard includes toggles, filters, and selectors to compare adopters/non-adopters and filter by household characteristics, providing clarity in text and filters[cite: 85].

**View the interactive dashboard here:**
[https://lookerstudio.google.com/u/0/reporting/c33378ab-1332-4df5-8dfa-14fcf2b7c77d/page/sU7LF?s=g-Kgzrjoax4](https://lookerstudio.google.com/u/0/reporting/c33378ab-1332-4df5-8dfa-14fcf2b7c77d/page/sU7LF?s=g-Kgzrjoax4)

---

## 7. Presentation Slides

[cite_start]A comprehensive presentation, titled "EDAB Presentation - The Standard Deviants - Group 1," was delivered, summarizing the project, methodology, and key findings[cite: 1]. [cite_start]This presentation provides an executive overview of the analysis, addressing the research question with evidence, and concludes with actionable recommendations[cite: 47, 62, 64].

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
    [Open Notebook in Colab](https://colab.research.com/github/lukskalashs/csa-maize-impact-analysis/blob/main/Group_1_The_Standard_Deviants.ipynb)
3.  **Run all cells:** Execute all cells in the notebook sequentially. Ensure all required libraries are installed (they should be handled by Colab's environment or explicitly listed in your notebook). The code is designed to be reproducible end-to-end.

---

## 10. Group Members

* **Suhail Malek** - Student No: 2023334119
* **Lwazi Nhlapo** - Student No: 2021856345
* **Lukhanyo Kalashe** - Student No: 2023575000
* **Botlhale Korku Agbotame** - Student No: 2021484890
* **Kgomotso Natasha Sikhonde** - Student No: 2021541467
* **Oratile Menyatsoe** - Student No: 2023839000
* **Tsholofelo Motlhale** - Student No: 2020619553

---
