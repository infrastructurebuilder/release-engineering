---
aliases:
  - Blue/Green Deployments
tags: []
title: Blue/Green Deployments
linter-yaml-title-alias: Blue/Green Deployments
date created: 2025-10-04T08:48:41.000
date modified: 2025-10-09T08:02:11.472
---

# Blue/Green Deployments

In [this model](https://martinfowler.com/bliki/BlueGreenDeployment.html) a [[deployment]] currently running (the "blue") is considered _viable_. A [[deployment]] of a new environment ("green") is _desirable_. So one deploys the "green" version, starts to redirect traffic to the green instance, and as long as everything is fine the green is kept, the blue is removed, and the green is renamed as the "new blue" [[environment]]. If things go wrong, then traffic is diverted entirely back to the existing "blue" and the "green" is destroyed (or possibly examined to see what went wrong).