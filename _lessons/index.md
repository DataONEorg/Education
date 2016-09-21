---
title: DataONE lessons
layout: index
---

# List of lessons

<ul>
{% for lesson in site.lessons %}
  <li>
    <a
      href = "{{ site.baseurl }}/{{ lesson.url }}"
      title = "{{ lesson.title }}"
      target = "_blank"
      >
        {{ lesson.title }}
      </a>
  </li>
{% endfor %}
</ul>
