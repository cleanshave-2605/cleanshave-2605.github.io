---
layout: "page"
title: "Inducing Robustness in 2D-DPO"
description: "Improving preference optimisation robustness under noisy labels with Robust 2D-DPO."
img: "assets/img/12.jpg"
importance: 1
category: "coursework"
---

Course project, CS 769 | Prof. Ganesh Ramakrishnan | March–May 2025.

- Diagnosed a lack of segment-level noise robustness in 2D-DPO, causing a win-rate drop from 43% to 37%.
- Formulated Robust 2D-DPO and trained a Pythia 6.9B model on 6,400 HelpSteer-2D prompts to test robustness.
- Increased win rate from 37% to 45% in the presence of noisy labels.
- Accelerated model training and inference by parallelising over four NVIDIA H100 GPUs.
