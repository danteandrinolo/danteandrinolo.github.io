---
layout: page
permalink: /courses/
title: courses
description: Graduate and advanced courses I have taken.
nav: true
nav_order: 7
---

<div class="courses">
{% for school in site.data.courses %}
  <h2 class="year">{{ school.institution }}</h2>
  <div class="course-list">
  {% for course in school.courses %}
    <div class="course-item">
      <h3 class="course-title">{% if course.code %}{{ course.code }} {% endif %}{{ course.name }}</h3>
      {% if course.term or course.grade %}
      <div class="course-meta">
        {% if course.term %}<span class="course-term">{{ course.term }}</span>{% endif %}
        {% if course.grade %}<span class="course-instructor">Grade: {{ course.grade }}</span>{% endif %}
      </div>
      {% endif %}
      {% if course.description %}
      <div class="course-description">{{ course.description | markdownify }}</div>
      {% endif %}
      {% if course.notes %}
      <div class="course-description"><strong>My notes:</strong> {{ course.notes | markdownify | remove: '<p>' | remove: '</p>' }}</div>
      {% endif %}
      {% if course.notes_url %}
      <a class="btn btn-sm z-depth-0" role="button" href="{{ course.notes_url | relative_url }}" target="_blank" rel="noopener noreferrer">Notes (PDF)</a>
      {% endif %}
    </div>
  {% endfor %}
  </div>
{% endfor %}
</div>
