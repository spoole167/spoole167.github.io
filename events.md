---
layout: default
---

{% for event in site.events %}

  {% include box.md date=event.date ref=event.name title=event.name text=event.content %}

{% endfor %}
