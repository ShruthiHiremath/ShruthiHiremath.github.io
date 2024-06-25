---
title: "Layout Agnostic Human Activity Recognition in Smart Homes through Textual Descriptions Of Sensor Triggers (TDOST)"
collection: publications
date: 2024-05-20
venue: 'Arxiv (Under Review)'
paperurl: 'https://arxiv.org/pdf/2405.12368'
citation: 'Thukral, Megha, Sourish Gunesh Dhekane, Shruthi K. Hiremath, Harish Haresamudram, and Thomas Ploetz. "Layout Agnostic Human Activity Recognition in Smart Homes through Textual Descriptions Of Sensor Triggers (TDOST)." arXiv preprint arXiv:2405.12368 (2024).'
---

Human activity recognition (HAR) using ambient sensors in smart homes has numerous applications for human healthcare and wellness. However, building general-purpose HAR models that can be deployed to new smart home environments requires a significant amount of annotated sensor data and training overhead. Most smart homes vary significantly in their layouts, i.e., floor plans and the specifics of sensors embedded, resulting in low generalizability of HAR models trained for specific homes. We address this limitation by introducing a novel, layout-agnostic modeling approach for HAR systems in smart homes that utilizes the transferrable representational capacity of natural language descriptions of raw sensor data. To this end, we generate Textual Descriptions Of Sensor Triggers (TDOST) that encapsulate the surrounding trigger conditions and provide cues for underlying activities to the activity recognition models. Leveraging textual embeddings, rather than raw sensor data, we create activity recognition systems that predict standard activities across homes without either (re-)training or adaptation on target homes. Through an extensive evaluation, we demonstrate the effectiveness of TDOST-based models in unseen smart homes through experiments on benchmarked CASAS datasets. Furthermore, we conduct a detailed analysis of how the individual components of our approach affect downstream activity recognition performance.
