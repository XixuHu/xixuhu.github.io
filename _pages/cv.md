---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can access the PDF version [here](/files/CV.pdf). (Last update: 2023.2)

Education
======
* B.S. in Statistics, University of Science and Technology of China, 2016.9-2020.6
* Ph.D in Data Science, City University of Hong Kong, 2020.9-2024.6 (expected)

Research experience
======
* Fall 2018: Research Assistant
  * Department of Statistics & Finance, University of Science and Technology of China
  * A Bayesian Method for Systemic Risk Assessment in Financial Networks: 
    - Collected data from different banks’ yearbooks to build a complete Chinese banks liability database.  
    - Applied a Bayesian methodology and constructed a Gibbs sampler to generate samples for individual liabilities in Chinese interbank networks.
    - Derived default probabilities of individual banks and compared the performance with other reconstruction models.
  * Research Output: One article published in [Physica A: Statistical Mechanics and its Applications](https://www.sciencedirect.com/journal/physica-a-statistical-mechanics-and-its-applications): [Solvency contagion risk in the Chinese commercial banks’ network](https://www.sciencedirect.com/science/article/abs/pii/S0378437121004015?via%3Dihub) 
  * Supervisor: Prof. [Yu Chen](http://staff.ustc.edu.cn/~cyu/)

* Summer 2019: Research Assistant
  * Department of Mathematics, Arizona State University
  * A Competitive Model for Drug-Resistant Evolution of E. coli cells: 
    - Developed a biological reasonable ODE model to mathematically demonstrate the drug-resistant evolution of E. coli.  
    - Validated our model using real biological experimental data and the numerical simulation fit the data perfectly.
    - Used this model to further inspire new explanation of biological mechanisms about drug- resistant evolution.
  * Mathematical System of Nutrient Allocation Strategy in E. coli cells
    - Built and modified an equation system to depict the dynamic behavior of GFP/OD and greatly fitted the experiments.
    - Used MATLAB to search for the optimized parameters and adjusted parameters in various conditions.
    - Generalized the system into other complicated situations and the proved to be satisfactory and robust.
  * Research Output: One paper published in [SIAM Undergraduate Research Online](https://www.scilit.net/journal/1012895): [Clinical data validated mathematical model for intermittent abiraterone response in castration-resistant prostate cancer patients](https://www.siam.org/Portals/0/Publications/SIURO/Vol14/S130057PDF.pdf?ver=2021-02-22-130958-820)
  * Supervisor: Prof. [Yang Kuang](https://math.la.asu.edu/~kuang/)

* Fall 2019: Research Assistant
  *  School of CIDSE, Arizona State University
  * Multimodal Machine Learning for Alzheimer Disease Diagnosis: 
    - Using neuroimaging data from ADNI database to explore multimodal learning in Alzheimer disease diagnosis. 
    - Develop EM algorithm to deal with missing modalities problem in multimodal learning of Alzheimer disease diagnosis
    - Construct convolutional neural networks using magnetic resonance imaging to classify patients with Alzheimer disease and normal control people.
  * Supervisor: Prof. [Jing Li](https://sites.gatech.edu/jing-li/)



Programming Languages
======
C, MATLAB, R, Python

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
