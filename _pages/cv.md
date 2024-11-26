---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Computer Science, Télécom Paris, 2024
* MSc in Computer Science and Engineering, École polytechnique, 2021
* MSc in Computer Science and Engineering, Télécom Paris, 2021
* Preparatory School MPSI-MP*, Lycée privé Sainte-Geneviève, 2014-2016

Work experience
======
* February 2021 - November 2024: PhD in Computer Science
  * [Télécom Paris](https://www.telecom-paris.fr/en/home)
  * Thesis Title: "Meta-Evaluation Methodology and Benchmark for Automatic Story Generation"
  * Superviors: [Fabian M. Suchanek](https://www.suchanek.name/) and [Chloé Clavel](https://clavel.wp.imt.fr/)

* July-December 2020: Machine Learning Research Intern
  * [DeepLife](https://www.deeplife.co/)
  * Designed and benchmarked algorithms for predicting the evolution of biological cell states.
  * Supervisor: Jean-Baptiste Morlot

* March-July 2019: Research Intern
  * Télécom Paris
  * Designed a clustering algorithm capable of one-shot learning and object description.
  * Supervisor: Jean-Louis Dessalles

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
