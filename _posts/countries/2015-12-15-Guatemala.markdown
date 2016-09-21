---
layout: country
title:  "Guatemala"
description: ""
date:   2015-12-15 16:25:17
category: "country"
contact: <a href="mailto:mhzhang@ucdavis.edu">Dr Minghua Zhang</a>, <a href="mailto:jehill@ucdavis.edu">Jim Hill</a> and <a href="mailto:mozbell@ucdavis.edu">Mark Bell</a>
permalink: /countries/guatemala
image-banner: guatemala_banner
---


<div class="relatedprojects">
<h3>Related Projects</h3>
	{% for post in site.tags.Guatemala limit:3 %}
	<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
	    <div class="relatedprojects__card">
	        <h4>
	              {{ post.title }}
	            </h4>
	        <p class="feed-description">{{ post.description }}</p>
	        <p class="primary-color">Learn More</p>
	    </div>
    </a>
    {% endfor %}
</div>
