---
title: Understand the geospatial parameters of multiple data sources
layout: cover_bps
tags:
  - analyze
  - documentation
  - geography
  - geospatial
  - integrate
  - metadata
  - provenance
step:
  - analyze
  - integrate
related:
  - consider-the-compatability
  - identify-and-use
  - use-consistent-codes
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---


Understand the input geospatial data parameters, including scale, map projection, geographic datum, and resolution, when integrating data from multiple sources. Care should be taken to ensure that the geospatial parameters of the source datasets can be legitimately combined. If working with raster data, consider the data type of the raster cell values as well as if the raster data represent discrete or continuous values. If working with vector data, consider feature representation (e.g., points, polygons, lines). It may be necessary to re-project your source data into one common projection appropriate to your intended analysis. Data product quality degradation or loss of data product utility can result when combining geospatial data that contain incompatible geospatial parameters. Spatial analysis of a dataset created from combining data having considerably different scales or map projections may result in erroneous results.

Document the geospatial parameters of any output dataset derived from combining multiple data products. Include this information in the final data product's metadata as part of the product's provenance or origin.

## Description Rationale
Awareness and proper use of geospatial data parameters can affect the ability to interpret or produce sound analysis results.

## Related Best Practices
- Consider the compatibility of the data you are integrating
- Identify and use relevant metadata standards
- Use consistent codes

## Additional Information
Burley, T.E., and Peine, J.D., 2009' NBII-SAIN Data Management Toolikit, U.S. Geological Survey Open-File Report 2009-1170, 96p. Available from: http://pubs.usgs.gov/of/2009/1170/

## Examples
Combining geospatial data created at a 1:24,000 scale with data that were created at a 1:100,000 scale results in data that are only as accurate as the least accurate input (essentially resolution is lost). Combining geospatial data that have considerably differing map projections can also result in spatial errors and potentially erroneous results. Combining raster data with a 10m resolution with raster data that have a 100m resolution will result in data that are only as accurate as the least accurate input (essentially resolution is lost).
