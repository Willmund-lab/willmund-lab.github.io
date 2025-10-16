---
title: Team
nav:
  order: 4
  tooltip: Meet the team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'scientific staff'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'secretary'" %}
{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html %}

## Students
{% include list.html data="members" component="portrait" filter="role == 'master'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'bachelor'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'hiwi'" style="small" %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumn'" style="small" %}



{% include section.html %}
