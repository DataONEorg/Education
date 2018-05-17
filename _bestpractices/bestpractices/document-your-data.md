---
title: Document your data organization strategy
layout: bestpractice
tags:
- data management plan
- data model
- data normalization
- database
- describe
step:
- describe
related:
- define-the-data 
- develop-a-quality 
- ensure-flexible-data 
---

## Best Practice

The following are strategies for effective data organization:
- Sparse matrix: Optimal data models for storing data avoid sparse matrices, i.e. if many data points within a matrix are empty a data table with a column for parameters and a column for values may be more appropriate.
- Repetitive information in a wide matrix: repeated categorical information is best handled in separate tables to reduce redundancy in the data table. In database design this is called normalization of data.
- Column name is a value or repeating group: If the column name contains variable information, e.g. date or species name, the parameter/value organization of data is recommended as well for storage. Although the wide matrix is needed for statistical analysis and graphing it cannot be queried or subset in that format.

## Description Rationale

Data management requires an effective strategy for data organization.

## Related Best Practices

- Define the data model
- Develop a quality assurance and quality control plan
- Ensure flexible data services for virtual datasets

## Additional Information

Borer, E. T., E. W. Seabloom, M. B. Jones, and M. Schildhauer. 2009. Some simple guidelines for effective data management. ESA Bulletin 90:205-214. https://doi.org/10.1890/0012-9623-90.2.205 
