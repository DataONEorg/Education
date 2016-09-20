---
title: Lesson title
update: Sept. 20, 2016
layout: slides
---

# It's working!

- The lesson goes in `docs/lesson_name.md`
- That's it.

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
