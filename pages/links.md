---
layout: page
title: 友情鏈結 Friendship Link
description: 友情鏈結
keywords: 
comments: true
menu: 友情鏈結 Friendship Link
permalink: /links/
---

> God made relatives. Thank God we can choose our friends.

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 友情链接

<ul>
{% for link in site.data.links %}
  {% if link.src == 'www' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
