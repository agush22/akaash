---
layout: projects
title: Design
---
{% for project in site.design_projects %}
  <div class="project">
    <img src="{{ project.thumbnail }}"/>
    <a class="overlay" href="{{ project.url }}">
      <div class="text"> {{ project.title }} </div>
    </a>
  </div>
{% endfor %}
