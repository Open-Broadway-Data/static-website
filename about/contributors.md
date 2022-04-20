---
title: "Contributors"
layout: page
permalink: /about/contributors.html
menus:
  about:
    identifier: contributors
    is_child: True
    weight: 3
---
# Our Contributors

<div class="name-list">
<ul>
  {%- for item in site.data.contributors -%}
    <li> {{ item.name }} <small>({{ item.role }})</small>
    </li>
  {% endfor %}
</ul>
</div>

<hr>

<div class="myGallery">

  {%- for item in site.data.contributors -%}
    <div class="item">
      <img
        src="/images/headshots/{{ item.name | downcase | replace: " ", "-"}}.jpeg"
        alt="{{ item.name }} headshot"
      />
      <span class="caption">
      {{ item.name }} ({{ item.role }})
      </span>
    </div>
  {% endfor %}
</div>
