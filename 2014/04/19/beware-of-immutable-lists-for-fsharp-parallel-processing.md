---
title: "Beware of Immutable Lists for F# Parallel Processing (techtinkering.com)"
author: Lawrence Woodman
excerpt: >-
  With F#, the *list* often feels like the default choice of data structure. It is immutable and hence easy to reason about, however its use can come at a great cost. If you are using lists to process large amounts of data, then a lot of time will be spent creating objects and garbage collecting. When I stress tested lists with F#, it became clear that this can cause a major synchronization issue when parallel processing. In fact, I was often seeing programs written in parallel which were effectively just context switching between threads rather than running in parallel.
license: CC BY 4.0
markdown file: "https://github.com/lawrencewoodman/techtinkering.com/blob/master/content/articles/2014-04-19-beware-of-immutable-lists-for-fsharp-parallel-processing.md"
retrieved: 2026-09-18
techtinkering of:
  - F# (programming language)
type: website
url: /techtinkering.com/2014/04/19/beware-of-immutable-lists-for-fsharp-parallel-processing/
website: "https://techtinkering.com/2014/04/19/beware-of-immutable-lists-for-fsharp-parallel-processing/"
when: 2014-04-19
tags:
  - website
  - TechTinkering
---