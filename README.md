# Dynamic-Network-Embedding

This repository contains a collection of Python notebooks reproducing the synthetic and real data examples from the NeurIPS paper <a href="https://proceedings.neurips.cc/paper/2021/hash/5446f217e9504bc593ad9dcf2ec88dda-Abstract.html">Spectral embedding for dynamic networks with stability guarantees</a>. If you use this code in your own experiments, please cite the following publication:

Gallagher, I., Jones, A., & Rubin-Delanchy, P. (2021). Spectral embedding for dynamic networks with stability guarantees. *Advances in Neural Information Processing Systems, 34*.

The algorithms described in these notebooks have now been included into the <a href="https://github.com/iggallagher/Spectral-Embedding">Spectral-Embedding</a> package, which includes many other spectral embedding techniques.

### Embedding Comparison.ipynb
Code used in Section 2 (Motivating example). The Python notebook provides functions for UASE, omnibus and independent spectral embedding to reproduce Figure 2. A new version called Embedding Comparison node2vec.ipynb by Ed Davis has since been added to include a dynamic embedding version of node2vec.

### Lyon Primary School.ipynb
Code used in Section 5 (Real data). The Python notebook computes the UASE for the unfolded adjacency matrix using the Lyon primary school social interaction data in the file ia-primary-school-proximity-attr.edges. The code reproduces the spectral embedding plot in Figure 2, the student clustering analysis resulting in Figure 3 and the classroom classification analysis resulting in Figure 4 in the Appendix.
