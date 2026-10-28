# Logistics Data Analytics Case Study
### Warehouse Operations, Shipment Efficiency & Predictive Modeling

## Overview

This project documents a four-week logistics data analytics case study based on a **simulated fresh-food warehouse and distribution scenario**. It explores how data analytics can support operational monitoring, shipment analysis, delivery-time prediction, and data-driven logistics recommendations.

The project follows an end-to-end analytical workflow, from KPI planning and data-preprocessing methodology to exploratory data analysis, predictive model evaluation, and business recommendations.

> **Disclaimer:** This is an educational case study using a simulated logistics scenario. It is not an official Sprouts Farmers Market analysis, and the reported findings should not be interpreted as actual company performance.

## Project Objectives

- Identify key performance indicators (KPIs) for warehouse and distribution operations.
- Document data-cleaning and preprocessing techniques.
- Explore shipment delivery times, transportation costs, inventory shrinkage, and picking performance.
- Compare regression models for delivery-time prediction.
- Develop recommendations for improving logistics efficiency.

## Project Workflow

### Week 1 — Strategic Planning & Data Exploration
- Defined logistics KPIs, including order fulfillment rate, shrinkage rate, and average picking time.
- Reviewed relevant datasets and analytical approaches.
- Outlined a roadmap for data preparation, exploratory analysis, predictive modeling, and optimization.

### Week 2 — Data Collection & Preprocessing
- Documented missing-value handling and duplicate removal.
- Explored IQR-based outlier detection, standardization, and normalization.
- Outlined a Python-based preprocessing workflow.

### Week 3 — Exploratory Data Analysis & Visualization
- Examined a reported simulated dataset of 1,200 shipment records.
- Documented analysis of delivery times, transportation costs, shrinkage trends, and warehouse-level picking performance.
- Explored relationships between shipment volume, delivery time, and transportation costs.

### Week 4 — Predictive Modeling & Recommendations
- Documented a comparison of Linear Regression and Random Forest regression for delivery-time prediction.
- Reviewed reported evaluation metrics and feature-importance findings.
- Proposed operational recommendations related to shipment prioritization, order batching, and delivery efficiency.

## Reported Model Evaluation

The weekly report documents the following model results:

| Metric | Linear Regression | Random Forest |
|---|---:|---:|
| RMSE (hours) | 2.528 | 2.554 |
| MAE (hours) | 2.029 | 2.056 |
| R² | 0.476 | 0.465 |

The report also records a five-fold cross-validation mean R² of 0.427 (standard deviation: 0.056) for Random Forest.

**Interpretation:** In the reported results, Linear Regression performed slightly better than Random Forest on the listed test metrics. The R² values indicate that substantial variation in delivery time remains unexplained.

**Validation note:** These metrics are transcribed from the project reports and have not been independently reproduced from the underlying dataset and execution artifacts.

## Tools & Technologies

- **Python** — analytical workflow and code examples
- **Pandas** — data manipulation and preprocessing
- **Scikit-learn** — regression modeling and evaluation
- **Matplotlib & Seaborn** — proposed data visualization workflow
- **Claude AI** — AI-assisted code generation and execution support

*The repository primarily contains weekly reports. Listing a technology reflects its documented use in the workflow and does not imply that every analysis or script has been independently implemented and validated.*

## Key Learnings

- Translating operational questions into measurable KPIs.
- Understanding common data-preprocessing techniques.
- Interpreting descriptive statistics, correlations, and regression metrics.
- Comparing predictive models without assuming that greater complexity guarantees better performance.
- Converting analytical findings into practical business recommendations.
- Using AI assistance as part of an analytical workflow while maintaining transparency about validation.

## Project Deliverables

The repository contains four weekly reports covering:

1. Strategic Planning and Data Exploration in Logistics
2. Data Collection, Cleaning, and Preprocessing
3. Advanced Data Analysis and Visualization
4. Predictive Modeling and Optimization

Refer to the `docx/` directory for the detailed reports.

## Limitations & Future Improvements

- Provide the underlying dataset and reproducible analysis scripts.
- Re-run the preprocessing and modeling workflow and verify the reported metrics.
- Include generated charts and model evaluation outputs.
- Compare models using a documented validation strategy.
- Implement and quantitatively evaluate route or load optimization before claiming optimization results.

## Conclusion

This case study demonstrates a structured approach to logistics analytics, connecting operational KPIs and exploratory analysis with predictive modeling and business recommendations. It also highlights the importance of reproducibility, careful interpretation, and transparent reporting.

---

**Project Type:** Educational Logistics Analytics Case Study  
**Dataset:** Simulated logistics scenario  
**AI Assistance:** Claude AI
