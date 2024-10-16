# Community Detection in Sparse Networks using NMF

This repository contains code and resources for performing community detection in sparse networks using Non-negative Matrix Factorization (NMF).

## Introduction
Community detection is a fundamental task in network analysis, aiming to identify groups of nodes that are densely connected within themselves and sparsely connected with nodes outside the group. In this project, we explore the application of NMF for community detection in sparse networks.

## Contents
- Analysis of different algorithms for community detection
- Implementation of NMF algorithm for community detection
- Evaluation metrics for assessing the quality of detected communities
- Example datasets for testing and experimentation

## Tasks
- Devise an algorithm for estimating the number of communities in the network (Assigned - Shivam Gupta)
- Implement CDNMF algorithm for community detection (In Progress - Shivam Agrawal)
- Evaluate the quality of detected communities using evaluation metrics
    - Synthetic Data
        - Synthetic data generation for testing and evaluation (Assigned - Shivam Gupta)
        - Testing on synthetic datasets (Assigned - Shivam Gupta)
    - Real-World Data
        - Data collection and preprocessing (Completed - Shivam Agrawal)
        - Testing on real-world datasets (In Progress - Shivam Agrawal)
- Analyse the performance of CDNMF by varying edge probabilities and community sizes (Not Assigned)
- Study the effect of positive and negative eigenvalues on the quality of detected communities (Not Assigned)
- Identify outlier communities and analyse their impact on the performance of CDNMF (Not Assigned)
- Read the following papers for proposing further improvements to the CDNMF algorithm
    - Kuang, D.; Ding, C.; Park, H. Symmetric nonnegative matrix factorization for graph clustering. (Not Assigned)
    - Ma, X.; Gao, L.; Yong, X.; Fu, L. Semi-supervised clustering algorithm for community structure detection in complex networks. (Not Assigned)

## Contributors
- Shivam Agrawal
- Shivam Gupta

## References
- https://chatgpt.com/share/9cdd17d6-49c5-4cfc-bd6e-774bddcc9872
- https://github.com/6lyc/CDNMF
- https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/chapters/factorization.md
- https://github.com/benedekrozemberczki/M-NMF

## Blockers
- Estimating the number of communities in the network
- Initialization of P matrix in CDNMF algorithm
- Deciding number of iterations and beta value
- Applying penalty based on feature matrix