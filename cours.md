---
layout: page
title: Cours
---
<div>
{% for cours in site.cours %}
  <div class="cours">
    {{ cours.content }}
  </div>
{% endfor %}
</div>
