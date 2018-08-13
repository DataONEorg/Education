---
title: Describe the temporal extent and resolution of your dataset
layout: bestpractice_cover
tags:
- date
- describe
- documentation
- measurement
- metadata
- time
step:
- describe
related:
- choose-and-use
- consider-the-compatibility
- use-consistent-codes
update:
  - August 30, 2011
author:
  - Ruth Duerr
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---



The temporal extent over which the data within your dataset or collection was acquired or collected should be described. Normally this is done by providing

- the earliest date of data acquisition
- the date that the last data in the collection was acquired

Year, month, day, and time should be included in the description. If data collection is still ongoing, the end date can be omitted, though some statement about this should be placed in the dataset abstract. The status of the data set should indicate that data collection is still ongoing if the metadata standard being used supports this type of documentation.

Describe the temporal resolution of your dataset collection. The temporal resolution of your dataset is the frequency with which data is collected or acquired. While many metadata standards provide standard nomenclature for describing simple temporal resolutions (e.g., daily or monthly), more complex temporal collection patterns may need to be described textually.

## Description Rationale

Describing the temporal boundaries of a data collection as a whole allows users to assess the collection for applicability to their research needs without having to individually assess the relevance of each measurement within the collection. Describing the temporal resolution of your data set or collection allows users to assess the utility of your data set against their needs without examining each component of your data set individually.

## Additional Information

NASA-GCMD (temporal coverage & data resolution): [https://gcmd.nasa.gov/add/difguide/index.html](https://gcmd.nasa.gov/add/difguide/index.html)

## Examples

Dates could be given in ISO 8601 date/time format (YYYY-MM-DDThh:mm:ss).

A data set collected daily since February 1, 1990 should be described as
- Start date: 1990-02-01

"Data measured every 5 minutes seasonally during the summer months of June - August"

If collection of data ended on March 19, 2002 the temporal extent would be:
- Start date: 1990-02-01
- Stop date: 2002-03-19
