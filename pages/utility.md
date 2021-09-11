---
layout: page-fullwidth
title: "Simple Utilities"
subheadline: "Solve your day-to-day and sometimes peculiar problem with them"
teaser: "The building this world easy to live in is always a work in progress..."
breadcrumb: true
permalink: "/utility/"
header:
   image_fullwidth: "header_roadmap_2.jpg"
---

<ul>
    {% for post in site.categories.utility %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    <p> {{post.teaser}}</p>
    {% endfor %}
</ul>
