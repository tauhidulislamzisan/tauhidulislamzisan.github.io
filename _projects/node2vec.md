---
layout: page
title: Node2Vec node classification
description: Big Data coursework, 2024
importance: 4
category: academic
---

Node classification on the PubMed Diabetes citation network (19,717 papers, three classes). Worked on its largest connected component (19,143 nodes, 43,678 edges): biased random walks with StellarGraph (p=1.0, q=0.5, 98,585 walks), 64-dimensional Word2Vec embeddings with gensim, and a cross-validated logistic regression classifier on a 70/30 split.

- **Result:** about 79.95% test accuracy from the graph embeddings alone, with a t-SNE view of the embeddings coloured by class.
- **Scope:** a course lab on a public benchmark, run once on a single split; no comparison against other embedding methods.
