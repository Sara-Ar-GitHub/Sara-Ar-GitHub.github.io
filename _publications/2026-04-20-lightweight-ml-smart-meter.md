---
title: "Lightweight Machine Learning for Anomaly Detection in Smart Meter Time-Series: A Comparative Study of Classical Models"
collection: publications
category: conferences
permalink: /publication/2026-lightweight-ml-smart-meter
excerpt: 'A leakage-free, time-aware evaluation of Isolation Forest, One-Class SVM and Random Forest on the Electricity Load Diagrams 2011-2014 dataset with controlled anomaly injection.'
date: 2026-04-20
venue: "AIDaM'26 - 1st National Conference on Artificial Intelligence and Data Management, University Ahmed Zabana of Relizane"
location: "Relizane, Algeria"
citation: 'Araar, S., Farou, B., Kouahla, Z., &amp; Seridi, H. (2026). &quot;Lightweight Machine Learning for Anomaly Detection in Smart Meter Time-Series: A Comparative Study of Classical Models.&quot; <i>AIDaM&#39;26, 1st National Conference on Artificial Intelligence and Data Management</i>, University Ahmed Zabana of Relizane, Algeria.'
---

Smart grids rely on large-scale smart meter deployments to ensure efficient energy management and monitoring. However, abnormal consumption behaviors caused by device malfunction, cyber-attacks, or system disturbances may compromise grid stability and reliability. This paper proposes a lightweight anomaly detection framework for smart meter time-series data using classical machine learning models. The study is conducted on the publicly available Electricity Load Diagrams 2011-2014 dataset, where synthetic anomalies (spike, drop, drift, and noise burst) are injected to simulate realistic abnormal consumption scenarios. A feature-based approach is adopted using statistical and temporal descriptors extracted from sliding windows. Three lightweight models are evaluated: Isolation Forest, One-Class Support Vector Machine (OC-SVM), and Random Forest. Experimental results demonstrate that the supervised Random Forest model achieves the best performance with an AUC of 0.932 and a recall of 0.676 on anomalous samples, significantly outperforming unsupervised alternatives. Feature importance analysis further reveals that variability and distribution-shape features are more discriminative than absolute consumption levels. The results confirm that lightweight classical machine learning remains an effective and practical solution for smart grid anomaly detection.
