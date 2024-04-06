---
layout: default
---

<div>
    <select id="domain-filter">
      <option value="">All Domains</option>
      {% assign domains = "" | split: "," %}
      {% for project in site.data.projects %}
        {% unless domains contains project.domain %}
          {% assign domains = domains | push: project.domain %}
          <option value="{{ project.domain }}">{{ project.domain }}</option>
        {% endunless %}
      {% endfor %}
    </select>
</div>

# Selected Materials

<div id="cards-container">
    {% for project in site.data.projects %}
    <div class="card" data-domain="{{ project.domain }}">
        <a href="{{ project.url }}" target="_blank" style="text-decoration: none; color: inherit;">
            <h2>{{ project.title }}</h2>
            <h3>({{ project.domain }})</h3>
            <img src="{{ project.image }}" alt="{{ project.title }}">
            <p>{{ project.description }}</p>
        </a>
    </div>
    {% endfor %}
</div>
