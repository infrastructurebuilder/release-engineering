---
aliases:
  - Tag Releases
tags:
  - TODO

title: Tag Releases
linter-yaml-title-alias: Tag Releases
date created: 2025-10-09T07:26:55.000
date modified: 2025-10-09T07:30:36.013
---

# Tag Releases

## Intro

Tag releases are just that. The release is a tag in some source code management system and is generally referred to by that tag. This started many years ago as a means for easy management of code by developers and is relatively popular in a number of languages and build systems.

Tag releases are somewhat the opposite of an [[intermediate form]] release. Formally for this discussion, a tag release is specifically tagging source code in a repository and referring to that tag as a [[release]]. No mention is made, nor is there usually evidence, that a given tag has passed through any [[gatekeeping]] operations in the process of producing this nominal release.

## Types

As a general rule, discussions with release engineering practitioners fall into three camps.

### That's AWESOME!

The first camp of practitioners find tag release techniques to be a welcome break from what they consider to be an arduous task. Those people are correct. It absolutely does remove most of the work from a formal [[intermediate form]]-based release process. It also removes almost all benefit from such a process.

### This is Madness!

The other camp feel like settling into just tagging software as a nominal release removes all the rigor that comes with the process. This isn't always true. It's entirely possible to provide rigor around the tag releases. The problem is that there's no production of any intermediate form. Effectively speaking, nothing really ever prevents a tag from being created in nearly any [[source code]] management tool.

### The Third Camp

There exists a third type of release practitioner. This actor is typically held hostage by some externally mandated practice that has inscrutable steps and obvious waste embedded in it. Large corporations and governmental entities will frequently have such a person (or more usually, a team) in place to handle this.

## Providing Arbitrage on the Weaknesses of Tag Releases

Good question. #TODO