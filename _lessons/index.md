---
title: DataONE lessons
layout: index
---

# DataONE Data Management Education Modules

{% for lesson in site.lessons %}
- [{{ lesson.title }}]({{ site.baseurl }}{{ lesson.url }})
{% endfor %}
