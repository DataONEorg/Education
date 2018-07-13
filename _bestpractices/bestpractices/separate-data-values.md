---
title: Separate data values from annotations
layout: bestpractice_cover
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
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---


A separate column should be used for data qualifiers, descriptions, and flags, otherwise there is the potential for problems to develop during analyses. Potential entries in the descriptor column:

- Potential sources of error
- Missing value justification (e.g. sensor off line, human error, data rejected outside of range, data not recorded
- Flags for values outside of expected range, questionable etc.

## Description Rationale

Mixing numeric and textual data in one column will cause problems with analysis. Sometimes it is necessary to have both, the value and a qualifier.
