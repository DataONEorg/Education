---
title: Ensure flexible data services for virtual datasets
layout: cover_bps
tags:
  - data archives
  - data services
  - describe
  - preserve
step:
  - describe
  - preserve
related:
  - consider-the-compatibility
  - describe-the-contents
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



In order for a large dataset to be effectively used by a variety of end users, the following procedures for preparing a virtual dataset are recommended:

- Identify data service users

- Define data access capabilities needed by community(s) of users. For example:
  - Spatial subsetting
  - Temporal subsetting
  - Parameter subsetting
  - Coordinate transformation
  - Statistical characterization

- Define service interfaces based upon Open Standards. For example:

  - Open Geospatial Consortium (OGC WMS, WFS, WCS)
  - W3C (SOAP)
  - IETF (REST – derived from Hypertext Transfer Protocol [HTTP])

- Publish service metadata for published services based upon Open Standards. For example:

  - Web Services Definition Language (WSDL)
  - RSS/Atom (see Service Casting reference below for an example of a model for publishing service metadata for a variety of service types)

## Description Rationale

Some datasets are too large to efficiently deliver in their entirety, or are not directly usable by some users. To enable their effective use by a variety of end users, data collections may be published as "virtual" datasets that are extracted and/or processed based upon source data and pre-defined functions that deliver products derived from the source data.

## Additional Information:

[Web Service Definition Language](http://www.w3.org/TR/wsdl)  
[Service Casting via RSS/Atom](http://wiki.esipfed.org/index.php/Atom_ServiceCasting_to_advertise_Web_Services)
