---
title: People
nav:
  order: 3
---

# People

{% include section.html %}

## Professors

<div style="display: flex; flex-wrap: wrap;">
{% include list.html data="members" component="portrait" filters="role:prof" %}
</div>

## Graduate Students

<div style="display: flex; flex-wrap: wrap;">
  {% include list.html data="members" component="portrait" filters="role:m" %}
</div>

## Undergraduate Students

<div style="display: flex; flex-wrap: wrap;">
{% include list.html data="members" component="portrait" filters="role:u" %}
</div>
