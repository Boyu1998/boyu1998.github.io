---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section id="about" class="home-section" markdown="1">

## About {#about-heading}

I am a Ph.D. student at the University of Bordeaux, supervised by [Romain Giot](https://www.labri.fr/perso/rgiot/). I work within the [Bench to Knowledge and Beyond (BKB)](https://www.labri.fr/en/bench-knowledge-and-beyond) team at Laboratoire Bordelais de Recherche en Informatique (LaBRI) in Bordeaux, France.

My research interest is explainable artificial intelligence (XAI), particularly in biometrics. I focus on two biometric modalities: Face Recognition (physiological biometric) and Keystroke Dynamics (behavioral biometric).

You can reach me at [boyu.zhu@u-bordeaux.fr](mailto:boyu.zhu@u-bordeaux.fr).

</section>

<section id="research" class="home-section" markdown="1">

## Research {#research-heading}

My research focuses on trustworthy and explainable methods for biometric systems, with an emphasis on understanding model decisions and improving their reliability.

</section>

<section id="publications" class="home-section" markdown="1">

## Publications {#publications-heading}

<div class="home-publications">
{% assign publications = site.publications | sort: "date" | reverse %}
{% for post in publications %}
  {% include publication-row.html %}
{% endfor %}
</div>

</section>

<section id="cv" class="home-section" markdown="1">

## CV {#cv-heading}

### Education

**Ph.D. in Biometrics and Explainability of Artificial Intelligence** · 2024–Present<br>
University of Bordeaux, Talence, France

**Master's Degree in Data Science** · 2020–2023<br>
Paris-Saclay University, Orsay, France

**Bachelor's Degree in Computer Science** · 2019–2020<br>
Paris-Saclay University, Orsay, France

**University Diploma of Technology (DUT) in Computer Science** · 2017–2019<br>
Paris Cité University, Paris, France

### Experience

**Ph.D. Student** · 2024–Present<br>
LaBRI, University of Bordeaux — Talence, France

- Supervisor: [Romain Giot](https://www.labri.fr/perso/rgiot/), Associate Professor at the University of Bordeaux
- Research topic: *Beyond Explainability and Evaluation Standards: A Better Understanding of Biometric Authentication*
- Analyzing evaluation protocols, performance metrics, and global and local explainability methods for biometric authentication, with a focus on keystroke dynamics and face recognition.

**Research Assistant Intern** · 2024<br>
IBISC Laboratory, Paris-Saclay University — Évry, France

- Supervisor: Blaise Hanczar, Full Professor at Paris-Saclay University
- Research topic: *Transformers in Precision Medicine*
- Applied Transformer models to phenotype prediction from omics data and investigated model variants to balance computational cost, training time, and prediction accuracy.

**Research Assistant Intern** · 2023<br>
DAVID Laboratory, Paris-Saclay University — Versailles, France

- Supervisor: Mustapha Lebbah, Full Professor at Paris-Saclay University
- Research topic: *Attention-based Missing Value Imputation*
- Investigated a Transformer-based method for improving prediction accuracy on datasets with missing values and implemented models using Keras and TensorFlow.

[Download my full CV (PDF)](/files/Research_CV_Boyu_Zhu_2026_EN.pdf).

</section>

<section id="supervision-teaching" class="home-section" markdown="1">

## Supervision and Teaching {#supervision-teaching-heading}

### Master's Student Supervision

**[Dorsaf Ziedi](https://www.linkedin.com/in/ziedi-dorsaf/)** — February 2026–August 2026<br>
Research subject: *Explainable Evaluation of Biometrics for Bias Discovery*<br>
Co-supervised with [Romain Giot](https://www.labri.fr/perso/rgiot/).

</section>
