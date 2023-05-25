---
layout: default
permalink: /presentations/
title: Presentations
---


# Short Presentations

TBD

<ul>
{% for item in site.data.presentations  %}
{% if item.type == "short" %}
  <li><strong>{{ item.title }}</strong><br/>
  <i>{{ item.authors }}</i></li>
  <small>{{ item.abstract }}</small>  <br/>

{% endif %}
{% endfor %}
</ul>

# Long Presentations

<ul>
{% for item in site.data.presentations  %}
{% if item.type == "long" %}
  <li><strong>{{ item.title }}</strong><br/>
  <i>{{ item.authors }}</i></li>
  <small>{{ item.abstract }}</small>  <br/>

{% endif %}
{% endfor %}
</ul>