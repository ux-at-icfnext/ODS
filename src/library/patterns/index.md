---
layout: layouts/base
title: Patterns
---
<div class="grid-container">

# {{ title }}

_page still in progress_

<ul>
  {% for l in collections.patterns %}
    <li><a href="{{ l.url }}"
    {% if page.url == l.url %} class="text-fuchsia-500" {% endif %}>{{ l.data.title}}</a></li>
  {% endfor %}
</ul>

</div>