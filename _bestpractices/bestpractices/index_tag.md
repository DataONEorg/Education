---
title: Best Practices Tag Archive
layout: bestpracitice_tag
depth: 1
entries_layout: list
show_excerpts: true
permalink: /bptags/
---

<!-- the content/layout call for the list of tags  -->

  <h1>Tags for {{the_collection}} collection</h1>

    <h2>Best Practice by Tag</h2>
      {% for tag in tags %}
      <h3>{{ tag }}</h3>
        <ul>
        {%- assign items = site[ the_collection ] | where: "tags", tag -%}
        {%- for item in items %}
          <li><a href="{{ site.baseurl }}/{{ item.url }}">{{ item.title }}</a></li>{% endfor %}
        </ul>
      {% endfor %}

<div id="archives">
{% for tag in site.tags %}
  <div class="archive-group">
    {% capture tag_name %}{{ tag | first }}{% endcapture %}
    <div id="#{{ tag_name | slugize }}"></div>
    <p></p>

    <h3 class="tag-head">{{ tag_name }}</h3>
    <a name="{{ tag_name | slugize }}"></a>
    {%- assign items = site[ the_collection ] | where: "tags", tag -%}
    {% for item in items[tag_name] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ item.url }}">{{item.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
{% endfor %}
</div>
