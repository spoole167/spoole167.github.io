---
layout: default
---

{% for slide in site.slides %}
  <h2>{{ slide.name }} - {{ slide.date }}</h2>
<a href="{{ slide.url }}">Details</a>
{% endfor %}
