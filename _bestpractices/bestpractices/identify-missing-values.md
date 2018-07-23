---
title: Identify missing values and define missing value codes
layout: bestpractice_cover
tags:
  - assure
  - coding
  - missing values
step:
  - assure
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


Missing values should be handled carefully to avoid their affecting analyses. The content and structure of data tables are best maintained when consistent codes are used to indicate that a value is missing in a data field. Commonly used approaches for coding missing values include:
- Use a missing value code that matches the reporting format for the specific parameter. For example, use ""-999.99"", when the reporting format is a FORTRAN-like F7.2.
- For character fields, it may be appropriate to use ""Not applicable"" or ""None"" depending upon the organization of the data file.
- It might be useful to use a placeholder value such as ""Pending assignment"" when compiling draft information to facilitate returning to incomplete fields.
- Do not use character codes in an otherwise numeric field.

Whatever missing value is chosen, it should be used consistently throughout all data associated files and identified in the metadata and/or data description files.

## Description Rationale
Missing values are common in environmental data and affect the interpretation, analysis and calculations. Therefore, they need to be carefully defined and properly described. In addition many instruments will automatically add missing value codes in their datastream which will have to be dealt with for storage and analysis.

## Additional Information

Monitoring programs like EPA, USGS, etc. have online documentation on how do handle missing values and can be consulted.

L. A. Hook, L.A., T.W. Beaty, S. SanthanaVannan, L. Baskaran, and R. B. Cook. 2007. Best Practices for Preparing Environmental Data Sets to Share and Archive. [http://dx.doi.org/10.3334/ORNLDAAC/BestPractices-2010](http://dx.doi.org/10.3334/ORNLDAAC/BestPractices-2010)
Cook, R. B., Olson, R. J., Kanciruk, P., and Hook, L. A. 2001. Best Practices for Preparing Ecological and Ground-Based Data Sets to Share and Archive. Bulletin of ESA 82: 138-141. [http://www.jstor.org/stable/20168543](http://www.jstor.org/stable/20168543)
Borer, E. T., Seabloom, E. W., Jones, M. B., & Schildhauer, M. 2009. Some Simple Guidelines for Effective Data Management. Bull. of ESA 90: 209-214. [https://doi.org/10.1890/0012-9623-90.2.205](https://doi.org/10.1890/0012-9623-90.2.205)
