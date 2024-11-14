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
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}


{% include section.html %}

## Bachelor/Master students
{% include list.html data="members" component="portrait" filters="role: master, group: master" style="small" %}
{% include list.html data="members" component="portrait" filters="role: bachelor, group: bachelor" style="small" %}

{% include section.html %}



{% endcapture %}

{% include grid.html style="square" content=content %}
