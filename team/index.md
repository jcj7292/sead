---
title: Team
nav:
  order: 4
  tooltip: About our team
---


<!-- <h1><a style="text-decoration: none; color: inherit;" href="/members/angeloudis-p.html">Director</a></h1> -->
# Principle Investigator
{% capture floatcontent %}

  <!-- Avatar -->
  {%
  include figure.html
  image="images/team/jie-chen.jpg"
  link="team"
  width="180px"
  class="portrait-image"
%}

 <!-- Name & Role -->
  <div class="text-center" style="margin-top:0px; font-weight: var(--bold); font-size: 1.1rem" > Jie Chen </div> 
  <div class="text-center" style="margin-top: -10px"> Assistant Professor  </div> <br>

{% endcapture %}

{% include float.html content=floatcontent %}


{% assign member = site.members | where: "slug", "angeloudis-p" | first %}

{% for affiliation in member.affiliations %}
<p style="margin: 0.1px; "> -  {{ affiliation }} </p>
{% endfor %}


<a style="text-decoration: none; color: inherit;" href="/members/angeloudis-p.html">
Dr. Jie Chen is an Assistant Professor in Mechanical Engineering at Virginia Tech. He was a Postdoctoral Fellow in Mechanical Engineering at Northwestern University (IDEAL Lab) after gaining PhD from Mechanical Engineering at Arizona State University (PARA Lab). His research focuses on physics-based uncertainty-aware data-driven analysis and design under uncertainty applied in advanced manufacturing, advanced materials systems, and fatigue & fracture. &nbsp;&nbsp;&nbsp;
 <a href="/members/angeloudis-p.html">(more)</a>









{% include section.html %}
# Principle Investigator

{% capture floatcontent %}


  <div class="portrait-wrapper">
    <a href="/sead/members/jie-chen.html" class="portrait" data-style="" aria-label="Jane Smith">
      <img src="/sead/images/team/jie-chen.jpg" class="portrait-image" alt="member portrait" loading="lazy" onerror="this.src = '/sead/images/fallback.svg'; this.onerror = null;">
  
      
        <span class="portrait-text">
          
            <span class="portrait-name">
              Jie Chen
            </span>
          
  
          
            <span class="portrait-role">
              
              <!-- <i class="icon fa-solid fa-microscope"></i> -->
              <span>Principal Investigator</span>
            </span>
          
        </span>
      
    </a>
  </div>

{% endcapture %}

{% include float.html content=floatcontent %}


{% assign member = site.members | where: "slug", "angeloudis-p" | first %}

{% for affiliation in member.affiliations %}
<p style="margin: 0.1px; "> -  {{ affiliation }} </p>
{% endfor %}


<a style="text-decoration: none; color: inherit;" href="/sead/members/jie-chen.html">
Dr. Jie Chen is an Assistant Professor in Mechanical Engineering at Virginia Tech. He was a Postdoctoral Fellow in Mechanical Engineering at Northwestern University (IDEAL Lab) after gaining PhD from Mechanical Engineering at Arizona State University (PARA Lab). His research focuses on physics-based uncertainty-aware data-driven analysis and design under uncertainty applied in advanced manufacturing, advanced materials systems, and fatigue & fracture. &nbsp;&nbsp;&nbsp;
 <a href="/sead/members/jie-chen.html">(more)</a>











 



{% include section.html %}
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
