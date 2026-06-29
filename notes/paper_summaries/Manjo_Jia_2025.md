# Paper Summary

**Full Citation:** Z. Jia, J. He, L. He, M. Sheng, J. Liu, Q. Wu, and Z. Han, "Dynamic Trajectory Optimization and Power Control for Hierarchical UAV Swarms in 6G Aerial Access Network," arXiv preprint arXiv:2508.18702, 2025. https://arxiv.org/abs/2508.18702

## Summary

From reading the paper, I think the main goal is to improve communication and data collection in 6G aerial access networks by using a hierarchical UAV swarm instead of relying on a single UAV. The authors divide the UAVs into two groups, where the head UAV acts as an aerial relay and receives data collected by the tail UAVs from ground users. They then optimize the flight paths of the tail UAVs, the placement of the head UAV, and the transmit power by combining Voronoi-based area partitioning with a bio-inspired Whale Optimization Algorithm to balance energy consumption and communication delay. The results show that this approach improves network performance and uses resources more efficiently than traditional UAV deployment methods.

## Relevance to Our Survey

This paper is relevant to our survey because UAVs are an important part of Space-Air-Ground Integrated Networks (SAGIN). It shows how a hierarchical UAV swarm can improve communication coverage and data collection by allowing different UAVs to perform different roles within the network. The paper also demonstrates how trajectory planning and power control can be optimized to reduce energy consumption and communication delays, which are important challenges in SAGIN. These ideas could help improve the efficiency and scalability of future AI-enabled and 6G integrated communication networks.

## Critical Comment

One limitation I noticed is that the paper evaluates the proposed approach using simulations, so it is difficult to know how well it would perform in a real 6G UAV network. The optimization also assumes a relatively stable environment, but in real situations, ground users may move, wireless conditions can change, and UAVs may experience unexpected disruptions. In addition, the Whale Optimization Algorithm may require more computation as the number of UAVs and users increases, which could affect its ability to make fast decisions in large-scale networks. I think future work should test the approach in more realistic environments and evaluate how well it performs as the network becomes larger and more dynamic.

## AI Disclosure

I used Claude to help me find the paper and explain some of the technical concepts after I had read the abstract and key sections of the paper. The AI helped me understand the main ideas and organize my thoughts, but I wrote the summary, relevance, critical comment, and analysis in my own words based on my understanding of the paper.
