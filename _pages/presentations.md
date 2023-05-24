---
layout: default
permalink: /presentations/
title: Presentations
---


# Short Presentations

TBD

<!-- <ul>
{% for item in site.data.presentations  %}
{% if item.type == "short" %}
  <li><strong>{{ item.title }}</strong><br/>
  <small><i>{{ item.authors }}</i></small></li>
  <small><i>{{ item.abstract }}</i></small>
{% endif %}
{% endfor %}
</ul> -->

# Long Presentations

<ul>
{% for item in site.data.presentations  %}
{% if item.type == "long" %}
  <li><strong>{{ item.title }}</strong><br/>
  <small><i>{{ item.authors }}</i></small></li>
  <small><i>{{ item.abstract }}</i></small>
{% endif %}
{% endfor %}
</ul>