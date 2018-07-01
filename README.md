# EducationUI

This repository provides a Jekyll site that renders content from other Git
repositories where the content is located.


UI generation for education. Content included as submodules.

```
git submodule add https://github.com/DataONEorg/BestPractices.git bestpractices
git submodule add https://github.com/DataONEorg/Education.git lessons
```

When cloning:

```
git clone --recursive https://github.com/DataONEorg/EducationUI.git
```

It is important to note that `/ui/bestpractices` and `/ui/lessons` are both
separate git repositories. Git commands should not attempt to perform actions
across repositories, e.g. attempting to `git mv` between repositories won't
work.


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
{{ endfor %}
```

The lesson collection is a bit odd because we need to treat each folder as an
item, but Jekyll treats each file as an item. Metadata from both the 
`slides.md` and `index.md` is used in rendering, but it takes a bit of extra
work.

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
