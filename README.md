# MIT-StreetCar-Delay

## Overview

The project aims to predict streetcar delays, focusing on which routes, days of the week, and times of the day experience the most significant delays. It employs techniques like PCA, clustering, classification, and regression to analyze patterns and generate predictions.

---

## Summary

### What We've Done:
- Cleaned and processed the dataset.
- Explored delay patterns using EDA.
- Applied PCA to identify key factors influencing delays.
- Built clustering models to group routes and delay behaviors.
- Developed classification and regression models for delay predictions.
- Tuned hyperparameters to improve model performance.
- Evaluated results with metrics like accuracy and R².

---

### Key Findings

#### Positive Outcomes:
- **Identified Key Factors**: Routes, time of day, and days of the week significantly impact delays.
- **Effective Dimensionality Reduction**: PCA reduced feature space while retaining relevant information.
- **Clustering Insights**: Grouped routes with similar delay characteristics.

#### Challenges:
- **Class Imbalance**: Delay categories were heavily skewed, reducing model recall for rare categories.
- **Model Limitations**: Frequent "No further splits with positive gain" warnings in LightGBM models.
- **Overfitting**: Some regression models performed poorly on validation sets.
- **Cluster Interpretability**: Difficulty understanding the characteristics defining certain clusters.

---

## Outstanding Tasks
- Data quality improvements (e.g., handle noisy or irrelevant features).
- Further interpret clustering results.
- Address class imbalance with resampling.
- Refine models and deploy real-time predictions.
