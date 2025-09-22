---
layout: home
title: Projects
---


<div class="project-list">
  {% for project in site.data.projects %}
  <div class="project-item">
    <img align='left' src="/assets/images/{{ project.icon }}" width="150px" alt="{{ project.name }} Icon" class="project-icon" style="margin-right: 20px; margin-bottom: 10px; border-radius: 1%">
    <div class="project-content">
      <h3><a href="{{ project.link }}">{{ project.name }}</a></h3> <p style="color: gray">{{ project.description }}</p>
    </div>
  </div>
  {% endfor %}
</div>