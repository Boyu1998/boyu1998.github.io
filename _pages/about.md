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

**Master's Degree in Data Science**, Paris-Saclay University · 2023

**Bachelor's Degree in Computer Science**, Paris-Saclay University · 2020

### Experience

**Research Assistant Intern** · 2024<br>
IBISC Laboratory, Paris-Saclay University — Évry, France

Research topic: *Transformers in Precision Medicine*

**Research Assistant Intern** · 2023<br>
DAVID Laboratory, Paris-Saclay University — Versailles, France

Research topic: *Attention-based Missing Value Imputation*

[Download my full CV (PDF)](/files/Research_CV_Boyu_Zhu_2026_EN.pdf).

</section>

<section id="supervision-teaching" class="home-section" markdown="1">

## Supervision and Teaching {#supervision-teaching-heading}

### Master's Student Supervision

**[Dorsaf Ziedi](https://www.linkedin.com/in/ziedi-dorsaf/)** — February 2026–August 2026<br>
Research subject: *Explainable Evaluation of Biometrics for Bias Discovery*<br>
Co-supervised with [Romain Giot](https://www.labri.fr/perso/rgiot/).

</section>
