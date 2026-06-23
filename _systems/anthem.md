---
layout: system
title: anthem
summary: A translator between answer set programs and first-order logic.
state: stable
permalink: /anthem/
---

_Anthem_ is a tool for automated verification of ASP programs. For a broad
class of clingo and ASP-Core-2 programs, _anthem_ can translate a program into
a set of formulas written in the syntax of first-order logic. Given a
specification (written in first-order logic or as another ASP program), anthem
can automatically check certain types of equivalence hold between a program of
interest and the specification by invoking the automated theorem prover
vampire.

## Documentation

- [Manual](https://docs.potassco.org/anthem/)
- [API documentation](https://docs.rs/anthem/)

## Resources

- Source code on [GitHub](https://github.com/potassco/anthem)

## Publications

- Fandinno, J., Hansen, Z., Lierler, Y., Glinzer, C., Heuer, J., Schaub, T., Stolzmann, T., & Lifschitz, V.
  [ANTHEM 2.0: Automated Reasoning for Answer Set Programming]({{ site.publicationurl }}#DBLP:journals/tplp/FandinnoHLGHSSL25), TPLP, 2025
