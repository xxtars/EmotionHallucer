# Abstract

Emotion understanding is a critical yet challenging task.
Recent advances in Multimodal Large Language Models (MLLMs) have significantly enhanced their capabilities in this area.
However, MLLMs often suffer from hallucinations, generating irrelevant or nonsensical content.
To the best of our knowledge, despite the importance of this issue, there has been no dedicated effort to evaluate emotion-related hallucinations in MLLMs.
In this work, we introduce *EmotionHallucer*, the first benchmark for detecting and analyzing emotion hallucinations in MLLMs.
Unlike humans, whose emotion understanding stems from the interplay of biology and social learning, MLLMs rely solely on data-driven learning and lack innate emotional instincts. Fortunately, emotion psychology provides a solid foundation of knowledge about human emotions.
Building on this, we assess emotion hallucinations from two dimensions: emotion psychology knowledge and real-world multimodal perception.
To support robust evaluation, we utilize an adversarial binary question–answer (QA) framework, which employs carefully crafted basic and hallucinated pairs to assess the emotion hallucination tendencies of MLLMs.
By evaluating 38 LLMs and MLLMs on EmotionHallucer, we reveal that:
i) most current models exhibit substantial issues with emotion hallucinations;
ii) closed-source models outperform open-source ones in detecting emotion hallucinations, and reasoning capability provides additional advantages;
iii) existing models perform better in emotion psychology knowledge than in multimodal emotion perception.
As a byproduct, these findings inspire us to propose the *PEP-MEK* framework, which yields an average improvement of 9.90\% in emotion hallucination detection across selected models.
