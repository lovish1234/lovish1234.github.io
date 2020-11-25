---
layout: post
title:  "Causal Physical Reasoning"
categories: research
authors: <strong>Lovish Chum</strong>, with Chengzhi Mao
image: /images/new_projects/causal.gif
venue: Causal Inference Course 
code: https://github.com/lovish1234/CausalComputerVision
report: /pdfs/projects/causal.pdf
---
In this project, we take a step towards learning causal visual features. For this, we have created a simulation environment called _Causal-PHYRE_. For each task in the dataset, we control the outcome, cause and confounder. We start out by observing if a vanilla NN architecture detect the causal structure of tasks from simulated videos. Further, we simulate interventions in the environment to explicitly aid learning causal structure of underlying tasks. Experiments show that intervention-based learning strategy not only improves the detection of _real_ cause rather than confounder. This concurres with assertion in Pearl Causal Hierarchy (PCH), which says that it is impossible to learn causal structure using just interventional data.