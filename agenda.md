---
layout: default
---
{% include event_list.html %}

{% for event in future_conferences %}
<div class="col-md-6">
{% include box.md date=event.date ref=event.country title=event.title   %}
</div>
{% endfor %}