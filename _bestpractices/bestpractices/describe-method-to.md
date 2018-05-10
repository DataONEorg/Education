---
title: Describe method to create derived data products
layout: bestpractice
tags:
- analyze
- data processing
- describe
- provenance
step:
- analyze
- describe
related:
- consider-the-compatibility
- document-your-data
- use-consistent-codes
---

## Best Practice
When describing the process for creating derived data products, the following information should be included in the data documentation or the companion metadata file:

- Description of primary input data and derived data
- Why processing is required
- Data processing steps and assumptions
  - Assumptions about primary input data
  - Additional input data requirements
  - Processing algorithm (e.g., volts to mol fraction, averaging)
  - Assumptions and limitations of algorithm
  - Describe how algorithm is applied (e.g., manually, using R, IDL)
- How outcome of processing is evaluated
  - How problems are identified and rectified
  - Tools used to assess outcome
  - Conditions under which reprocessing is required
- How uncertainty in processing is assessed
  - Provide a numeric estimate of uncertainty
- How processing technique changes over time, if applicable

## Related Best Practices
- Consider the compatibility of the data you are integrating
- Document your data organization strategy
- Use consistent codes

## Additional Information
Bourque, Linda B., Clark, Virginia A. Processing Data: The Survey Example (Quantitative Applications in the Social Sciences), Sage Publications, Inc. (December 14, 2008), ISBN 08056781901
