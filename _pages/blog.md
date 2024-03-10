---
title: "Blog"
layout: post
sitemap: false
permalink: /blog.html
---

## Blog Posts

<div class="jumbotron">
{% for post in site.data.blogs %}
<b>{{ post.date }}</b>
<b>{{ post.title }}</b>

{{ post.content }}
{% endfor %}
</div>
