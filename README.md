# Design Principles for Edge AI

Designing and architecting software that incorporates AI operating on edge devices presents unique challenges and design considerations. Often, edge AI is used for one of the four reasons: (1) to reduce AI model latency, (2) to process distributed data sets, (3) to operate in environments with poor network connectivy, or (4) to process highly secure data sets. Due to the diversity of these use cases, not to mention the variety and complexity of modern edge hardware, it can often be a challenge to select the best design pattern for an AI-powered edge application.

Based on our experiences--and the experience of other luminaries in the edge computing world--we created a set of design principles to help. Inspired by the likes of the agile manifesto, these design principles are intended to help bound and direct the design and develompent of edge AI systems. We hope you find them to be helpful guideposts on your edge AI journey.


Modzy's Product & Engieering Team

23 August 2023

## 8 Principles for Edge AI Design

1. People before tech; users and their needs come first
2. Minimize manual interactions with edge devices
3. Application code and model code live separate lives, treat them accordingly
4. High-performance hardware is scarce and should be used judiciously
5. Network instability is a feature, not a bug, in edge computing
6. Protocols are your permission to connect applications across many devices
7. AI models perform worse over time; continuous improvement is the only defense
8. Less is more
