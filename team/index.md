---
title: Team
nav:
  order: 4
  tooltip: About our team
---
# Team


{% include section.html %}
## Principle Investigator

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
              <span>Assistant Professor</span>
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
## Research Team
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: master, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html background="images/background.jpg" dark=true %}

We are always looking for new members to our team. For more information on how to join us, you can review Join Us page.
{% include button.html icon="fa-solid fa-handshake-angle" text="Join Us" link="join" style="button" %}

{% include section.html %}
## Alumni
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alumni" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alumni" style="small" %}
{% include list.html data="members" component="portrait" filters="role: master, group: alumni" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alumni" style="small" %}



{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

