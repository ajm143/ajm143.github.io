---
layout: default
title: Publications
category: publications
---
{% assign counter=0 %}

{% for post in site.posts %}
  {% if post.categories contains 'publications' %}
    {% assign counter=counter | plus:1 %} 

{{ counter }}.  *"{{ post.title }}"*, *{{ post.authors }}*,  *{{ post.journal }}*, **{{ post.volume}}**, *{{ post.pages }}* _({{ post.year }})_ [DOI: {{ post.doi }}](http://doi.org/{{ post.doi }})  {{ post.content | remove: '<p>' | remove: '</p>' }}

  {% endif %}
{% endfor %}
