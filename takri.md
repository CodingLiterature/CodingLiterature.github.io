---
layout: page
title: Takri
---

```This page is authored by Pankaj Khajuria.```

<div class="tposts">
{% for post in site.posts %}
    {% if post.categories contains 'takri' %}
    <div class="tpost">
        <h1 class="tpost-title">
            <a href="{{post.url}}"> {{post.title}} </a>
        </h1>
        
        <!--
        <span class="post-date">{{ post.date | date_to_string }}</span>
        -->
        {{ post.excerpt | replace: '<p>' | replace: '</p>' }} <br>
            <a href="{{ post.url }}"> more...</a><br>
    </div>
 
    {% endif %}
{% endfor %}
</div>

```This page is authored by Pankaj Khajuria.```
