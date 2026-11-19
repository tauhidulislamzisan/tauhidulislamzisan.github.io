---
layout: page
title: ATLAS API optimisation and architecture review
description: Planning and review work for ATLAS (2026)
importance: 8
category: products
---

Planning and documentation work on the ATLAS test management platform, aimed at making the API leaner and the codebase easier to change safely.

- **API optimisation plan:** a staged plan to stop the app loading far more data than each screen needs at start-up. It proposes metadata-only list endpoints, explicit per-tab data endpoints with fixed response types, removing duplicated start-up calls, and an additive rollout that keeps the existing contract available while the frontend migrates.
- **Tests first:** the plan sequences baseline tests for intended current behaviour before any contract change, then updated tests, end-to-end smoke tests for critical flows and CI enforcement, with object-level authorisation checks on every new endpoint.
- **Architecture review:** module-by-module maps of the FastAPI backend and the React/TypeScript frontend (layering, data model, endpoints, cross-module dependencies and flags for cleanup), each with a companion diagram.
- **Status:** these are plans and review documents; this entry does not claim the proposed changes shipped.
