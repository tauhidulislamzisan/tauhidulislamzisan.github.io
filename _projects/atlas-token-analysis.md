---
layout: page
title: AI-assisted development workflow analysis
description: Token-economy study for the ATLAS repository (2026)
importance: 14
category: products
---

An analysis of what AI coding agents read and what it costs across the ATLAS repository's todo-driven development pipeline, and a set of changes to reduce waste without losing grounding.

- **Method:** inventoried every instruction document, command and skill in the agent chain, sampled six completed todos and verified their claimed outputs against the code (9 of 9 spot-checked files matched), and tallied documentation-reading gates across 291 completed todos.
- **Findings and fixes:** identified the main cost sinks (very large source files read whole, a stale second documentation scheme, an ever-growing todo listing) and proposed five concrete fixes, such as section maps for large files and splitting an oversized testing guide.
- **Workflow design:** wrote operating principles for mixed agent tooling on a shared branch, plus drafts of two commands, one that lets a domain expert supply the knowledge to cut planning cost and one that records a small token review per completed todo and feeds aggregated findings back into the process.
