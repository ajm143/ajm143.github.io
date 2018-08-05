---
layout: default
title: Publications
category: publications
---
{% assign counter=site.posts.length %}

{% for post in site.posts %}
  {% if post.categories contains 'publications' %}
    {% assign counter=counter | minus:1 %} 

{{ counter }}. {% if post.oa %} <a href="{{ post.oa }}">![OA]({{ site.url }}/images/OA.png){:style="height : 20px"}</a> {% endif %} {% if post.arx %} <a href="{{ post.arx }}">![ARX]({{ site.url }}/images/arx.png){:style="height : 20px"}</a> {% endif %} "{{ post.title }}", *{{ post.authors }}*,  *{{ post.journal }}*, **{{ post.volume}}**, *{{ post.pages }}* _({{ post.year }})_ [DOI: {{ post.doi }}](http://doi.org/{{ post.doi }})  {{ post.content | remove: '<p>' | remove: '</p>' }}

  {% endif %}
{% endfor %}
