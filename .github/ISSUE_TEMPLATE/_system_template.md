---
name: New System Entry
about: Submit a new system to be added to the Potassco collection
title: "[New System] NAME"
labels: new-system
---

# Instructions

- Replace all upper case fields with actual content.
  - NAME should be a one word name for the system, ideally lowercase and without spaces. You can use dashes if needed.
  - SUMMARY should be a one sentence description of the system. It should be concise and informative, giving readers a quick overview of what the system does.
  - STATE: use "stable" (for maintained and documented), "experimental" (for work in progress), or "deprecated".
  - DESCRIPTION: provide a detailed description of the system, its features, use cases, and any other relevant information. You can also include examples and screenshots to illustrate the system's capabilities.
- Adjust URLs below if necessary, especially if the system doesn't have documentation or a GitHub repository.
- Add publication links if available.
  1. Fill in fields AUTHORS, TITLE, CONFERENCE and YEAR.
  2. Find the publication at <https://www.cs.uni-potsdam.de/wv/publications/>.
  3. Copy the last part of its URL, e.g. corr/abs-2502-09222 and use it to replace the URL SUFFIX below.

```
---
layout: system
title: NAME
summary: SUMMARY
state: STATE
permalink: /NAME/
---

DESCRIPTION

## Documentation

- [Documentation webpage](https://docs.potassco.org/NAME/)

## Resources

- Source code on [GitHub](https://github.com/potassco/NAME/)

## Publications

- AUTHORS [TITLE]({{ site.publicationurl }}/#DBLP:journals/SUFFIX), CONFERENCE, YEAR
```
