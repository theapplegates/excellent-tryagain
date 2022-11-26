---
title: Search
seo:
  title: Search page
permalink: /search/index.html
description: Search Page
layout: page
---
<!DOCTYPE  html>
<html>
	<head>
  	...
  <!-- Before the closing </head> -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/docsearch.js@2/dist/cdn/docsearch.min.css"
    />

	</head>
	<body>
		...
    <!-- Before the closing </body> -->
    <script src="https://cdn.jsdelivr.net/npm/docsearch.js@2/dist/cdn/docsearch.min.js"></script>
    <script>
      docsearch({
        // Your Search API Key
        apiKey: '03d9a726aa662b449953113ca9f5ecaa',
        // The index populated by the DocSearch scraper
        indexName: 'index',
        // Your Algolia Application ID
        appId: 'HK1HO6U689',
        // Replace inputSelector with a CSS selector
        // matching your search input
        inputSelector: 'div#search',
        // Set debug to true to inspect the dropdown
        debug: false,
      });
    </script>

	</body>
</html>
  
<div id="search"></div>
