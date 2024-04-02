<div class="resume-wrap ftco-animate">
    <span class="date">{{ include.date | date: "%-d %B %Y" }}</span>
{% if include.title %}
    <h2>{{ include.title }}</h2>
{% endif %}
{% if include.ref %}
    <span class="position">{{ include.ref }}</span>
{% endif %}
{% if include.text %}
    <p class="mt-4">{{ include.text }}</p>
{% endif %}
</div>
