---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact


{%
  include button.html
  type="email"
  text="willmund@staff.uni-marburg.de"
  link="willmund@staff.uni-marburg.de"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Zentrum+f%C3%BCr+Synthetische+Mikrobiologie/@50.807702,8.8107576,17.71z/data=!4m6!3m5!1s0x47bc884bbd5d0ed9:0xfb37bcffe9f2b6c0!8m2!3d50.8077126!4d8.8106635!16s%2Fg%2F11c3v6zp5r?entry=ttu&g_ep=EgoyMDI0MTExMi4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Synmikro_outside.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Synmikro_foyer.jpg"
%}

{% capture col3 %}

{%
  include figure.html
  image="images/Synmikro_atrium.jpg"
%}

{% endcapture %}



{% include cols.html col1=col1 col2=col2 col3=col3 %}
