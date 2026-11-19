---
layout: page
title: GoaldenView backend and data platform
description: Football data and ranking API (2024 to 2026)
importance: 6
category: products
---

Primary developer of the GoaldenView backend, the service behind the GoaldenView web app and its weekly footballer popularity rankings.

- **Stack:** Python 3.11, FastAPI, SQLAlchemy with MySQL, Celery and Redis for background jobs, Docker, AWS S3 and Cloudflare for asset storage, GitLab CI/CD.
- **Platform features:** token-based authentication with TOTP two-factor and login-activity tracking, an SQLAdmin-based admin panel for managing users, players, clubs, leagues and rankings, and a journalist application and credentialing flow with email notifications. Stripe and Mailchimp integrations support subscriptions and mailing.
- **Data pipeline:** league, club and player builders with CSV import, weekly ranking updates, support for additional leagues added over time, and a player-image sync from the development to the production environment.
