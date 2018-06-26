---
title: Develop a quality assurance and quality control plan
layout: cover_bps
tags:
- assure
- data consistency
- flag
- measurement
- quality
step:
- assure
related:
- communicate-data-quality
- confirm-a-match
- define-the-data
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---


Just as data checking and review are important components of data management, so is the step of documenting how these tasks were accomplished. Creating a plan for how to review the data before it is collected or compiled allows a researcher to think systematically about the kinds of errors, conflicts, and other data problems they are likely to encounter in a given data set. When associated with the resulting data and metadata, these documented quality control procedures help provide a complete picture of the content of the dataset. A helpful approach to documenting data checking and review (often called Quality Assurance, Quality Control, or QA/QC) is to list the actions taken to evaluate the data, how decisions were made regarding problem resolution, and what actions were taken to resolve the problems at each step in the data life cycle. Quality control and assurance should include:

- determining how to identify potentially erroneous data
- how to deal with erroneous data
- how problematic data will be marked (i.e. flagged)

For instance, a researcher may graph a list of particular observations and look for outliers, return to the original data source to confirm suspicions about certain values, and then make a change to the live dataset. In another dataset, researchers may wish to compare data streams from remote sensors, finding discrepant data and choosing or dropping data sources accordingly. Recording how these steps were done can be invaluable for later understanding of the dataset, even by the original investigator.

Datasets that contain similar and consistent data can be used as baselines against each other for comparison.

- Obtain data using similar techniques, processes, environments to ensure similar outcome between datasets.
- Provide mechanisms to compare data sets against each other that provide a measurable means to alert one of differences if they do indeed arise. These differences can indicate a possible error condition since one or more data sets are not exhibiting the expected outcome exemplified by similar data sets.

One efficient way to document data QA/QC as it is being performed is to use automation such as a script, macro, or stand alone program. In addition to providing a built-in documentation, automation creates error-checking and review that can be highly repeatable, which is helpful for researchers collecting similar data through time.

The plan should be reviewed by others to make sure the plan is comprehensive.

## Description Rationale

A plan for QA/QC is needed so that others can understand how to best use the data, and avoid potential mistakes that might occur due to use of poor quality data. Explicitly documenting how you check your data for errors and conflicts can also help resolve current and future questions about the data.

## Examples

Water quality data for EPA is collected with a QA/QC plan often called QAPP Quality Assurance Project Plan.

See Quality Management Tools - QA Project Plans

A Quality Assurance Project Plan documents the planning, implementation, and assessment procedures for a particular project, as well as any specific quality assurance and quality control activities. It integrates all the technical and quality aspects of the project in order to provide a "blueprint" for obtaining the type and quality of environmental data and information needed for a specific decision or use. All work performed or funded by EPA that involves the acquisition of environmental data must have an approved Quality Assurance Project Plan.

[http://www.epa.gov/QUALITY/qapps.html](http://www.epa.gov/QUALITY/qapps.html)
