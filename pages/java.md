---
layout              : page
format				: blog-index
show_meta           : false
title               : "Java & Springboot"
subheadline         : "Guide to java and Springboot tricks and tips"
teaser              : "Utility codes, tricks and tips for picky java and Springboot problems."
breadcrumb: true
header:
   image_fullwidth  : "manu-schwendener-DSwBHyWKiVw-unsplash.jpg"
permalink           : "/java/"
---

<ul>
    {% for post in site.categories.java %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    <p> {{post.teaser}}</p>
    {% endfor %}
</ul>
{% include _pagination.html %}