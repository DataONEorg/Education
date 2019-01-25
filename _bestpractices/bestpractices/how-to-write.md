---
title: How to write a Best Practice file
layout: bestpractice_cover
tags:
  - !tag here!
step:
  - life cycle stage here
related:
  - first-three-words
update:
  - May 08, 2018
author:
  - First and last name of person authoring the best practice, list separate bullet for each new person
organization: DataONE
org_url: http://www.your_website.org
org_logo: org.png
resource: true
categories: ["Best Practice"]
---

## Filename

Each file is named as the first three words of the title, separated by dashes.
This page's title is "How to write a best practice", therefore the filename is
`how-to-write.md`.

## Header

The header (aka: front matter) for best practices has the following fields:

`title`: the title of the webpage, as it will appear in the lists

`layout`: is always `bestpractice` (*NB* this will likely be done automatically using the collections features from jekyll)

`tags`: a list of (short) keywords describing the content of the best practice text

`step`: a list of one or more steps of the data lifecycle to which this best practice applies

`related`: a list of related best practices identifiers -- an identifier is the first three words of the title, separated by dashes (optional)

`update`: the date this best practice was created

`author`: a list of authors that created the best practice

`organization`: name of organization that oversaw the creation of the best practice

`org_url`: website of the organization, organization logo will open this webpage when selected

`org_logo`: name of the organization’s logo file, this must me a png

`categories`: this must be listed as [“Best Practice”], used for sorting and accessing education materials


## in 'Raw' view, these are the headers you should have

content
- thing 1
- thing 2
  - another thing
  - one last thing

## Description Rationale

content

## Additional Information

a few things

## Examples

content
