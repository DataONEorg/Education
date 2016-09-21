---
title: DataONE lessons
---

# List of lessons

<ul>
{% for lesson in site.lessons %}
  <li>
    <a
      href="{{ lesson.url }}"
      title = "{{ lesson.title }}">
        {{ lesson.title }}
      </a>
  </li>
{% endfor %}
</ul>
