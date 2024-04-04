---
layout: layouts/base
---
TODO: ADD breadcrumb option

<div class="grid-row grid-gap">
  <div class="tablet:grid-col-3">{% include 'patterns/sidenav/sidenav.md' %}</div>
  <div class="tablet:grid-col-fill usa-prose">
    <h1> {{ title  | capitalize }}</h1>
    {{ content }}
  </div>
</div>