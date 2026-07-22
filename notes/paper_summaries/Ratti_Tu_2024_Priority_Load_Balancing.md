# Paper Summary

**Full Citation:** H. Tu, P. Bellavista, L. Zhao, G. Zheng, K. Liang, and K.-K. Wong, "Priority-Based Load Balancing With Multiagent Deep Reinforcement Learning for Space-Air-Ground Integrated Network Slicing," *IEEE Internet of Things Journal*, vol. 11, no. 19, pp. 30690–30703, 2024. DOI: https://doi.org/10.1109/JIOT.2024.3416157

## Summary

This paper studies network slicing in SAGIN. Network slicing means that one physical network can provide separate services for different needs, such as emergency communication, low-delay services, or normal mobile data. The authors use multi-agent deep reinforcement learning to balance traffic across ground base stations, UAVs, and satellites. The method gives priority to more important services when resources are limited.

## Relevance to Our Survey

This paper is useful because future 6G SAGINs will need to support many users and service types at the same time. It shows how AI can make load-balancing decisions across all three network layers. It can support our literature review on resource allocation, network slicing, and quality of service.

## Critical Comment

Giving some services higher priority may create fairness problems if low-priority users are moved more often to slower or less reliable connections. The paper should be tested in a larger and more realistic network to see whether it can balance emergency needs, fairness, delay, and energy use at the same time.

## AI Disclosure

I used ChatGPT to help find relevant papers for this project. I then read and studied the paper myself and wrote this summary based on my own understanding. I used AI only to help organize the format and improve grammar and clarity.
