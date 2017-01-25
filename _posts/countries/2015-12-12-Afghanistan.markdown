---
layout: country
title:  "Afghanistan"
description: "AAEP II seeks to build the capacity of Afghanistan’s Ministry of Agriculture, Irrigation, and Livestock and selected Directorates to deliver effective extension services to rural clientele in targeted regions across Afghanistan."
date:   2015-12-01 16:25:17
category: "country"
contact: <a href="mailto:mhzhang@ucdavis.edu">Dr Minghua Zhang</a><br/><a href="mailto:jehill@ucdavis.edu">Jim Hill</a><br/><a href="mailto:mozbell@ucdavis.edu">Mark Bell</a>
permalink: /countries/afghanistan
image-banner: afghanistan_banner
---

Funded by the Walmart foundation, the project aims to provide credible relevant information for the safe and sustainable production of apples in China. The majority of apples in china are produced by small-scale farmers (many of whom are women) and they are struggling with rising costs and reduced returns.

<div class="relatedprojects">

<h3>Related Projects</h3>
	{% for post in site.tags.afghanistan limit:3 %}
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

<h3>Associated Training</h3>

AAEP II uses the same extension model employed by the first phase (AAEP I) which includes:

1. Training Workshops;

2. Thematic Workgroups;

3. Provincial Model Teaching Farms (PMTFs);

4. Farmer Field Schools (FFSs);

5. Farmer Field Demonstrations (FFDs); and

6. Mini-Fund Projects.
