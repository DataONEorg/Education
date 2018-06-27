---
title: Maintain consistent data typing
layout: bestpractice_cover
tags:
  - database
  - describe
  - documentation
  - format
  - metadata
step:
  - describe
related:
  - create-a-data
  - preserve-information-keep
  - use-consistant-codes
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



Choose the right data type and precision for data in each column. As examples: (1) use date fields for dates; and (2) use numerical fields with decimal places precision. Comments and explanations should not be included in a column that is meant to include numeric values only. Comments should be included in a separate column that is designed for text. This allows users to take advantage of specialized search and computing functionality and improves data quality. If a particular spreadsheet or software system does not support data typing, it is still recommended that one keep the data type consistent within a column and not mix numbers, dates and text.

## Description Rationale

Strict data typing provides quality control and enables extended analytical procedures such as date calculations and quality assurance procedures.
