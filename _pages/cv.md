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
* Ph.D in Bioinformatics and Systems Biology, University College Dublin, 2026 (expected)
* M.S. in Bioinformatics, with focus on Protein Structure and Drug Design, Autonomous University of Barcelona 2022
* B.S. in Biotechnology, University of Oviedo, 2021

Work experience
======
* Jan 2023 - Present: Industrial PhD Student
  * IBM Research and University College Dublin
  * Duties included:
     * Research on automation, OOD evaluation, and development of foundation and machine learning models for peptide modelling
     * Teaching Assistance
     * Webserver maintenance: [http://peptide.ucd.ie](http://peptide.ucd.ie)
  * Supervisor: Prof. Denis Shields and Dr. Thanh Lam Hoang

* Feb 2022 - Dec 2022: Research and Development Assistant
  * Autonomous University of Barcelona (Insilichem research group)
  * Duties included: Developing a 3D CNN model to predict metal diffusion paths in protein structures.
  * Supervisor: Dr. Jean-Didier Maréchal

* Nov 2020 - Jun 2021: Research Assistant (intern)
  * University of Oviedo (BIOMIC research group)
  * Duties included: Experimental work on genetic engineering of a strain of *Streptomyces* to produce novel bioactive natural products (PCR, CRISPR-Cas9, HPLC, etc.).
  * Supervisor: Prof. Carmen Méndez
  
Skills
======
* Autonomous Research
  * Project Management
  * Scientific/Grant/Invention Disclosure writing
  * Teaching/Science communication
* Computational Chemistry / Cheminformatics
  * Molecular Dynamics
  * Docking
  * RDKit
* Bioinformatics
  * Sequence/Structural alignment
  * Protein structural modelling
  * Statistics
* Machine learning
  * Deep learning: Protein and Chemical Language Models / GNN / CNN
  * Traditional Machine Learning
  * Model out-of-distribution evaluation
  * Software engineering
* Other
  * Webserver building and maintenance
  * Software Engineering (Python/R/MATLAB)

Service and leadership
======

* Reviewer: 41 papers
  * Nature Communications: 1 paper
  * Briefings in Bioinformatics: 4 papers
  * Bioinformatics Advances: 1 paper
  * Journal of Cheminformatics: 1 paper
  * NeurIPS: 10 (main) + 4 (AI4Science) papers
  * ICML: 6 (main) + 4 (AI4Science) papers
  * ICLR: 4 papers
  * AAAI: 4 papers
  * AISTATS: 2 papers

* Conference Organising Committee:
  * CECAM "Peptide computational methods and applications"

* Patents: 3 filed patents

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> 
