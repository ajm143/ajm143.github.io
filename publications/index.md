---
layout: default
title: Publications
category: publications
---
{% for post in site.posts %}
{% if post.categories contains 'publications' %}
<div class="entry">
{{ post.content | strip_html | truncatewords: 100 }}
</div>
{% endif %}
{% endfor %}
