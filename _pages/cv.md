---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PhD candidate in Computer Science at the LabSTIC Laboratory, University of 8 May 1945 Guelma, Algeria.
I work on machine learning for networked physical systems, and on provably secure protocols for the
constrained devices that instrument them.

Education
======
* **Ph.D. in Computer Science**, University of 8 May 1945 Guelma, LabSTIC Laboratory.
  Thesis: *Cyberattack Detection in Smart Grid Networks*. Submitted; defence expected autumn 2026.
* **Master's degree in Computer Science — Information Systems**,
   Higher National School of Computer Science (ESI — École nationale Supérieure d'Informatique,
  ex-INI), Algiers, Algeria, 2013.
* **State Engineer's degree in Computer Science — Information Systems**,
   Higher National School of Computer Science (ESI — École nationale Supérieure d'Informatique,
  ex-INI), Algiers, Algeria, 2008–2013.
  

Research experience
======
* **Doctoral researcher**, LabSTIC Laboratory, University of 8 May 1945 Guelma. Two complementary axes:
  * *Graph machine learning for physical networks.* Topology-aware GCN, GAT and GraphSAGE detectors
    trained on AC power-flow data generated with pandapower (F1 = 94.2%, ROC-AUC ~ 0.97), with
    GNNExplainer attribution; a counterfactual graph-learning framework on the heterogeneous UNSW-MG24
    microgrid dataset; a digital-twin pipeline benchmarking six unsupervised anomaly detectors; a
    leakage-free comparative study of lightweight models on real smart-meter time series.
  * *Provably secure protocols for constrained grid devices.* PSUL-SG, an ultra-lightweight PUF-based
    authentication and key agreement protocol (0.355 ms, 960 bits, 0.0117 mJ per session on the meter
    side); Q-PUFAuth, a lattice-based     post-quantum successor. All verified formally, under the Random Oracle and Real-or-Random models and mechanically with AVISPA and ProVerif.

* **Research prototype: LAPLACE** (2026). An end-to-end closed discovery loop on a simulated 118-bus
  transmission network: uncertainty-aware graph world model, curiosity-driven experiment selection under
  a hard safety envelope, and symbolic distillation of the learned dynamics scored against ground truth.
  Openly archived and citable: [https://doi.org/10.5281/zenodo.22081404](https://doi.org/10.5281/zenodo.22081404).
  [Details](/portfolio/).


Professional experience
======
* **Principal Specialised Technical Inspector**,
  Direction of National Transmissions (*Direction des Transmissions Nationales*), Guelma Province,
  Algeria. December 2015 – present.
  Operation, maintenance and supervision of the province's transmission and telecommunications
  infrastructure. Doctoral research carried out in parallel with this post; ten years of daily contact
  with a live networked infrastructure inform the modelling assumptions behind my research on
  networked physical systems.

Technical skills
======
* **Machine learning**: PyTorch, graph neural networks (GCN, GAT, GraphSAGE), deep ensembles,
  scikit-learn; anomaly detection, counterfactual explanation, GNNExplainer; experiment design and
  leakage-free evaluation protocols.
* **Physical-system simulation**: pandapower (power-flow generation at scale), digital-twin construction,
  smart-grid and microgrid datasets (UNSW-MG24, smart-meter time series).
* **Symbolic and statistical methods**: sparse symbolic regression (SINDy), uncertainty quantification
  and calibration.
* **Formal methods**: AVISPA, ProVerif, BAN logic, Real-or-Random and Random Oracle proof models.
* **Programming and tools**: Python, C, Git, LaTeX, Linux.

Languages
======
* Arabic, French, English.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks and presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service
======
* Reviewer and student member activities.

