---
title: "Digital Twin Validation with Multi-Epoch, Multi-Variate Output Data"
authors: '<b>Linyun He</b>, Luke Rhodes-Leader, Eunhye Song'
collection: publications
permalink: /publication/2024-Multi_dim_DT_validation
date: 2024-12-15
venue: '2024 Winter Simulation Conference'
venueType: conference
page: 347-358
paperurl: 'https://ieeexplore.ieee.org/document/10838742'
status: published
---

## Abstract
This paper studies validation of a simulation-based process digital twin (DT). We assume that at any point the DT is queried, the system state is recorded. Then, the DT simulator is initialized to match the system state and the simulations are run to predict the key performance indicators (KPIs) at the end of each time epoch of interest. Our validation question is if the distribution of the simulated KPIs matches that of the system KPIs at every epoch. Typically, these KPIs are multi-variate random vectors and non-identically distributed across epochs making it difficult to apply the existing validation methods. We devise a hypothesis test that compares the marginal and joint distributions of the KPI vectors, separately, by transforming the multi-epoch data to identically distributed observations. We empirically demonstrate that the test has good power when the system and the simulator sufficiently differ in distribution.

## Citation
```bibtex
@inproceedings{he2024digital,
  title={Digital Twin Validation with Multi-Epoch, Multi-Variate Output Data},
  author={He, Linyun and Rhodes-Leader, Luke and Song, Eunhye},
  booktitle={2024 Winter Simulation Conference (WSC)},
  pages={347--358},
  year={2024},
  organization={IEEE}
}
```