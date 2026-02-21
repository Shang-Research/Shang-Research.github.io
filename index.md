---
title: "Home"
layout: gridlay
sitemap: false
permalink: /
---

{% comment %}
<div style="text-align: center; margin: 20px 0;">
  <h2 style="font-size: 1.8rem; font-weight: bold; color: black;">
    We are looking for mutiple group members.
   <br/>
 <a style="font-weight: bold;"><span style="color: red;">Openings of Master and PhD Positions</span></a> 
  <a href="{{ site.url }}{{ site.baseurl }}/papers/2025GraduatePositions.pdf" style="font-size: 1.8rem; font-weight: bold;"><span style="color: #2a7ae2;">here.</span> 
  </h2>
  </div>
{% endcomment %}

Our research group is dedicated to exploring a wide spectrum of Earth and environmental sciences, particularly interested in Earth-life systems across different temporal and spatial scales. Our research is driven by the overarching goal of answering fundamental questions about the microscopic/macroscopic interactions, dynamical properties, and evolutionary processes of <span style="font-weight: bold;">**Earth-life systems**</span> as well as identifying basic rules governing Earth’s sustainability and exoplanets’ habitability. We use an ensemble of approaches, including <span style="font-weight: bold;">**mechanistic theoretical models**</span> (based on fundamental physics), <span style="font-weight: bold;">**high-dimensional mathematical models**</span> (with numerical simulations), <span style="font-weight: bold;">**machine learning methods**</span> and <span style="font-weight: bold;">**big data analyses**</span>, <span style="font-weight: bold;">**computational biology**</span> and <span style="font-weight: bold;">**bioinformatics**</span> as well as <span style="font-weight: bold;">**laboratory experiments**</span>. 


{% for member in site.data.pi %}
<div class="jumbotron" style="background-color:#EBEFF1;">
<div class="row">
<div class="col-sm-2">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%" style="max-width:250px"/>
</div>
<div class="col-sm-9 col-xs-12">
<h4>{{ member.name }}</h4>
{{ member.info }}<br>

<!--  
{% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-2x"></i></a> {% endif %} {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %} {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %} {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-2x"></i></a> {% endif %} {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %} {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
 -->

<ul style="overflow: hidden">
<li> {{ member.education[0] }} </li>
<li> {{ member.education[1] }} </li>
<li> {{ member.education[2] }} </li>
<!-- <li> {{ member.education[3] }} </li> -->
</ul>
Email: {{ member.email}}
</div>
</div>
</div>

{% endfor %}


#### Main Research Interests

<ul style="list-style-type: disc; margin-left: 20px;">
  <li style="margin-bottom: 10px;"> 
    <span style="font-size: 1.1rem;">Methodological Research</span>
    <ul style="list-style-type: circle; margin-left: 20px; margin-top: 5px;">
      <li><span style="font-size: 1rem; ">Mechanistic theories, computational algorithms, and AI-based models.</span></li>
      <li><span style="font-size: 1rem; ">Causal inference, stochastic process, and probabilistic models.</span></li>
      <li><span style="font-size: 1rem; ">Computational biology & phylogenetics & molecular evolution. </span></li> 
      <li><span style="font-size: 1rem; ">Complex systems theory (particularly nonlinear dynamics $\&$ network theory).</span></li>

    </ul>
  </li>

  <li style="margin-top: 20px;"> 
    <span style="font-size: 1.1rem; ">Specific Scientific Topics</span>
    <ul style="list-style-type: circle; margin-left: 20px; margin-top: 5px;">
      <li><span style="font-size: 1rem; ">Biogeochemical cycles, sustainable Earth, and habitable exoplanets.</span></li>
      <li><span style="font-size: 1rem; ">Microbial metabolisms, ecology, and evolution.</span></li>
      <li><span style="font-size: 1rem; ">Co-evolution of Earth and life throughout geological time.</span></li>
    </ul>
  </li>
</ul>
