---
aliases:
  - Infrastructure As Code
tags: []

title: Infrastructure As Code
linter-yaml-title-alias: Infrastructure As Code
date created: 2025-10-04T08:48:41.000
date modified: 2025-10-09T07:30:36.706
---

# Infrastructure As Code

Infrastructure as Code (IAC) has now come into wide adoption. IAC is an aspect of [[operations]] that forces the management of the [[idempotence#Operational State|operational state]] of an infrastructure to be dealt with as an aspect of [[configuration management]].

In an IAC environment, rather than placing the onus of operating the infrastructure onto the eyes, hands, and keyboards, of operations personnel, the infrastructure is configured using source code in one or more IAC tools, such as [[Terraform]]. This allows a number of improvements over the process

1. The code can be stored in a [[source code]] repository (like [[git]]).
2. The code in that repository can be [[peer review|peer-reviewed]].
3. The state of the system can be inferred from some state storage[^state].
4. If a state starts to drift out of configuration, another [[idempotence|idempotent]] application of the IAC code should bring it back into compliance.

IAC comes with some costs. Most of these costs are measured by additional time required to produce the IAC source code, and the increased complexity of understanding necessary to craft the correct IAC sources.

[^state]: Without having to go and look directly