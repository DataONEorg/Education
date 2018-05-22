---
title: Contributing to Lessons
layout: layout
---

# Guidelines for contributors and content editors

Thank you for your interest in contributing to these educational materials. This document provides advice for [updating current content](#update), [suggesting changes to content](#suggest), and [forking content for your own use](#fork), as well as an introduction to [how the content is organized](#structure) and the [tools we use to display content](#tools) .

This repository was developed by the DataONE Community Engagement and
Outreach Working Group and continues to be maintained by members of this
team.

---

## Update current content <a id="update"></a>
Want to update to link or method? See a spelling error? Changes can be easily proposed by opening the [GitHub Education page](http://github.com/DataONEorg/Education) and editing content directly. For help, try this brief [GitHub tutorial](https://guides.github.com/activities/forking/) on forking and editing content.

### Editing content

1. Create a fork of the repository into your github account
2. Modify the files that you want to change ([See "Structure" below for tips on making changes](#structure))
3. Submit a pull-request against the `master` branch of this repository
4. Your changes will be reviewed

### Page not rendering?

Check that the `title` field of the YAML header (the first line of each
lesson) is in quotes.

## Suggest changes to content <a id="suggest"></a>

1. Open an [*Issue*][issue] on this repository.
2. Your suggestions will be reviewed by a member of the DataONE CEO Working Group.
3. Changes will be pushed to the repository by a CEO Working Group team member regularly/as needed.

[issue]: https://github.com/DataONEorg/Education/issues

## Fork content for your own use <a id="fork"></a>

Forking and editing content through GitHub, rather than downloading and privately editing, enables others to use your edited content and track how these materials are being used.

1. Create a fork of the repository into your github account
2. Modify the files that you want to change ([See "Structure" below for tips on making changes](#structure))

___

## Structure of the education materials <a id="structure"></a>

All of the content is generated from markdown documents. These guidelines will walk
you through the repository organization, the markdown basics, and any additional
information.

### Repository organization

The content linked to each tile on the home page is held within a single folder in the `lessons` directory. Each lesson
folder is called `XX_keyword`, where `XX` is the order content is displayed via tiles on the home page, and `keyword` is
a brief description of the content. Edits can be made to the descriptive information contained in the `cover_page.md` (the page that opens when a tile is selected on the home page).  If education materials include slides, these slides are in a file called
`slides.md`. Do not use another filename. For example, the [demonstration
lesson][demolessonhtml] markdown file can be [viewed here][demolessonmd]. This
demonstration lesson showcases most of the features you can use if publishing slides.

[demolessonhtml]: https://dataoneorg.github.io/Education/lessons/00_markdown/index.html "Rendered demonstration lesson"
[demolessonmd]: https://github.com/DataONEorg/Education/blob/master/lessons/00_markdown/index.md "Raw markdown file for the demonstration lesson"

You are free to add other directories to your lesson. Images go in `images`, and
PDF files in `pdf`. For example, a lesson repository could look like:

~~~
01_management/
  index.md
  index.png
  images/
    image1.png
    image3.jpg
  pdf/
    one-pager.pdf
~~~

### Information about the tools used <a id="tools"></a>

The markdown documents are rendered into a website using [*Jekyll*][jekyll]. When sharing presentations, slides
themselves are rendered using [*remarkjs*][remark]. The rendering is done using GitHub
pages, which builds the site from the `master` branch. You can build the site
locally with `jekyll serve -w`, and it will be available at
[`http://localhost:4000`][local] for you to review.

[jekyll]: https://jekyllrb.com/ "Jekyll website"
[remark]: https://remarkjs.com/#1 "RemarkJS website"
[local]: http://localhost:4000

The stylesheets are defined in `resources/styles`, and rendered to
`resources/dataone.css` using `lessc` (just type `make` from the root).



Thank you for your interest in making these data management education modules more useful!
