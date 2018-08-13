---
title: Communicate data quality
layout: bestpractice_cover
tags:
  - assure
  - flag
  - qualify
step:
  - assure
related:
  - ensure-basic-quality
  - ensure-datasets-used
update:
  - Aug 30, 2011
author:
  - DataONE Best Practices Working Group
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---



Information about quality control and quality assurance are important components of the metadata:

- Qualify (flag) data that have been identified as questionable by including a flagging_column next to the column of data values. The two columns should be properly associated through a naming convention such as Temperature, flag_Temperature.
- Describe the quality control methods applied and their assumptions in the metadata. Describe any software used when performing the quality analysis, including code where practical. Include in the metadata who did the quality control analysis, when it was done, and what changes were made to the dataset.
- Describe standards or test data used for the quality analysis. For instance, include, when practical, the data used to make a calibration curve.
- If data with qualifier flags are summarized to create a derived data set, include the percent flagged data and percent missing data in the metadata of the derived data file. High frequency observations are often downsampled, and it is critical to know how much of the data were rejected in the primary data.

## Description Rationale

Data quality and any methods used for quality control should be communicated so others can assess the data independently.

## Additional Information

Hook, L.A., Beaty, T.W., Santhana-Vannan, S., Baskaran, L. and Cook, R.B. 2007. Best practices for preparing environmental data sets to share and archive. Oak Ridge National Laboratory Distributed Active Archive Center, Oak Ridge, Tennessee, U.S.A. (daac.ornl.gov/PI/bestprac.html)

Sheldon, W., Henshaw, D. and Ramsey, K. 2007. Final Report: Workshop to define quality management standards for data completeness in derived data products. Long Term Ecological Research Network Document Archive, University of New Mexico, Albuquerque, NM.

## Additional Information (Biblio)

[Best Practices for Preparing Ecological and Ground-Based Data Sets to Share and Archive](https://www.dataone.org/content/best-practices-preparing-ecological-and-ground-based-data-sets-share-and-archive)
