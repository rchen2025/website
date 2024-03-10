---
title: "Blog"
layout: textlay
sitemap: false
permalink: /blog.html
---
## Blog Posts

<div class="jumbotron">
{% for post in site.data.blogs %}
<b><a href="{{ site.url }}{{ site.baseurl }}{{ post.permalink }}"> {{ post.title }}</a></b><br>
<b>{{ post.date }}</b>

{{ post.preview }}
{% endfor %}
</div>
