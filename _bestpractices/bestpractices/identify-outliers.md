---
title: Identify outliers
layout: cover_bps
tags:
  - analyze
  - annotation
  - assure
  - quality
step:
  - analyze
  - assure
related:
  - develop-a-quality
  - identify-missing-values
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



Outliers may not be the result of actual observations, but rather the result of errors in data collection, data recording, or other parts of the data life cycle. The following can be used to identify outliers for closer examination:

Statistical determination:
- Outliers may be detected by using Dixon’s test, Grubbs test or the Tietjen-Moore test.

Visual determination:
- Box plots are useful for indicating outliers
- Scatter plots help identify outliers when there is an expected pattern, such as a daily cycle

Comparison to related observations:
- Difference plots for co-located data streams can show unreasonable variation between data sources. Example: Difference plots from weather stations in close proximity or from redundant sensors can be constructed.
- Comparisons of two parameters that should covary can indicate data contamination. Example: Declining soil moisture and increasing temperature are likely to result in decreasing evapotranspiration.

No outliers should be removed without careful consideration and verification that they are not representing true phenomena.
Description Rationale:

## Description Rationale

Outliers may represent data contamination, a violation of the assumptions of the study, or failure of the instrumentation. Although outliers may be valid observations it is important to identify and examine their validity.

## Additional Information

V. Barnett and T. Lewis, Outliers in Statistical Data (John Wiley & Sons, 2d ed., New York, NY, 1985).

Edwards, D. 2000. Data Quality Assurance. Pages 70-91 in: Ecological Data: design, management, and processing. Michener, W. and Brunt, J., eds. Blackwell Science Ltd. (ISBN: 0-682-05231-7).
