---
layout: default
---


<div class="row g-5 mb-5">
  <div>
    <h3 class="fw-bold border-bottom pb-3 mb-5">Index</h3>
    {% for lecture in site.data.courses.os %}
      <p><a href="{{ site.github.url }}/courses/os/{{ lecture.url}}">{{ lecture.name }}</a></p>
    {% endfor %}
  </div>
</div>
