---
title: "Week-ahead dispatching of active distribution networks using hybrid energy storage systems"
collection: publications
permalink: /publication/jacobs2024week
date: 2024-09-01
venue: 'Sustainable Energy, Grids and Networks'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2352467724002297'
doi: '10.1016/j.segan.2024.101500'
pubtype: 'journal'
authors: 'Jacobs, M., Gupta, R., & Paolone, M.'
excerpt_separator: ""
---
This paper presents a week-long scheduling approach to address the issues associated with uncertain stochastic generation. Specifically, the method is designed for active distribution networks (ADNs) hosting hybrid energy storages, composed by a hydrogen energy storage system (HESS) and a battery energy storage system (BESS). The inclusion of a pressurized HESS allows to balance energy over longer time periods, as opposed to methods considering only BESSs. To this end, this paper combines linearized models for the electricity grid with linearized models of the HESS to solve a tractable scheduling problem. The proposed optimal schedule consists of an active power trajectory at the grid connection point (GCP), called the dispatch plan, and the unit commitment schedule of a PEM fuel cell and electrolyzer system interfacing the electricity network with the HESS. Additionally, a bilevel model predictive control strategy is proposed, where the upper layer MPC computes a storage target accounting for the full horizon, while the lower layer computes the controllable resource setpoints to minimize the dispatch tracking error in each period. A numerical experiment shows the effectiveness of the proposed scheduling and control to accurately compute and track a dispatch plan over a full week. The results clearly show the benefits of combining a HESS with a BESS especially in periods where the prosumption is highly uncertain. Finally, we discuss the computational challenges associated with the weekly horizon and the use of a HESS that exhibits different dynamics than a BESS and propose an approach to mitigate the computational cost.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S2352467724002297)

DOI: [10.1016/j.segan.2024.101500](https://doi.org/10.1016/j.segan.2024.101500)
