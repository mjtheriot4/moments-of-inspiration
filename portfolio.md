---
layout: portfolio
title: Micah Theriot Portfolio
---

<div id="portfolio" >
	<h1 class="pageTitle">Portfolio</h1>
	<div>
		<ul>
			{% for photos in site.data.filmPhotos %}
			<a href="{{photos.url | prepend: sitebaseurl}}" class="image-link">
				<li style="background-image: url('{{photos.url | prepend: sitebaseurl}}')">
				</li>
			</a>
			{% endfor %}
		</ul>
		<div class="clearfix"></div>
	</div>
