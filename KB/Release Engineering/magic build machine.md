---
date updated: '2021-04-28T14:07:32-05:00'
tags:
  - '#TODO'

---

# Magic Build Machine

A magic build machine is a specialized [[build environment]].  The specialization of the environment is that it does the following:
- Is capable of performing a [[build]] of some set of needed code
- Is incapable of being properly replicated

Make no mistake:  having to rely on a magic build machine is a Very Bad Thing™.

## Rationale
During the course of building a [[build environment]], it is important to remember that most systems are [[ephemeral]] -- that at some point in the future, they will disappear.  Therefore, it it often in one's best interest to be able to replicate such an [[environment]] from scratch in the event that it dies.  The most efficient way to do this is to create the environment with [[IAC]] code that allows easy reproduction of the local configuration.  A far less attractive, but also generally easier, way to do this is with backups of the original.


## Why So Serious?
It would be reasonable to ask why this topic has its own page.  The answer is simple: because across the course of decades and probably hundreds of locations, the authors have never know of any place that had _zero_ instances of magic build machines.  They were not always essential, but they were always there.