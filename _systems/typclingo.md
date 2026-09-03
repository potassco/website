---
layout: system
title: typclingo
summary: A type checker for Clingo ASP programs
state: experimental
permalink: /typclingo/
---

This is a prototype implementation of a type checker for logic programs. It supports type annotations for predicates and functions, and checks whether the program is well-typed in the sense that the meets of the types involved in rules are non-empty.

Type annotations are written in comments, so the ASP program itself is never modified and can be passed to clingo as usual. typclingo runs as a preprocessor ahead of the normal workflow, adding a layer of static checking without changing how programs are written or solved.

## Resources

- Source code on [GitHub](https://github.com/potassco/typclingo/)

## Publications
