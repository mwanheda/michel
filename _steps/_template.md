---
layout: default
time: ''
description: >
  Short description here
types: []
permalink:
---

Content here

{% for reference in page.references %}
[{{ forloop.index }}] {{ reference.author }}. {{ reference.title }}.
[{{ reference.url }}]({{ reference.url }})
{% endfor %}