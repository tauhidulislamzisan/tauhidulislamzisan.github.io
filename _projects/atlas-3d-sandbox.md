---
layout: page
title: ATLAS 3D integration sandbox
description: Integration harness for the ATLAS 3D module
importance: 13
category: products
---

A standalone sandbox app for developing and debugging the integration between the ATLAS desktop application and its 3D scene module, without needing the full product around it.

- **Stack:** React 19, TypeScript, Vite, Zustand, TanStack Query, shadcn/ui with Tailwind CSS, Tauri, and Vitest.
- **Mock 3D API:** a mock of the 3D module's interface (scene, trajectory and asset loading, pose updates and plan export) with small test data sets, so the app side can be built and tested independently.
- **Replay logging:** a log of app-to-3D commands and 3D-to-app callbacks stored in IndexedDB with a built-in viewer that filters by session and exports JSONL, so interaction sequences can be replayed and issues reproduced.
