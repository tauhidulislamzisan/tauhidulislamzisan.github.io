---
layout: page
title: Tree-based ensemble comparison
description: Machine Learning coursework, 2024
importance: 5
category: academic
---

Compared Decision Tree, Random Forest, AdaBoost and XGBoost in a course report. The Decision Tree was evaluated on Iris (150 samples, 67/33 split); the three ensembles were evaluated on scikit-learn's Breast Cancer dataset, with feature-importance plots for each ensemble and a Random Forest decision-boundary visualisation on a synthetic moons dataset.

- **Result:** test accuracy of about 0.972 (Random Forest), 0.979 (AdaBoost) and 0.986 (XGBoost) on one train/test split, with the report recommending hyperparameter search as a next step.
- **Scope:** differences between the ensembles are small and come from a single split, so they are not a robust ranking.
