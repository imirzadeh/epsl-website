---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Power-Aware System Design"
summary: "The stringent constrained resources available on tiny sensor nodes introduce a number of challenges regarding accuracy, power-efficiency, user-comfort, and security. These design considerations, however, often impose conflicting requirements. Thus, a comprehensive research approach to design future medical embedded systems and corresponding optimizations at different levels must consider these interdependent and conflicting requirements. We research methods of optimizing medical embedded systems for power-efficiency while taking into account other performance metrics. The goal is to develop tools, methodologies, and algorithms towards comprehensive approaches to address cross-layer optimization issues related to power, performance, user-comfort, and security."
authors: []
tags: []
categories: []
date: 2020-01-13T23:58:23-08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# About the Project
The stringent constrained resources available on tiny sensor nodes introduce a number of challenges regarding accuracy, power-efficiency, user-comfort, and security. These design considerations, however, often impose conflicting requirements. Thus, a comprehensive research approach to design future medical embedded systems and corresponding optimizations at different levels must consider these interdependent and conflicting requirements. We research methods of optimizing medical embedded systems for power-efficiency while taking into account other performance metrics. The goal is to develop tools, methodologies, and algorithms towards comprehensive approaches to address cross-layer optimization issues related to power, performance, user-comfort, and security.

# Related Papers
##  Optimal and Adaptive Compressed Sensing with Unsupervised Learning
Activity recognition, as an important component of behavioral monitoring and intervention, has attracted enormous attention, especially in Mobile Cloud Computing (MCC) and Remote Health Monitoring (RHM) paradigms. While recently resource constrained wearable devices have been gaining popularity, their battery life is limited and constrained by the frequent wireless transmission of data to more computationally powerful back-ends. Here we propose an ultra-low power activity recognition system using a novel adaptive compressed sensing technique that aims to minimize transmission costs. Coarse-grained on-body sensor localization and unsupervised clustering modules are devised to autonomously reconfigure the compressed sensing module for further power saving. We perform a thorough heuristic optimization using Grammatical Evolution (GE) to ensure minimal computation overhead of the proposed methodology. Our evaluation on a real-world dataset and a low power wearable sensing node demonstrates that our approach can reduce the energy consumption of the wireless data transmission up to 81.2% and 61.5%, with up to 60.6% and 35.0% overall power savings in comparison with baseline and a naive state-of-the-art approaches, respectively. These solutions lead to an average activity recognition accuracy of 89.0%, only 4.8% less than the baseline accuracy, while having a negligible energy overhead of on-node computation.

## Adaptive Compressed Sensing at the Fingertip of Internet-of-Things Sensors
With the proliferation of wearable devices in the Internet-of-Things applications, designing highly power-efficient solutions for continuous operation of these technologies in life-critical settings emerges. We propose a novel ultra-low power framework for adaptive compressed sensing in activity recognition. The proposed design uses a coarse-grained activity recognition module to adaptively tune the compressed sensing module for minimized sensing/transmission costs. We pose an optimization problem to minimize activity-specific sensing rates and introduce a polynomial time approximation algorithm using a novel heuristic dynamic optimization tree. Our evaluations on real-world data shows that the proposed autonomous framework is capable of generating feedback with +80% confidence and improves power reduction performance of the state-of-the-art approach by a factor of two.

## CyHOP
CyHOP is a generic framework for real-time power-performance optimization in networked wearable systems. Power consumption is a major obstacle in designing stringent resource constraint wearables. Several system-level design considerations contribute to energy consumption of these systems which must be taken into account while designing the system. We propose a power-performance optimization framework, namely CyHOP (Cyclic and Holistic Optimization framework), for connected wearable motion sensors. While existing work focus solely on one design parameter, our approach globally trades-off the performance of activity recognition and power consumption. CyHOP is capable of optimally adjusting the system to fulfill specific application needs. Using a smoothing technique, the initial multi-variate non-convex optimization problem is reduced to a convex problem and solved using our devised derivative-free optimization approach, namely, cyclic coordinate search.
