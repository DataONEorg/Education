---
title: "Stylesheet for GitHub Slides"
author: DataONE Community Engagement & Outreach Working Group
update: 2017-04-07T12:00:00Z
layout: slides
tags: [GitHub]
categories: ["Technical Tutorial"]
status: draft
---

# Site Structure

~~~
dataone_lessons/
├── lessons/
│   ├── lesson_folder/   <- A lesson, e.g. "00_markdown"
│   │   └── ...
│   └── ...
├── resources/           <- Images and other resources shared by lessons
├── _lessons/            <- Link to the lessons/ folder
├── _plugins/            <- Any local plugins (will not work on GitHub)
├── _layouts/            <- Templates for rendering lessons and other content
├── config.yml           <- Site configuration information
├── Gemfile              <- Describes items needed by Jekyll
├── index.md             <- Landing page content for the site
└── remark2pdf           <- script that generates a PDF from a lesson
~~~


---

# Lesson Folders

Each lesson is a separate folder in the `lessons` folder:

~~~
dataone_lessons/
├── lessons/
│   ├── lesson_folder/   <- e.g. "00_markdown"
│   │   ├── index.md     <- Markdown file that makes the actual presentation
│   │   ├── cover.md     <- Landing page for the lesson
│   │   ├── cover.png    <- Landing page image for lesson
│   │   └── images/      <- Images specific to a lesson
│   │       ├── image_1.jpg
│   │       └── ...
│   └── ...
├── resources/           <- Images and other resources shared by lessons
...

~~~


---
# Lesson Presentation

Each lesson is a single markdown document that is converted to HTML by [remark](https://github.com/gnab/remark) javascript. 

Each slide starts with a `# title`, and ends with `---`:

 ~~~md
 # This is the Slide Title

 This is the content of the slide.
 
 ---
 # This is the Title of the Next Slide
 
 This is the content of the next slide.
 ~~~

Spaces are important in Markdown. For example, if you are not seeing a new slide, then check that there are no spaces to the left of the slide terminator `---`.

---

# General Info

Lesson title and metadata go in the `yaml` header:

~~~ yaml
 ---
 title: "Lesson title"    <-- The Title of the Presentation
 update: Sept. 20, 2016   <-- When the slides where last edited
 layout: slides           <-- How the slides are rendered
  
 ---
  
 # Title of the first content slide
~~~

Everything *below* that is markdown.


The `yaml` header is the first element of a presentation, and will give the
title, date of latest update, and (possibly) other data. The line `layout:
slides` is **very important** because it controls how the slides are rendered.

---

# Markdown 101

- `*italics*` is *italics*
- `**bold**` is **bold**
- `***bold italics***` is ***bold italics***
- `[DataONE](https://www.dataone.org)`
will appear as [DataONE](https://www.dataone.org)

.one-half[
~~~md
- List item 1
- List item 2
  - Nested list item

1. Enumerated list
2. Second item
  - We can mix both
~~~
]
.one-half[
- List item 1
- List item 2
  - Nested list item

1. Enumerated list
2. Second item
  - We can mix both
]

See the [remark wiki](https://github.com/gnab/remark/wiki/Markdown) for more.

---

# Headings

.one-half[
~~~md
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
~~~
]

.one-half[
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
]

.full-width[
Heading levels are specified by the number of `#` at the beginning of a line. Six levels of headings are supported.
]
---

# Quotes

~~~
> Text goes here
~~~

> Text goes here

---

# Syntax Highlighting

``` md
  ~~~ R
  <your code here>
  ~~~
```

renders as

~~~ R
random_thing <- function(x, r, ...) {
  return(r(x, ...))
}

plot(random_thing(100, runif))
~~~

You can also put code inline, using backticks:

~~~ md
 This is `inline` code.
~~~

---

# Tables

.one-half[
Markdown can do tables:

~~~ md
|   Animal | Diet      | Fuzzy? |
|---------:|:----------|:------:|
| Hedgehog | rings     |   no   |
|   Racoon | garbage   |  meh   |
|      Cat | hairballs |  yup   |
~~~

]

.one-half[
This renders as:

|   Animal | Diet      | Fuzzy? |
|---------:|:----------|:------:|
| Hedgehog | rings     |   no   |
|   Racoon | garbage   |  meh   |
|      Cat | hairballs |  yup   |
]

---

# Notes

.one-third[
Notes are everything that comes below `???`. Press **P** to toggle presenter
mode.
]

.two-third[
~~~ md
Notes are everything that comes below `???`.
Press **P** to toggle presenter mode.

???

These are the notes, and *they can* be in markdown too.
~~~
]

???

These are the notes, and *they can* be in markdown too.
---

# Columns

.two-third[

It is possible to have columns or various widths in the presentation. The
columns should be wrapped the following way:
~~~
.one-third[
  content
]
~~~

You can chain columns in any way you want, *e.g.* 1/3 then 2/3, 1/4 then 1/2
then 1/2. As long as it sums to one, it's fine.

]

.one-third[
**Possible values**

- `.one-third`
- `.two-third`
- `.one-half`
- `.one-fourth`
- `.three-fourth`
- `.full-width`
]

---

# Nested Columns

.three-fourth[

This is a three-fourth column, and splitted in two.

.one-half[
~~~ R
for (i in c(1:10)) {
  print(i)
}
~~~
]
.one-half[
~~~ julia
for i in 1:10
  print(i)
end
~~~
]

Then the column resumes after the split.

]

.one-fourth[
**It works!**
]


---

# Image Captions

~~~ md
![D. Lafrenière et al., ApJ Letters](images/data-loss.jpg)
*D. Lafrenière et al., ApJ Letters*
~~~

![D. Lafrenière et al., ApJ Letters](images/data-loss.jpg)
*D. Lafrenière et al., ApJ Letters*

---
#About Statement (final slide)

Participate in our GitHub repo: [https://dataoneorg.github.io/dataone_lessons/](https://dataoneorg.github.io/dataone_lessons/)

**Suggested citation:**
DataONE Education Module: Data Management. DataONE. Retrieved November 12, 2016. From [https://dataoneorg.github.io/dataone_lessons/](https://dataoneorg.github.io/dataone_lessons/)

**Copyright license information:**
No rights reserved; you may enhance and reuse for your own purposes.  We do ask that you provide appropriate citation and attribution to DataONE.

![CCBY0](images/ccpd.png)