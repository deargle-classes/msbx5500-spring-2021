---
title: Class Log
---

# Class Log

<ul>
{% assign logs = site.logs | sort: title | reverse %}
{% for log in logs %}
<li><a href='#{{log.title}}'>{{log.title}}</a></li>
{% endfor %}
</ul>

{% for log in logs %}
<h1 id="{{log.title}}">{{ log.title }}</h1>

{% if log.whiteboard_img %}
  {% assign whiteboard_url = '/assets/images/' | append: log.whiteboard_img %}
  <a href='{{ whiteboard_url | relative_url }}'>Whiteboard</a>
{% endif %}

{{ log.content | markdownify }}
{% endfor %}
