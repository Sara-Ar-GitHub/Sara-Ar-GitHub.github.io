---
title: "Topology-Aware Cyberattack Detection in Smart Grids Using Explainable Graph Neural Networks"
collection: publications
category: conferences
permalink: /publication/2026-topology-aware-gnn
excerpt: 'GAT, GCN and GraphSAGE detectors over simulated AC power-flow graphs, with GNNExplainer identifying the buses that drove each decision. GraphSAGE reaches F1 = 94.2% and ROC-AUC close to 0.97.'
date: 2026-04-15
venue: "A2I-26 - Third National Conference on Applications of Artificial Intelligence, M'Hamed Bougara University"
location: "Boumerdes, Algeria"
citation: 'Araar, S., Farou, B., Kouahla, Z., &amp; Seridi, H. (2026). &quot;Topology-Aware Cyberattack Detection in Smart Grids Using Explainable Graph Neural Networks.&quot; <i>A2I-26, Third National Conference on Applications of Artificial Intelligence</i>, M&#39;Hamed Bougara University, Boumerdes, Algeria.'
---

Smart grids integrate advanced sensing and communication technologies that improve power system efficiency but also increase vulnerability to cyberattacks. Detecting such attacks is challenging because electrical measurements are strongly interconnected through the grid topology. This paper proposes a graph-based cyberattack detection framework using Graph Neural Networks (GNNs). The power grid is modeled as a graph and a dataset is generated from AC power flow simulations with the pandapower framework, where multiple attack scenarios are injected into electrical measurements. Three architectures - GAT, GCN, and GraphSAGE - are evaluated. Experimental results show that GraphSAGE achieves the best performance with an F1-score of about 94% and a ROC-AUC close to 0.97. To improve transparency, GNNExplainer is used to identify the buses contributing most to attack detection, providing interpretable insights for smart grid monitoring.
