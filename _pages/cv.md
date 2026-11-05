---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV as a PDF]({{ base_path }}/files/Ranga_Baminiwatte_CV.pdf)

Education
======
* **Ph.D. in Biomedical Data Science and Informatics**, Clemson University & Medical University of South Carolina, 2023 – 2027 (expected)
* **M.S. in Biomedical Data Science and Informatics** (en route to Ph.D.), Clemson University & Medical University of South Carolina, 2023 – 2025
* **B.S. in Applied Mathematics and Computer Science** (Data Science and Business Analytics track), Higher School of Economics, Moscow, 2018 – 2023

Research experience
======
* **Graduate Research Assistant**, Clemson University, Aug 2023 – present
  * Design AI and statistical methods for disease understanding, multimodal phenotyping and biomedical knowledge representation using medical images, clinical features and knowledge graphs.
  * Build end-to-end deep learning pipelines: preprocessing, GPU-optimised training, hyperparameter search, evaluation and reporting.

* **Research Assistant**, Higher School of Economics, Moscow, Jan 2023 – Aug 2023
  * Developed machine learning models for research questions in linguistics and physics.
  * Data engineering and evaluation on noisy multi-sensor datasets (eye tracking, demographics, text).

* **Student Intern**, Raiffeisen Bank Russia, Moscow, Nov 2020 – May 2021
  * Researched blockchain-based compliance validation with smart contracts and SQL-backed databases for corporate settlements.

Skills
======
* **Programming:** Python, R, C++, JavaScript, SQL
* **Frameworks:** PyTorch, TensorFlow, scikit-learn, PyTorch Geometric, Deep Graph Library (DGL), Hugging Face Transformers
* **Tools:** Linux, SLURM, Flask, PostgreSQL, Git
* **Domains:** Graph ML, statistical modelling, contrastive learning, phenotyping, applied genomics, computer vision, NLP

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks and posters
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Awards and scholarships
======
* **Sep 2025:** Excellence in Communications Award, Clemson University HPC Poster Competition
* **Aug 2023:** Graduate Research Assistantship, Clemson University
* **Jan 2023:** Open Doors: Russian Scholarship Project
* **Aug 2017:** Russian Federation State Scholarship for International Students

Service
======
* Peer reviewer for computational genomics manuscripts
