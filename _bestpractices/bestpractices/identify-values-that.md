---
title: Identify values that are estimated
layout: bestpractice
tags:
  - analyze
  - assure
  - flag
  - quality
step:
  - analyze
  - assure
related:
  - develop-a-quality
  - identify-outliers
  - identify-missing-values
---

## Best Practice
Data tables should ideally include values that were acquired in a consistent fashion. However, sometimes instruments fail and gaps appear in the records. For example, a data table representing a series of temperature measurements collected over time from a single sensor may include gaps due to power loss, sensor drift, or other factors. In such cases, it is important to document that a particular record was missing and replaced with an estimated or gap-filled value.

Specifically, whenever an original value is not available or is incorrect and is substituted with an estimated value, the method for arriving at the estimate needs to be documented at the record level. This is best done in a qualifier flag field. An example data table including a header row follows:

Day, Avg Temperature, Flag
1, 31.2, actual
2, 32.3, actual
3, 33.4, estimated
4, 35.8, actual

## Description Rationale
Correct interpretation of the content of a data table typically depends on knowing which data values were actually recorded in the field or estimate using other approaches.

## Related Best Practices
- Develop a quality assurance and quality control plan
- Identify outliers
- Identify missing values and define missing value codes

## Additional Information
Hook, Les A., Suresh K. Santhana Vannan, Tammy W. Beaty, Robert B. Cook, and Bruce E. Wilson. 2010. Best Practices for Preparing Environmental Data Sets to Share and Archive. Available online (http://daac.ornl.gov/PI/BestPractices-2010.pdf) from Oak Ridge National Laboratory Distributed Active Archive Center, Oak Ridge, Tennessee, U.S.A. doi:10.3334/ORNLDAAC/BestPractices-2010
