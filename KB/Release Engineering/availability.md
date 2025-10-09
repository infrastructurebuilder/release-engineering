---
aliases:
  - Availability
tags: []

title: Availability
linter-yaml-title-alias: Availability
date created: 2025-10-04T08:48:41.000
date modified: 2025-10-09T07:30:36.553
---

# Availability

<dl>
<dt>availability</dt>
<dd>the general state of being accessible by an intended consumer</dd>
</dl>

Availability is a transient attribute indicating accessibility by [[audience|valid consumers]].

A [[service]], [[platform]], [[environment]], or [[artifact]] may or may not be available.

If it is available, then it is in a place where it could be accessed by a valid [[audience|consumer]].

If it is unavailable, then it has become (or possibly was never) accessible by its consumer base.

Note that as a transient attribute, availability will come and go depending on internal and external factors.  As a rule, [[operations]] strives for nominally "high" availability (whatever that means to the target consumer and consumable).

> For instance, if AWS goes down and your application is hosted on AWS, then it has become inaccessible. You might need to do something to rectify this, or you might need to do nothing, waiting until AWS recovers.
