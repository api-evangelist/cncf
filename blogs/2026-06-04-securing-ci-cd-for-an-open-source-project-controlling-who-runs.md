---
title: "Securing CI/CD for an Open Source Project: Controlling Who Runs What"
url: "https://www.cncf.io/blog/2026/06/04/securing-ci-cd-for-an-open-source-project-controlling-who-runs-what/"
date: "2026-06-04"
author: "Andre Martins, Feroz Salam"
feed_url: "https://www.cncf.io/blog/feed/"
---
The first part of a three-part series details how the Cilium project hardens its supply chain against compromise by controlling who can trigger builds and what code CI is allowed to execute. The authors describe using a custom GitHub bot called Ariane to restrict workflow triggers to verified organization members, separating trusted and untrusted code in pull request builds, and using CODEOWNERS rules to gate CI configuration changes. The patterns described are designed to be applicable to any open source project using GitHub Actions.
