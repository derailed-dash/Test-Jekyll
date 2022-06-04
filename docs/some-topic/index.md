---
layout: default
title: "Some Topic"
---
# {{ page.topic}}

Just experimenting...

## Links Index

<ol>
  {% assign top_level = site.data.navigation.pages | where: 'name', page.title %}
  {% for member in top_level[0].members %}
      <li><a href="{{ member.link | absolute_url }}">{{ member.name }}</a></li>
  {% endfor %}
</ol>