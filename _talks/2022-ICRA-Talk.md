---
title: "Probabilistic Coordination of Heterogeneous Teams From Capability Temporal Logic Specifications"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2021-10-21-talkl-4
venue: ""
date: 2022-05-026
location: "Philadelphia, PA"
---

[Talk Presentation](https://www.youtube.com/watch?v=DgnUI9CoGhk&t=221s)

This paper explores coordination of heterogeneous
teams of agents from high-level specifications.
We employ Capability Temporal Logic (CaTL) to express rich, temporal-spatial tasks that require cooperation between many agents with unique capabilities.
CaTL specifies combinations of \emph{tasks}, each with desired locations, duration, and set of capabilities, freeing the user from considering specific agent trajectories 
and their impact on multi-agent cooperation.
CaTL also provides a quantitative robustness metric of satisfaction based on availability of required capabilities for each task.
The novelty of this paper focuses on satisfaction of CaTL formulas under probabilistic conditions. Specifically, we consider uncertainties in robot motion 
(e.g., agents may fail to transition between regions with some probability) and local probabilistic workspace properties
(e.g., if there are not enough agents of a required capability to complete a collaborative task).
The proposed approach automatically formulates a mixed-integer linear program given agents, their dynamics and capabilities, an abstraction of the workspace, 
and a CaTL formula. 
In addition to satisfying the given CaTL formula, the optimization considers the following secondary goals (in decreasing order of priority): 
1) minimize the risk of transition failure due to uncertainties; 
2) 2) maximize probabilities of regional collaborative satisfaction (if there is an excess of agents); 
3) 3) maximize the availability robustness of CaTL for potential agent attrition; 
4) 4) minimize the total agent travel time. We evaluate the performance of the proposed framework and demonstrate its scalability via numerical simulations. 
