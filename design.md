---
layout: page
title: Design
---
{% for project in site.design_projects %}
  <div class="project">
    <a href="{{ project.url }}"><img src={{ project.title }}/></a>
  </div>
{% endfor %}
