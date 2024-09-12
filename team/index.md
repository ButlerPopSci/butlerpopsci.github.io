---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$), alumni: false" %}
{% include section.html %}

# Alumni
{% include section.html %}
{% include list.html data="members" component="portrait" filters="alumni: true" %}
{% include section.html %}