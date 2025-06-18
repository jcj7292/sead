---
---

## Where Machine Learning Meets Engineering Analysis & Design under Uncertainty
The Stochastic Engineering Analysis & Design (SEAD) Lab focuses on 

1. **Physics for Machine Learning**: Integrate engineering analysis & design knowledge into stochastic machine learning algorithm development.

2. **Machine Learning for Physics**: Harness machine learning for engineering analysis & design knowledge discovery under uncertainty.

{% include section.html %}

<!-- ## Highlights -->

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{% include list.html data="posts" component="post-excerpt" %}

{%
  include button.html
  link="news"
  text="Browse our news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/home/home-news.svg"
  link="news"
  title="Our News"
  text=text
%}

{% capture text %}

Our research integrates machine learning algorithms into engineering analysis and design under uncertainty, focusing on process-structure-property-performance relationships.

{%
  include button.html
  link="research"
  text="See our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/home/home-research.svg"
  link="research"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="join"
  text="Join us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/home/home-team.svg"
  link="team"
  title="Our Team"
  text=text
%}
