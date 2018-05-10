---
title: Choose and use standard terminology to enable discovery
layout: bestpractice
tags:
  - controlled vocabulary
  - describe
  - documentation
  - metadata
  - ontologies
  - preserve
  - standards
---

## Best practice

Terms and phrases that are used to represent categorical data values or for creating content in metadata records should reflect appropriate and accepted vocabularies in your community or institution. Methods used to identify and select the proper terminology include:

 - Identify the relevant descriptive terms used as categorical values in your community prior to start of the project (ex: standard terms describing soil horizons, plant taxonomy, sampling methodology or equipment, etc.)
 - Identify locations in metadata where standardized terminology should be used and sources for the terms. Terminology should reflect both data type/content and access methods.
 - Review existing thesauri, ontologies, and keyword lists for your use before making up a new terms. Potential sources include: Semantic Web for Earth and Environmental Terminology (SWEET), Planetary Ontologies, and NASA Global Change Master Directory (GCMD)
 - Enforce use of standard terminology in your workflow, including:
    - Use of lookup tables in data-entry forms
    - Use of field-level constraints in databases (restrict data import to match accepted domain values)
    - Use XML validation
    - Do manual review
  - Publish metadata using Open Standards, for example:
    - z39.50
    - OGC Catalog Services for Web (CSW)
    - Web Accessible Directory (WAD)

If you must use an unconventional or unique vocabulary, it should be identified in the metadata and fully defined in the data documentation (attribute name, values, and definitions).

## Description Rationale

The consistent use of well-defined, referenced terminology in describing data products, their parameters, and access methods improves the ability to discover those products for specific uses and access via well-known methods. Determine if there are controlled vocabulary terms, scientific taxonomies, and ontologies used by your community, and use those when creating metadata for your dataset.

## Related Best Practices 

- Assign descriptive file names
- Identify and use relevant metadata standards
- Plan data management early in your project

## Additional Information

Controlled vocabulary: http://www.nlm.nih.gov/mesh/meshhome.html

SWEET Web Site: http://sweet.jpl.nasa.gov/ontology/

Biological ontologies: http://www.obofoundry.org/

Taxonomy: http://www.biodiversitylibrary.org/

## Examples

Ecological Informatics, Volume 2, Issue 3, October 2007, Pages 279-296 Meta-information systems and ontologies. A Special Feature from the 5th International Conference on Ecological Informatics ISEI5, Santa Barbara, CA, Dec. 4–7, 2006 - Novel Concepts of Ecological Data Management S.I.

Guidelines for the Construction, Format, and Management of Monolingual Controlled Vocabularies. 2010. ANSI/NISO Z39.19. (http://www.niso.org/kst)

Olsen, L.M., G. Major, K. Shein, J. Scialdone, R. Vogel, S. Leicester, H. Weir, S. Ritz, T. Stevens, M. Meaux, C.Solomon, R. Bilodeau, M. Holland, T. Northcutt, R. A. Restrepo, 2007 . NASA/Global Change Master Directory

(GCMD) Earth Science Keywords. Version 6.0.0.0.0
Citing GCMD Keywords (http://gcmd.nasa.gov/Resources/valids/)
