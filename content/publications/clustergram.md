---
title: "Clustergram: Visualization and diagnostics for cluster analysis"
date: "2023-09-02"
---

<span class="pygment">Authors:</span> Fleischmann, M.<br>
<span class="pygment">Journal:</span> Journal of Open Source Software, 8(89), 5240<br>
<span class="pygment">DOI:</span> [10.21105/joss.05240](https://doi.org/10.21105/joss.05240)<br>
<span class="pygment">Open Access</span>

## abstract

Given a heterogeneous group of observations, researchers often try to find more homogenous groups within them. Typical is the use of clustering algorithms determining these groups based on statistical similarity. While there is an extensive range of algorithms to be chosen from, they often share one specific limitation - the algorithm itself will not determine the optimal number of clusters a group of observations shall be divided into. The solution is usually depending on internal cluster validity measures, but those provide only limited insight and can result in a suboptimal choice. This paper presents a Python package named clustergram offering tools to analyze the clustering solutions and visualize the behavior of observations in relation to a tested range of options for the number of classes, enabling a deeper understanding of the behavior of observations splitting into classes and better-informed decisions on the optimal number of classes.