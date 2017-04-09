---
layout: portfolio
title: My Portfolio
---

<div id="portfolio" >
	<h1 class="pageTitle">Portfolio</h1>
	<div>
		<ul>
			{% for photos in site.data.filmPhotos %}
			<li style="background-image: url('{{photos.url}}')"></li>
			{% endfor %}
		</ul>
		<div class="clearfix"></div>
	</div>
