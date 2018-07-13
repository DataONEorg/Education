---
title: Describe the spatial extent and resolution of your dataset
layout: bestpractice_cover
tags:
  - describe
  - documentation
  - geospatial
  - location
  - measurement
  - metadata
step:
  - describe
related:
  - choose-and-use
  - consider-the-compatibility
  - use-consistent-codes
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---



The spatial extent of your data set or collection as a whole should be described. The minimum acceptable description would be a bounding box describing the northern most, southern most, western most, and eastern most limits of the data.

- If the entire collection is from a single location, use the same values for northerly/southerly limits and easterly/westerly values.
- Be sure to specify in the metadata what units you choose to describe your spatial extent.
- Use the following guidelines for quality control:
  - If the collection spans the north pole, the northerly limit should be 90.0 degrees
  - If the collection spans the south pole, the southerly limit should be -90.0 degrees
  - If the collection crosses the date line, the westerly limit should be greater than the easterly limit

If your data collection or dataset as a whole contains data acquired over a range of spatial locations during each collection period, it is important to document the spatial resolution of your dataset. Many metadata standards have standard terminology for describing data spacing or resolution (e.g. every half degree, 250 m resolution, etc.), but it may be necessary to describe complex data acquisition schemes textually.

## Description Rationale

Describing the spatial boundaries of a data collection as a whole allows users to assess the collection for applicability to their research needs without having to individually assess the relevance of each individual component of the collection.

## Additional Information

NASA-GCMD (spatial coverage & data resolution): [https://gcmd.nasa.gov/add/difguide/index.html](https://gcmd.nasa.gov/add/difguide/index.html)

## Examples

A data collection consisting of a number of buoys floating in the Arctic ocean might have a spatial extent of...

- Northernmost latitude: 90.0
- Westernmost longitude: -180.0
- Easternmost longitude: 180.0
- Southernmost latitude: 66.0

250m gridded data:

- Data are measured every 250 m along a series of 1 km transects defined in a shape file
