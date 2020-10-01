---
slides: ""
url_pdf: ""
summary: The stringent constrained resources available on tiny sensor nodes
  introduce a number of challenges regarding accuracy, power-efficiency,
  user-comfort, and security. These design considerations, however, often impose
  conflicting requirements. Thus, a comprehensive research approach to design
  future medical embedded systems and corresponding optimizations at different
  levels must consider these interdependent and conflicting requirements. We
  research methods of optimizing medical embedded systems for power-efficiency
  while taking into account other performance metrics. The goal is to develop
  tools, methodologies, and algorithms towards comprehensive approaches to
  address cross-layer optimization issues related to power, performance,
  user-comfort, and security.
authors: [EPSL]
url_video: ""
date: 2020-01-13T23:58:23-08:00
external_link: ""
url_slides: ""
title: Power-Aware System Design
tags: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
categories: []
url_code: ""
---
The stringent constrained resources available on tiny sensor nodes introduce a number of challenges regarding accuracy, power-efficiency, user-comfort, and security. These design considerations, however, often impose conflicting requirements. Thus, a comprehensive research approach to design future medical embedded systems and corresponding optimizations at different levels must consider these interdependent and conflicting requirements. We research methods of optimizing medical embedded systems for power-efficiency while taking into account other performance metrics. The goal is to develop tools, methodologies, and algorithms towards comprehensive approaches to address cross-layer optimization issues related to power, performance, user-comfort, and security.

# Related Papers

##  Optimal Policy for Deployment of Machine Learning Models on Energy-Bounded Systems
With the recent advances in both machine learning and embedded systems research, the demand to deploy these computational models on edge devices has increased substantially. Without deploying computational models on edge devices, frequent transmission of sensor data to the cloud results in rapid battery depletion because energy consumption due to wireless data transmission is significantly higher than that of on-the-device data processing. This rapid power dissipation leads to a considerable reduction in battery lifetime of the system, therefore jeopardizing real-world utility of smart devices. A major challenge that obstructs the deployment of machine learning models on edge devices is the power limitations of these systems. It is well-established that for difficult machine learning tasks, models with higher performance often require more computation power and thus are not power-efficient choices for deployment on edge devices. However, trade-offs between performance and power consumption are not well studied. While numerous methods (e.g., model compression) have been developed to obtain an optimal model, these methods focus on improving the efficiency of a single model. In an entirely new direction, we introduce an effective method to find a combination of multiple  models that are optimal in terms of power-efficiency and performance by solving an optimization problem in which both performance and power consumption are taken into account. The general goal of our optimization problem is to find an optimal distribution of model allocations that maximize expected performance subject to a given power budget. Experimental results demonstrate that on the ImageNet dataset, we can achieve a 20% energy reduction with only a 0.3% accuracy drop compared to Squeeze-and-Excitation Networks.  Compared to a pruned convolutional neural network for human activity recognition task, while consuming 1.7% less energy, our proposed policy achieves 1.3% higher accuracy.

##  Optimal and Adaptive Compressed Sensing with Unsupervised Learning
Activity recognition, as an important component of behavioral monitoring and intervention, has attracted enormous attention, especially in Mobile Cloud Computing (MCC) and Remote Health Monitoring (RHM) paradigms. While recently resource constrained wearable devices have been gaining popularity, their battery life is limited and constrained by the frequent wireless transmission of data to more computationally powerful back-ends. Here we propose an ultra-low power activity recognition system using a novel adaptive compressed sensing technique that aims to minimize transmission costs. Coarse-grained on-body sensor localization and unsupervised clustering modules are devised to autonomously reconfigure the compressed sensing module for further power saving. We perform a thorough heuristic optimization using Grammatical Evolution (GE) to ensure minimal computation overhead of the proposed methodology. Our evaluation on a real-world dataset and a low power wearable sensing node demonstrates that our approach can reduce the energy consumption of the wireless data transmission up to 81.2% and 61.5%, with up to 60.6% and 35.0% overall power savings in comparison with baseline and a naive state-of-the-art approaches, respectively. These solutions lead to an average activity recognition accuracy of 89.0%, only 4.8% less than the baseline accuracy, while having a negligible energy overhead of on-node computation.

## Adaptive Compressed Sensing at the Fingertip of Internet-of-Things Sensors
With the proliferation of wearable devices in the Internet-of-Things applications, designing highly power-efficient solutions for continuous operation of these technologies in life-critical settings emerges. We propose a novel ultra-low power framework for adaptive compressed sensing in activity recognition. The proposed design uses a coarse-grained activity recognition module to adaptively tune the compressed sensing module for minimized sensing/transmission costs. We pose an optimization problem to minimize activity-specific sensing rates and introduce a polynomial time approximation algorithm using a novel heuristic dynamic optimization tree. Our evaluations on real-world data shows that the proposed autonomous framework is capable of generating feedback with +80% confidence and improves power reduction performance of the state-of-the-art approach by a factor of two.

## CyHOP
CyHOP is a generic framework for real-time power-performance optimization in networked wearable systems. Power consumption is a major obstacle in designing stringent resource constraint wearables. Several system-level design considerations contribute to energy consumption of these systems which must be taken into account while designing the system. We propose a power-performance optimization framework, namely CyHOP (Cyclic and Holistic Optimization framework), for connected wearable motion sensors. While existing work focus solely on one design parameter, our approach globally trades-off the performance of activity recognition and power consumption. CyHOP is capable of optimally adjusting the system to fulfill specific application needs. Using a smoothing technique, the initial multi-variate non-convex optimization problem is reduced to a convex problem and solved using our devised derivative-free optimization approach, namely, cyclic coordinate search.
