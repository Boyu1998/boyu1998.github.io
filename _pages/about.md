---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section id="about" class="home-section" markdown="1">

# About {#about-heading}

I am a Ph.D. student at the University of Bordeaux, supervised by [Romain Giot](https://www.labri.fr/perso/rgiot/). I'm working in the [Bench to Knowledge and Beyond (BKB)](https://www.labri.fr/en/bench-knowledge-and-beyond) team at [Laboratoire Bordelais de Recherche en Informatique (LaBRI)](https://www.labri.fr/en) in Bordeaux, France.

My research interest is Explainable Artificial Intelligence (XAI), particularly in Biometrics. I focus on two biometric modalities: Face Recognition (Physiological biometric) and Keystroke Dynamics (Behavioral biometric).

You can reach me at [boyu.zhu@u-bordeaux.fr](mailto:boyu.zhu@u-bordeaux.fr).

</section>

<section id="research" class="home-section" markdown="1">

# Research {#research-heading}

## Explainable AI

Deep learning is now widely used, but its decisions often remain a black box. Explainable AI (XAI) aims to understand how these models work. XAI includes post-hoc explanations and models that are interpretable by design. My research focuses on post-hoc methods, such as SHAP and Grad-CAM, and on combining XAI with visualization methods.

Explanations can be global or local. Global explanations describe the overall behavior of a model, while local explanations explain a single prediction. I study the development of both approaches and how they can be combined.

## Biometrics

Biometrics verifies a person's identity using physical or behavioral traits. My research focuses on one-to-one biometric verification, especially face recognition as a physical biometric and keystroke dynamics as a behavioral biometric.

Deep learning has improved the accuracy of biometric systems, but its decisions remain a black box. Explainable biometric verification can make these systems more trustworthy. It can help researchers find bias and understand why verification fails. It can also make biometric systems more transparent to users.

</section>

<section id="publications" class="home-section" markdown="1">

# Publications {#publications-heading}

<div class="home-publications">
{% assign publications = site.publications | sort: "date" | reverse %}
{% for post in publications %}
  {% include publication-row.html %}
{% endfor %}
</div>

</section>

<section id="cv" class="home-section" markdown="1">

# CV {#cv-heading}

## Education

- **Master's Degree in Data Science**, Paris-Saclay University · 2023
- **Bachelor's Degree in Computer Science**, Paris-Saclay University · 2020

## Experience

- **Research Assistant Intern**, IBISC Laboratory, Paris-Saclay University · 2024
  - Topic: *Transformers in Precision Medicine*
- **Research Assistant Intern**, DAVID Laboratory, Paris-Saclay University · 2023
  - Topic: *Attention-based Missing Value Imputation*

[Download my full CV (PDF)](/files/Research_CV_Boyu_Zhu_2026_EN.pdf).

</section>

<section id="supervision-teaching" class="home-section" markdown="1">

# Supervision and Teaching {#supervision-teaching-heading}

## Master's Student Supervision

**[Dorsaf Ziedi](https://www.linkedin.com/in/ziedi-dorsaf/)** — February 2026–August 2026<br>
Research subject: *Explainable Evaluation of Biometrics for Bias Discovery*<br>
Co-supervised with [Romain Giot](https://www.labri.fr/perso/rgiot/).

</section>
