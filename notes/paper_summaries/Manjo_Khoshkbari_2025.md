# Paper Summary

**Full Citation:** H. Khoshkbari, G. Kaddoum, B. Selim, O. Abbasi, and H. Yanikomeroglu, "Distributed Beamforming in Massive MIMO Communication for a Constellation of Airborne Platform Stations," in ICC 2025 - IEEE International Conference on Communications, 2025, pp. 4383–4388. https://arxiv.org/abs/2512.23900

## Summary (3–5 sentences in your own words)

From reading the paper, I think the main goal is to find a better way for multiple airborne base stations to work together and provide wireless coverage. Normally, these stations need to share channel state information (CSI) with each other to coordinate their beamforming, but that creates extra communication overhead and can slow the network down. The authors propose using a multi-agent reinforcement learning approach, where each airborne platform learns to make its own beamforming decisions without needing to share CSI with the other platforms. They compare their method with two traditional beamforming techniques and show that it performs better, especially in situations with high interference. Overall, the paper suggests that AI can improve the efficiency and scalability of future airborne wireless networks while reducing the need for constant information exchange between platforms.

## Relevance to Our Survey

I think this paper is relevant to our survey because SAGIN depends on communication between airborne platforms, satellites, and ground networks. Since these platforms are constantly moving, coordinating them efficiently can be difficult and requires a lot of communication. The paper shows that using multi-agent reinforcement learning allows each airborne platform to make its own beamforming decisions without sharing channel state information (CSI) with the others. This reduces communication overhead while still maintaining good network performance, making the approach useful for future SAGIN and 6G wireless networks where fast and reliable communication is important.

## Critical Comment

One limitation I noticed is that the paper mainly evaluates its proposed method using simulations with airborne platform stations instead of testing it in a real SAGIN environment that includes satellites, airborne platforms, and ground stations. The simulation results are promising, but I think there are still questions about how well the approach would perform in real-world conditions where factors such as weather, long communication delays, and constantly changing network conditions could affect performance. I also wonder how practical it would be to train and maintain a multi-agent reinforcement learning system in a large network. I think future research should test this approach in more realistic scenarios to show that it can work outside of simulations.

## AI Disclosure

I used Claude to help me find the paper and explain some of the technical concepts in simpler terms after I had read the abstract. The AI helped me understand the paper and organize my thoughts, but I wrote the summary, relevance, and critical comment based on my own understanding of the paper.
