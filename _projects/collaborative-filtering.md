---
layout: page
title: Collaborative filtering and graph ranking
description: Big Data coursework (2024)
importance: 3
category: academic
---

**When:** 2024 · **Course:** Fundamentals of Big Data Technology · **Data:** a ratings matrix with 610 users and 9,724 movies

Evaluated user-based and item-based collaborative filtering (cosine similarity) with an 80/20 holdout. In the archived coursework run, item-based filtering reached an MAE of about 0.81 and an RMSE of about 1.14. Also explored SVD and CUR decomposition and compared a custom PageRank implementation with NetworkX.

**Notes**
- SVD/CUR reconstruction error is not comparable to predictive RMSE.
- The custom PageRank was not shown to match the NetworkX numbers exactly.
