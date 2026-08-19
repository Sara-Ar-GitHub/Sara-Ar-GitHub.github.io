---
title: "Lightweight Machine Learning for Anomaly Detection in Smart Meter Time-Series: A Comparative Study of Classical Models"
collection: talks
type: "AIDaM’26 – 1st National Conference on Artificial Intelligence and Data Management"
permalink: /talks/2014-02-01-talk-2
venue: "University Ahmed Zabana of Relizane, Algeria"
date: April 20, 2026
location: "Relizane, Algeria"
---

Smart grids rely on large-scale smart meter deployments to ensure efficient energy management and monitoring. However, abnormal consumption behaviors caused by device malfunction, cyber-attacks, or system disturbances may compromise grid stability and reliability. This paper proposes a lightweight anomaly detection framework for smart meter time-series data using classical machine learning models. The study is conducted on the publicly available Electricity Load Diagrams 2011–2014 dataset, where synthetic anomalies (spike, drop, drift, and noise burst) are injected to simulate realistic abnormal consumption scenarios. A feature-based approach is adopted using statistical and temporal descriptors extracted from sliding windows. Three lightweight models are evaluated: Isolation Forest, One-Class Support Vector Machine (OC-SVM), and Random Forest. Experimental results demonstrate that the supervised Random Forest model achieves the best performance with an AUC of 0.932 and a recall of 0.676 on anomalous samples, significantly outperforming unsupervised alternatives. Feature importance analysis further reveals that variability and distribution-shape features are more discriminative than absolute consumption levels. The results confirm that lightweight classical machine learning remains an effective and practical solution for smart grid anomaly detection.
