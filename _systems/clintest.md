---
layout: system
title: clintest
summary: A test framework for clingo programs.
state: stable
permalink: /clintest/
---

`clintest` is a Python framework that enables you to write efficient unit tests
for `clingo` programs quickly. Here is a brief showcase of how to devise and
run multiple tests:

```python
from clintest.test import Assert, And
from clintest.quantifier import All, Any
from clintest.assertion import Contains
from clintest.solver import Clingo

solver = Clingo("0", "a. {b}.")
test = And(
    Assert(Any(), Contains("a")),
    Assert(All(), Contains("b")),
    Assert(Any(), Contains("c")),
)

solver.solve(test)
test.assert_()
```

## Documentation

- [Documentation webpage](https://docs.potassco.org/clintest)

## Resources

- Source code on [GitHub](https://github.com/potassco/clintest)
