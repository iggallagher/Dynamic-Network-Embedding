# Dynamic-Network-Embedding

This repository contains a collection of Python notebooks reproducing the synthetic and real data examples from the NeurIPS paper "Spectral embedding for dynamic networks with stability guarantees":
Gallagher, I., Jones, A., & Rubin-Delanchy, P. (2021). Spectral embedding for dynamic networks with stability guarantees. Advances in Neural Information Processing Systems, 34.

### Embedding Comparison.ipynb
Code used in Section 2 (Motivating example). The Python notebook provides functions for UASE, omnibus and independent spectral embedding to reproduce Figure 2.

### Lyon Primary School.ipynb
Code used in Section 5 (Real data). The Python notebook computes the UASE for the unfolded adjacency matrix using the Lyon primary school social interaction data in the file ia-primary-school-proximity-attr.edges. The code reproduces the spectral embedding plot in Figure 2, the student clustering analysis resulting in Figure 3 and the classroom classification analysis resulting in Figure 4 in the Appendix.
