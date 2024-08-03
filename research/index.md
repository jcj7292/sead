---
title: Research
nav:
  order: 2
  tooltip: Research overview
---

# Research

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

{% include button.html text="Physics for ML" link="research#physics-for-ml" %}
{% include button.html text="ML for Physics" link="research#ml-for-physics" %}


{% include section.html %}

## Physics for ML

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.


{% include section.html %}

## ML for Physics

### Digital Twin for Monitoring and Control in Additive Manufacturing

{%
  include figure.html
  image="images/research/digital-twin.svg"
  width="62%"
%}

Additive Manufacturing (AM) is a disruptive Industry 4.0 technology that offers superior flexibility of manufacturing complex products and reduces energy and material waste. However, AM part quality is highly variable due to inadequate dimensional tolerances, surface roughness, and defects, thereby limiting its broad acceptance. To this end, we develop Digital twin (DT) technology for real-time monitoring and control. This framework dynamically adjusts the AM process parameters based on the non-destructive testing signals (digital-to-physical). Physics-based computational models such as the finite element method and computational fluid dynamics have been widely applied to predict thermal behavior in AM processes. However, they suffer from intensive computational costs, thus are not suitable for applications in online control and iterative design. To enable real-time control in AM, we develop advanced machine learning methods. High-fidelity simulation is used for offline training. Multi-fidelity models are used for online prediction. Meanwhile, both high and low-fidelity models will be updated from the AM experimental data (physical-to-digital). Adaptive sampling approaches are used for both online and offline data collections. In addition, uncertainty will be quantified to develop statistical confidence in the ability to control and monitor the process.



### High-throughput Data Analysis for Automated Materials Discovery
{% capture content %}
  {% 
    include figure.html
    image="images/research/materials-discovery.svg"
    width="80%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

Automated materials discovery brings energy efficiency and environmental conservation. Recent innovations in high-throughput materials synthesis and characterization have enabled data generation on material microstructure and properties in unprecedented quantity. However, the development of techniques analyzing big data is behind the experimental data acquisition, which hinders high-throughput materials discovery. Motivated by these challenges, we use advanced AI/ML approaches to extract actionable knowledge and information from large quantities of data generated by high-throughput synthesis, testing and characterization, leading to a dramatic acceleration of search for innovative materials. We utilize ML approaches to enable these goals including dimensionality reduction, linking high-dimensional microstructure representations to key macro-scale material properties, and deep learning models to map images to both low- and high-dimensional outputs.

{% include float.html clear=true %}

### Uncertainty Quantification and Propagation in Multiscale Materials Modeling
{% capture content %}
  {% 
    include figure.html
    image="images/research/multiscale-uq-up.svg"
    width="82%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

Multiscale modeling is needed for discovery or design of materials. One major obstacle in successful utilization of multiscale methods across broad range of spatial and temporal scales is uncertainty quantification (UQ) of nonlinear behavior of microscale phases and uncertainty propagation (UP) to the macroscale quantities of interest. Our objective is to integrate UQ and UP methods into multiscale modeling. The methods entail quantification of uncertainty from a number of sources in experiment and simulation including the incomplete knowledge (epistemic uncertainty) of the modelled physics and the inherent randomness (aleatoric uncertainty) in material parameters (e.g., microstructures). We develop data-driven methods to account for uncertainties across models and scales in a diverse range of systems. A particularly crucial application involves crack initiation and propagation under fatigue loadings, demanding the integration of temporal and spatial scales. Fatigue-related issues at the macroscale level exhibit substantial randomness, necessitating reliable UQ techniques to be applied at the microscale level.

{% include float.html clear=true %}
