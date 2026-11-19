---
layout: page
title: Arrhythmia classifier comparison
description: Machine Learning coursework (2024)
importance: 2
category: academic
---

**When:** 2024 · **Course:** Machine Learning · **Data:** UCI Arrhythmia dataset (452 cases, 279 original features)

Compared six classifiers (kNN, logistic regression, decision tree, linear SVM, kernel SVM and Random Forest), each with and without PCA, giving 12 configurations on an 80/20 split. Preprocessing, confusion matrices and held-out evaluation are documented in a formal course report.

**Evaluation notes**
- Imputation was applied to the full table before the train/test split, so I do not report the archived accuracy as a valid result.
- The planned fix is imputation inside the training fold, with stratified or repeated evaluation and class-aware metrics.
