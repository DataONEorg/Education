---
title: Separate data values from annotations
layout: bestpractice
tags:
  - annotation
  - describe
  - documentation
  - flag
  - format
  - metadata
 step:
  - describe
related:
  - develop-quality-assurance
  - identify-and-use
  - plan-data-management
---

## Best Practice
A separate column should be used for data qualifiers, descriptions, and flags, otherwise there is the potential for problems to develop during analyses. Potential entries in the descriptor column:

-Potential sources of error
-Missing value justification (e.g. sensor off line, human error, data rejected outside of range, data not recorded
-Flags for values outside of expected range, questionable etc.

## Description Rationale
Mixing numeric and textual data in one column will cause problems with analysis. Sometimes it is necessary to have both, the value and a qualifier.

## Related Best Practices
- Develop a quality assurance and quality control plan
- Identify and use relevant metadata standards
- Plan data management early in your project
