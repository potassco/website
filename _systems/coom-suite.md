---
layout: system
title: coom-suite
summary: Python package to parse and solve product configuration problems specified in COOM using ASP.
state: stable
permalink: /coom-suite/
---

The [COOM language](https://www.coom-lang.org/) is a domain-specific language for modelling product configuration problems.
While currently geared towards ASP, the COOM Suite is intended to serve as a general workbench for experimentation with industrial-scale product configuration problems.
It includes a (customizable) [ANTLR v4](https://www.antlr.org/) parser to convert COOM specifications into facts, and currently contains two ASP encodings for solving: one for [clingo](https://potassco.org/clingo) and one for hybrid solver [flingo](https://potassco.org/flingo/).

In addition, a simple UI, a range of examples, and a [benchmark collection](https://github.com/potassco/coom-benchmarks) with various scalable benchmark sets is provided.

## Documentation

- [Documentation webpage](https://docs.potassco.org/coom-suite/)

## Resources

- Source code on [GitHub](https://github.com/potassco/coom-suite/)

## Publications

- Baumeister, J., Hahn, S., Herud, K., Ostrowski, M., Reutelshöfer, J., Rühling, N., Schaub, T., & Wanko, P. [Towards Industrial-scale Product Configuration]({{ site.publicationurl }}/#DBLP:journals/corr/abs-2504-00013), TPLP, 2026
