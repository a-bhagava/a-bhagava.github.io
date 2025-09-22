---
title: "Filtering Synthesizable Reactions Using Graph Neural Networks"
date: 2023-06-01 
tags: ["graph learning","property prediction"]
description: " Oct 2022 - May 2023 " 
author: "Anvita Bhagavathula (Advisors: Jacques Boitreaud and Antoine Brochard)"
summary: " June 2023 - Aug 2023, Aqemia " 

cover:
    image: "proj4.png"
    relative: true

---

##### Project Overview

Supervised by Jacques Boitreaud and Dr. Antoine Brochard, I undertook a project on automating the time-intensive process of screening synthetic feasibility of drug candidates to help the medicinal chemists in the company. The fundamental challenge with this project was to create an architecture that was robust enough to generalize to in-house testing data, which had a distribution shift compared to the USPTO-MIT training data. To address this problem, I wanted to create a context-informed and chemically-constrained model. I formulated and implemented a unique attention-based architecture that used reactant and product graphs with encoded reaction site masks, generated using substructure matching, to do so. By the end of the summer, my model was performing with a false positive rate less than 0.1, filtering out almost all of the same reactions as Dr. Nicolas George, the in-house medicinal chemist. The most rewarding part of this project was seeing the tangible impact my research could have, as my model ultimately accelerated the rate at which promising molecules were screened from hours to seconds.
