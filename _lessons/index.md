---
title: DataONE lessons
layout: index
---

# DataONE Data Management Education Modules

{% comment %}
The following part extracts all the tags from the lessons
{% endcomment %}
{% assign rawtags = "" %}
{% assign rawcats = "" %}
{% for lesson in site.lessons %}
	{% assign ttags = lesson.tags | join:'|' | append:'|' %}
	{% assign rawtags = rawtags | append:ttags %}
	{% assign ccats = lesson.categories | join:'|' | append:'|' %}
	{% assign rawcats = rawcats | append:ccats %}
{% endfor %}
{% assign rawtags = rawtags | split:'|' | sort %}
{% assign rawcats = rawcats | split:'|' | sort %}

{% comment %}
Removes duplicated tags
{% endcomment %}
{% assign tags = "" %}
{% for tag in rawtags %}
	{% if tag != "" %}
		{% if tags == "" %}
			{% assign tags = tag | split:'|' %}
		{% endif %}
		{% unless tags contains tag %}
			{% assign tags = tags | join:'|' | append:'|' | append:tag | split:'|' %}
		{% endunless %}
	{% endif %}
{% endfor %}
{% assign cats = "" %}
{% for cat in rawcats %}
	{% if cat != "" %}
		{% if cats == "" %}
			{% assign cats = cat | split:'|' %}
		{% endif %}
		{% unless cats contains cat %}
			{% assign cats = cats | join:'|' | append:'|' | append:cat | split:'|' %}
		{% endunless %}
	{% endif %}
{% endfor %}

{% comment %}
Show the tags 
{% endcomment %}

## Tags
{% for tag in tags %}
* [{{ tag }}](#{{ tag | slugify }})
{% endfor %}

## Categories
{% for cat in cats %}
* [{{ cat }}](#{{ cat | slugify }})
{% endfor %}

## Lessons
{% assign idx = 0 %}
{% for lesson in site.lessons %}
- [![{{ lesson.title }}]({{ site.baseurl }}/lessons/{{ lesson.deck }}/{{ lesson.deck }}.png)]({{ site.baseurl }}{{ lesson.url }}) [PDF]({{ site.baseurl }}/lessons/{{ lesson.deck }}/{{ lesson.deck }}.pdf)
{% endfor %}
