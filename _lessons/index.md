---
title: DataONE lessons
layout: index
---

# DataONE Data Management Education Modules

{% assign idx = 0 %}
{% for lesson in site.lessons %}
- {% increment idx %} - [{{ lesson.title }}]({{ site.baseurl }}{{ lesson.url }})
{% endfor %}
