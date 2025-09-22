---
title: "Leveraging Machine Learning to Predict Protein Digestibility"
date: 2022-05-01 
tags: ["protein digestibility","datasets","property prediction"]
description: " June 2022 - September 2022 " 
author: "Anvita Bhagavathula (Advisors: Ranveer Chandra, Sara Malvar)"
summary: " June 2022 - September 2022, Microsoft Research" 

cover:
    image: "proj1.png"
    relative: true

---

##### Project Overview

Advised by Dr. Sara Malvar and Dr. Ranveer Chandra at Microsoft Research, I developed a multimodal machine-learning based method to predict food protein digestibility, a value normally determined using extensive animal experimentation. To tackle this problem, I first created a 2000-point ground-truth protein property dataset that mapped features such as food nutritional information and protein sequence embeddings, extracted from a pre-trained transformer model, to digestibility coefficients. Then, I used Shapley value analysis to only select features that had established relationships to protein digestibility in the literature to train tree-based models on. We found that this biologically-interpretable dimensionality reduction was key in achieving the high accuracies our models did through an ablation study. We filed a provisional patent for this methodology. The downstream impact of our results is the reduction of animal experimentation in the development of new food products.
