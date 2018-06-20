---
title: Ensure datasets used are reproducible
layout: cover_bps
tags:
  - analyze
  - assure
  - data archives
  - data processing
  - discover
  - provenance
  - replicable data
step:
  - analyze
  - assure
  - discover
related:
  - define-the-parameters
  - mark-data-with
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
---



When searching for data, whether locally on one's machine or in external repositories, one may use a variety of search terms. In addition, data are often housed in databases or clearinghouses where a query is required in order access data. In order to reproduce the search results and obtain similar, if not the same results, it is necessary to document which terms and queries were used.

- Note the location of the originating data set
- Document which search terms were used
- Document any additional parameters that were used, such as any controls that were used (pull-down boxes, radio buttons, text entry forms)
- Document the query term that was used, where possible
- Note the database version and/or date, so you can any limit newly-added data sets since the query was last performed
- Note the name of the website and URL, if applicable

## Description Rationale

In order to reproduce a data set or result set, it is necessary to document which terms were originally used to capture that data. By documenting this information while the search is being conducted, one greatly enhances the chance of being able to reproduce the results at a later date.

## Related Best Practices

- Define the parameters
- Mark data with quality control flags

## Additional Information:

A query example can either be formatted as a URL string (http://www.google.com/#sclient=psy&hl=en&site=&source=hp&q=data+backup+policy&aq=f&aqi=p-p2g3&aql=f&oq=&pbx=1&bav=on.2,or.r_gc.r_pw.&fp=d6a6fda25e240d6) or a database string (select * from database_name where collection_data IS NOT NULL).
