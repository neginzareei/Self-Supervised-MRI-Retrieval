# Self-Supervised-MRI-Retrieval
This repository presents the research project developed as part of my Master's thesis.

Title:
Metaheuristic Hyperparameter Optimization of Self-Supervised Oh-A-DINO for MRI Image Retrieval

Overview
The study investigates the use of metaheuristic optimization algorithms to improve the performance of the Oh-A-DINO self-supervised learning framework for MRI image retrieval.

Research Objectives:
1-Develop a retrieval framework for brain MRI images.
2-Optimize DINO-A-Oh hyperparameters.
3-Compare Genetic Algorithm (GA), Differential Evolution (DE), and Particle Swarm Optimization (PSO).
4-Evaluate retrieval quality using Precision@1, Precision@5, and Precision@10.

Dataset:
Experiments were conducted on the IXI brain MRI dataset 

Method:
The Oh-A-DINO self-supervised representation learning framework was implemented as the baseline retrieval model. MRI images were encoded into feature embeddings, and image retrieval was performed based on embedding similarity. To provide a more meaningful assessment than cosine similarity alone, retrieval performance was evaluated using Precision@1, Precision@5, and Precision@10 metrics.

Main Findings
Method	P@1	P@5	P@10
Baseline	0.476	0.410	0.419
DE	0.695	0.658	0.645
GA	0.762	0.740	0.729
PSO	0.843	0.792	0.773

Publication Status

The associated manuscript is currently under review.

To preserve the integrity of the publication process, the implementation code is temporarily maintained in a private repository and will be released upon publication.

Researchers and potential collaborators may contact me for additional information.
