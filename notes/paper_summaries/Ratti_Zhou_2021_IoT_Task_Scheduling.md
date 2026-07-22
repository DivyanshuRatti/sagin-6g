# Paper Summary

**Full Citation:** C. Zhou, W. Wu, H. He, P. Yang, F. Lyu, N. Cheng, and X. Shen, "Deep Reinforcement Learning for Delay-Oriented IoT Task Scheduling in SAGIN," *IEEE Transactions on Wireless Communications*, vol. 20, no. 2, pp. 911–925, 2021. DOI: https://doi.org/10.1109/TWC.2020.3029143

## Summary

This paper investigates how delay-sensitive Internet of Things (IoT) tasks can be scheduled efficiently in a Space-Air-Ground Integrated Network (SAGIN). In the proposed system, a UAV collects computing tasks from IoT devices and decides whether each task should be processed locally, offloaded to a nearby ground base station, or sent to a Low Earth Orbit (LEO) satellite. The authors formulate the scheduling problem as a constrained Markov Decision Process (CMDP) and propose a deep risk-sensitive reinforcement learning algorithm that learns scheduling decisions while considering both task delay and the UAV's limited battery capacity. Simulation results show that the proposed method reduces task processing delay by up to 30% compared with probabilistic scheduling methods while keeping the UAV's energy consumption within its allowed limit.

## Relevance to Our Survey

This paper fits our survey because task offloading and edge computing are mThis paper is highly relevant to our survey because it demonstrates how reinforcement learning can support intelligent task offloading and edge computing in SAGIN. Instead of relying on fixed scheduling rules, the proposed AI model learns where computation should be performed based on changing network conditions and energy availability. This approach is valuable for delay-sensitive applications such as smart transportation, industrial monitoring, disaster response, and remote IoT services where fast and adaptive decision-making is essential.ajor challenges in SAGIN. It shows that AI can help the network decide where data should be processed instead of sending every task to one central cloud. This is important for remote monitoring, disaster response, and IoT services where fast decisions are needed.

## Critical Comment

The proposed approach is evaluated only through simulations, so its performance in real-world deployments is still uncertain. Factors such as changing weather conditions, UAV mobility, battery degradation, communication failures, and unpredictable wireless interference could affect the scheduling decisions. In addition, the paper does not discuss the computational cost of training the reinforcement learning model, which could be important for practical deployment on resource-constrained UAVs.

## AI Disclosure

I reread the paper carefully and revised my original summary based on my understanding of the research. I used ChatGPT only to improve the grammar, formatting, and clarity of the final document while keeping the technical content and interpretation based on my own reading of the paper.
