---
title: Team
nav:
  order: 4
  tooltip: About our team
---


<!-- <h1><a style="text-decoration: none; color: inherit;" href="/members/angeloudis-p.html">Director</a></h1> -->
# Principle Investigator


 
# Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}


















{% include section.html %}

# Research Team


{% include list.html data="members" component="portrait" filters="role: senior" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|senior$|alumni$)" %}

{% include section.html %}

# Alumni

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html %}

# Visiting Researchers

- **Luciano Greco**,  University of Padova
- **Kenta Matsui**, Komatsu Corporation
- **Anna Konovalenko**, Molde University College
- **Dirk Briskorn**, University of Wuppertal
- **Ryusuke Fujita**, Tokyo Tech

 

{% include section.html background="images/background.jpg" dark=true %}

 We are always looking for new members to our team. We will advertise any funded opportunities that specific to our group on LinkedIn, as well as in the UTSG and robotics-worldwide mailing lists, while several scholarship schemes and fellowships are offered by Imperial College London. 
 
 For more information on how to join us, you can review our [recruitment](/apply/) page. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photos/itsc.jpg" %}
{% include figure.html image="images/photos/dinner.jpg" %}
{% include figure.html image="images/photos/trb.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
