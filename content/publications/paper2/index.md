---
title: "Understanding the Implications of Uncertainty in Embodied Carbon Models for Sustainable Computing" 
date: 2024-07-09
tags: ["sustainability", "hardware"]
author: ["Anvita Bhagavathula", "Leo Han", "Udit Gupta"]
description: "Conference paper at HotCarbon'24" 
summary: "Paper at HotCarbon'24 (Workshop on Sustainable Computer Systems)" 
cover:
    image: "paper2.png"
    alt: "Dimensions of a sausage dog"
    relative: true
editPost:
    URL: "https://hotcarbon.org/assets/2024/pdf/hotcarbon24-final146.pdf"
    Text: "HotCarbon'24"

---

##### Abstract

Quantifying the embodied carbon emissions of computer systems is a growing area of interest and several models to do so have already been established. However, these models are fundamentally deterministic and do not account for the fact that hardware and software characteristics of systems have inherent uncertainties – spatial, temporal, process-driven, and system-driven – which can cause extensive variation in carbon emission estimates. Our work aims to investigate the effect of these uncertainties on embodied carbon footprint estimates and system design choice trade-offs. We propose a novel probabilistic framework that generates distribution based outputs of embodied carbon emissions. We demonstrate the approach on modeling chip manufacturing carbon footprint by first characterizing uncertainty in the energy-per-area, gas-per-area, yield, and carbon intensity of fabrication parameters and observing how embodied carbon per area estimates change for various technology process nodes. We then apply this distribution-based framework to a case study focusing on laptop GPU chip choice, comparing the NVIDIA RTX A3000 Mobile with the Intel Arc Pro A60M from a sustainability perspective. Lastly, we investigate how the probability of making the correct carbon optimal choice changes when the carbon footprint is embodied-dominated or operational dominated.

---

##### Download

+ [Paper](https://hotcarbon.org/assets/2024/pdf/hotcarbon24-final146.pdf)
+ [Slides](https://hotcarbon.org/assets/2024/pdf/slides-146.pdf)

---

##### Citation

Anvita Bhagavathula, Leo Han, and Udit Gupta. 2024. Understanding the
Implications of Uncertainty in Embodied Carbon Models for Sustainable
Computing. In Proceedings of 3rd Workshop on Sustainable Computer Systems
(HotCarbon’24). ACM, New York, NY, USA, 7 pages.

```BibTeX
@inproceedings{Bhagavathula2024HotCarbon,
  author    = {Anvita Bhagavathula and Leo Han and Udit Gupta},
  title     = {Understanding the Implications of Uncertainty in Embodied Carbon Models for Sustainable Computing},
  booktitle = {Proceedings of the 3rd Workshop on Sustainable Computer Systems (HotCarbon'24)},
  year      = {2024},
  publisher = {ACM},
  address   = {New York, NY, USA},
  pages     = {1--7},
}
```