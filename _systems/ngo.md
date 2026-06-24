---
layout: system
title: ngo
summary: Non-Ground Optimizer to improve ASP encodings.
state: stable
permalink: /ngo/
---

Impress your friends with faster encodings! _Ngo_ is a program and python
library to optimize ASP encodings for performance. You can either optimize your
encoding once or simply keep your readable and maintainable encoding and
transform it every time before you actually solve. The transformation is
independent from instances and purely syntactical.

```sh
pip install ngo
cat encoding.lp | ngo > improved_encoding.lp
```

## Documentation

- [Documentation webpage](https://docs.potassco.org/ngo/)

## Resources

- Source code on [GitHub](https://github.com/potassco/ngo)
