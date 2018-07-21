---
layout: page
title: Archives
---

{% for post in site.posts %}
{% unless post.categories contains 'takri' %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endunless %}
{% endfor %}
