---
layout: default
---
{% assign sorted = site.events | sort: 'date'   %}
{% for event in sorted limit: 20 %}
<div class="col-md-6">
{% include box.md date=event.date ref=event.country title=event.title   %}
</div>
{% endfor %}