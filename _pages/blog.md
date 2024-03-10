---
title: "Blog"
layout: textlay
sitemap: false
permalink: /blog.html
---
## Blog Posts

<div class="jumbotron">
{% for post in site.data.blogs %}

<li><a href="../_pages/_blogposts/blog1.html"><b>{{ post.title }}</b><br></a></li>

<b>{{ post.date }}</b>

{{ post.preview }}
{% endfor %}
</div>
