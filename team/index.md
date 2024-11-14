---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}


{% include section.html %}

## Students
{% include list.html data="members" component="portrait" filter="role == 'master'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'bachelor'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'hiwi'" style="small" %}




{% include section.html %}
