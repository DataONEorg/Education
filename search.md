---
title: Search page for Data Management education materials
layout: layout
---


# Search the Data Management Skill Building Hub

Results are listed in order of find, not by best match to search word, and will be alphabetically ordered by result type.




<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="search...">
<ul id="results-container"></ul>
</div>


<!-- Script pointing to search-script.js -->
<script src="{{ site.baseurl }}/js/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
window.simpleJekyllSearch = new SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '{{ site.baseurl }}/search.json',
  searchResultTemplate: '<p><strong><span>{categories}: </span><a href="{url}" title="{desc}">{title}</a></strong><br><span> Life Cycle Step(s): {step}</span><br><span> Authoring Organization: {organization}</span></p>',
  noResultsText: 'No results found',
  fuzzy: true,
  limit: 100,
})
</script>
