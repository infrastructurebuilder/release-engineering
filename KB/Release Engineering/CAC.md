---
aliases:
  - Configuration as Code
tags: []
title: Configuration as Code
linter-yaml-title-alias: Configuration as Code
date created: 2025-10-04T08:48:41.000
date modified: 2025-10-09T07:29:08.131
---

# Configuration as Code

Configuration as code is a general term to describe [[configuration management]] in terms of source code that can be captured, diff'd, [[release]]d, and otherwise managed in much the same manner as executable domain code.

Specifically, configuration captured as code is generally considered to be some set of inputs to some set of [[configuration management]] systems that produce some set of changes on some set of infrastructure or domain systems.

While it is certainly possible to capture the "configuration database" of an application using an SQL/DDL dump, most people in [[DevSecOps]] tend to think of the level of abstraction as being a bit higher.

Tools like [[Ansible]], Puppet, Chef, cfengine were the earlier entries in this space. [[Terraform]] and others have the capacity to provide configuration as code using application-specific providers.