---
layout: page
title: Služby
description: Daniela Mlchová
background: '/img/bg-sluzby.jpg'
---

<ul class="list-group list-group-flush">
{% for sluzba in site.sluzby %}
  <li class="list-group-item"><a href="{{ sluzba.url }}">{{ sluzba.title }}</a></li>
{% endfor %}
</ul>