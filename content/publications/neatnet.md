---
title: "Adaptive continuity-preserving simplification of street networks"
date: "2025-11-24"
---

<span class="pygment">Authors:</span> Fleischmann, M., Vybornova, A., Gaboardi, J.D., Brázdová, A., Dančejová, D..<br>
<span class="pygment">Journal:</span> Computers, Environment and Urban Systems (123)<br>
<span class="pygment">DOI:</span> [10.5311/10.1016/j.compenvurbsys.2025.102354](https://doi.org/10.1016/j.compenvurbsys.2025.102354)<br>
<span class="pygment">Open Access</span>

## abstract

Street network data is widely used to study human-based activities and urban structure. Often, these data
are geared towards transportation applications, which require highly granular, directed graphs that capture
the complex relationships of potential traffic patterns. While this level of network detail is critical for certain
fine-grained mobility models, it represents a hindrance for studies concerned with the morphology of the street
network. For the latter case, street network simplification — the process of converting a highly granular input
network into its most simple morphological form — is a necessary, but highly tedious preprocessing step,
especially when conducted manually. In this manuscript, we develop and present a novel adaptive algorithm
for simplifying street networks that is both fully automated and able to mimic results obtained through a
manual simplification routine. The algorithm — available in the neatnet Python package — outperforms
current state-of-the-art procedures when comparing those methods to manually, human-simplified data, while
preserving network continuity.