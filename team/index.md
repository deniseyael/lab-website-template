---
title: People
nav:
  order: 3
---

# Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

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
