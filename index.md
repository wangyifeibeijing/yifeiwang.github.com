# YIFEI  WANG
## Personal Details 
Name: Yifei Wang ( 王 逸非 )

Email: wany107@aucklanduni.ac.nz

School of Computer Science, University of Auckland

## Research Interest
Graph Theory, Graph neural network, Self-supervised learning

## Research Experience
Residual Entropy-based GCN for Community Detection
- Classical community detection methods only utilize topology, without inherent structures of the features. GCN-based models rely on Auto Encoder or Ncut stages, which is not suitable for Community Detection.
- We designed a residual entropy to quantify structural information for community detection on attributed graphs, and combine it with GCN to find ideal solution.
- The model outperforms others. We are preparing the paper.

Research on Clustering Models Based on Spectral Methods
- The time complexity of spectral clustering limits the application of it. Many approaches try to replace the original graph with a bipartite graph based on anchors, but this is difficult to combine with other models. 
- My solution is utilizing anchor-based graph and used the augmented spectral decomposition to replace the original spectral decomposition.
- Based on this research, I finished my master thesis Research on Clustering Models Based on Spectral Methods.

Anomaly Detection Model (for National Platform for Research Infrastructure Instruments)
- There were about 20000 error messages, but the number of items was too large to be checked manually.
- I construct the graphs with/without item names respectively, and compare the topology to find the anomaly items.
- This model detected more than 8000 items, which satisfied the platform operators.

Regularized Non-negative Spectral Embedding for Clustering
- There are two types of classical spectral clustering models: multi-stage models suffer from mis-match between different stages, and one-stage models before rely on c-connected graphs, which need threshold set manually.
- Our research shows the connection between clustering-indicator and spectral-embedding. We solve the problem in one stage by learning a soft-indicator matrix based on spectral embedding directly.
- The RNSE model performs better than models before. We published it on ICTAI 2019.

## Publication
Yifei Wang, Rui Liu, Yong Chen, Hui Zhang, and Zhiwen Ye, “Regularized Non-negative Spectral Embedding for Clustering”, International Conference on Tools with Artificial Intelligence (ICTAI), Portland, OR, USA, 2019, pp. 493-500.

