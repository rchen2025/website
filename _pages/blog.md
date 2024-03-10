---
title: "Blog"
layout: textlay
sitemap: false
permalink: /blog.html
---
## Blog Posts

<div class="jumbotron">
{% for post in site.data.blogs %}
<b>{{ post.title }}</b><br>
<b>{{ post.date }}</b>

{{ post.preview }}
{{ post.content }}
{% endfor %}
</div>
