# Paper Summary

**Full Citation:** Y. Qin, Y. Yang, F. Tang, X. Yao, M. Zhao, and N. Kato, "Differentiated Federated Reinforcement Learning Based Traffic Offloading on Space-Air-Ground Integrated Networks," *IEEE Transactions on Mobile Computing*, vol. 23, no. 12, pp. 11000–11013, 2024. DOI: https://doi.org/10.1109/TMC.2024.3389011

## Summary

This paper combines federated learning with reinforcement learning for traffic offloading in SAGIN. Different areas of the network can have different traffic, users, and link conditions, so one identical AI policy may not work everywhere. The authors propose differentiated federated reinforcement learning, where several agents learn policies suited to their own regions while still sharing useful model knowledge. Their method aims to improve throughput, lower packet loss, and reduce packet delay.

## Relevance to Our Survey

This paper is strongly related to our topic because it combines two important AI directions: federated learning and reinforcement learning. It shows a decentralized way to make traffic decisions without sending all raw information to one central controller. This can support our discussion about scalable and privacy-aware AI for SAGIN.

## Critical Comment

Federated learning still requires model updates to be exchanged. In satellite and aerial networks, those updates may be delayed, costly, or interrupted by changing links. The paper needs more evidence about how the method works when devices have very different computing power, data quality, and communication reliability.

## AI Disclosure

I used ChatGPT to help find relevant papers for this project. I then read and studied the paper myself and wrote this summary based on my own understanding. I used AI only to help organize the format and improve grammar and clarity.
