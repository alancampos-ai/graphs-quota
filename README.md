# Graphs Quota

#### Article:   <small><strong>Interval-quota matchings in chain graphs</strong>  <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a>  <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a>  <a href="https://drive.google.com/drive/folders/1HGzCo9WKmTU7dlOZhaCHo8pxqkh0ZxLk?usp=sharing"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

We study exact quota-constrained matchings in Ferrers-ordered chain graphs with laminar, prefix, and interval quotas. We give an integral-flow formulation for laminar quotas, exact demand-capacity tests and a canonical $O(n+m)$ construction for prefix quotas, and a shortest-path envelope for one-interval quotas. Feasibility is NP-complete when every quota set has interval number at most two, even with universal neighborhoods, unit quotas, and two-element sets.

All applicable checks passed across $29{,}606$ prefix and $360$ generalized instances. Six procedures were compared on $180$ prefix instances, with $60$ paired instances per size. At $(n,m)=(100,150)$, the ordered scan was $21.2\%$, $89.4\%$, $99.1\%$, $99.97\%$, and $66.2\%$ faster than the Earliest-slot Ferrers greedy, Hopcroft--Karp, Dinic maximum flow, sparse mixed-integer optimization, and Full-profile scan, respectively. Holm-adjusted paired tests gave $p\leq0.0171$ for all five comparisons at every size.

The resource study measured $687.57$--$739.05$ ns per input item and approximately $112$ MiB peak CPU RSS for $n\in\{100,1000,5000\}$. GPU-board energy and memory are concurrent telemetry measured during CPU execution; FLOPs and MACs are not applicable to these exact integer procedures.

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
