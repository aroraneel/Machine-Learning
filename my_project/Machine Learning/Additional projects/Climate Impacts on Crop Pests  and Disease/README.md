# Climate-Driven Pest & Disease Impact Analysis in Africa

## Overview
This project analyzes how **climate change influences pest pressure, pest performance, and crop yield losses across Africa**.  
Using **GAUL administrative boundary datasets** and multiple **pest-impact datasets**, the analysis identifies vulnerable crops, high-risk countries, emerging hotspots, and differences across future climate scenarios.

The work is implemented as a **single, well-structured Jupyter Notebook** with clearly documented analytical steps.

---

## Objectives
The analysis aims to answer the following key questions:

- Which crops are most vulnerable to pests and diseases across Africa?
- Which countries experience the highest pest-driven yield losses?
- How does pest pressure change over time (2040 → 2060)?
- Which country–crop combinations show emerging risks?
- How do impacts differ under climate scenarios **SSP245 vs SSP585**?
- Do climate models agree on future pest performance trends?

---

## Data Sources
- **GAUL Administrative Boundaries (Africa)**  
  - A0: Country level  
  - A1: First administrative level  
  - A2: Second administrative level  

- **Pest & Disease Impact Datasets**
  - Pest yield impact (%) – crop-level losses
  - Pest performance (%) – survival and reproduction potential
  - Multiple countries, crops, climate models, and future time periods

---

## Methodology
- Merged and cleaned multi-level GAUL geographic datasets
- Handled missing values and normalized numeric features
- One-hot encoded categorical variables
- Aggregated pest impacts by crop, country, time, and scenario
- Computed change metrics to identify emerging risks
- Compared low- and high-emission climate scenarios
- Analyzed agreement across climate models

---

## Key Analyses Performed
- Crop vulnerability ranking
- Country-level pest pressure assessment
- Country–crop hotspot detection
- Time-based trend analysis (2040 → 2060)
- Emerging pest risk identification
- Scenario comparison (SSP245 vs SSP585)
- Climate model agreement analysis

---

## Visualizations
The notebook includes:
- Bar charts for crop and country vulnerability
- Boxplots showing impact distributions
- Heatmaps of country × crop risk
- Time-series plots of pest performance
- Scenario comparison charts highlighting SSP differences

These visuals are suitable for **reports, presentations, and policy briefs**.

---

## Key Findings
- Pest-driven crop losses **increase across most of Africa** under future climates
- Several staple crops show **significant worsening by 2060**
- **SSP585 consistently produces larger impacts** than SSP245
- Certain countries emerge as **high-risk hotspots**
- Climate models broadly **agree on increasing pest pressure**, though magnitudes vary

---

## Recommendations
- Strengthen pest surveillance and early warning systems
- Expand Integrated Pest Management (IPM) practices
- Invest in climate-resilient crop varieties
- Prioritize countries and crops with large SSP585–SSP245 gaps

---

## Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- GeoPandas  
- Jupyter Notebook  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
