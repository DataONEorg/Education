---
title: Ensure basic quality control
layout: bestpractice_cover
tags:
  - assure
  - coding
  - quality
step:
  - assure
related:
  - confirm-a-match
  - ensure-datasets-used
  - consider-the-compatibility
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



Quality control practices are specific to the type of data being collected, but some generalities exist:

- Data collected by instruments:
  - Values recorded by instruments should be checked to ensure they are within the sensible range of the instrument and the property being measured. Example: Concentrations cannot be < 0, and wind speed cannot exceed the maximum speed that the anemometer can record.

- Analytical results:

  - Values measured in the laboratory should be checked to ensure that they are within the detection limit of the analytical method and are valid for what is being measured. If values are below the detection limit, they should be properly coded and qualified.
  - Any ancillary data used to assess data quality should be described and stored. Example: data used to compare instrument readings against known standards.

- Observations (such as bird counts or plant cover):

  - Range checks and comparisons with historic maxima will help identify anomalous values that require further investigation.
  - Comparing current and past measurements help identify highly unlikely events. For example, it is unlikely that the girth of a tree will decrease from one year to the next.

- Codes should be used to indicate quality of data:

  - Codes should be checked against the list of allowed values to validate code entries
  - When coded data are digitized, they should be re-checked against the original source. Double data entry, or having another person check and validate the data entered, is a good mechanism for identifying data entry errors.

Dates and times:

- Ensure that dates and times are valid
- Time zones should be clearly indicated (UTC or local)

Data Types:

- Values should be consistent with the data type (integer, character, datetime) of the column in which they are entered. Example: 12-20-2000A should not be entered in a column of dates).
- Use consistent data types in your data files. A database, for instance, will prevent entry of a string into a column identified as having integer data.

Geographic coordinates:

- Map coordinates to detect errors

## Description Rationale

Quality control procedures identify potential problems with data that could affect its use.

## Additional Information:

Chapman, Arthur D. 2005. Principles of Data Quality, version 1.0. Report for the Global Biodiversity Information Facility, Copenhagen.

US Environmental Protection Agency. 2002. Guidance on Environmental Data Verification and Data Validation. [http://www.epa.gov/quality/qs-docs/g8-final.pdf](http://www.epa.gov/quality/qs-docs/g8-final.pdf)
