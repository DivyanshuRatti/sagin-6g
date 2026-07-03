# Paper Summary

**Full Citation:** C. Zhou, W. Wu, H. He, P. Yang, F. Lyu, N. Cheng, and X. Shen, "Deep Reinforcement Learning for Delay-Oriented IoT Task Scheduling in SAGIN," *IEEE Transactions on Wireless Communications*, vol. 20, no. 2, pp. 911–925, 2021. DOI: https://doi.org/10.1109/TWC.2020.3029143

## Summary

This paper studies how Internet of Things (IoT) tasks can be scheduled in a Space-Air-Ground Integrated Network. A task may be processed by a UAV, sent to a ground base station, or sent through a satellite link. The authors use deep reinforcement learning to decide where each task should go. Their main goal is to reduce task delay while keeping the UAV's energy use within a safe limit.

## Relevance to Our Survey

This paper fits our survey because task offloading and edge computing are major challenges in SAGIN. It shows that AI can help the network decide where data should be processed instead of sending every task to one central cloud. This is important for remote monitoring, disaster response, and IoT services where fast decisions are needed.

## Critical Comment

The proposed method is evaluated in a simulated setting. In a real deployment, UAV batteries, weather, user movement, and weak wireless links could make task scheduling more difficult. The paper would be stronger if it included tests with real UAVs or a more detailed study of training cost and battery use.

## AI Disclosure

I used ChatGPT to help find relevant papers for this project. I then read and studied the paper myself and wrote this summary based on my own understanding. I used AI only to help organize the format and improve grammar and clarity.
