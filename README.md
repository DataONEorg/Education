<<<<<<< HEAD
# Welcome to the Data Management Skillbuilding Hub
=======
# Education UI
>>>>>>> 3f0c595a054f7a92d4a655579d715fabfd4ab999

This repository is a central location for education materials focused on data management. We invite all kinds of materials, please consider [contributing][CONTRIB]. Examples include: tutorials, best practices, exercises, presentations, etc.

At launch (June 2018) the repository contains DataONE Education Modules to serve as an example of what materials can be added to the repo. These Modules have been translated from PowerPoint format to a more easily updated format that you can view in your browser. Each Education Module contains a set of slides with annotations, as well as a hands on exercise, a one-page explanatory sheet, and occasionally data. These resources are intended to be flexible and updated by a range of users and audiences. Please fork and update content for your own use.

<<<<<<< HEAD
[CONTRIB]: CONTRIBUTING.md "Contribution guidelines"
=======
  https://dataoneorg.github.io/Education/
>>>>>>> 3f0c595a054f7a92d4a655579d715fabfd4ab999

## Where to find the material?

<<<<<<< HEAD
A list of the available materials can be found on [the repository's website][website]. The first page will present you with a list of the available resources. Clicking on any given resource will bring you to the resource page, where you can launch included materials. These may include a presentation, a PDF download of the slides, a handout, and/or exercises.
=======
```
git submodule add https://github.com/DataONEorg/hub_bespractices.git bestpractices
git submodule add https://github.com/DataONEorg/hub_lessons.git lessons
```
>>>>>>> 3f0c595a054f7a92d4a655579d715fabfd4ab999

[website]: https://dataoneorg.github.io/Education/ "Homepage for the Data Management Skillbuilding Hub"

<<<<<<< HEAD
=======
```
git clone --recursive https://github.com/DataONEorg/Education.git
```
>>>>>>> 3f0c595a054f7a92d4a655579d715fabfd4ab999

## Guidelines for content editors

We are glad that you want to contribute to the material! You will find more information in our [contribution guidelines][CONTRIB].

<<<<<<< HEAD
=======
Remember you are working with three different repositories:

1. EducationUI
2. `_bestpractices` (i.e. https://github.com/DataONEorg/hub_bestpractices)
3. `_lessons` (i.e. https://github.com/DataONEorg/hub_lessons)

Edits made in the `_bestpractices` or `_lessons` folders are committed to their respective repositories.

Example: An edit is made to `README.md` in `_bestpractices`, commit and push that change, then update the parent repo to the new version of the submodule:

```
cd _bestpractices
git commit -m "Fixed everything" README.md
git push
cd ..
git commit -m "Bringing submodule to latest version" _bestpractices
git push
```

After this, the remote copy of the BestPractices repo will be up to date, and the remote copy of EducationUI on GitHub will be updated so that the `_bestpractices` submodule is pointing to the latest revision.


## Working with the liquid tags

A few hints for working with Liquid tags, which are the tags using in the 
templates.

Whitespace can be controlled by adding a `-` to the opening and/or closing
liquid tag. e.g.

```
{% assign blah="foo" %}
```

Would result in a newline being output, whereas:

```
{%- assign blah="foo" %}
```

would not. 


List the available collections:

```
{%- for collection in site.collections %}
  {{ collection.label }}
{%- endfor %}
```

The lesson collection is a bit odd because we need to treat each folder as an
item, but Jekyll treats each file as an item. Metadata from both the 
`slides.md` and `index.md` is used in rendering, but it takes a bit of extra
work to get those metadata attributes when rendering a page.

From the context of the index page, the slides page can be accessed as follows:

```
{%- assign slides_id = page.id | split: "/" | slice: 0,3 | join: "/" | append: "/slides" %}
{%- assign slides = site[ page.collection ] | where: 'id', slides_id | first %}
{{ slides.title }}
```

Similarly, from the slides page, the index can be accessed:

```
{%- assign index_id = page.id | split: "/" | slice: 0,3 | join: "/" | append: "/index" %}
{%- assign index = site[ page.collection ] | where: 'id', index_id | first %}
{{ index.tags }}
```

To get a list of tags used in a collection, include the `collection_tags.html`
file using a liquid tag like:

```
{% include collection_tags.html the_collection="bestpractices" %}
```
where the value of the `the_collection` property is the name of the collection
to evaluate. The list of tags will then be available as the `tags` liquid
variable.
>>>>>>> 3f0c595a054f7a92d4a655579d715fabfd4ab999

## Maintainers

The Data Management Skillbuilding Hub webpage and repository are maintained by the Community Engagement and Outreach Working Group at DataONE. Please open an issue If you have a question or concern, please open an <a href="https://github.com/DataONEorg/Education/issues" target="_blank">Issue</a>.
