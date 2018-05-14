---
title: Describe the overall organization of your dataset
layout: bestpractice
tags:
- data model
- database
- describe
- documentation
- metadata
step:
- describe
related:
- consider-the-compatibility
- document-your-data
- use-consistent-codes
---

## Best Practice
Data sets or collections are often composed of multiple files that are related. Files may have come from (or still be stored in) a relational database, and the relationships among the data tables or other entities are important if the data are to be reused. These relationships should be documented for a repository.

Describe the overall organization of your data set or collection. Often, a data set or collection contains a large number of files, perhaps organized into a number of directories or database tables. By describing and documenting this organization, files and data can be easily located and used.

At a minimum, the organization and relationships between the directories and files, or database tables and other supporting materials, need to be fully described. Use a description of the data set or collection (e.g, an abstract) to describe what tables contain, where the supporting material, metadata, or other documentation are located, and/or descriptions of directory contents. Consider describing the logical relationships between data entities using an entity relationship diagram (ERD).

Associated specimens: if specimens (e.g., taxonomic vouchers, DNA samples) were collected with the data, include the name of the repository in which these specimens reside.

## Description Rationale
Relationships among data entities should be described documented to enable understanding by future users and repositories.

## Related Best Practices
- Consider the compatibility of the data you are integrating
- Document your data organization strategy
- Use consistent codes

## Additional Information
Specimen repositories: http://www.biorepositories.org/
Describing data table constraints with Ecological Metadata Language (EML): https://knb.ecoinformatics.org/#external//emlparser/docs/eml-2.1.1/./eml-constraint.html
