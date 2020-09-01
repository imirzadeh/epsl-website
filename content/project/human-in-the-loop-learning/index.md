---
title: Human-in-the-Loop Learning
summary: Designing active learning strategies that collect labeled sensor data
  in uncontrolled environments is challenging because (i) without taking into
  account user's cognitive factors, active learning places much burden on the
  user and lowers adoption of the technology; and (ii) the labels expressed by
  end-users exhibit significant amounts of temporal and spacial variations
  leading to poor performance of the learned models. In this project, we design,
  develop, and validate human-in-the-loop technologies that collect sensor data
  in-the-wild and develop algorithms and tools (i) to maximize the active
  learning performance taking informativeness of sensor data, burden of data
  labeling on user, and reliability of prospective labels into account; and (ii)
  for understanding and inferring complex health events using wearable and
  mobile sensors.
image2: featured.jpg
date: 2020-08-27T05:18:17.047Z
authors: [EPSL]
---
## Mindful Active Learning
We propose a novel active learning framework for activity recognition using wearable sensors. Our work is unique in that it takes limitations of the oracle into account when selecting sensor data for annotation by the oracle. Our approach is inspired by human-beings' limited capacity to respond to prompts on their mobile device. This capacity constraint is manifested not only in the number of queries that a person can respond to in a given time-frame but also in the time lag between the query issuance and the oracle response. We introduce the notion of mindful active learning and propose a computational framework, called EMMA, to maximize the active learning performance taking informativeness of sensor data, query budget, and human memory into account. We formulate this optimization problem, propose an approach to model memory retention, discuss the complexity of the problem, and propose a greedy heuristic to solve the optimization problem. Additionally, we design an approach to perform mindful active learning in batch where multiple sensor observations are selected simultaneously for querying the oracle. We demonstrate the effectiveness of our approach using three publicly available activity datasets and by simulating oracles with various memory strengths. We show that the activity recognition accuracy ranges from 21% to 97% depending on memory strength, query budget, and difficulty of the machine learning task. Our results also indicate that EMMA achieves an accuracy level that is, on average, 13.5% higher than the case when only informativeness of the sensor data is considered for active learning. Moreover, we show that the performance of our approach is at most 20% less than the experimental upper-bound and up to $80$\% higher than the experimental lower-bound. To evaluate the performance of EMMA for batch active learning, we design two instantiations of EMMA to perform active learning in batch mode. We show that these algorithms improve the algorithm training time at the cost of a reduced accuracy in performance. Another finding in our work is that integrating clustering into the process of selecting sensor observations for batch active learning improves the activity learning performance by 11.1% on average, mainly due to reducing the redundancy among the selected sensor observations. We observe that mindful active learning is most beneficial when the query budget is small and/or the oracle's memory is weak. This observation emphasizes advantages of utilizing mindful active learning strategies in mobile health settings that involve interaction with older adults and other populations with cognitive impairments.
