---
layout: page
title: Cours
---
<div>
{% for cours in site.cours %}
	<div class="cours">
		<h2><a href="{{ cours.url }}">{{ cours.title }}</a></h2>
	</div>
{% endfor %}
</div>
