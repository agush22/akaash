---
layout: projects
title: Photography
---
{% for project in site.photo_projects %}
  <div class="project">
    <img src="{{ project.thumbnail }}"/>
    <a class="overlay" href="{{ project.url }}">
      <div class="text"> {{ project.title }} </div>
    </a>
  </div>
{% endfor %}
