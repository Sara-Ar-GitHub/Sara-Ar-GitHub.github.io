---
permalink: /
title: "Sara Araar"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Computer Science at the [LabSTIC Laboratory](https://www.univ-guelma.dz/),
University of 8 Mai 1945 Guelma, Algeria. My thesis has been submitted and my defence is expected
in Winter 2026-2027.

I work on the security of smart grids from two sides that are usually studied separately.

**Prevention.** I design authentication and key agreement protocols for metering devices that
cannot afford public-key cryptography at runtime. My protocol PSUL-SG uses an SRAM Physical
Unclonable Function together with a reverse fuzzy extractor to achieve provable mutual
authentication at 0.355 ms of computation, 960 bits of communication and 0.0117 mJ of energy on
the meter side. Its successor, Q-PUFAuth, replaces the classical primitives with lattice-based
post-quantum ones. Both carry proofs in the Random Oracle and Real-or-Random models and are
mechanically verified with AVISPA and ProVerif.

**Detection.** I build learning-based detectors for attacks on grid measurements. My topology-aware
approach models the power grid as a graph and applies Graph Neural Networks over AC power flow
data, reaching an F1-score of 94.2 % with GNNExplainer identifying
which buses drove each decision — because an alert an operator cannot interpret is an alert they
cannot act on.

What interests me is the space between the two: a device that is cryptographically authenticated
but physically compromised produces measurements that no protocol will reject and only detection
can catch.

## Selected publications

**PSUL-SG: A provably secure ultra-lightweight mutual authentication and key agreement protocol
for smart-grid IoT devices.**
*Computers and Electrical Engineering*, vol. 135, art. 111172, 2026. Elsevier.
[DOI](https://doi.org/10.1016/j.compeleceng.2026.111172) · [Code](#)

**Q-PUFAuth: Quantum-Resistant PUF-Based Authentication and Key Agreement for Secure Smart Grids.**
Springer *Communications in Computer and Information Science*, vol. 2818 (in press).
[Volume](https://link.springer.com/book/9783032267191) · [Preprint](#)

**Digital Twin–Driven Unsupervised Anomaly Detection Framework for Cyber-Physical Threats in
Smart Grids.**
Springer *Advances in Intelligent Systems and Computing*, vol. 1469 (in press).
[Volume](https://link.springer.com/book/9783032299857) · [Preprint](#)

[Full publication list](/publications/)

## Currently

Looking for a postdoctoral position in smart grid security, applied cryptography for constrained
devices, or machine learning for cyber-physical system protection. Available from January 2027.

[CV](/files/cv.pdf) · [Google Scholar](https://scholar.google.com/citations?user=ZTpsAIkAAAAJ) ·
[ORCID](https://orcid.org/0009-0004-4370-1373) ·
[ResearchGate](https://www.researchgate.net/profile/Sarra-Araar)
