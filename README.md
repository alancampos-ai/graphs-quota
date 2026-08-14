# theo-vect 

#### Article:   <small><strong>A logarithmic-quadratic algorithm for vector optimization</strong>  <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a>  <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a>  <a href="https://drive.google.com/drive/folders/10ie-yEHf3BjvKvFWveSlF1-Qlhto9Jqj?usp=sharing"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

We propose a logarithmic--quadratic primal-dual proximal method for convex vector optimization over a closed, convex, pointed cone. The scalarization weight is updated jointly with the primal variable on a normalized dual base under self-concordant barrier regularization, yielding a maximal monotone KKT operator. We give sufficient conditions for existence of zeros and prove exact and summably inexact convergence to weak Pareto solutions, with a linear estimate under strong monotonicity. Orthant, Lorentz-cone, and Tikhonov tests assess residual accuracy and cost.

#### Dependencies

* Python 3.11
* NumPy 1.26.4
* SciPy 1.13.1
* Matplotlib 3.11.1
* CVXPY 1.6.7
* Clarabel 0.11.1
* SCS 3.2.11

#### Installation

```bash
pip install numpy==1.26.4 scipy==1.13.1 matplotlib==3.11.1 cvxpy==1.6.7 clarabel==0.11.1 scs==3.2.11
```

#### License (MIT)

* Copyright (c) alancampos-ai
* Code released under the MIT License.

