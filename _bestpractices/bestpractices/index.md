---
title: Best Practices Index
layout: collection_index
depth: 1
---

{% for page in site.pages %}
  {% if page.layout == 'bestpractice' %}
  <div class="bestPractice">
  <h1 class="title">{{ page.title }}</h1>
  <br />
  {% for tag in page.tags %}<span class="tag">{{ tag }}</span>{% endfor %}
  </div>
  {% endif %}
{% endfor %}
