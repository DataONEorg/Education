---
title: Search page for Data Management education materials
layout: layout
---


# Search the Data Management Skill Building Hub


## At this time search only scans through Best Practices


<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="search...">
<ul id="results-container"></ul>
</div>

<p> Top ten search results </p>
<!-- Script pointing to search-script.js -->
<script src="{{ site.baseurl }}/js/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
window.simpleJekyllSearch = new SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '{{ site.baseurl }}/search.json',
  searchResultTemplate: '<p><a href="{url}" title="{desc}">{title}</a><br><span> Type: {categories}</span><span> Step: {step}</span></p>',
  noResultsText: 'No results found',
  limit: 10,
  fuzzy: false,
})
</script>
