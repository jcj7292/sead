---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# Contact

Our lab is located in the Blacksburg campus of  Virginia Tech.

<!-- 
Our full address is:

Skempton Building
Imperial College London
SW7 2BU, London
-->



{%
  include button.html
  type="email"
  text="jiechen@vt.edu"
  link="jiechen@vt.edu"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}
{% capture col1 %}

{%
  include figure.html
  image="images/contact/downtown-blacksburg.jpg"
  caption="Downtown Blacksburg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/vt-campus.jpg"
  caption="Virginia Tech Campus"
%}

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}


