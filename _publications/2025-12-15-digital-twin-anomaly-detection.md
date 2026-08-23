---
title: "Digital Twin-Driven Unsupervised Anomaly Detection Framework for Cyber-Physical Threats in Smart Grids"
collection: publications
category: conferences
permalink: /publication/2025-digital-twin-anomaly-detection
excerpt: 'Six unsupervised detectors trained on normal operation only, benchmarked inside a compact digital twin of a power system. LOF and One-Class SVM reach F1 = 0.90.'
date: 2025-12-15
venue: "International Conference on Applied Artificial Intelligence and Emerging Technologies, Ziane Achour University of Djelfa"
location: "Djelfa, Algeria"
citation: 'Araar, S., Farou, B., Kouahla, Z., &amp; Seridi, H. (2025). &quot;Digital Twin-Driven Unsupervised Anomaly Detection Framework for Cyber-Physical Threats in Smart Grids.&quot; <i>International Conference on Applied Artificial Intelligence and Emerging Technologies</i>, Djelfa, Algeria. To appear in <i>Advances in Intelligent Systems and Computing</i>, vol. 1469, Springer.'
---

The increasing digitalization of smart grids enhances operational efficiency but simultaneously expands their exposure to cyber-physical anomalies that can jeopardize system stability and power quality. This paper presents a lightweight digital twin-driven anomaly detection framework that emulates both normal and abnormal power behaviors through a compact simulator generating voltage, current, and frequency signals. Synthetic anomalies - including spikes, drifts, and sensor flatlines - are injected to reproduce realistic cyber-physical disturbances. Six unsupervised learning algorithms, namely Local Outlier Factor (LOF), One-Class SVM, Isolation Forest, Autoencoder, LODA, and Elliptic Envelope, are trained exclusively on normal operational data to model nominal system behavior without requiring labeled attacks. Statistical features extracted from sliding windows are standardized and fed into each detector for automated benchmarking. Experimental results demonstrate that LOF (Precision = 0.91, F1 = 0.90) and One-Class SVM (Precision = 0.90, F1 = 0.90) outperform the other models, achieving the best trade-off between detection accuracy and generalization capability. Unlike previous works relying on fixed thresholds or supervised labeling, the proposed framework integrates multiple detection paradigms within a fully unsupervised, reproducible, and extensible digital twin pipeline. This work establishes a foundation for scalable real-time anomaly detection in next-generation smart energy systems.
