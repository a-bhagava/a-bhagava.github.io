---
title: "PF∆: : A Benchmark Dataset for Power Flow under Load, Generation, and Topology Variations" 
date: 2025-10-24
tags: ["graph learning","power flow","benchmarking"]
author: ["Ana K. Rivera","Anvita Bhagavathula", "Alvaro Carbonero", "Priya Donti"]
description: " NeurIPS Datasets & Benchmarks Track, 2025 " 
summary: " Conference paper at NeurIPS Datasets & Benchmarks Track, 2025" 

cover:
    image: "paper1.png"
    alt: "Some Uses For Olive Oil"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2510.22048"
    Text: "NeurIPS Datasets & Benchmarks Track, 2025"

---

##### Abstract

Power flow (PF) calculations are the backbone of real-time grid operations, across workflows such as contingency analysis (where repeated PF evaluations assess grid security under outages) and topology optimization (which involves PF-based searches over combinatorially large action spaces). Running these calculations at operational timescales or across large evaluation spaces remains a major computational bottleneck. Additionally, growing uncertainty in power system operations from the integration of renewables and climate-induced extreme weather also calls for tools that can accurately and efficiently simulate a wide range of scenarios and operating conditions. Machine learning methods offer a potential speedup over traditional solvers, but their performance has not been systematically assessed on benchmarks that capture real-world variability. This paper introduces PFΔ, a benchmark dataset for power flow that captures diverse variations in load, generation, and topology. PFΔ contains 859,800 solved power flow instances spanning six different bus system sizes, capturing three types of contingency scenarios (N , N -1, and N -2), and including close-to-infeasible cases near steady-state voltage stability limits. We evaluate traditional solvers and GNN-based methods, highlighting key areas where existing approaches struggle, and identifying open problems for future research. Our dataset is available at this https URL and our code with data generation scripts and model implementations is at this https URL.

---

##### Download

+ [Paper](https://arxiv.org/abs/2510.22048)
+ [Summary Slides](https://neurips.cc/virtual/2025/loc/san-diego/poster/121747)

---

##### Citation

Rivera, A. K., Bhagavathula, A., Carbonero, A., & Donti, P. (2025). PF $\Delta $: A Benchmark Dataset for Power Flow under Load, Generation, and Topology Variations. arXiv preprint arXiv:2510.22048.

```BibTeX
@misc{rivera2025pfdeltabenchmarkdatasetpower,
      title={PF$\Delta$: A Benchmark Dataset for Power Flow under Load, Generation, and Topology Variations}, 
      author={Ana K. Rivera and Anvita Bhagavathula and Alvaro Carbonero and Priya Donti},
      year={2025},
      eprint={2510.22048},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.22048}, 
}
```
