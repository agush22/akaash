---
layout: page
title: Photography
---
{% for project in site.photo_projects %}
  <div class="project">
    <a href="{{ project.url }}"><img src="{{ project.thumbnail }}"/></a>
    <div class="overlay">
    <div class="text"> {{ project.title }} </div>
    </div>
  </div>
{% endfor %}
