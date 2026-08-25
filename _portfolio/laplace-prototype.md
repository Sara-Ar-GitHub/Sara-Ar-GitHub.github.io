---
title: "LAPLACE: a working prototype of a closed discovery loop"
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22081404.svg)](https://doi.org/10.5281/zenodo.22081404)
excerpt: "An agent that builds an uncertainty-aware model of a 118-bus power network, chooses its own experiments under a hard safety envelope, and distils what it learns into symbolic equations scored against ground truth."
collection: portfolio
---

LAPLACE is a small end-to-end prototype of a closed scientific discovery loop, built on a simulated 118-bus transmission network (`pandapower` case118). The loop runs from model to experiment to law:

* a **world model** - a message-passing graph neural network, implemented in plain PyTorch - predicts the electrical state of the network;
* a **deep ensemble** turns the model's disagreement into a usable measure of its own ignorance;
* a **curiosity acquisition rule** selects the next intervention where that disagreement is largest, filtered through a **hard voltage-envelope safety screen**;
* the resulting experiment retrains the model, and a **sparse symbolic regression** step distils the learned dynamics into candidate equations, scored against the network's admittance matrix - ground truth known by construction.

**What it shows.** Curiosity-driven selection beats random experiment selection by 8-17% in out-of-distribution RMSE on voltage magnitude across three seeds. It also actively seeks danger: 23-33 of the 74 selected interventions violate the voltage envelope, against 8-11 for random selection, because ignorance concentrates where operation is unsafe. That is the argument for a safety screen inside the loop rather than around it. Symbolic distillation recovers 49 out of 49 true electrical neighbours on the six most connected buses without being given the true adjacency matrix, with a coefficient R-squared of 0.91 over 98 coefficients.

**What it does not show.** Sparse regression still returns spurious terms (median 21 per bus). One diagonal admittance term is structurally non-identifiable from the active-power equation alone - a partial-identifiability result rather than a failure. Ensemble uncertainty is under-dispersed: 2-sigma coverage reaches 0.70 against a nominal 0.95. Curiosity currently serves the world model, not the law; coupling the two is the research programme, not the prototype.

The prototype supports my postdoctoral programme on agentic scientific discovery in engineered physical systems.
