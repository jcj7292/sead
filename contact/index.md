---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# Contact

Our lab is located in the Blacksburg campus of  Virginia Tech.

Our full address is:

307 Durham Hall

1145 Perry Street

Blacksburg, VA 24061




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
    link="https://www.google.com/maps/place/Durham+Hall,+Blacksburg,+VA+24061/@37.2316582,-80.4261852,693m/data=!3m2!1e3!4b1!4m6!3m5!1s0x884d956d06750d91:0xdba267f758757581!8m2!3d37.2316582!4d-80.4236103!16s%2Fg%2F1v29cqlf?entry=ttu"
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


