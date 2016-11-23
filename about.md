---
layout: page
title: A propos
---
The game has changed. The word is out. And you are a killer. Apparently it s all over town. Somebody crossed you, you got angry, you crushed their skull with an ATM machine. Who cares! Just as long as it s our competitors who believe it and not the police.

<div>
{% for partners in site.data.partners %}
  <li>
    <a href="https://github.com/{{ partners.github }}">
      {{ partners.nom }}
    </a>
  </li>
{% endfor %}
</div>
