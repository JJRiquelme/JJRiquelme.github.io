---
layout: single
title: "Yann LeCun puts it plainly: today’s AI still can’t abstract."
date: 2025-03-23
categories: [AI, MachineLearning, VJEPA, YannLeCun, ArtificialIntelligence, RepresentationLearning, EmbodiedAI, Abstraction, PhysicsAndAI, PredictiveModels, AIResearch, DeepLearning]
excerpt: "Yann LeCun highlights abstraction as the central missing piece in current AI systems, and proposes a path forward through architectures like V-JEPA."
---
This short post points to an insightful interview and Meta’s recent write-up on V-JEPA, an architecture aimed at bridging that gap. It’s a useful listen—not just for AI researchers, but for anyone thinking about how machine learning interfaces with physical systems and real-world prediction.

---
title: "V-JEPA and the Missing Abstraction Layer in AI"
date: 2025-03-30
categories: [AI, Self-Supervised Learning]
tags: [VJEPA, YannLeCun, MetaAI, Abstraction, PredictiveModels]
author_profile: true
---

One of the most interesting conversations in AI right now isn't about scale or compute—it's about abstraction. Despite the rapid progress in large language models and vision systems, today’s AI still struggles to build internal representations that generalize beyond surface patterns. In a recent podcast interview, Yann LeCun puts this limitation front and center, arguing that the lack of an effective abstraction mechanism is the core bottleneck in current AI systems.

That conversation is well worth the time. It’s more than just a technical deep dive; it frames the underlying architectural problems that constrain how AI models perceive and predict the world. In LeCun’s view, supervised learning and reinforcement learning are both too limited to get us to human-level understanding. Instead, he proposes something different: a predictive, self-supervised approach based on latent spaces and masked modeling of future states.

This idea is formalized in Meta AI’s recent proposal: V-JEPA (Video Joint Embedding Predictive Architecture). The full write-up is available on Meta’s AI blog, and the technical details can be found in the arXiv paper, accompanied by the GitHub repository and a recent submission to ICLR 2024 (OpenReview link).

What’s novel about V-JEPA is its move away from pixel-level reconstruction or token prediction. Instead, it learns to predict latent representations of future video frames, without reconstructing the input. This is important. Rather than forcing the model to generate high-fidelity outputs, it focuses on building abstract, compressed representations that are predictive of what comes next—arguably a better proxy for understanding.

For those of us working on physical systems—whether in scanning probe microscopy, robotics, or sensor networks—this line of research is highly relevant. A model that can learn dynamics in latent space, by observing sequences and predicting coherent futures, is much more aligned with how we interact with real systems. It’s not about matching pixels or words; it’s about modeling what might happen, based on partial observations. That is abstraction in action.

It’s still early days. The V-JEPA model is under active development, and the results so far—though promising—leave room for refinement. But the shift in architectural thinking is significant. It reflects an evolving consensus that next-generation AI needs more than just more data and parameters. It needs structure, dynamics, and prediction grounded in abstract representations.

For anyone thinking about AI’s role in modeling physical systems, experimental processes, or intelligent instrumentation, V-JEPA is worth a close look—not just as a tool, but as a conceptual pivot.

Interview 
- 🎧 [Podcast](https://pod.link/1522960417/)
- 🧠 [Meta’s official blog post](https://ai.meta.com/blog/v-jepa-yann-lecun-ai-model-video-joint-embedding-predictive-architecture/)
- 📄 [arXiv paper](https://arxiv.org/abs/2404.08471)
- 💻 [GitHub repo](https://github.com/facebookresearch/jepa)
- 🔬 [Vision](https://openreview.net/forum?id=BZ5a1r-kVsf)