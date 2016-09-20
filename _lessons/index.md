---
title: Moving the lessons to github
update: Sept. 20, 2016
layout: slides
---

# It's working!

- Each lesson is its own `lesson_name.md` file in the github repository
- The maintainer ensures that the github pages are built from the `master` branch
- That's it

---

# General infos

Lesson title and metadata go in the `yaml` header:

~~~ yaml
---
title: Lesson title
update: Sept. 20, 2016
layout: slides
---
~~~

Everything *below* that is markdown.

---

# Markdown ?

- `*italics*` is *italics*
- `**bold**` is **bold**

Lists:

~~~
- List item 1
- List item 2
  - Nested list item

1. Enumerated list
2. Second item
  - We can mix both
~~~

---

# Quotes

~~~
> Text goes here
~~~

> Text goes here

---

# Syntax highlighting

```
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

---

# Tables

This bit of code...

~~~ md
|   Animal | Diet      | Fuzzy? |
|---------:|:----------|:------:|
| Hedgehog | rings     |   no   |
|   Racoon | garbage   |  meh   |
|      Cat | hairballs |  yup   |
~~~

becomes

|   Animal | Diet      | Fuzzy? |
|---------:|:----------|:------:|
| Hedgehog | rings     |   no   |
|   Racoon | garbage   |  meh   |
|      Cat | hairballs |  yup   |

---

# Notes

Notes are everything that comes below `???`. Press **P** to toggle presenter
mode.

???

These are the notes, and *they can* be in markdown too.

---

# Columns

.two-third[
~~~
.one-third[
  content
]
~~~
]

.one-third[
**Possible values**

- `.one-third`
- `.two-third`
- `.one-half`
- `.one-fourth`
- `.three-fourth`
]
