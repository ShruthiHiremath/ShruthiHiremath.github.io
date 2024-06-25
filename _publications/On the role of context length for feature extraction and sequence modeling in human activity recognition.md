---
title: "On the role of context length for feature extraction and sequence modeling in human activity recognition"
collection: publications
permalink: /publication/On the role of context length for feature extraction and sequence modeling in human activity recognition
date: 2021-09-21
venue: 'ISWC '21: Proceedings of the 2021 ACM International Symposium on Wearable Computers'
slidesurl: 'http://academicpages.github.io/files/Deriving Effective Human Activity Recognition Systems Through Objective Task Complexity Assessment.pdf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3460421.3478825'
---

At the core of human activity recognition (HAR) lies a time-series analysis problem. Given the sequential nature of the data, sensor readings are analyzed in their temporal contexts thereby focusing on two modeling components: feature extraction and sequence modeling for activity classification. Many HAR approaches utilize identical context lengths for both model components. In this paper we show that the consideration of such identical temporal contexts is not ideal. Motivated by the fact that features should capture temporally local characteristics of the data whereas sequence modeling should focus on longer ranging relationships, we modify a state-of-the-art HAR model (DeepConvLSTM) and experiment with different temporal contexts. Our evaluation on seven benchmark datasets demonstrates the benefit of separately optimizing temporal contexts for feature extraction and sequence modeling in HAR.
