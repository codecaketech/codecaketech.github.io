---
layout: page
show_meta: false
title: "Machine Learning"
subheadline: "Fussy and Not-so-fussy discussion on random ML topics"
teaser : "Machine learning is fascinating. You must be agreeing, no?"
breadcrumb: true
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/machine_learning/"
---
<div class="row">
	<div class="medium-8 columns t30">
		{% include _pagination.html %}
	</div><!-- /.medium-7.columns -->


</div>
<ul>
    {% for post in site.categories.machine_learning %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
