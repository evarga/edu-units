---
layout: default
---

# Available Learning Materials
{% for project in site.data.projects %}
<div class="card">
    <a href="{{ project.url }}" target="_blank" style="text-decoration: none; color: inherit;">
        <h2>{{ project.title }}</h2>
        <h3>({{ project.domain }})</h3>
        <img src="{{ project.image }}" alt="{{ project.title }}">
        <p>{{ project.description }}</p>
    </a>
</div>
{% endfor %}