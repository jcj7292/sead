---
title: Research
nav:
  order: 2
  tooltip: Research overview
---

# Research

Our research is two-fold: first, integrating engineering analysis and design knowledge into the development of stochastic machine learning (ML) algorithms (**Physics for ML**); and second, harnessing machine learning for the discovery of engineering analysis and design knowledge under uncertainty (**ML for Physics**). Our engineering applications focus on process-structure-property-performance relationships, both static and fatigue, including additive manufacturing, digital twins, and high-throughput materials characterization.

{% include button.html text="Physics for Machine Learning" link="research#physics-for-machine-learning" %}
{% include button.html text="Machine Learning for Physics" link="research#machine-learning-for-physics" %}


{% include section.html %}

## Physics for Machine Learning

### Physics-based Machine Learning
{% capture content %}
  {% 
    include figure.html
    image="images/research/physics-based-ml.svg"
    width="75%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

Neither a ML-only nor a physics-only approach can be considered sufficient for complex scientific and engineering problems. The motivation for physics-based ML is to combine physics-based and ML models to leverage their complementary strengths. In addition, given that artificial intelligence aims to replicate human intelligence, a compelling concept is to create ML algorithms that are informed by the operational principles of the human brain. Our research is incorporating physics knowledge/human intelligence into the ML architecture design. The developed methods have been applied in multiple engineering problems including fatigue life modeling of metal and composite materials, probabilistic fatigue properties of AM considering the effects of process parameters and missing data, and natural frequency prediction of bridges.

{% include float.html clear=true %}

### Multi-fidelity Machine Learning

{%
  include figure.html
  image="images/research/multi-fidelity.svg"
  width="62%"
%}

Multi-fidelity data exist in almost every engineering and science discipline, which can be from simulation, experiments, and a hybrid form. High fidelity data are usually associated with higher accuracy and expense (e.g., high resolution experimental testing or finer scale simulation), while low-fidelity data are on the opposite side in terms of accuracy and cost. We develop machine learning based multi-fidelity data aggregation methods to combine two or multiple sources of different fidelity data to alleviating the computational cost but still achieving high accuracy. The methods have been applied in finite element analysis with random microstructure, fatigue crack growth prognosis with monitoring, accelerating microstructure simulation and data collecting in Computed Tomography scanning.

### Uncertainty Quantification (UQ)
{% capture content %}
  {% 
    include figure.html
    image="images/research/uq.svg"
    width="82%"
  %}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

Uncertainty is ubiquitous in any physical system. Proper UQ is critical in decision-making, reliability, and resource allocation. The uncertainty includes aleatoric uncertainty due to intrinsic variability and epistemic uncertainty due to lack of knowledge/data. We employ Bayesian statistics for accounting for both types of uncertainties. We also develop UQ method in ML to combine the flexibility of ML with reliability of UQ. The developed methods have been applied in nondestructive testing, automated materials characterization, and catalyst discovery.

{% include float.html clear=true %}




{% include section.html %}

## Machine Learning for Physics

### Digital Twin for Monitoring and Control in Additive Manufacturing

{%
  include figure.html
  image="images/research/digital-twin.svg"
  width="62%"
%}

Additive Manufacturing (AM) is a disruptive Industry 4.0 technology that offers superior flexibility of manufacturing complex products and reduces energy and material waste. However, AM part quality is highly variable due to inadequate dimensional tolerances, surface roughness, and defects, thereby limiting its broad acceptance. To this end, we develop Digital twin (DT) technology for real-time monitoring and control. DT allows dynamically adjusting the AM process parameters based on the non-destructive testing signals (digital-to-physical). Meanwhile, both computational models are updated from the AM experimental data (physical-to-digital). Adaptive sampling approaches are used for both online and offline data collections. In addition, uncertainty will be quantified to develop statistical confidence in the ability to control and monitor the process.



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

Automated materials discovery brings energy efficiency and environmental conservation. Recent innovations in high-throughput materials synthesis and characterization have enabled data generation on material microstructure and properties in unprecedented quantity. However, the development of techniques analyzing big data is behind the experimental data acquisition, which hinders high-throughput materials discovery. Motivated by these challenges, we use advanced AI/ML approaches to extract actionable knowledge and information from large quantities of data generated by high-throughput synthesis, testing and characterization, leading to a dramatic acceleration of search for innovative materials.

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

Multiscale modeling is needed for discovery or design of materials. One major obstacle in successful utilization of multiscale methods across broad range of spatial and temporal scales is uncertainty quantification (UQ) of nonlinear behavior of microscale phases and uncertainty propagation (UP) to the macroscale quantities of interest. Our objective is to integrate UQ and UP methods into multiscale modeling. We model uncertainty from a number of sources in experiment and simulation including the incomplete knowledge (epistemic uncertainty) of the modelled physics and the inherent randomness (aleatoric uncertainty) in material parameters (e.g., microstructures). We develop data-driven methods to account for uncertainties across models and scales in a diverse range of systems. A particularly crucial application involves crack initiation and propagation under fatigue loadings, demanding the integration of temporal and spatial scales. Fatigue-related issues at the macroscale level exhibit substantial randomness, necessitating reliable UQ techniques to be applied at the microscale level.

{% include float.html clear=true %}
