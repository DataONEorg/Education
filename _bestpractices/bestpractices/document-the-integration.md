---
title: Document the integration of multiple datasets
layout: cover_bps
tags:
- citation
- data consistency
- documentation
- integrate
- metadata
- provenance
step:
- integrate
related:
- consider-the-compatibility
- document-steps-used
- preserve-information-keep
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



Document that steps used to integrate disparate datasets.
- Ideally, one would adopt mechanisms to systematically capture the integration process, e.g. in an executable form such as a script or workflow, so that it can be reproduced
- In lieu of a scientific workflow system, document the process, scripts, or queries used to perform the integration of data in documentation that will accompany the data (metadata)
- Provide a conceptual model that describes the relationships among datasets from different sources
- Use unique identifiers in the data records to maintain data integrity by reducing duplication
- Identify foreign key fields in the data records which support the relationship between the data sources
- When you use datasets and data elements from within those datasets as a source for new datasets, it is important to identify and document those data within the documentation of the new/derived dataset. This is known as dataset provenance; provenance describes the origin or source of something. Just as you would cite papers that are sources for your research paper, it is critical to identify the sources of the data used within your own datasets. This will allow for:
  - tracing the chain of use of datasets and data elements
  - credit and attribution to accrue to the creators of the original datasets
  - the possibility that if errors or new information about the original datasets or data elements comes to light, that any impact on your new datasets and interpretation of such could be traced

## Description Rationale

Provide enough information about the process used to integrate disparate datasets so that others can properly use your data and/or your process to integrate similar data sources.

## Related Best Practices

- Consider the compatibility of the data you are integrating
- Document steps used in data processing
- Preserve information: keep your raw data raw

## Examples

Some proposed guidelines and methods of citing datasets and data elements can be found at:

- [DataCite: Cite your data](http://www.datacite.org.s3-website-eu-west-1.amazonaws.com/cite-your-data.html)
- [Dryad: Citing Data](http://wiki.datadryad.org/Citing_Data)
- [A Proposed Standard for the Scholarly Citation of Quantitative Data](http://www.dlib.org/dlib/march07/altman/03altman.html)
- [Dataverse Network Data Citation Standard](https://dataverse.org/)

## Additional Information (Biblio)

[A survey of approaches to automatic schema matching.](https://doi.org/10.1007/s007780100057)
