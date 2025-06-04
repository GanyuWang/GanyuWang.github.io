---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<link rel="stylesheet" href="{{ '/assets/css/main.scss' | relative_url }}">


### FedOne: Query-Efficient Federated Learning for Black-box Discrete Prompt Learning

*Dec. 2023 – May. 2025*
Proposed a novel federated learning framework tailored for black-box discrete prompt tuning on cloud-based LLMs, addressing the high query cost previously overlooked in federated black-box prompt learning scenarios. We theoretically proved and empirically validates that activating only one client per round achieves optimal query efficiency under this scenario. The framework is evaluated on GLUE tasks and real-world APIs (e.g., GPT-3.5), showing significant reductions in query overhead and computational demands. This work has been accepted by [ICML 2025](/files/ICML2025_FedOne_BDPL.pdf).

<div style="position: relative; display: inline-block; width: auto;">
  <div class="badge">ICML 2025</div>
  <img src="/images/Project_FedOne.jpg" alt="FedOne Framework" style="width: 100%; border-radius: 5px;">
</div>



### Communication Efficiency and Privacy-preserving Computation in Vertical Federated Learning
*Apr. 2022 - Jan. 2024*   
Developed an innovative Vertical Federated Learning framework that combines various optimization techniques to improve convergence rates while preserving data privacy. Proposed a theoretical analysis of the framework's convergence and differential privacy guarantees, achieving substantial reductions in communication costs. This series of works are published in [NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/2b5af479527167d4af78847a9b9b645f-Abstract-Conference.html) and [Machine Learning Journal (MLJ)](https://link.springer.com/article/10.1007/s10994-024-06541-y).

<div style="position: relative; display: inline-block; width: auto;">
  <!-- Badge -->
  <div class="badge">
    NeurIPS 2023
  </div>
  <!-- Image -->
  <img src="/images/Project_a_unified_framework.jpg" alt="A Unified Framework" style="width: 100%; border-radius: 5px;">
</div>

### Event-Driven Online Federated Learning
*Jan. 2023 - Oct. 2024*   
We address a critical challenge in Vertical Federated Learning (VFL): the absence of synchronous data streaming across clients in online learning scenarios. While prior research often assumes that all clients receive data for the same entity simultaneously, real-world applications are inherently dynamic, characterized by event-driven and asynchronous data arrivals. To overcome this limitation, we propose a novel event-driven online VFL framework that enables asynchronous client activation based on event triggers. This approach significantly reduces communication and computation costs by activating only the relevant subset of clients for each event, offering a scalable and efficient solution for collaborative learning in dynamic environments. Our research expands the practical applicability of online VFL to domains such as IoT networks, sensor systems, and distributed enterprise solutions. This work has been published in [ICLR 2025](https://openreview.net/forum?id=FCBbh0HCrF&noteId=BXVaiTkcq9). 

<div style="position: relative; display: inline-block; width: auto;">
  <!-- Badge -->
  <div class="badge">
    ICLR 2025
  </div>
  <!-- Image -->
  <img src="/images/Project_ED_OVFL.jpg" alt="Event-Driven Online VFL" style="width: 50%; border-radius: 5px;">
</div>



### Kernelized AUC Maximization in Vertical Federated Learning
*Jun. 2023 - Jul. 2024*  
Contributed to the Asynchronous Vertical Federated Kernelized AUC Maximization (AVFKAM) project, designed to enhance model performance on imbalanced datasets. This project demonstrates notable improvements in training efficiency for federated systems. Published in [KDD 2024](https://dl.acm.org/doi/10.1145/3637528.3671930).


<div style="position: relative; display: inline-block; width: auto;">
  <!-- Badge -->
  <div class="badge">
    KDD 2024
  </div>
  <!-- Image -->
  <img src="/images/Project_asy_auc_combine.jpg" alt="Kernelized AUC Maximization" style="width: 100%; border-radius: 5px;">
</div>


