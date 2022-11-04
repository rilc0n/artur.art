---
layout: page
title:
permalink: /search/
---

<!-- Html Elements for Search -->
<div id="search-container" style="text-align: center">
<input type="text" id="search-input" placeholder="search..." autofocus onfocus="this.select()" size=50>
<ul id="results-container"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="/js/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json'
})
</script>
