# pdpm-workshop-2025

A beginner‑friendly course on single‑cell RNA‑seq analysis, covering data characteristics, Scanpy workflow, manifold‑learning‑based dimensionality reduction, and trajectory inference with key mathematical concepts and practical examples.

---

## Table of Contents

1. [Course Overview](#course-overview)  
2. [Prerequisites](#prerequisites)  
3. [Course Outline](#course-outline)  
   1. [Introduction to Single‑Cell Data](#introduction-to-single‑cell-data)  
   2. [Scanpy Workflow](#scanpy-workflow)  
   3. [Manifold Learning & Dimensionality Reduction](#manifold-learning--dimensionality-reduction)  
      - PCA  
      - t‑SNE  
      - UMAP  
      - Diffusion Maps  
   4. [Trajectory Inference](#trajectory-inference)  
      - Diffusion Pseudotime (DPT)  
      - PAGA  
      - Other Methods (Monocle3, Slingshot)  
   5. [Hands‑On Session](#hands‑on-session)  
   6. [Summary & Next Steps](#summary--next-steps)  
4. [Recommended Reading](#recommended-reading)  
5. [License & Acknowledgements](#license--acknowledgements)  

---

## Course Overview

This workshop will guide you through the fundamentals of single‑cell RNA‑seq analysis:

- Understand the unique challenges of high-dimensional, sparse single‑cell data  
- Learn a complete Scanpy-based preprocessing and analysis pipeline  
- Dive into the mathematical foundations of popular nonlinear dimensionality‑reduction techniques  
- Explore trajectory inference approaches to reconstruct developmental or differentiation pathways  
- Work through hands‑on examples with real datasets  

---

## Prerequisites

- Basic familiarity with Python (variables, functions, `pip`)  
- Fundamental understanding of gene expression and RNA‑seq concepts  
- A laptop with Python ≥ 3.8 installed  

---

## Course Outline

### 1. Introduction to Single‑Cell Data
- Characteristics of single‑cell RNA‑seq  
- Technical noise, dropouts, and batch effects  
- Biological heterogeneity and lineage concepts  

### 2. Scanpy Workflow
- AnnData structure (`.X`, `.obs`, `.var`)  
- Quality control and filtering  
- Normalization, log‐transformation, and HVG selection  
- Neighborhood graph construction  

### 3. Manifold Learning & Dimensionality Reduction
- **PCA**: covariance matrix, eigen decomposition  
- **t‑SNE**: pairwise affinities, KL divergence  
- **UMAP**: fuzzy simplicial sets, cross‐entropy loss  
- **Diffusion Maps**: Markov transition matrices, spectral embedding  

### 4. Trajectory Inference
- Concept of pseudotime  
- **Diffusion Pseudotime (DPT)**: diffusion distance, root cell selection  
- **PAGA**: cluster graph abstraction, connectivity metrics  
- Overview of **Monocle3**, **Slingshot**, **SCORPIUS**  

### 5. Hands‑On Session
- Loading 10x Genomics demo data  
- Running the full Scanpy pipeline end‑to‑end  
- Visualizing embeddings and lineage trajectories  
- Q&A with live debugging  

### 6. Summary & Next Steps
- Common pitfalls and best practices  
- Further resources and community forums  
- Ideas for extending analysis  

---

## Recommended Reading

- Wolf, F. A., Angerer, P., & Theis, F. J. (2018). SCANPY: large-scale single-cell gene expression data analysis. *Genome Biology* 19, 15.  
- Becht, E., McInnes, L., Healy, J., et al. (2019). Dimensionality reduction for visualizing single-cell data using UMAP. *Nature Biotechnology* 37, 38–44.  
- van Dijk, D., Sharma, R., Nainys, J., et al. (2018). Recovering Gene Interactions from Single-Cell Data Using Data Diffusion. *Cell* 174, 716–729.e27.  
- Haghverdi, L., Büttner, M., Wolf, F. A., Buettner, F., & Theis, F. J. (2016). Diffusion pseudotime robustly reconstructs lineage branching. *Nature Methods* 13, 845–848.  
- Coifman, R. R., & Lafon, S. (2006). Diffusion maps. *Applied and Computational Harmonic Analysis* 21, 5–30.  
- McInnes, L., Healy, J., & Melville, J. (2020). UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction. *arXiv* preprint arXiv:1802.03426.  

---

## License & Acknowledgements

This workshop materials are released under the [MIT License](LICENSE).  
Thanks to the Scanpy development team and the single‑cell analysis community for their ongoing contributions.
