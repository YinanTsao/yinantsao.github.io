---
layout: page
title: IWQoS 2026
---

<h3>A paper accepted at IWQoS 2026</h3>

The paper "Scylla: Scheduling Multiple Latency-Sensitive Applications in the Edge-Cloud Continuum" has been accepted by <a href="https://iwqos2026.ieee-iwqos.org/" target="_blank">IWQoS 2026</a> as a regular paper in the Edge-Cloud Resource Allocation track.

We extend the scheduling methodology of LASSY to handle multi-application concurrency through the development of the <a href="https://github.com/YinanTsao/Scylla">Scylla</a> global scheduling model. Recognizing that edge nodes are rarely dedicated to a single task, Scylla generalizes the single-application formulation to jointly schedule multiple co-located applications competing for shared resources across the edge-cloud continuum, mitigating the "Noisy Neighbor" effect through a holistic deployment plan that ensures all applications meet their respective SLOs without mutual performance interference. As the joint optimization of multiple applications causes the problem scale and computation time to grow rapidly, we further introduce the Layered Permutation Search (LPS) heuristic, which decomposes the global problem into a sequence of single-application problems and explores application orderings at controllable depth, achieving near-optimal placement plans within practical time limits even for large numbers of applications.
 
Yinan will present the paper during the conference during June 29 - July 2 2026 in Istanbul, Turkey.

